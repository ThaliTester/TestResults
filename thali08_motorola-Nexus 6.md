#### Test 79751015a95812e_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-05 08:05:11.324   872  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380372, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:05:12.052  3762  3762 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 08:05:12.057  3762  3762 D AndroidRuntime: CheckJNI is OFF
08-05 08:05:12.094  3762  3762 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 08:05:12.144  3762  3762 I Radio-JNI: register_android_hardware_Radio DONE
08-05 08:05:12.166  3762  3762 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 08:05:12.174   872  1732 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 08:05:12.225   872  1732 I ActivityManager: Start proc 3771:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-05 08:05:12.233  3762  3762 D AndroidRuntime: Shutting down VM
08-05 08:05:12.333  3771  3771 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-05 08:05:12.359  3771  3771 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-05 08:05:12.366  3771  3771 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1413-1415)
08-05 08:05:12.367  3771  3771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:05:12.379  3771  3771 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {346e213}
08-05 08:05:12.379  3771  3771 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 08:05:12.380  3771  3771 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 08:05:12.387  3771  3771 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 08:05:12.389  3771  3771 E SysUtils: ApplicationContext is null in ApplicationStatus
08-05 08:05:12.408  3771  3771 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-05 08:05:12.418  3771  3771 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 08:05:12.419  3771  3771 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 08:05:12.419  3771  3771 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 08:05:12.419  3771  3771 I Adreno  : Build Date                       : 10/20/15
08-05 08:05:12.419  3771  3771 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 08:05:12.419  3771  3771 I Adreno  : Local Branch                     : M14
08-05 08:05:12.419  3771  3771 I Adreno  : Remote Branch                    : 
08-05 08:05:12.419  3771  3771 I Adreno  : Remote Branch                    : 
08-05 08:05:12.419  3771  3771 I Adreno  : Reconstruct Branch               : 
,08-05 08:05:12.485   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b83e8f:true
,08-05 08:05:12.528  3771  3771 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 08:05:12.542  3771  3771 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-05 08:05:12.599  3771  3808 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 08:05:12.612  3771  3795 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-05 08:05:12.648  3771  3808 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 08:05:12.672  1663  1663 I Keyboard.Facilitator: onFinishInput()
,08-05 08:05:12.712   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +432ms (total +506ms)
,08-05 08:05:12.757  3771  3771 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3771
,08-05 08:05:12.852  3771  3771 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 08:05:13.009  3771  3810 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1685128912
,08-05 08:05:13.016  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 08:05:13.016  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 08:05:13.016  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 08:05:13.016  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 08:05:13.016  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 08:05:13.017  3771  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24560e6 added. We now have 1 listener(s)
,08-05 08:05:13.020  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-05 08:05:13.022  3771  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 08:05:13.022  3771  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:13.023  3771  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 08:05:13.026  3771  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588927d added. We now have 1 listener(s)
,08-05 08:05:13.026  3771  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:13.032   872  1315 D WifiService: New client listening to asynchronous messages
,08-05 08:05:13.033  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:05:13.033  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 08:05:13.034  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 08:05:13.034  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 08:05:13.035  3771  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 08:05:13.039  3771  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:13.039  3771  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-05 08:05:13.050  3771  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:13.050  3771  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:13.050  3771  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-05 08:05:13.051  3771  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:13.052  3771  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 08:05:13.053  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:13.055  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:13.071  3771  3771 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 08:05:14.121  3771  3817 W jxcore-log: Initializing JXcore engine
,08-05 08:05:14.121  3771  3817 W jxcore-log: JXcore engine is ready
,08-05 08:05:14.158  3817  3817 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-05 08:05:14.158  3817  3817 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9824]" dev="sockfs" ino=9824 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-05 08:05:14.158  3817  3817 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-05 08:05:14.158  3817  3817 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25725]" dev="sockfs" ino=25725 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-05 08:05:14.174  3771  3817 W jxcore-log: Starting JXcore engine
,08-05 08:05:14.257  3771  3817 W jxcore-log: Platform android
08-05 08:05:14.257  3771  3817 W jxcore-log: 
,08-05 08:05:14.257  3771  3817 W jxcore-log: Process ARCH arm
08-05 08:05:14.257  3771  3817 W jxcore-log: 
,08-05 08:05:14.476  3771  3817 I jxcore-log: JXcore Cordova bridge is ready!
08-05 08:05:14.476  3771  3817 I jxcore-log: 
,08-05 08:05:14.476  3771  3817 W jxcore-log: JXcore engine is started
,08-05 08:05:14.486  3771  3810 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 08:05:14.491  3771  3771 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 08:05:23.855   872  1991 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-05 08:05:30.084  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 08:05:30.084  3771  3817 I jxcore-log: 
08-05 08:05:30.086  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 08:05:30.086  3771  3817 I jxcore-log: 
,08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:30.099  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:30.105  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.107  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 08:05:30.107  3771  3817 I jxcore-log: 
,08-05 08:05:30.109  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 08:05:30.109  3771  3817 I jxcore-log: 
,08-05 08:05:30.445  3771  3817 D ExecuteNativeTests: Running unit tests
,08-05 08:05:30.503  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:30.503  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 added. We now have 2 listener(s)
,08-05 08:05:30.505  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 08:05:30.505  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:30.505  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:30.505  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:30.505  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 added. We now have 2 listener(s)
08-05 08:05:30.505  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:30.505  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 08:05:30.511  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:30.521  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:30.525  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-05 08:05:30.525  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:30.528  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 08:05:30.529  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-05 08:05:30.529  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:05:30.531  3771  3817 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-05 08:05:30.531  3771  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 08:05:30.532  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:05:30.532  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:05:30.532  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:05:30.532  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.532  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:30.533  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.533  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.533  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.533  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.533  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:30.533  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:30.534  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 removed from the list
,08-05 08:05:30.534  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.534  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 removed from the list
,08-05 08:05:30.538  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.539  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.539  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.539  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.539  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.543  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 08:05:30.544  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.544  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.545  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.551  3771  3817 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-05 08:05:30.553  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:30.553  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.554  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:05:30.555  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.555  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:30.555  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.555  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.555  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.556  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.556  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.556  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.556  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.557  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.557  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.559  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 08:05:30.559  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.560  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.560  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 08:05:30.568  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 08:05:30.569  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 08:05:30.570  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 08:05:30.570  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:30.570  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.570  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.570  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.571  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:30.571  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.571  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.571  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.571  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.571  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.571  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.571  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.571  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.571  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.573  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 08:05:30.573  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.573  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.573  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.574  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 08:05:30.575  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:30.583  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:30.584  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.585  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 08:05:30.585  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:30.585  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:30.585  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:05:30.585  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.585  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:05:30.588  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:05:30.588  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:05:30.589  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.591  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.595  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:05:30.598  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:05:30.598  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:05:30.601  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-05 08:05:30.605  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-05 08:05:30.605  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:05:30.606  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 08:05:30.607  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:05:30.608  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:30.613  2549  2564 D BtGatt.GattService: registerClient() - UUID=563d0b36-5a6c-446c-a9cc-8b76658367e8
,08-05 08:05:30.613  2549  2606 D BtGatt.GattService: onClientRegistered() - UUID=563d0b36-5a6c-446c-a9cc-8b76658367e8, clientIf=5
,08-05 08:05:30.614  3771  3782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:05:30.615  2549  2755 D BtGatt.GattService: start scan with filters
,08-05 08:05:30.625  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:05:30.626  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:05:30.626  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:05:30.626  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:05:30.626  2549  2610 D BtGatt.ScanManager: handling starting scan
,08-05 08:05:30.629  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:30.629  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:05:30.630  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:05:30.631  2549  2610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:30.631  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:05:30.634  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:05:30.638  2549  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 08:05:30.639  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.639  2549  2610 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-05 08:05:30.639  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:30.639  3771  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 08:05:30.640  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.640  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:05:30.641  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.641  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 08:05:30.641  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:05:30.644  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:30.644  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:30.644  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 08:05:30.646  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-05 08:05:30.646  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-05 08:05:30.648  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:30.649  2549  2564 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:05:30.650  2549  2755 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:05:30.650  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:05:30.651  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-05 08:05:30.651  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:30.651  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:05:30.651  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 08:05:30.653  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:30.654  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 08:05:30.654  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.654  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:05:30.655  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:05:30.655  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:05:30.656  2549  2610 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 08:05:30.656  2549  2610 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:05:30.656  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 08:05:30.659  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.659  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.659  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:30.659  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.660  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.660  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:30.660  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.660  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:05:30.660  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.660  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.660  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.661  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 08:05:30.665  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:30.676  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:30.678  2549  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 08:05:30.678  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.681  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 08:05:30.681  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 08:05:30.682  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:30.682  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:30.682  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:05:30.682  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:30.683  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:05:30.685  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:05:30.685  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.691  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.693  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:05:30.693  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:05:30.695  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.698  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:05:30.698  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.699  2549  2610 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:05:30.699  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:05:30.702  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:05:30.702  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:05:30.707  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 08:05:30.707  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:30.707  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:05:30.707  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.707  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:05:30.708  2549  2610 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:05:30.709  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:30.713  2549  2755 D BtGatt.GattService: registerClient() - UUID=53c05e39-0210-454c-a3b1-ca404fb2da3f
08-05 08:05:30.714  2549  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:30.714  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.714  2549  2606 D BtGatt.GattService: onClientRegistered() - UUID=53c05e39-0210-454c-a3b1-ca404fb2da3f, clientIf=5
,08-05 08:05:30.715  3771  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:05:30.715  2549  2564 D BtGatt.GattService: start scan with filters
,08-05 08:05:30.721  2549  2610 D BtGatt.ScanManager: handling starting scan
,08-05 08:05:30.721  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:05:30.721  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 08:05:30.721  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:05:30.721  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:05:30.730  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:05:30.731  2549  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:05:30.731  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:05:30.732  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.732  2549  2610 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:05:30.732  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:05:30.738  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:05:30.741  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:05:30.741  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.742  2549  2610 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 08:05:30.742  2549  2610 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:05:30.744  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:05:30.749  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.749  3771  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-05 08:05:30.749  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.749  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-05 08:05:30.749  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.749  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 08:05:30.749  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:05:30.749  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:30.749  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:30.749  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 08:05:30.750  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:05:30.750  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:05:30.751  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:30.751  2549  2562 D BtGatt.GattService: stopScan() - queue size =1
08-05 08:05:30.753  2549  2767 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:05:30.754  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 08:05:30.754  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:05:30.754  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:30.755  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:05:30.755  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:05:30.758  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:30.758  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:05:30.758  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:05:30.759  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:05:30.759  2549  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:05:30.759  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:30.759  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.760  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 08:05:30.761  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.761  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-05 08:05:30.761  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.761  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.761  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:05:30.761  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.761  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.761  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.761  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.761  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:30.762  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.762  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.763  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 08:05:30.764  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.764  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:05:30.764  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.765  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 08:05:30.767  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:05:30.767  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.767  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.777  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:05:30.777  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.778  2549  2610 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:30.779  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:30.783  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 08:05:30.784  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:30.784  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-05 08:05:30.784  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:30.784  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-05 08:05:30.785  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:30.785  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:05:30.789  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:30.789  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.789  2549  2610 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:05:30.789  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:05:30.789  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:05:30.790  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:30.793  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:30.799  2549  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:30.799  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.802  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:05:30.804  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:05:30.804  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:05:30.811  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:05:30.812  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:05:30.812  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:05:30.813  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:30.818  2549  2755 D BtGatt.GattService: registerClient() - UUID=e144509c-6cba-4310-a9f2-fad2b8fa991f
,08-05 08:05:30.819  2549  2606 D BtGatt.GattService: onClientRegistered() - UUID=e144509c-6cba-4310-a9f2-fad2b8fa991f, clientIf=5
08-05 08:05:30.819  3771  3782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:05:30.819  2549  2564 D BtGatt.GattService: start scan with filters
,08-05 08:05:30.826  2549  2610 D BtGatt.ScanManager: handling starting scan
08-05 08:05:30.826  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:05:30.826  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 08:05:30.826  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:05:30.827  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:05:30.835  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:05:30.836  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:30.837  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:05:30.840  2549  2606 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:05:30.840  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.840  2549  2610 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:05:30.845  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:05:30.848  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:05:30.849  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.849  3771  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 08:05:30.849  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.849  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-05 08:05:30.849  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.849  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-05 08:05:30.849  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-05 08:05:30.849  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:30.850  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-05 08:05:30.850  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:05:30.851  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:05:30.851  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:05:30.851  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:05:30.851  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.852  2549  2610 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:05:30.852  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:05:30.852  2549  2610 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:05:30.853  2549  2564 D BtGatt.GattService: stopScan() - queue size =1
08-05 08:05:30.854  2549  2767 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:05:30.855  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 08:05:30.855  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-05 08:05:30.855  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:30.856  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:05:30.856  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 08:05:30.858  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:30.859  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 08:05:30.859  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-05 08:05:30.859  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:05:30.861  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 08:05:30.863  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.863  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.864  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:30.864  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.864  3771  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-05 08:05:30.864  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.865  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:05:30.865  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.865  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.865  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:30.866  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
,08-05 08:05:30.866  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.866  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.866  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.867  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.868  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.868  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.871  2549  2606 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:05:30.871  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.871  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.872  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.872  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:05:30.872  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.874  3771  3817 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-05 08:05:30.876  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:30.876  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.876  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.877  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.877  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:30.877  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.878  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.878  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 08:05:30.879  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.879  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.879  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.879  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.879  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:30.880  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.882  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:05:30.882  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:05:30.883  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 08:05:30.883  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 08:05:30.883  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.883  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.885  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 08:05:30.886  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-05 08:05:30.886  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.886  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-05 08:05:30.886  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 08:05:30.887  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.887  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.887  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
,08-05 08:05:30.887  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.887  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.887  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.887  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:30.888  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.888  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.888  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:30.889  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.889  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.889  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.890  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list,
08-05 08:05:30.891  3771  3817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 08:05:30.891  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.891  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.891  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.891  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.892  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.892  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.892  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.892  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.892  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.892  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.892  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.892  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.893  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.893  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.895  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.895  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.896  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.896  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.896  2549  2606 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:05:30.896  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.897  2549  2610 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:05:30.898  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 08:05:30.899  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.899  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.899  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.900  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.900  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already re,moved
08-05 08:05:30.900  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.900  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.901  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.901  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.901  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.901  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.902  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.902  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.902  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.904  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.904  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.904  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.905  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.906  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 08:05:30.906  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:05:30.906  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:05:30.906  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:05:30.907  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 08:05:30.907  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 08:05:30.907  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.907  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.907  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.907  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.908  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.908  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.908  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.908  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.908  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.908  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.908  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.909  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.909  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.909  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.910  2549  2606 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:30.910  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.910  2549  2610 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:05:30.913  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.913  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.913  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.914  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.916  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:05:30.917  3771  3817 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 08:05:30.918  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 08:05:30.921  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:05:30.922  3771  3817 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 08:05:30.922  2549  2606 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 08:05:30.922  2549  2606 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 08:05:30.922  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 08:05:30.923  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 08:05:30.924  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 08:05:30.925  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 08:05:30.926  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 08:05:30.926  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 08:05:30.926  3771  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:05:30.926  3771  3817 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 08:05:30.926  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:05:30.926  3771  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:05:30.927  3771  3817 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 08:05:30.927  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:05:30.927  3771  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 08:05:30.927  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 08:05:30.931  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 08:05:30.932  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 08:05:30.932  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 08:05:30.932  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 08:05:30.933  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-05 08:05:30.933  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 08:05:30.933  3771  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 08:05:30.934  3771  3817 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 08:05:30.934  3771  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 405)
08-05 08:05:30.934  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.935  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.935  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.935  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.935  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.935  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.935  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 08:05:30.936  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.936  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.936  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.936  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.936  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.936  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.936  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.936  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.938  3771  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 405
08-05 08:05:30.938  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.938  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.938  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.938  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.939  3771  3820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:05:30.939  3771  3817 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 08:05:30.939  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.939  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.939  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.939  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.940  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.940  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.940  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.940  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.940  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.940  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.940  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.940  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.940  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.940  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.941  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.942  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.942  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.942  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.942  3771  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 08:05:30.943  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.943  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.943  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.943  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.943  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.943  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.943  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.943  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.943  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.943  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.943  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.944  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.944  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.944  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.945  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.945  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.945  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.945  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.946  3771  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 08:05:30.946  3771  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 08:05:30.946  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:05:30.946  3771  3817 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 08:05:30.946  3771  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 08:05:30.946  3771  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 08:05:30.947  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:05:30.947  3771  3817 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 08:05:30.947  3771  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 08:05:30.947  3771  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 08:05:30.947  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:05:30.947  3771  3817 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 08:05:30.947  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.947  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.948  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.948  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.948  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.948  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.948  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.948  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.948  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.948  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.948  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.948  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.948  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.948  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.950  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.950  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.950  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.950  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.950  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.951  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.951  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.951  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.951  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.951  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.951  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.951  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.951  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.951  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.951  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.951  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.952  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.952  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.952  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.952  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.952  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.952  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.952  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.952  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.952  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.952  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.952  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.952  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.952  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.953  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.953  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.953  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.953  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.954  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.954  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.954  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.954  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.955  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:05:30.956  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:30.957  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 08:05:30.958  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:05:30.958  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 08:05:30.958  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:05:30.958  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:05:30.959  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:05:30.959  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.959  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 08:05:30.959  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:05:30.959  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 08:05:30.959  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.959  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:05:30.959  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.959  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.959  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:30.959  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:30.959  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:05:30.959  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:05:30.960  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.960  3771  3822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:05:30.960  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.961  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:30.961  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.961  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:30.961  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:30.962  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.962  3771  3822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 08:05:30.962  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.962  3771  3822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:05:30.962  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.962  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.962  3771  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 08:05:30.962  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 08:05:30.962  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.962  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.963  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.963  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.963  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.963  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManag,erSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.963  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.963  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.963  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.963  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.963  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.965  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.966  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.966  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.966  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.969  3771  3817 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 08:05:30.969  3771  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 08:05:30.969  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 08:05:30.969  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 08:05:30.970  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.970  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.970  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.970  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.970  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.970  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.971  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.971  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.971  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.971  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.971  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.971  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.971  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.971  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.972  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.972  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.973  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.973  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
,08-05 08:05:30.975  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.975  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.975  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.976  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.976  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.976  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.981  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.981  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.981  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.981  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.981  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.981  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.981  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.981  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.983  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.983  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.983  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.983  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.984  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:30.984  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:30.985  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:30.985  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:30.985  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.985  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.985  3771  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e824ea6 not in the list
08-05 08:05:30.986  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.986  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.986  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:30.986  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.986  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.986  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:30.986  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:30.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:30.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:30.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:30.988  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd640e7 not in the list
08-05 08:05:30.990  3771  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 08:05:30.990  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:05:30.990  3771  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 08:05:30.990  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 08:05:30.990  3771  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 08:05:30.990  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 08:05:30.993  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 08:05:30.993  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 08:05:30.993  3771  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 08:05:30.994  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 08:05:30.994  3771  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 08:05:30.994  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 08:05:30.994  3771  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 08:05:30.994  3771  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 08:05:30.995  3771  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 08:05:30.995  3771  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 08:05:30.996  3771  3817 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 08:05:30.996  3771  3817 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 08:05:30.996  3771  3817 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 08:05:30.996  3771  3817 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 08:05:31.006  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:31.006  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef4fb71 added. We now have 2 listener(s)
08-05 08:05:31.006  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:31.008  3771  3817 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 08:05:31.008   872   882 D WifiService: setWifiEnabled: true pid=3771, uid=10000
08-05 08:05:31.008   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 08:05:31.011  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:31.011  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d51ad56 added. We now have 3 listener(s)
08-05 08:05:31.012  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:31.027  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 08:05:31.027  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51b31d7 added. We now have 4 listener(s)
,08-05 08:05:31.028  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:31.031  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 08:05:31.031  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90deac4 added. We now have 5 listener(s)
08-05 08:05:31.031  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-05 08:05:31.035   872  1380 D WifiService: setWifiEnabled: false pid=3771, uid=10000
,08-05 08:05:31.036   872  1380 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:05:31.046  2549  2601 D BluetoothAdapterState: Current state: ON, message: 23
,08-05 08:05:31.046  2549  2601 D BluetoothAdapterProperties: Setting state to 13
,08-05 08:05:31.047  2549  2601 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-05 08:05:31.050  2549  2601 D BluetoothAdapterProperties: onBluetoothDisable()
,08-05 08:05:31.050  2549  2601 I BluetoothAdapterState: Entering PendingCommandState
,08-05 08:05:31.050  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:31.053  2549  2549 D BluetoothMapService: onReceive
08-05 08:05:31.053  2549  2549 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:05:31.053  2549  2549 D BluetoothMapService: STATE_TURNING_OFF
08-05 08:05:31.053  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 08:05:31.054  2549  2549 D BluetoothMapService: MAP Service closeService in
,08-05 08:05:31.054  2549  2549 D BluetoothMapMasInstance0: MAP Service shutdown
08-05 08:05:31.054  2549  2549 D ObexServerSockets0: shutdown(block = true)
08-05 08:05:31.055  2549  2768 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-05 08:05:31.055  2549  2549 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 08:05:31.055  2549  2549 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 08:05:31.055  2549  2769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-05 08:05:31.056  2549  2751 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-05 08:05:31.057   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 08:05:31.056  2549  2549 I BtOppRfcommListener: stopping Accept Thread
08-05 08:05:31.057   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-05 08:05:31.057   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 08:05:31.057   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:05:31.057  2549  3302 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 08:05:31.058  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:31.058  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:05:31.058  2549  3302 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-05 08:05:31.059  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:31.059  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 08:05:31.059  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:31.061  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.061   872   885 I ActivityManager: Start proc 3825:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-05 08:05:31.062  2549  2606 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:05:31.062  2549  2601 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-05 08:05:31.069   872  1314 E native  : do suspend true
08-05 08:05:31.069  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.074  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:31.074  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 08:05:31.075  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:31.075  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:31.077  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.079  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.080  2549  2549 D HeadsetService: Received stop request...Stopping profile...
08-05 08:05:31.081  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.083   872   872 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:31.083   872   872 D BluetoothHeadset: Proxy object disconnected
,08-05 08:05:31.083   872   872 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:31.083  1739  1985 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:31.083  1370  1839 D BluetoothHeadset: Proxy object disconnected
,08-05 08:05:31.084  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-05 08:05:31.084   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:05:31.085  2549  2549 D A2dpService: Received stop request...Stopping profile...
08-05 08:05:31.085   872  1992 D DhcpClient: Clearing IP address
,08-05 08:05:31.086  2549  2759 D A2dpStateMachine: Exit Disconnected: -1
08-05 08:05:31.088   872   872 D BluetoothA2dp: Proxy object disconnected
08-05 08:05:31.088  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-05 08:05:31.089  2549  2549 D HidService: Received stop request...Stopping profile...
08-05 08:05:31.089  2549  2549 D HidService: Stopping Bluetooth HidService
,08-05 08:05:31.089   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:31.090  1516  2318 V NativeCrypto: Read error: ssl=0x9aface00: I/O error during system call, Connection timed out
08-05 08:05:31.095  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-05 08:05:31.095  2549  2549 D HealthService: Received stop request...Stopping profile...
08-05 08:05:31.095  1370  1370 D HidProfile: Bluetooth service disconnected
08-05 08:05:31.096   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 08:05:31.096   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-05 08:05:31.097   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
08-05 08:05:31.097   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 08:05:31.097   872  1314 E native  : do suspend true
08-05 08:05:31.100  2549  2549 D PanService: Received stop request...Stopping profile...
08-05 08:05:31.100  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 08:05:31.100  1370  1370 D PanProfile: Bluetooth service disconnected
08-05 08:05:31.101  2549  2549 D BluetoothMapService: Received stop request...Stopping profile...
,08-05 08:05:31.101  2549  2549 D BluetoothMapService: stop()
08-05 08:05:31.101   401   401 E Parcel  : Reading a NULL string not supported here.
08-05 08:05:31.101  2549  2549 D BluetoothMapAppObserver: deinitObservers()
,08-05 08:05:31.101  2549  2549 D BluetoothMapAppObserver: removeReceiver()
08-05 08:05:31.102  1370  1370 D BluetoothMap: Proxy object disconnected
08-05 08:05:31.102  1370  1370 D MapProfile: Bluetooth service disconnected
08-05 08:05:31.103  2549  2549 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:31.103  2549  2549 V BluetoothAdapterState: isTurningOn()=false
,08-05 08:05:31.103  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:31.103  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:31.104  2549  2549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 08:05:31.105  2549  2549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:05:31.105  2549  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-05 08:05:31.105  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.105  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.105  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.105  2549  2549 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:31.105  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.105  2549  2606 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-05 08:05:31.105  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:31.105  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:31.106  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.106  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:31.106  2549  2730 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.106  2549  2730 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:31.106  2549  2730 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:05:31.106  2549  2730 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:31.106  2549  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-05 08:05:31.106  2549  2549 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 08:05:31.106  2549  2549 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 08:05:31.106  2549  2606 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isTurningOff()=true
,08-05 08:05:31.106  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.107  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:31.107  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:31.107  2549  2549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 08:05:31.107  2549  2606 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-05 08:05:31.108  2549  2549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:05:31.108  2549  2549 V BluetoothAdapterState: isTurningOff()=true
,08-05 08:05:31.109  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.112   872  1995 D DhcpClient: Receive thread stopped
08-05 08:05:31.113   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-05 08:05:31.110  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:31.114  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:31.114  2549  2549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 08:05:31.114  2549  2549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 08:05:31.114   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-05 08:05:31.115  2549  2549 D BluetoothMapService: MAP Service closeService in
08-05 08:05:31.115  2549  2549 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:31.115  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.115  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:31.115  2549  2549 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:31.115  2549  2549 D BluetoothMapService: cleanup()
08-05 08:05:31.115  2549  2549 D BluetoothMapService: MAP Service closeService in
,08-05 08:05:31.116  2549  2601 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-05 08:05:31.116  2549  2601 D BluetoothAdapterProperties: Setting state to 15
08-05 08:05:31.116  2549  2601 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-05 08:05:31.116   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-05 08:05:31.117  2549  2601 I BluetoothAdapterState: Entering BleOnState
08-05 08:05:31.117  1370  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:31.117   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:31.117  1370  1839 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 08:05:31.118  1370  1384 D BluetoothMap: onBluetoothStateChange: up=false
,08-05 08:05:31.118  1516  2318 V NativeCrypto: SSL shutdown failed: ssl=0x9aface00: I/O error during system call, Broken pipe
08-05 08:05:31.118  1370  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:05:31.119   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:05:31.119  1370  1839 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 08:05:31.119   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:31.119  1739  1858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:31.120  1370  1384 D BluetoothPan: onBluetoothStateChange on: false
08-05 08:05:31.121   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 08:05:31.122  2549  2601 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-05 08:05:31.122  2549  2601 D BluetoothAdapterProperties: Setting state to 16
08-05 08:05:31.122  2549  2601 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-05 08:05:31.122  2549  2601 D BluetoothAdapterProperties: onBleDisable
08-05 08:05:31.122  2549  2601 I BluetoothAdapterState: Entering PendingCommandState
08-05 08:05:31.123  2549  2602 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-05 08:05:31.123  2549  2730 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 08:05:31.124  2549  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:31.124  3771  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 405)
08-05 08:05:31.125  2549  2606 D BluetoothAdapterProperties: Scan Mode:20
,08-05 08:05:31.128  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:31.128  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:31.128  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.128  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:31.130  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:31.131  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:31.131  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.131  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:31.132  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:31.133  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.135   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-05 08:05:31.137  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:31.137  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:31.137  1861  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:05:31.137  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.137  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:31.139  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:31.139  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:31.139  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:31.139  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:31.141   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-05 08:05:31.158  3825  3825 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-05 08:05:31.159   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:31.167  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 08:05:31.171  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:31.174   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0cec98:true
,08-05 08:05:31.177   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:31.177   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-05 08:05:31.177   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:31.183   872  1777 I ActivityManager: Start proc 3841:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-05 08:05:31.185   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-05 08:05:31.188  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:31.189  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:31.220  3841  3841 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-05 08:05:31.223  3825  3825 D LocalBluetoothProfileManager: Adding local MAP profile
,08-05 08:05:31.225  3825  3825 D BluetoothMap: Create BluetoothMap proxy object
,08-05 08:05:31.233  3825  3825 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-05 08:05:31.234   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-05 08:05:31.251  3825  3825 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:05:31.256   872  1732 I ActivityManager: Killing 2853:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-05 08:05:31.327  2549  2606 I bt_hci  : shut_down
08-05 08:05:31.327  2549  2612 D bt_hwcfg: hw_epilog_process
,08-05 08:05:31.330  2549  2612 I bt_vendor: low_power_mode_cb
,08-05 08:05:31.360  2549  2612 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-05 08:05:31.360  2549  2612 I bt_vendor: epilog_cb
08-05 08:05:31.360  2549  2612 I bt_hci  : epilog_finished_callback
,08-05 08:05:31.367  2549  2606 I bt_hci_h4: hal_close
,08-05 08:05:31.368  2549  2606 I bt_userial_vendor: device fd = 51 close
,08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.k.d(PG:583)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.419  3841  3841 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.419  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.420  3841  3841 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.420  3841  3841 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:05:31.420  3841  3841 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:05:31.426  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-05 08:05:31.437  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:31.464  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-05 08:05:31.483   872   883 I ActivityManager: Start proc 3877:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-05 08:05:31.487  3825  3825 D DockEventReceiver: finishStartingService: stopping service
08-05 08:05:31.489   872  1777 I ActivityManager: Killing 3480:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-05 08:05:31.552  2549  2602 D bt_stack_manager: event_shut_down_stack finished.
,08-05 08:05:31.552  2549  2601 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-05 08:05:31.554  2549  2601 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-05 08:05:31.555  2549  2549 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 08:05:31.556  2549  2549 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 08:05:31.556  2549  2549 D BtGatt.GattService: stop()
08-05 08:05:31.556  2549  2549 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 08:05:31.569  2549  2549 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:31.569  2549  2549 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:31.569  2549  2549 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:31.570  2549  2549 V BluetoothAdapterState: isBleTurningOff()=true
08-05 08:05:31.570  2549  2601 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-05 08:05:31.570  2549  2601 D BluetoothAdapterProperties: Setting state to 10
08-05 08:05:31.570  2549  2601 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-05 08:05:31.571  2549  2601 I BluetoothAdapterState: Entering OffState
,08-05 08:05:31.572   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-05 08:05:31.574  3877  3877 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-05 08:05:31.590  2549  2549 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-05 08:05:31.590  2549  2549 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-05 08:05:31.590  2549  2549 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 08:05:31.591  2549  2602 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-05 08:05:31.593  2549  2602 D bt_stack_manager: event_clean_up_stack finished.
,08-05 08:05:31.612  2549  2549 I art     : System.exit called, status: 0
,08-05 08:05:31.612  2549  2549 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 08:05:31.693   872   883 I ActivityManager: Process com.android.bluetooth (pid 2549) has died
,08-05 08:05:31.709  3877  3877 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-05 08:05:31.727  3841  3865 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-05 08:05:31.741   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99e96a:true
,08-05 08:05:31.744   872   882 I ActivityManager: Start proc 3904:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-05 08:05:31.800  3904  3904 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-05 08:05:31.961  3904  3921 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-05 08:05:31.961  3904  3921 I Babel_SMS: MmsConfig.loadMmsSettings
08-05 08:05:31.962  3904  3921 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-05 08:05:31.962  3904  3921 I Babel_SMS: MmsConfig.loadFromDatabase
,08-05 08:05:31.996  3904  3921 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-05 08:05:31.996  3904  3921 I Babel_SMS: MmsConfig.loadFromResources
08-05 08:05:31.997  3904  3921 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-05 08:05:31.998  3904  3921 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-05 08:05:32.027  3904  3904 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 08:05:32.030  3904  3904 I Babel_Crash: startup - clean
,08-05 08:05:32.052  3904  3904 I Babel_telephony: TeleModule.launchCompleted
,08-05 08:05:32.064   872  1531 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-05 08:05:32.075  3904  3904 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-05 08:05:32.083  3904  3904 W Babel   : BAM#gBA: invalid account id: -1
,08-05 08:05:32.083  3904  3904 W Babel   : BAM#gBA: invalid account id: -1
08-05 08:05:32.083  3904  3904 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-05 08:05:32.092  3904  3926 I Babel   : deleted: false for 0
,08-05 08:05:32.101   872   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-05 08:05:32.145  1974  1974 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-05 08:05:32.151  1974  2345 I iu.UploadsManager: num queued entries: 0
,08-05 08:05:32.153  1974  2345 I iu.UploadsManager: num updated entries: 0
,08-05 08:05:32.158  1974  1974 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 08:05:32.161  1974  2345 I iu.SyncManager: NEXT; no task
,08-05 08:05:32.163  1974  1974 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 08:05:32.183  3904  3904 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:05:32.192   872  1777 I ActivityManager: Start proc 3929:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-05 08:05:32.229  3904  3904 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 08:05:32.242  3904  3904 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:05:32.252  3904  3904 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:05:32.263  3904  3904 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:05:32.271  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-05 08:05:32.274  3904  3904 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 08:05:32.278  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:32.289   872   883 I ActivityManager: Killing 3500:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-05 08:05:32.297  3929  3929 D SprintDMHelper: simOperator: 
,08-05 08:05:32.298  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 08:05:32.380   872  1732 I ActivityManager: Start proc 3941:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-05 08:05:32.382   872  1732 I ActivityManager: Killing 3318:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-05 08:05:32.434  3904  3904 I vclib   : onServiceConnected
,08-05 08:05:32.523   872  3421 I ActivityManager: Start proc 3956:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-05 08:05:32.527  3904  3955 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-05 08:05:32.530   872   883 I ActivityManager: Killing 3365:android.process.acore/u0a5 (adj 15): empty #17
,08-05 08:05:32.595  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-05 08:05:32.648  3956  3956 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-05 08:05:32.648  3956  3956 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-05 08:05:32.648  3956  3956 I GAv4    :   adb logcat -s GAv4
,08-05 08:05:32.662  3956  3956 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:05:32.668  3956  3956 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:05:32.702  3956  3973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:05:32.806  3956  3956 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-05 08:05:32.842  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 08:05:32.850  3956  3956 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1896-1899)
,08-05 08:05:32.850  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 08:05:32.862  3956  3956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f54717}
,08-05 08:05:32.863  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 08:05:32.863  3956  3956 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 08:05:32.876  3956  3956 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 08:05:32.878  3956  3956 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 08:05:32.895  3956  3956 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-05 08:05:32.908  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-05 08:05:32.908  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 08:05:32.908  3956  3956 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 08:05:32.908  3956  3956 I Adreno  : Build Date                       : 10/20/15
08-05 08:05:32.908  3956  3956 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 08:05:32.908  3956  3956 I Adreno  : Local Branch                     : M14
08-05 08:05:32.908  3956  3956 I Adreno  : Remote Branch                    : 
08-05 08:05:32.908  3956  3956 I Adreno  : Remote Branch                    : 
08-05 08:05:32.908  3956  3956 I Adreno  : Reconstruct Branch               : 
,08-05 08:05:32.970  3956  3956 I NSApplication: Starting up...
,08-05 08:05:32.978  3956  4002 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-05 08:05:33.004   872  1747 I ActivityManager: Start proc 4007:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-05 08:05:33.005   872  1747 I ActivityManager: Killing 3596:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-05 08:05:33.070  4007  4007 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-05 08:05:33.249   872  1777 I ActivityManager: Killing 3611:com.android.musicfx/u0a18 (adj 15): empty #17
,08-05 08:05:33.271  3423  3432 W art     : Suspending all threads took: 6.107ms
,08-05 08:05:34.062   872   882 D WifiService: setWifiEnabled: true pid=3771, uid=10000
08-05 08:05:34.063   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:05:34.074   872  1314 D WifiConfigStore: Loading config and enabling all networks 
08-05 08:05:34.085  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:34.085  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:34.085  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:34.085  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:34.086  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:34.086  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:34.086  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:34.086  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:34.109   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-05 08:05:34.110   872  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 08:05:34.110   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-05 08:05:34.111   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-05 08:05:34.112   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-05 08:05:34.112   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-05 08:05:34.113   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-05 08:05:34.113   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-05 08:05:34.126   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 08:05:34.126   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-05 08:05:34.128   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:34.178   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-05 08:05:34.178   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-05 08:05:34.184   872  1314 E native  : do suspend true
,08-05 08:05:34.199   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 08:05:34.200   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-05 08:05:34.216   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 08:05:35.630   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 08:05:35.701   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.19 rxSuccessRate=12.88 delta 1000 -> 994
,08-05 08:05:35.703   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-05 08:05:35.703   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 08:05:35.720   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-05 08:05:35.766   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-05 08:05:35.768  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-05 08:05:36.201  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 08:05:36.237  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-05 08:05:36.238  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-05 08:05:36.242   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 08:05:36.248   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 08:05:36.248   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:05:36.248   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-05 08:05:36.267   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 08:05:36.281   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:36.282   872  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-05 08:05:36.287   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-05 08:05:36.314   872  4030 D DhcpClient: Receive thread started
,08-05 08:05:36.394   872  1314 E native  : do suspend false
,08-05 08:05:36.412   872  1992 D DhcpClient: Broadcasting DHCPDISCOVER
,08-05 08:05:36.426   872  4030 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172417, domain null
,08-05 08:05:36.427   872  1992 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172417 seconds
,08-05 08:05:36.429   872  1992 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-05 08:05:36.440   872  4030 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-05 08:05:36.441   872  1992 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-05 08:05:36.445   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:36.449   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-05 08:05:36.452   872  1314 E native  : do suspend true
,08-05 08:05:36.453   872  1992 D DhcpClient: Scheduling renewal in 86399s,
,08-05 08:05:36.470   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-05 08:05:36.472   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-05 08:05:36.473   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-05 08:05:36.476   872  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-05 08:05:36.483   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-05 08:05:36.557   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 08:05:36.557   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 08:05:36.560   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-05 08:05:36.562   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-05 08:05:36.565   872  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-05 08:05:36.579   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-05 08:05:36.585   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-05 08:05:36.585   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-05 08:05:36.586   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-05 08:05:36.586   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 08:05:36.587   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-05 08:05:36.587   872  1316 D ConnectivityService:    accepting network in place of null
08-05 08:05:36.588   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 08:05:36.598   872  4029 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405647, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:05:36.654   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:36.681   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 08:05:36.703   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:36.708   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 08:05:36.708   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:36.711   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 08:05:36.713   872   889 D Tethering: MasterInitialState.processMessage what=3
08-05 08:05:36.731  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:36.731  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:05:36.731  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:36.731  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:36.735  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:36.735  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:05:36.735  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:36.735  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 08:05:36.759  1974  1974 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-05 08:05:36.760  1974  2345 I iu.UploadsManager: num queued entries: 0
,08-05 08:05:36.762  1974  2345 I iu.UploadsManager: num updated entries: 0
,08-05 08:05:36.764  1974  2345 I iu.SyncManager: NEXT; no task
,08-05 08:05:36.775  1974  1974 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 08:05:36.777  1974  1974 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 08:05:36.780   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 06:05:36 GMT], X-Android-Received-Millis=[1470377136778], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470377136736]}
,08-05 08:05:36.781  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:36.783   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 08:05:36.783   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-05 08:05:36.783   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-05 08:05:36.785   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-05 08:05:36.793  1974  4044 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-05 08:05:36.793  1974  4044 W BaseAppContext: Using Auth Proxy for data requests.
,08-05 08:05:36.797  3929  3929 D SprintDMHelper: simOperator: 
,08-05 08:05:36.797  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 08:05:36.802  1974  4044 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 08:05:36.825  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:05:36.828  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:05:36.960  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-05 08:05:36.960  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-05 08:05:36.960  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:05:36.960  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:05:36.979  1974  4044 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-05 08:05:37.038  3904  4047 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-05 08:05:37.041   872  1380 I ActivityManager: Killing 2044:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-05 08:05:37.068   872  1766 D WifiService: setWifiEnabled: false pid=3771, uid=10000
,08-05 08:05:37.068   872  1766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:05:37.093  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 08:05:37.096   872  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-05 08:05:37.096   872  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-05 08:05:37.096   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-05 08:05:37.097   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 08:05:37.117   872  1314 E native  : do suspend true
,08-05 08:05:37.125   872  1992 D DhcpClient: Clearing IP address
,08-05 08:05:37.126   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:37.128   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-05 08:05:37.131   872  4030 D DhcpClient: Receive thread stopped
,08-05 08:05:37.135  1516  4051 V NativeCrypto: Read error: ssl=0x9aface00: I/O error during system call, Connection timed out
,08-05 08:05:37.136  1516  4051 V NativeCrypto: SSL shutdown failed: ssl=0x9aface00: I/O error during system call, Broken pipe
,08-05 08:05:37.146   872  1732 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-05 08:05:37.146   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-05 08:05:37.147   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 08:05:37.147   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED,
,08-05 08:05:37.147   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-05 08:05:37.148   872  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-05 08:05:37.153   401   401 E Parcel  : Reading a NULL string not supported here.
,08-05 08:05:37.156   872  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-05 08:05:37.163   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-05 08:05:37.164   872  1314 E native  : do suspend true
,08-05 08:05:37.165   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-05 08:05:37.188   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:37.205   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:37.206   872  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 08:05:37.206   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:37.209   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-05 08:05:37.209   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-05 08:05:37.225  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:37.225  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:37.225  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:37.225  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:37.227  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:37.227  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:37.227  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:37.227  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:37.243  1974  1974 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-05 08:05:37.244  1974  2345 I iu.UploadsManager: num queued entries: 0
08-05 08:05:37.244  1974  2345 I iu.UploadsManager: num updated entries: 0
,08-05 08:05:37.249  1974  2345 I iu.SyncManager: NEXT; no task
,08-05 08:05:37.252  1974  1974 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-05 08:05:37.253  1974  1974 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 08:05:37.254  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:37.258  3929  3929 D SprintDMHelper: simOperator: 
,08-05 08:05:37.258  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 08:05:37.281  3904  4063 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-05 08:05:37.323   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-05 08:05:37.326   872  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-05 08:05:37.326   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 08:05:37.329   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 08:05:37.342   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 08:05:37.348   872  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-05 08:05:37.354  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:37.354  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:37.354  1861  2072 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 08:05:37.354  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:37.354  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:37.355  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:37.355  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:37.355  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:37.355  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:37.708   872  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-05 08:05:40.114   872   889 I ActivityManager: Start proc 4069:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-05 08:05:40.256  4069  4069 D AdapterServiceConfig: Adding HeadsetService
,08-05 08:05:40.256  4069  4069 D AdapterServiceConfig: Adding A2dpService
08-05 08:05:40.256  4069  4069 D AdapterServiceConfig: Adding HidService
08-05 08:05:40.257  4069  4069 D AdapterServiceConfig: Adding HealthService
,08-05 08:05:40.257  4069  4069 D AdapterServiceConfig: Adding PanService
,08-05 08:05:40.257  4069  4069 D AdapterServiceConfig: Adding GattService
08-05 08:05:40.257  4069  4069 D AdapterServiceConfig: Adding BluetoothMapService
,08-05 08:05:40.273   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccc41f5:true
,08-05 08:05:40.273  4069  4069 D BluetoothAdapterState: make() - Creating AdapterState
,08-05 08:05:40.278  4069  4069 I bt_bluedroid: init
,08-05 08:05:40.279  4069  4081 I BluetoothAdapterState: Entering OffState
,08-05 08:05:40.285  4069  4082 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-05 08:05:40.285  4069  4082 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 08:05:40.285  4069  4082 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 08:05:40.286  4069  4082 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-05 08:05:40.288  4069  4069 I bt_bluedroid: get_profile_interface socket
,08-05 08:05:40.291  4069  4069 I bt_bluedroid: get_profile_interface sdp
,08-05 08:05:40.294  4069  4085 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 08:05:40.298  4069  4085 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 08:05:40.298  4069  4080 I bt_bluedroid: config_hci_snoop_log
,08-05 08:05:40.302   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-05 08:05:40.314  4069  4081 D BluetoothAdapterState: Current state: OFF, message: 0
,08-05 08:05:40.314  4069  4081 D BluetoothAdapterProperties: Setting state to 14
,08-05 08:05:40.315  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-05 08:05:40.319  4069  4081 D BluetoothBondStateMachine: make
,08-05 08:05:40.325  4069  4086 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 08:05:40.334  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
,08-05 08:05:40.337  4069  4069 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-05 08:05:40.347  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:40.350  4069  4069 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 08:05:40.352  4069  4069 D BtGatt.GattService: Received start request. Starting profile...
,08-05 08:05:40.352  4069  4069 D BtGatt.GattService: start()
08-05 08:05:40.353  4069  4069 I bt_bluedroid: get_profile_interface gatt
08-05 08:05:40.356  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:40.356  4069  4069 D BtGatt.AdvertiseManager: advertise manager created
,08-05 08:05:40.366  4069  4069 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:40.366  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:40.366  4069  4069 V BluetoothAdapterState: isBleTurningOn()=true
08-05 08:05:40.366  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:40.367  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-05 08:05:40.367  4069  4081 I bt_bluedroid: enable
,08-05 08:05:40.368  4069  4082 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-05 08:05:40.370  4069  4082 I bt_hci  : start_up
,08-05 08:05:40.392  4069  4082 I bt_vendor: alloc value 0xb39e1189
08-05 08:05:40.392  4069  4082 I bt_vendor: init
,08-05 08:05:40.393  4069  4082 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-05 08:05:40.393  4069  4082 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-05 08:05:40.504  4069  4082 D bt_hci  : start_up starting async portion
08-05 08:05:40.504  4069  4089 I bt_hci  : event_finish_startup
08-05 08:05:40.505  4069  4089 I bt_hci_h4: hal_open
08-05 08:05:40.505  4069  4089 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 08:05:40.514  4069  4089 I bt_userial_vendor: device fd = 51 open
,08-05 08:05:40.544  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 08:05:40.576  4069  4089 D bt_hwcfg: Chipset BCM4354A2
08-05 08:05:40.577  4069  4089 D bt_hwcfg: Target name = [BCM4354A2]
,08-05 08:05:40.577  4069  4089 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-05 08:05:41.231  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-05 08:05:41.232  4069  4089 D bt_hwcfg: Settlement delay -- 100 ms
08-05 08:05:41.232  4069  4089 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 08:05:41.349  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 08:05:41.351  4069  4089 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-05 08:05:41.379  4069  4089 I bt_hwcfg: vendor lib fwcfg completed
,08-05 08:05:41.379  4069  4089 I bt_vendor: firmware callback
08-05 08:05:41.380  4069  4089 I bt_hci  : firmware_config_callback
,08-05 08:05:41.392  4069  4091 I bt_btu  : btu_task pending for preload complete event
,08-05 08:05:41.392  4069  4091 I bt_btu_task: Bluetooth chip preload is complete
08-05 08:05:41.393  4069  4091 I bt_btu  : btu_task received preload complete event
,08-05 08:05:41.404  4069  4091 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 08:05:41.404  4069  4091 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-05 08:05:41.404  4069  4091 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 08:05:41.405  4069  4091 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 08:05:41.405  4069  4091 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 08:05:41.405  4069  4091 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 08:05:41.405  4069  4091 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 08:05:41.406  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTM
,08-05 08:05:41.406  4069  4091 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 08:05:41.407  4069  4091 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 08:05:41.407  4069  4091 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 08:05:41.407  4069  4091 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 08:05:41.408  4069  4091 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 08:05:41.408  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-05 08:05:41.409  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 08:05:41.545  4069  4091 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395ed9d
,08-05 08:05:41.545  4069  4091 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395ed9d 
,08-05 08:05:41.569  4069  4085 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-05 08:05:41.571  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 08:05:41.571  4069  4085 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 08:05:41.573  4069  4085 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 08:05:41.576  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
,08-05 08:05:41.576  4069  4085 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:05:41.577  4069  4085 D bt_hci  : do_postload posting postload work item
,08-05 08:05:41.578  4069  4089 I bt_hci  : event_postload
08-05 08:05:41.579  4069  4089 I bt_vendor: sco_config_cb
08-05 08:05:41.579  4069  4089 I bt_hci  : sco_config_callback postload finished.
08-05 08:05:41.580  4069  4085 D bt_bte_conf: Device ID record 1 : primary
08-05 08:05:41.580  4069  4085 D bt_bte_conf:   vendorId            = 000f
08-05 08:05:41.580  4069  4085 D bt_bte_conf:   vendorIdSource      = 0001
08-05 08:05:41.580  4069  4085 D bt_bte_conf:   product             = 1200
08-05 08:05:41.581  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:41.581  4069  4085 D bt_bte_conf:   version             = 1436
08-05 08:05:41.581  4069  4085 D bt_bte_conf:   clientExecutableURL = 
08-05 08:05:41.581  4069  4085 D bt_bte_conf:   serviceDescription  = 
08-05 08:05:41.581  4069  4085 D bt_bte_conf:   documentationURL    = 
,08-05 08:05:41.582  4069  4085 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-05 08:05:41.582  4069  4082 D bt_stack_manager: event_start_up_stack finished
08-05 08:05:41.583  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-05 08:05:41.583  4069  4081 D BluetoothAdapterProperties: Setting state to 15
08-05 08:05:41.584  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-05 08:05:41.584  4069  4081 I BluetoothAdapterState: Entering BleOnState
,08-05 08:05:41.585  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:41.586  4069  4089 I bt_vendor: low_power_mode_cb
,08-05 08:05:41.591  4069  4081 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-05 08:05:41.591  4069  4081 D BluetoothAdapterProperties: Setting state to 11
08-05 08:05:41.591  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-05 08:05:41.598  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:41.599  4069  4069 D HeadsetService: Received start request. Starting profile...
,08-05 08:05:41.604  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:41.607  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:41.609  4069  4069 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 08:05:41.609  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
08-05 08:05:41.611  4069  4069 D HeadsetStateMachine: make
,08-05 08:05:41.620  4069  4069 D HeadsetStateMachine: max_hf_connections = 1
,08-05 08:05:41.620  4069  4069 I bt_bluedroid: get_profile_interface handsfree
08-05 08:05:41.620  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-05 08:05:41.620  4069  4085 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-05 08:05:41.624  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:41.625  4069  4069 D A2dpService: Received start request. Starting profile...
,08-05 08:05:41.626  4069  4069 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 08:05:41.626  4069  4069 I bt_bluedroid: get_profile_interface avrcp
,08-05 08:05:41.633  4069  4069 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 08:05:41.633  4069  4069 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:05:41.633  4069  4069 D A2dpStateMachine: make
,08-05 08:05:41.635  4069  4069 I bt_bluedroid: get_profile_interface a2dp
08-05 08:05:41.636  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-05 08:05:41.638  4069  4100 D A2dpStateMachine: Enter Disconnected: -2
,08-05 08:05:41.638  4069  4069 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 08:05:41.639  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:41.640  4069  4069 D HidService: Received start request. Starting profile...
08-05 08:05:41.640  3825  3825 D BluetoothInputDevice: Proxy object connected
,08-05 08:05:41.640  4069  4069 I bt_bluedroid: get_profile_interface hidhost
08-05 08:05:41.640  4069  4069 D HidService: setHidService(): set to: null
08-05 08:05:41.640  4069  4085 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39403e5
08-05 08:05:41.641  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-05 08:05:41.641  4069  4069 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:05:41.641  3825  3825 D HidProfile: Bluetooth service connected
08-05 08:05:41.642  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:41.642  4069  4069 D HealthService: Received start request. Starting profile...
08-05 08:05:41.644  4069  4069 I bt_bluedroid: get_profile_interface health,
,08-05 08:05:41.645  4069  4069 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 08:05:41.646  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:41.647  4069  4069 D PanService: Received start request. Starting profile...
,08-05 08:05:41.647  3825  3825 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 08:05:41.647  4069  4069 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-05 08:05:41.647  4069  4069 I bt_bluedroid: get_profile_interface pan
08-05 08:05:41.649  4069  4085 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 08:05:41.650  3825  3825 D PanProfile: Bluetooth service connected
08-05 08:05:41.650  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:41.652  4069  4069 D BluetoothMapService: Received start request. Starting profile...
08-05 08:05:41.652  4069  4069 D BluetoothMapService: start()
,08-05 08:05:41.653  3825  3825 D BluetoothMap: Proxy object connected
08-05 08:05:41.653  3825  3825 D MapProfile: Bluetooth service connected
08-05 08:05:41.654  3825  3825 D BluetoothMap: getConnectedDevices()
08-05 08:05:41.655  4069  4069 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-05 08:05:41.655  3825  3825 D BluetoothMap: Bluetooth is Not enabled
08-05 08:05:41.656  4069  4069 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-05 08:05:41.656  4069  4069 D BluetoothMapAppObserver: createReceiver()
08-05 08:05:41.657  4069  4069 D BluetoothMapAppObserver: initObservers()
08-05 08:05:41.657  4069  4069 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-05 08:05:41.667  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,08-05 08:05:41.667  4069  4069 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:41.667  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:41.667  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:41.668  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOn()=true
,08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:41.670  4069  4098 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 08:05:41.670  4069  4069 V BluetoothAdapterState: isTurningOn()=true
,08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:41.671  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:41.672  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-05 08:05:41.672  4069  4081 D BluetoothAdapterProperties: ScanMode =  20
,08-05 08:05:41.672  4069  4081 D BluetoothAdapterProperties: State =  11
08-05 08:05:41.676  4069  4085 D BluetoothAdapterProperties: Scan Mode:21
08-05 08:05:41.676  4069  4081 D BluetoothAdapterProperties: Setting state to 12
08-05 08:05:41.677  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 08:05:41.677  4069  4085 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:05:41.678  4069  4081 I BluetoothAdapterState: Entering OnState
08-05 08:05:41.678  1370  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:41.680  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:41.681   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:05:41.681  3825  3835 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:05:41.683  1370  1839 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:05:41.683  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:41.685  3825  3836 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:05:41.685  4069  4069 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-05 08:05:41.685  4069  4069 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-05 08:05:41.686  1370  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-05 08:05:41.687  4069  4069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:05:41.688  1370  1370 D BluetoothMap: Proxy object connected
08-05 08:05:41.688  1370  1839 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 08:05:41.688  1370  1370 D MapProfile: Bluetooth service connected
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:41.688  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:41.688  1370  1370 D BluetoothMap: getConnectedDevices()
08-05 08:05:41.690   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 08:05:41.691  1370  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 08:05:41.691  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:41.693  1370  1370 D BluetoothInputDevice: Proxy object connected
08-05 08:05:41.693  1370  1370 D HidProfile: Bluetooth service connected
08-05 08:05:41.693   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:41.694  4069  4069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:05:41.694  1739  1755 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:41.695  3825  3835 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 08:05:41.695  4069  4069 D ObexServerSockets: Succeed to create listening sockets 
08-05 08:05:41.696  4069  4069 D ObexServerSockets0: startAccept()
,08-05 08:05:41.696  3825  3836 D BluetoothMap: onBluetoothStateChange: up=true
08-05 08:05:41.696  4069  4069 D ObexServerSockets0: prepareForNewConnect()
08-05 08:05:41.696  1370  1839 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:05:41.698  4069  4069 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-05 08:05:41.698  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 08:05:41.699  1370  1370 D PanProfile: Bluetooth service connected
,08-05 08:05:41.699   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:05:41.699  4069  4069 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-05 08:05:41.701   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-05 08:05:41.705  4069  4107 D ObexServerSockets0: Accepting socket connection...
,08-05 08:05:41.706  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:41.707  1370  1370 D BluetoothA2dp: Proxy object connected
,08-05 08:05:41.707   872   872 D BluetoothA2dp: Proxy object connected
,08-05 08:05:41.707  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:41.708  4069  4106 D ObexServerSockets0: Accepting socket connection...
08-05 08:05:41.708  4069  4069 D BluetoothMapService: onReceive
08-05 08:05:41.708  4069  4069 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:05:41.708  4069  4069 D BluetoothMapService: STATE_ON
08-05 08:05:41.709  3825  3825 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-05 08:05:41.723  3825  3825 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-05 08:05:41.728  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 08:05:41.729  4069  4069 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-05 08:05:41.729  4069  4069 D ObexServerSockets0: prepareForNewConnect()
,08-05 08:05:41.734  3825  3825 D BluetoothA2dp: Proxy object connected
,08-05 08:05:41.737  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:41.742  3825  3825 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:05:41.750  3825  3825 D BluetoothPbap: Proxy object connected
,08-05 08:05:41.750  1370  1370 D BluetoothPbap: Proxy object connected
08-05 08:05:41.751  1370  1370 D PbapServerProfile: Bluetooth service connected
08-05 08:05:41.751  3825  3825 D PbapServerProfile: Bluetooth service connected
,08-05 08:05:41.761  4069  4112 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:05:41.782   872   872 D BluetoothHeadset: Proxy object connected
,08-05 08:05:41.782  4069  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:05:41.782   872   872 D BluetoothHeadset: Proxy object connected
08-05 08:05:41.783   872   872 D BluetoothHeadset: Proxy object connected
08-05 08:05:41.783  1739  1858 D BluetoothHeadset: Proxy object connected
08-05 08:05:41.784  1370  1385 D BluetoothHeadset: Proxy object connected
08-05 08:05:41.785  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-05 08:05:41.786  4069  4116 I BtOppRfcommListener: Accept thread started.
,08-05 08:05:41.794   872   889 D BluetoothHeadset: Proxy object connected
,08-05 08:05:41.795  1739  1985 D BluetoothHeadset: Proxy object connected
,08-05 08:05:41.799   872   889 D BluetoothHeadset: Proxy object connected
,08-05 08:05:41.826  3825  3836 D BluetoothHeadset: Proxy object connected
,08-05 08:05:41.827  3825  3825 D HeadsetProfile: Bluetooth service connected
,08-05 08:05:41.867  1516  2295 I art     : Waiting for a blocking GC DisableMovingGc
,08-05 08:05:41.876  1516  2295 I art     : WaitForGcToComplete blocked for 9.565ms for cause DisableMovingGc
,08-05 08:05:41.877  1516  2295 I art     : Starting a blocking GC DisableMovingGc
,08-05 08:05:43.087  4069  4081 D BluetoothAdapterState: Current state: ON, message: 23
,08-05 08:05:43.087  4069  4081 D BluetoothAdapterProperties: Setting state to 13
,08-05 08:05:43.088  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-05 08:05:43.090  4069  4081 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 08:05:43.097  4069  4069 D BluetoothMapService: onReceive
08-05 08:05:43.098  4069  4069 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 08:05:43.098  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
08-05 08:05:43.098  4069  4069 D BluetoothMapService: STATE_TURNING_OFF
08-05 08:05:43.099  4069  4069 D BluetoothMapService: MAP Service closeService in
,08-05 08:05:43.099  4069  4069 D BluetoothMapMasInstance0: MAP Service shutdown
08-05 08:05:43.099  4069  4069 D ObexServerSockets0: shutdown(block = true)
08-05 08:05:43.101  4069  4106 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-05 08:05:43.104  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 08:05:43.104  4069  4069 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:43.105  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:43.105  4069  4107 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-05 08:05:43.110  4069  4093 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-05 08:05:43.110  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:43.110  4069  4069 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 08:05:43.111  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:43.111  4069  4069 I BtOppRfcommListener: stopping Accept Thread
08-05 08:05:43.112  4069  4116 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 08:05:43.115  4069  4116 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 08:05:43.116  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:05:43.116  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-05 08:05:43.118  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:43.118  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:43.119  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-05 08:05:43.121  3771  3771 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 08:05:43.121  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:43.125  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:43.127  4069  4069 D HeadsetService: Received stop request...Stopping profile...
08-05 08:05:43.129  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:43.131   872   872 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:43.131   872   872 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:43.132  3825  3835 D BluetoothHeadset: Proxy object disconnected
,08-05 08:05:43.133  4069  4069 D A2dpService: Received stop request...Stopping profile...
08-05 08:05:43.133   872   872 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:43.133  4069  4100 D A2dpStateMachine: Exit Disconnected: -1
08-05 08:05:43.133  1739  1752 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:43.135  1370  1839 D BluetoothHeadset: Proxy object disconnected
08-05 08:05:43.135  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-05 08:05:43.135  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-05 08:05:43.135   872   872 D BluetoothA2dp: Proxy object disconnected
08-05 08:05:43.136  4069  4069 D HidService: Received stop request...Stopping profile...
08-05 08:05:43.136  4069  4069 D HidService: Stopping Bluetooth HidService
,08-05 08:05:43.138  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-05 08:05:43.138  1370  1370 D HidProfile: Bluetooth service disconnected
,08-05 08:05:43.138  3825  3825 D DockEventReceiver: finishStartingService: stopping service
08-05 08:05:43.139  4069  4069 D HealthService: Received stop request...Stopping profile...
08-05 08:05:43.139  3825  3825 D HeadsetProfile: Bluetooth service disconnected
08-05 08:05:43.140  3825  3825 D BluetoothA2dp: Proxy object disconnected
,08-05 08:05:43.142  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:43.142  4069  4069 D PanService: Received stop request...Stopping profile...
,08-05 08:05:43.143  3825  3825 D BluetoothInputDevice: Proxy object disconnected
08-05 08:05:43.143  3825  3825 D HidProfile: Bluetooth service disconnected
,08-05 08:05:43.145  4069  4069 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:43.145  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,08-05 08:05:43.145  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:43.145  3825  3825 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 08:05:43.145  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:43.145  3825  3825 D PanProfile: Bluetooth service disconnected
08-05 08:05:43.146  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 08:05:43.146  1370  1370 D PanProfile: Bluetooth service disconnected
,08-05 08:05:43.148  4069  4069 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 08:05:43.148  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-05 08:05:43.148  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 08:05:43.148  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:43.148  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:43.148  4069  4069 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 08:05:43.148  4069  4085 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-05 08:05:43.149  4069  4069 D BluetoothMapService: Received stop request...Stopping profile...
08-05 08:05:43.149  4069  4069 D BluetoothMapService: stop()
08-05 08:05:43.149  4069  4069 D BluetoothMapAppObserver: deinitObservers()
,08-05 08:05:43.149  4069  4069 D BluetoothMapAppObserver: removeReceiver()
,08-05 08:05:43.150  1370  1370 D BluetoothMap: Proxy object disconnected
,08-05 08:05:43.151  1370  1370 D MapProfile: Bluetooth service disconnected
08-05 08:05:43.151  4069  4069 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:43.151  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:43.151  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:43.151  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:43.152  3825  3825 D BluetoothMap: Proxy object disconnected
08-05 08:05:43.152  3825  3825 D MapProfile: Bluetooth service disconnected
08-05 08:05:43.152  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-05 08:05:43.152  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:43.153  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:43.153  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 08:05:43.153  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:05:43.153  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 08:05:43.153  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 08:05:43.153  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,08-05 08:05:43.153  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:43.153  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:43.153  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:43.154  4069  4069 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 08:05:43.154  4069  4069 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 08:05:43.154  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 08:05:43.156  1370  1370 D BluetoothPbap: Proxy object disconnected
08-05 08:05:43.156  1370  1370 D PbapServerProfile: Bluetooth service disconnected
08-05 08:05:43.156  4069  4069 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:43.157  3825  3825 D BluetoothPbap: Proxy object disconnected
,08-05 08:05:43.157  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:43.157  3825  3825 D PbapServerProfile: Bluetooth service disconnected
08-05 08:05:43.157  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:43.157  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:43.157  4069  4069 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 08:05:43.157  4069  4085 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-05 08:05:43.158  4069  4069 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 08:05:43.158  4069  4069 V BluetoothAdapterState: isTurningOff()=true
08-05 08:05:43.158  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:43.158  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:43.158  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:43.158  4069  4069 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 08:05:43.159  4069  4069 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 08:05:43.159  4069  4069 D BluetoothMapService: MAP Service closeService in
08-05 08:05:43.160  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,08-05 08:05:43.160  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,08-05 08:05:43.160  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:43.160  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:43.160  4069  4069 D BluetoothMapService: cleanup()
08-05 08:05:43.160  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-05 08:05:43.160  4069  4069 D BluetoothMapService: MAP Service closeService in
,08-05 08:05:43.160  4069  4081 D BluetoothAdapterProperties: Setting state to 15
08-05 08:05:43.160  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-05 08:05:43.161  4069  4081 I BluetoothAdapterState: Entering BleOnState
08-05 08:05:43.162  1370  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:43.163   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:43.163  3825  3836 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 08:05:43.163  1370  1839 D BluetoothPbap: onBluetoothStateChange: up=false
,08-05 08:05:43.164  3825  3835 D BluetoothPan: onBluetoothStateChange on: false
08-05 08:05:43.166  1370  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-05 08:05:43.166  1370  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:05:43.167   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 08:05:43.167  1370  1839 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 08:05:43.168   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:43.168  1739  1755 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 08:05:43.168  3825  3836 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 08:05:43.169  3825  3835 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 08:05:43.169  3825  3836 D BluetoothMap: onBluetoothStateChange: up=false
08-05 08:05:43.169  1370  1385 D BluetoothPan: onBluetoothStateChange on: false
,08-05 08:05:43.170   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 08:05:43.170  3825  3835 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 08:05:43.171  4069  4081 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-05 08:05:43.171  4069  4081 D BluetoothAdapterProperties: Setting state to 16
08-05 08:05:43.171  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-05 08:05:43.172  4069  4081 D BluetoothAdapterProperties: onBleDisable
08-05 08:05:43.172  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
08-05 08:05:43.172  4069  4082 D bt_stack_manager: event_shut_down_stack is bringing down the stack.,
08-05 08:05:43.174  4069  4091 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 08:05:43.175  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 08:05:43.175  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:43.176  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:05:43.176  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:43.178  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:43.178  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-05 08:05:43.179  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:43.184  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:43.187  3825  3825 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:05:43.375  4069  4085 I bt_hci  : shut_down
,08-05 08:05:43.377  4069  4089 I bt_vendor: low_power_mode_cb
08-05 08:05:43.378  4069  4089 D bt_hwcfg: hw_epilog_process
,08-05 08:05:43.397  4069  4089 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-05 08:05:43.398  4069  4089 I bt_vendor: epilog_cb
,08-05 08:05:43.398  4069  4089 I bt_hci  : epilog_finished_callback
,08-05 08:05:43.408  4069  4085 I bt_hci_h4: hal_close
,08-05 08:05:43.409  4069  4085 I bt_userial_vendor: device fd = 51 close
,08-05 08:05:43.544  4069  4082 D bt_stack_manager: event_shut_down_stack finished.
,08-05 08:05:43.545  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-05 08:05:43.553  4069  4069 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 08:05:43.553  4069  4081 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-05 08:05:43.555  4069  4069 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 08:05:43.555  4069  4069 D BtGatt.GattService: stop()
,08-05 08:05:43.556  4069  4069 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 08:05:43.562  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,08-05 08:05:43.564  4069  4069 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:43.564  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:43.564  4069  4069 V BluetoothAdapterState: isBleTurningOff()=true
08-05 08:05:43.565  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-05 08:05:43.566  4069  4081 D BluetoothAdapterProperties: Setting state to 10
,08-05 08:05:43.566  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-05 08:05:43.569  4069  4081 I BluetoothAdapterState: Entering OffState
08-05 08:05:43.570   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-05 08:05:43.594  4069  4069 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-05 08:05:43.594  4069  4069 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-05 08:05:43.595  4069  4082 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-05 08:05:43.608  4069  4069 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 08:05:43.610  4069  4082 D bt_stack_manager: event_clean_up_stack finished.
,08-05 08:05:43.614  4069  4069 I art     : System.exit called, status: 0
08-05 08:05:43.614  4069  4069 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 08:05:43.670   872  1380 I ActivityManager: Process com.android.bluetooth (pid 4069) has died
,08-05 08:05:44.592   872  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-05 08:05:46.084  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 08:05:46.084  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:49.092  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 08:05:49.092  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d348e2 added. We now have 6 listener(s)
08-05 08:05:49.093  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:49.097  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:49.098  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f71473 added. We now have 7 listener(s)
08-05 08:05:49.098  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:49.100  3771  3817 I System.out: IsBluetoothEnabled
,08-05 08:05:49.110  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:49.159   872   889 I ActivityManager: Start proc 4128:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-05 08:05:49.294  4128  4128 D AdapterServiceConfig: Adding HeadsetService
,08-05 08:05:49.295  4128  4128 D AdapterServiceConfig: Adding A2dpService
08-05 08:05:49.295  4128  4128 D AdapterServiceConfig: Adding HidService
08-05 08:05:49.296  4128  4128 D AdapterServiceConfig: Adding HealthService
,08-05 08:05:49.297  4128  4128 D AdapterServiceConfig: Adding PanService,
08-05 08:05:49.297  4128  4128 D AdapterServiceConfig: Adding GattService
08-05 08:05:49.298  4128  4128 D AdapterServiceConfig: Adding BluetoothMapService
,08-05 08:05:49.316   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@283503e:true
,08-05 08:05:49.318  4128  4128 D BluetoothAdapterState: make() - Creating AdapterState
,08-05 08:05:49.325  4128  4140 I BluetoothAdapterState: Entering OffState
08-05 08:05:49.325  4128  4128 I bt_bluedroid: init
,08-05 08:05:49.328  4128  4141 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 08:05:49.328  4128  4141 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 08:05:49.328  4128  4141 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 08:05:49.329  4128  4141 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-05 08:05:49.330  4128  4128 I bt_bluedroid: get_profile_interface socket
,08-05 08:05:49.335  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 08:05:49.336  4128  4128 I bt_bluedroid: get_profile_interface sdp
,08-05 08:05:49.338  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 08:05:49.343  4128  4139 I bt_bluedroid: config_hci_snoop_log
,08-05 08:05:49.344   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-05 08:05:49.351  4128  4140 D BluetoothAdapterState: Current state: OFF, message: 0
,08-05 08:05:49.351  4128  4140 D BluetoothAdapterProperties: Setting state to 14
08-05 08:05:49.351  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-05 08:05:49.357  4128  4140 D BluetoothBondStateMachine: make
,08-05 08:05:49.362  4128  4145 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 08:05:49.371  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
,08-05 08:05:49.373  4128  4128 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-05 08:05:49.382  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:49.385  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 08:05:49.386  4128  4128 D BtGatt.GattService: Received start request. Starting profile...
,08-05 08:05:49.387  4128  4128 D BtGatt.GattService: start()
,08-05 08:05:49.387  4128  4128 I bt_bluedroid: get_profile_interface gatt
08-05 08:05:49.390  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:49.390  4128  4128 D BtGatt.AdvertiseManager: advertise manager created
,08-05 08:05:49.404  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:49.405  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-05 08:05:49.405  4128  4128 V BluetoothAdapterState: isBleTurningOn()=true
,08-05 08:05:49.405  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:49.405  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-05 08:05:49.406  4128  4140 I bt_bluedroid: enable
,08-05 08:05:49.407  4128  4141 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-05 08:05:49.408  4128  4141 I bt_hci  : start_up
,08-05 08:05:49.427  4128  4141 I bt_vendor: alloc value 0xb39e1189
,08-05 08:05:49.428  4128  4141 I bt_vendor: init
08-05 08:05:49.428  4128  4141 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-05 08:05:49.428  4128  4141 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-05 08:05:49.536  4128  4141 D bt_hci  : start_up starting async portion
,08-05 08:05:49.536  4128  4148 I bt_hci  : event_finish_startup
08-05 08:05:49.537  4128  4148 I bt_hci_h4: hal_open
,08-05 08:05:49.537  4128  4148 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 08:05:49.549  4128  4148 I bt_userial_vendor: device fd = 51 open
,08-05 08:05:49.578  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 08:05:49.610  4128  4148 D bt_hwcfg: Chipset BCM4354A2
,08-05 08:05:49.610  4128  4148 D bt_hwcfg: Target name = [BCM4354A2]
08-05 08:05:49.611  4128  4148 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-05 08:05:50.264  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-05 08:05:50.265  4128  4148 D bt_hwcfg: Settlement delay -- 100 ms
08-05 08:05:50.266  4128  4148 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 08:05:50.382  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 08:05:50.383  4128  4148 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-05 08:05:50.413  4128  4148 I bt_hwcfg: vendor lib fwcfg completed
,08-05 08:05:50.413  4128  4148 I bt_vendor: firmware callback
08-05 08:05:50.413  4128  4148 I bt_hci  : firmware_config_callback
,08-05 08:05:50.424  4128  4150 I bt_btu  : btu_task pending for preload complete event
,08-05 08:05:50.425  4128  4150 I bt_btu_task: Bluetooth chip preload is complete
08-05 08:05:50.425  4128  4150 I bt_btu  : btu_task received preload complete event
,08-05 08:05:50.437  4128  4150 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 08:05:50.438  4128  4150 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 08:05:50.438  4128  4150 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 08:05:50.438  4128  4150 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 08:05:50.439  4128  4150 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-05 08:05:50.439  4128  4150 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 08:05:50.439  4128  4150 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 08:05:50.439  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 08:05:50.440  4128  4150 I         : BTE_InitTraceLevels -- TRC_GAP
,08-05 08:05:50.440  4128  4150 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 08:05:50.440  4128  4150 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 08:05:50.441  4128  4150 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 08:05:50.441  4128  4150 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 08:05:50.441  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-05 08:05:50.441  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 08:05:50.582  4128  4150 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395ed9d
,08-05 08:05:50.582  4128  4150 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395ed9d 
,08-05 08:05:50.589  4128  4144 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-05 08:05:50.591  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-05 08:05:50.592  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 08:05:50.595  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
08-05 08:05:50.598  4128  4144 D BluetoothAdapterProperties: Scan Mode:20
08-05 08:05:50.598  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:05:50.599  4128  4144 D bt_hci  : do_postload posting postload work item
,08-05 08:05:50.599  4128  4148 I bt_hci  : event_postload
08-05 08:05:50.599  4128  4148 I bt_vendor: sco_config_cb
08-05 08:05:50.599  4128  4148 I bt_hci  : sco_config_callback postload finished.
08-05 08:05:50.603  4128  4144 D bt_bte_conf: Device ID record 1 : primary
,08-05 08:05:50.603  4128  4144 D bt_bte_conf:   vendorId            = 000f
,08-05 08:05:50.603  4128  4144 D bt_bte_conf:   vendorIdSource      = 0001
08-05 08:05:50.604  4128  4144 D bt_bte_conf:   product             = 1200
08-05 08:05:50.604  4128  4144 D bt_bte_conf:   version             = 1436
08-05 08:05:50.604  4128  4144 D bt_bte_conf:   clientExecutableURL = 
08-05 08:05:50.604  4128  4144 D bt_bte_conf:   serviceDescription  = 
,08-05 08:05:50.605  4128  4144 D bt_bte_conf:   documentationURL    = 
08-05 08:05:50.605  4128  4144 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-05 08:05:50.605  4128  4141 D bt_stack_manager: event_start_up_stack finished
,08-05 08:05:50.606  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-05 08:05:50.607  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:50.608  4128  4140 D BluetoothAdapterProperties: Setting state to 15
08-05 08:05:50.608  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-05 08:05:50.613  4128  4148 I bt_vendor: low_power_mode_cb
08-05 08:05:50.614  4128  4140 I BluetoothAdapterState: Entering BleOnState
08-05 08:05:50.617  4128  4140 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-05 08:05:50.618  4128  4140 D BluetoothAdapterProperties: Setting state to 11
08-05 08:05:50.618  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-05 08:05:50.627  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:50.630  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:50.636  4128  4128 D HeadsetService: Received start request. Starting profile...
,08-05 08:05:50.640  4128  4128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 08:05:50.640  4128  4128 D HeadsetStateMachine: make
,08-05 08:05:50.644  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
,08-05 08:05:50.650  4128  4128 D HeadsetStateMachine: max_hf_connections = 1
,08-05 08:05:50.650  4128  4128 I bt_bluedroid: get_profile_interface handsfree
08-05 08:05:50.651  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-05 08:05:50.651  4128  4144 E bt_btif : btif_hf_upstreams_evt: Invalid index 1027
,08-05 08:05:50.656  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:50.657  4128  4128 D A2dpService: Received start request. Starting profile...
,08-05 08:05:50.657  4128  4128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 08:05:50.657  4128  4128 I bt_bluedroid: get_profile_interface avrcp
,08-05 08:05:50.663  4128  4128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 08:05:50.663  4128  4128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 08:05:50.663  4128  4128 D A2dpStateMachine: make
,08-05 08:05:50.664  4128  4128 I bt_bluedroid: get_profile_interface a2dp
,08-05 08:05:50.665  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-05 08:05:50.668  4128  4158 D A2dpStateMachine: Enter Disconnected: -2
,08-05 08:05:50.670  4128  4128 I BluetoothHidServiceJni: classInitNative: succeeds
,08-05 08:05:50.671  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:50.672  4128  4128 D HidService: Received start request. Starting profile...
08-05 08:05:50.672  4128  4128 I bt_bluedroid: get_profile_interface hidhost
08-05 08:05:50.672  4128  4128 D HidService: setHidService(): set to: null
08-05 08:05:50.672  4128  4144 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39403e5
08-05 08:05:50.672  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-05 08:05:50.672  4128  4128 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 08:05:50.673  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:50.674  4128  4128 D HealthService: Received start request. Starting profile...
,08-05 08:05:50.676  4128  4128 I bt_bluedroid: get_profile_interface health
,08-05 08:05:50.677  4128  4128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 08:05:50.678  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
,08-05 08:05:50.679  4128  4128 D PanService: Received start request. Starting profile...
08-05 08:05:50.679  4128  4128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 08:05:50.679  4128  4128 I bt_bluedroid: get_profile_interface pan
,08-05 08:05:50.679  4128  4144 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 08:05:50.685  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:50.687  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:50.688  4128  4128 D BluetoothMapService: Received start request. Starting profile...
08-05 08:05:50.688  4128  4128 D BluetoothMapService: start()
,08-05 08:05:50.690  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-05 08:05:50.691  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-05 08:05:50.691  4128  4128 D BluetoothMapAppObserver: createReceiver()
,08-05 08:05:50.693  4128  4128 D BluetoothMapAppObserver: initObservers()
08-05 08:05:50.693  4128  4128 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-05 08:05:50.702  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-05 08:05:50.702  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.702  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:50.702  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:50.706  4128  4156 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-05 08:05:50.706  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:50.707  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:50.708  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.709  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:50.709  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:50.710  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-05 08:05:50.711  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-05 08:05:50.711  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-05 08:05:50.711  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-05 08:05:50.711  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-05 08:05:50.711  4128  4140 D BluetoothAdapterProperties: ScanMode =  20
,08-05 08:05:50.712  4128  4140 D BluetoothAdapterProperties: State =  11
,08-05 08:05:50.713  4128  4140 D BluetoothAdapterProperties: Setting state to 12
,08-05 08:05:50.713  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 08:05:50.714  4128  4144 D BluetoothAdapterProperties: Scan Mode:21
08-05 08:05:50.714  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 08:05:50.716  1370  1839 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:05:50.718   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:50.718  3825  3835 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:05:50.718  4128  4140 I BluetoothAdapterState: Entering OnState
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:50.720  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:50.720  1370  1385 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 08:05:50.721  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-05 08:05:50.721  4128  4128 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-05 08:05:50.722  3825  3836 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:05:50.723  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:50.724  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:05:50.724  1370  1384 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 08:05:50.727  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:05:50.729  4128  4128 D ObexServerSockets: Succeed to create listening sockets 
,08-05 08:05:50.729  4128  4128 D ObexServerSockets0: startAccept()
08-05 08:05:50.729  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-05 08:05:50.730  1370  1839 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 08:05:50.731  4128  4128 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-05 08:05:50.731  4128  4128 D BluetoothSdpJni: SDP Create record success - handle: 0
08-05 08:05:50.732  4128  4164 D ObexServerSockets0: Accepting socket connection...
,08-05 08:05:50.733  4128  4165 D ObexServerSockets0: Accepting socket connection...
,08-05 08:05:50.734  1370  1370 D BluetoothMap: Proxy object connected
,08-05 08:05:50.734  1370  1370 D MapProfile: Bluetooth service connected
08-05 08:05:50.735  1370  1370 D BluetoothMap: getConnectedDevices()
08-05 08:05:50.734  3825  3825 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 08:05:50.735  3825  3825 D PanProfile: Bluetooth service connected
,08-05 08:05:50.737   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 08:05:50.738  1370  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 08:05:50.738   872   872 D BluetoothA2dp: Proxy object connected
,08-05 08:05:50.738  1370  1370 D BluetoothA2dp: Proxy object connected
,08-05 08:05:50.740   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:05:50.741  1739  1755 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:50.742  3825  3836 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 08:05:50.743  1370  1370 D BluetoothInputDevice: Proxy object connected
08-05 08:05:50.743  1370  1370 D HidProfile: Bluetooth service connected
08-05 08:05:50.744  3825  3825 D BluetoothInputDevice: Proxy object connected
08-05 08:05:50.744  3825  3825 D HidProfile: Bluetooth service connected
08-05 08:05:50.744  3825  3835 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 08:05:50.745  3825  3836 D BluetoothMap: onBluetoothStateChange: up=true
08-05 08:05:50.747  3825  3825 D BluetoothMap: Proxy object connected
,08-05 08:05:50.747  1370  1839 D BluetoothPan: onBluetoothStateChange on: true
08-05 08:05:50.747  3825  3825 D MapProfile: Bluetooth service connected
08-05 08:05:50.747  3825  3825 D BluetoothMap: getConnectedDevices()
,08-05 08:05:50.749  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 08:05:50.749  1370  1370 D PanProfile: Bluetooth service connected
08-05 08:05:50.749   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 08:05:50.750  3825  4168 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 08:05:50.751  3825  3825 D BluetoothA2dp: Proxy object connected
08-05 08:05:50.753   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-05 08:05:50.754  4128  4128 D BluetoothMapService: onReceive
08-05 08:05:50.754  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 08:05:50.754  4128  4128 D BluetoothMapService: STATE_ON
08-05 08:05:50.756  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:50.762  3825  3825 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 08:05:50.767  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 08:05:50.768  3825  3825 D DockEventReceiver: finishStartingService: stopping service
,08-05 08:05:50.783  3825  3825 D BluetoothPbap: Proxy object connected
08-05 08:05:50.783  1370  1370 D BluetoothPbap: Proxy object connected
,08-05 08:05:50.783  3825  3825 D PbapServerProfile: Bluetooth service connected
08-05 08:05:50.783  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-05 08:05:50.794  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-05 08:05:50.794  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-05 08:05:50.799  4128  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:05:50.821   872   872 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.822  4128  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:05:50.822   872   872 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.822  3825  3836 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.823  3825  3825 D HeadsetProfile: Bluetooth service connected
08-05 08:05:50.823   872   872 D BluetoothHeadset: Proxy object connected
08-05 08:05:50.823  4128  4176 I BtOppRfcommListener: Accept thread started.
08-05 08:05:50.824  1739  1858 D BluetoothHeadset: Proxy object connected,
08-05 08:05:50.825  1370  1384 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.826  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-05 08:05:50.841   872   889 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.843  1739  1985 D BluetoothHeadset: Proxy object connected
,08-05 08:05:50.846  3825  3835 D BluetoothHeadset: Proxy object connected
08-05 08:05:50.846  3825  3825 D HeadsetProfile: Bluetooth service connected
,08-05 08:05:50.849   872   889 D BluetoothHeadset: Proxy object connected
,08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:51.132  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:51.139  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:51.143  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 08:05:51.144  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60ef30 added. We now have 8 listener(s),
08-05 08:05:51.144  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:51.150   872  1777 D WifiService: setWifiEnabled: false pid=3771, uid=10000
08-05 08:05:51.151   872  1777 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:05:51.162  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:51.163   872  1742 D WifiService: setWifiEnabled: true pid=3771, uid=10000
08-05 08:05:51.163   872  1742 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 08:05:51.184   872  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:51.198  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:51.205  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:51.218   872  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-05 08:05:51.218   872  1314 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 08:05:51.218   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-05 08:05:51.219   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-05 08:05:51.220   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 08:05:51.220   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-05 08:05:51.221   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-05 08:05:51.221   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-05 08:05:51.241   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 08:05:51.241   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-05 08:05:51.244   371   870 D CommandListener: Setting iface cfg
,08-05 08:05:51.294   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-05 08:05:51.294   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 08:05:51.297   872  1314 E native  : do suspend true
,08-05 08:05:51.322   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 08:05:51.323   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-05 08:05:51.324   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:52.185  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:52.191  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:52.203  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-05 08:05:52.205  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-05 08:05:52.211  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fe06d81 Bundle[{}]
,08-05 08:05:52.213  3771  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 08:05:52.215  3771  3817 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 08:05:52.215  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 08:05:52.216  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-05 08:05:52.216  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 08:05:52.217  3771  3817 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-05 08:05:52.221  3771  3817 I System.out: Running OutgoingSocketThread
,08-05 08:05:52.225  3771  4182 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 436)
,08-05 08:05:52.229  3771  4182 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46447
,08-05 08:05:52.229  3771  4182 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 08:05:52.708   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 08:05:52.850   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.81 rxSuccessRate=14.19 delta 1000 -> 994
,08-05 08:05:52.852   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-05 08:05:52.852   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 08:05:52.866   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-05 08:05:52.912   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-05 08:05:52.916  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-05 08:05:53.224  3771  3817 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 437)
,08-05 08:05:53.225  3771  3817 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 437)
,08-05 08:05:53.234  3771  3817 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-05 08:05:53.236  3771  3817 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-05 08:05:53.236  3771  3817 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 443)
,08-05 08:05:53.242  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 08:05:53.243  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@146a7a9 added. We now have 2 listener(s)
,08-05 08:05:53.244  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.244  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.245  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.245  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.245  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e1112e added. We now have 9 listener(s)
08-05 08:05:53.245  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 08:05:53.246  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 08:05:53.249  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:53.254  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:53.257  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:53.258  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 08:05:53.258  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 08:05:53.259  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9dce5c added. We now have 3 listener(s)
,08-05 08:05:53.260  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.262  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:53.264  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 08:05:53.265  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.265  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 08:05:53.265  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.266  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5391565 added. We now have 10 listener(s)
,08-05 08:05:53.266  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.266  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:53.267  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:53.267  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:53.268  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.268  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.269  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.269  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.269  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@146a7a9 removed from the list
08-05 08:05:53.269  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.270  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e1112e removed from the list
08-05 08:05:53.270  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:53.270  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.271  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.272  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.273  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.274  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e1112e not in the list
08-05 08:05:53.275  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.275  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.276  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.276  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.277  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.277  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5391565 removed from the list
08-05 08:05:53.277  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.277  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.278  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.278  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.278  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9dce5c removed from the, list
08-05 08:05:53.280  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.280  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1123a added. We now have 2 listener(s)
,08-05 08:05:53.286  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.286  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 08:05:53.287  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.287  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.288  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e9eeb added. We now have 9 listener(s)
,08-05 08:05:53.288  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.289  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 08:05:53.296  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:53.304  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:53.309  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:53.310  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:53.311  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 08:05:53.311  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72aa2e1 added. We now have 3 listener(s)
,08-05 08:05:53.313  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:53.317  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 08:05:53.317  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.318  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 08:05:53.318  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.319  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.319  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ce1806 added. We now have 10 listener(s)
,08-05 08:05:53.319  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.320  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.320  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:53.320  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 08:05:53.320  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:53.321  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:05:53.328  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:05:53.329  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:05:53.340  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 08:05:53.342  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:05:53.343  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:05:53.344  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:05:53.353  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:05:53.354  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:05:53.355  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:05:53.356  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:53.364  4128  4167 D BtGatt.GattService: registerClient() - UUID=726c3a1a-1b63-4313-aca0-56dd8845b814
,08-05 08:05:53.365  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=726c3a1a-1b63-4313-aca0-56dd8845b814, clientIf=5
,08-05 08:05:53.367  3771  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:05:53.368  4128  4163 D BtGatt.GattService: start scan with filters
,08-05 08:05:53.373  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:05:53.373  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:05:53.373  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:05:53.373  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-05 08:05:53.374  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:05:53.376  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:53.377  4128  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a397605
08-05 08:05:53.377  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:05:53.377  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:05:53.378  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 08:05:53.379  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-05 08:05:53.380  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:05:53.385  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:05:53.386  3771  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 08:05:53.386  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:05:53.386  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.386  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:05:53.386  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.386  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 08:05:53.386  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-05 08:05:53.386  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:53.386  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:53.386  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:05:53.387  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:05:53.387  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:05:53.387  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-05 08:05:53.388  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:05:53.388  4128  4167 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:05:53.389  4128  4163 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:05:53.390  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:05:53.390  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:05:53.391  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:53.391  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-05 08:05:53.391  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:05:53.393  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:53.393  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 08:05:53.393  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:05:53.393  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:05:53.394  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-05 08:05:53.394   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-05 08:05:53.396  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:53.396  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:53.396  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:05:53.400  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:05:53.400  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:05:53.401  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:53.401  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.401  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.401  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.401  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 08:05:53.401  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1123a removed from the list
08-05 08:05:53.401  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.402  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e9eeb removed from the list
08-05 08:05:53.402  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:53.402  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:53.402   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 08:05:53.402   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 08:05:53.403   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 08:05:53.403  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.403  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:53.404  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 08:05:53.404  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.405  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.405  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:05:53.405  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 08:05:53.405  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.405  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e9eeb not in the list
08-05 08:05:53.405  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-05 08:05:53.405  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:53.406  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:05:53.407  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.407  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.407  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.407  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ce1806 removed from the list
,08-05 08:05:53.408  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 08:05:53.408  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 08:05:53.408  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.408  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.409  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72aa2e1 removed from the list
08-05 08:05:53.410  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.410  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b23ae92 added. We now have 2 listener(s)
08-05 08:05:53.413  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.413  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 08:05:53.413  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.414   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 08:05:53.418  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.419  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44e0063 added. We now have 9 listener(s)
08-05 08:05:53.419  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.419  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:05:53.422  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:05:53.422  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:05:53.422  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.423   371   870 D CommandListener: Setting iface cfg
08-05 08:05:53.423   872  1314 D WifiStateMachine: Start Dhcp Watchdog 3
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:53.425  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 08:05:53.427  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 08:05:53.427  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:53.428  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.428  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 08:05:53.428  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.428  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bbcd19 added. We now have 3 listener(s)
08-05 08:05:53.429  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.429   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-05 08:05:53.430  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.430  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.430  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 08:05:53.430  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.430  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.430  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aca21de added. We now have 10 listener(s)
08-05 08:05:53.430  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.430  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.431  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.431  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:53.431  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 08:05:53.431  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:53.431  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:05:53.434  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:05:53.434  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:05:53.436  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:05:53.436  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.436  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:05:53.437  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:05:53.438  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:05:53.438  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:05:53.440  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:05:53.440  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:05:53.440  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:05:53.441  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:05:53.442  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:53.442  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.442  4128  4138 D BtGatt.GattService: registerClient() - UUID=4c0509c5-9d14-4621-b87e-643d72617a01
08-05 08:05:53.443  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:05:53.444  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=4c0509c5-9d14-4621-b87e-643d72617a01, clientIf=5
08-05 08:05:53.444  3771  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:05:53.444  4128  4167 D BtGatt.GattService: start scan with filters
08-05 08:05:53.447  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:53.447  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.447  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:05:53.447  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:05:53.447  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:05:53.447  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-05 08:05:53.448  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:05:53.449   872  4185 D DhcpClient: Receive thread started
08-05 08:05:53.450  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:53.450  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:53.450  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-05 08:05:53.452  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-05 08:05:53.452  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 08:05:53.452  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.453  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-05 08:05:53.454  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.454  3771  3817 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:05:53.455  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:53.455  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:53.455  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:53.455  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.455  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.455  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 08:05:53.455  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.455  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b23ae92 removed from the list
08-05 08:05:53.455  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.455  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44e0063 removed from the list
08-05 08:05:53.455  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:53.455  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.456  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.456  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-05 08:05:53.456  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.456  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.457  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 08:05:53.457  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.457  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.457  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-05 08:05:53.457  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44e0063 not in the list
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:53.457  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:53.457  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:05:53.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:05:53.458  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:05:53.458  4128  4139 D BtGatt.GattService: stopScan() - queue size =1
08-05 08:05:53.459  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:05:53.459  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:05:53.459  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:05:53.459  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:53.459  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:05:53.459  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:05:53.460  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:53.460  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 08:05:53.460  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:05:53.460  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:05:53.461  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.462  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:53.462  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:53.462  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:53.462  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.462  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.462  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.462  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aca21de removed from the list
08-05 08:05:53.462  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.462  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.463  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.463  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.463  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bbcd19 removed from the list
08-05 08:05:53.463  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.463  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d27dea added. We now have 2 listener(s)
08-05 08:05:53.465  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.465  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.465  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.465  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.465  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff918db added. We now have 9 listener(s)
08-05 08:05:53.465  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.466  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:05:53.468  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:53.468  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:05:53.468  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:53.471  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:53.473  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 08:05:53.473  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.473  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:53.473  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:53.473  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.473  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a910651 added. We now have 3 listener(s)
08-05 08:05:53.474  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.475  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.475  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.475  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.475  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.476  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.476  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3528eb6 added. We now have 10 listener(s)
08-05 08:05:53.476  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.476  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.476  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:05:53.476  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:05:53.476  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:53.476  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:05:53.478  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:05:53.478  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 08:05:53.479  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:05:53.479  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.479  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:05:53.481  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:05:53.482  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:05:53.482  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:05:53.484  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:05:53.484  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:05:53.484  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:05:53.485  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:05:53.485  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:53.485  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.485  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:05:53.486  4128  4166 D BtGatt.GattService: registerClient() - UUID=dd01bab2-0629-4808-bd2a-83b0a97d03f1
08-05 08:05:53.486  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=dd01bab2-0629-4808-bd2a-83b0a97d03f1, clientIf=5
08-05 08:05:53.487  3771  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:05:53.487  4128  4139 D BtGatt.GattService: start scan with filters
08-05 08:05:53.489  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:05:53.489  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:05:53.489  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:05:53.489  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-05 08:05:53.490  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:53.490  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.491  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:53.491  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:05:53.491  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-05 08:05:53.491  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:05:53.492  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-05 08:05:53.495  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:53.496  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:53.496  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:53.496  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.496  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.496  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 08:05:53.496  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.496  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d27dea removed from the list
08-05 08:05:53.496  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.496  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff918db removed from the list
08-05 08:05:53.496  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:53.496  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.496  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.496  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-05 08:05:53.496  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.497  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 08:05:53.497  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.497  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.497  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-05 08:05:53.497  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.497  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.497  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.498  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff918db not in the list
08-05 08:05:53.498  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:05:53.498  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:05:53.498  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:05:53.498  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:05:53.498  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:05:53.498  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:05:53.499  4128  4167 D BtGatt.GattService: stopScan() - queue size =1
08-05 08:05:53.499  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:05:53.499  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:05:53.499  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:05:53.499  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:05:53.499  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:05:53.499  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 08:05:53.500  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:53.500  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 08:05:53.500  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:05:53.500  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:05:53.501  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.501  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 08:05:53.501  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:05:53.501  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:05:53.502  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.502  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.502  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.502  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3528eb6 removed from the list
08-05 08:05:53.502  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.502  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.502  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.502  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.502  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a910651 removed from the list
08-05 08:05:53.502  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 08:05:53.502  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.502  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.503  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff0e042 added. We now have 2 listener(s)
08-05 08:05:53.503  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:05:53.503  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-05 08:05:53.504  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.504  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.504  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.504  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.504  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc853 added. We now have 9 listener(s)
08-05 08:05:53.504  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.504  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 08:05:53.506  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 08:05:53.509  3771  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 08:05:53.510  3771  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 08:05:53.511  3771  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 08:05:53.511  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 08:05:53.511  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d2e89 added. We now have 3 listener(s)
08-05 08:05:53.512  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.512  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:05:53.512  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.512  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 08:05:53.513  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:05:53.513  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 08:05:53.513  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 08:05:53.514  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 08:05:53.514  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@230be8e added. We now have 10 listener(s)
08-05 08:05:53.514  3771  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 08:05:53.514  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:05:53.514  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:53.514  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:05:53.514  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.514  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.514  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:05:53.514  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.515  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff0e042 removed from the list
08-05 08:05:53.515  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.515  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc853 removed from the list
08-05 08:05:53.515  3771  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-05 08:05:53.515  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.515  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.515  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.516  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.516  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.516  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.517  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 08:05:53.517  3771  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc853 not in the list
08-05 08:05:53.517  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.517  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.517  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.517  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:05:53.517  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 08:05:53.517  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 08:05:53.518  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@230be8e removed from the list
08-05 08:05:53.518  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 08:05:53.518  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:05:53.518  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:05:53.518  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 08:05:53.518  3771  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d2e89 removed from the list
08-05 08:05:53.518  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 08:05:53.518  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:05:53.519  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 08:05:53.519  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:05:53.519  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:05:53.519  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:53.523  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:05:53.523  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.523  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:05:53.523  3771  4186 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: My test thread name)
08-05 08:05:53.523  3771  4186 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 450, thread name: My test thread name)
08-05 08:05:53.523  3771  4186 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 450, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 08:05:53.525  3771  4187 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
08-05 08:05:53.525  3771  4187 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
08-05 08:05:53.525  3771  4187 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 08:05:53.526  3771  3817 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 08:05:53.526  3771  3817 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 08:05:53.526  3771  3817 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 08:05:53.526  3771  3817 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 08:05:53.526  3771  3817 D com.test.thalitest.ThaliTestRunner: Total duration: 23025 ms
08-05 08:05:53.528  3771  3817 I jxcore-log: Total number of executed tests:  80
08-05 08:05:53.528  3771  3817 I jxcore-log: 
08-05 08:05:53.528  3771  3817 I jxcore-log: Number of passed tests:  80
08-05 08:05:53.528  3771  3817 I jxcore-log: 
08-05 08:05:53.528  3771  3817 I jxcore-log: Number of failed tests:  0
08-05 08:05:53.528  3771  3817 I jxcore-log: 
08-05 08:05:53.528  3771  3817 I jxcore-log: Number of ignored tests:  0
08-05 08:05:53.528  3771  3817 I jxcore-log: 
08-05 08:05:53.529  3771  3817 I jxcore-log: Total duration:  23025
08-05 08:05:53.529  3771  3817 I jxcore-log: 
08-05 08:05:53.529  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:05:53.529  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.529  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:05:53.530  3771  3817 I jxcore-log: Unit Test app is loaded
08-05 08:05:53.530  3771  3817 I jxcore-log: 
08-05 08:05:53.531   872  1314 E native  : do suspend false
08-05 08:05:53.534  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:05:53.535  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:05:53.536  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.536  3771  3817 I jxcore-log: 
08-05 08:05:53.539  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.539  3771  3817 I jxcore-log: 
08-05 08:05:53.540  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.540  3771  3817 I jxcore-log: 
08-05 08:05:53.541  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.541  3771  3817 I jxcore-log: 
08-05 08:05:53.541   872  1992 D DhcpClient: Broadcasting DHCPDISCOVER
08-05 08:05:53.541  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.541  3771  3817 I jxcore-log: 
08-05 08:05:53.542  3771  3771 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 08:05:53.543  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.543  3771  3817 I jxcore-log: 
08-05 08:05:53.544  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.544  3771  3817 I jxcore-log: 
08-05 08:05:53.545  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.545  3771  3817 I jxcore-log: 
08-05 08:05:53.546  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.546  3771  3817 I jxcore-log: 
,08-05 08:05:53.546  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.546  3771  3817 I jxcore-log: 
08-05 08:05:53.547  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.547  3771  3817 I jxcore-log: 
08-05 08:05:53.547  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:05:53.547  3771  3817 I jxcore-log: 
08-05 08:05:53.548  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.548  3771  3817 I jxcore-log: 
08-05 08:05:53.548  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.548  3771  3817 I jxcore-log: 
08-05 08:05:53.549  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.549  3771  3817 I jxcore-log: 
08-05 08:05:53.549  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:53.549  3771  3817 I jxcore-log: 
08-05 08:05:53.550  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.550  3771  3817 I jxcore-log: 
08-05 08:05:53.550  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.550  3771  3817 I jxcore-log: 
08-05 08:05:53.551  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.551  3771  3817 I jxcore-log: 
08-05 08:05:53.551  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.551  3771  3817 I jxcore-log: 
08-05 08:05:53.552  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.552  3771  3817 I jxcore-log: 
08-05 08:05:53.552  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.552  3771  3817 I jxcore-log: 
08-05 08:05:53.552   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-05 08:05:53.552   872  1992 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
08-05 08:05:53.553  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.553  3771  3817 I jxcore-log: 
08-05 08:05:53.553  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.553  3771  3817 I jxcore-log: 
08-05 08:05:53.553   872  1992 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
08-05 08:05:53.553  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.553  3771  3817 I jxcore-log: 
08-05 08:05:53.554  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 08:05:53.554  3771  3817 I jxcore-log: 
08-05 08:05:53.554  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.554  3771  3817 I jxcore-log: 
08-05 08:05:53.555  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.555  3771  3817 I jxcore-log: 
08-05 08:05:53.555  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.555  3771  3817 I jxcore-log: 
08-05 08:05:53.556  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.556  3771  3817 I jxcore-log: 
08-05 08:05:53.556  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.556  3771  3817 I jxcore-log: 
08-05 08:05:53.557  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.557  3771  3817 I jxcore-log: 
08-05 08:05:53.557  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 08:05:53.557  3771  3817 I jxcore-log: 
08-05 08:05:53.559  3771  3817 I jxcore-log: My device name is: motorola-Nexus 6
08-05 08:05:53.559  3771  3817 I jxcore-log: 
08-05 08:05:53.559  3771  3817 I jxcore-log: WARN testUtils: myNameCallback not set!
08-05 08:05:53.559  3771  3817 I jxcore-log: 
08-05 08:05:53.564   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-05 08:05:53.564   872  1992 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-05 08:05:53.565   371   870 D CommandListener: Setting iface cfg
08-05 08:05:53.567   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-05 08:05:53.569   872  1992 D DhcpClient: Scheduling renewal in 86399s
08-05 08:05:53.570   872  1314 E native  : do suspend true
08-05 08:05:53.579   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-05 08:05:53.580   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
08-05 08:05:53.581   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 08:05:53.583   872  1316 D ConnectivityService: Adding iface wlan0 to network 102
08-05 08:05:53.584   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-05 08:05:53.634   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 08:05:53.634   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-05 08:05:53.636   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-05 08:05:53.639   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-05 08:05:53.642   872  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-05 08:05:53.656   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-05 08:05:53.661   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-05 08:05:53.661   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-05 08:05:53.661   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-05 08:05:53.661   872  1316 D ConnectivityService:    accepting network in place of null
08-05 08:05:53.661   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-05 08:05:53.661   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 08:05:53.662   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 08:05:53.666   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422715, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:05:53.686   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:53.711   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 08:05:53.713   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-05 08:05:53.714   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:53.718   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-05 08:05:53.718   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 08:05:53.722  3771  3771 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 08:05:53.724  3771  3771 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 08:05:53.736   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 08:05:53.776  1974  1974 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-05 08:05:53.787  1974  1974 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 08:05:53.788  1974  1974 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 08:05:53.791  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 08:05:53.804  1974  2345 I iu.UploadsManager: num queued entries: 0
,08-05 08:05:53.804  1974  2345 I iu.UploadsManager: num updated entries: 0
08-05 08:05:53.805  1974  2345 I iu.SyncManager: NEXT; no task
,08-05 08:05:53.809  3929  3929 D SprintDMHelper: simOperator: 
,08-05 08:05:53.809  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 08:05:53.818  1974  4197 I MDM     : [218] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-05 08:05:53.818  1974  4197 W BaseAppContext: Using Auth Proxy for data requests.
,08-05 08:05:53.820  1974  4197 V GoogleAuthProtoRequest: [218] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 08:05:53.834   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 06:05:53 GMT], X-Android-Received-Millis=[1470377153832], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470377153792]}
,08-05 08:05:53.838   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 08:05:53.838   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-05 08:05:53.838   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-05 08:05:53.839   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-05 08:05:53.856  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:05:53.858  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:05:53.896  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:05:53.920  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-05 08:05:53.920  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-05 08:05:53.920  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:05:53.920  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:05:53.936  1974  4197 E MDM     : [218] SitrepService.a: Error sending sitrep.
,08-05 08:05:53.962  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:05:53.993  3904  4200 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-05 08:05:54.002  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:05:55.903  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 08:05:55.903  3771  3817 I jxcore-log: 
,08-05 08:05:56.564  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 08:05:56.564  3771  3817 I jxcore-log: 
,08-05 08:05:56.589  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 08:05:56.589  3771  3817 I jxcore-log: 
,08-05 08:05:57.932  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 08:05:57.932  3771  3817 I jxcore-log: 
,08-05 08:05:58.157  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 08:05:58.157  3771  3817 I jxcore-log: 
,08-05 08:05:58.163  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 08:05:58.163  3771  3817 I jxcore-log: 
,08-05 08:05:58.179  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 08:05:58.179  3771  3817 I jxcore-log: 
,08-05 08:05:58.184  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 08:05:58.184  3771  3817 I jxcore-log: 
,08-05 08:05:58.852  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 08:05:58.852  3771  3817 I jxcore-log: 
,08-05 08:05:58.865  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 08:05:58.865  3771  3817 I jxcore-log: 
,08-05 08:05:58.876  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 08:05:58.876  3771  3817 I jxcore-log: 
,08-05 08:05:58.883  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 08:05:58.883  3771  3817 I jxcore-log: 
,08-05 08:05:58.934  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 08:05:58.934  3771  3817 I jxcore-log: 
,08-05 08:05:58.993  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 08:05:58.993  3771  3817 I jxcore-log: 
,08-05 08:05:59.001  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 08:05:59.001  3771  3817 I jxcore-log: 
,08-05 08:05:59.166  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 08:05:59.166  3771  3817 I jxcore-log: 
,08-05 08:05:59.193  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 08:05:59.193  3771  3817 I jxcore-log: 
,08-05 08:05:59.199  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 08:05:59.199  3771  3817 I jxcore-log: 
,08-05 08:05:59.205  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 08:05:59.205  3771  3817 I jxcore-log: 
,08-05 08:05:59.224  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 08:05:59.224  3771  3817 I jxcore-log: 
,08-05 08:05:59.308  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 08:05:59.308  3771  3817 I jxcore-log: 
,08-05 08:05:59.320  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 08:05:59.320  3771  3817 I jxcore-log: 
,08-05 08:05:59.348  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 08:05:59.348  3771  3817 I jxcore-log: 
,08-05 08:05:59.360  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 08:05:59.360  3771  3817 I jxcore-log: 
,08-05 08:05:59.379  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 08:05:59.379  3771  3817 I jxcore-log: 
,08-05 08:05:59.415  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 08:05:59.415  3771  3817 I jxcore-log: 
,08-05 08:05:59.421  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 08:05:59.421  3771  3817 I jxcore-log: 
,08-05 08:05:59.640  3771  3817 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 08:05:59.640  3771  3817 I jxcore-log: 
,08-05 08:05:59.651  3771  3817 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-05 08:05:59.652  3771  3817 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-05 08:05:59.652  3771  3817 I jxcore-log: 
,08-05 08:05:59.700  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 08:05:59.700  3771  3817 I jxcore-log: 
08-05 08:05:59.701  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:05:59.701  3771  3817 I jxcore-log: 
08-05 08:05:59.702  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:05:59.702  3771  3817 I jxcore-log: 
08-05 08:05:59.703  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:05:59.703  3771  3817 I jxcore-log: 
08-05 08:05:59.703  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:05:59.703  3771  3817 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-05 08:05:59.703  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 08:05:59.703  3771  3817 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-05 08:06:00.749  3771  3817 I jxcore-log: TAP version 13
08-05 08:06:00.749  3771  3817 I jxcore-log: 
,08-05 08:06:00.753  3771  3817 I jxcore-log: # setup
08-05 08:06:00.753  3771  3817 I jxcore-log: 
,08-05 08:06:01.353  3771  3817 I jxcore-log: # 1. calling createNativeListener directly rejects
08-05 08:06:01.353  3771  3817 I jxcore-log: 
,08-05 08:06:01.471  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:01.471  3771  3817 I jxcore-log: 
,08-05 08:06:01.476  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 41891
08-05 08:06:01.476  3771  3817 I jxcore-log: 
,08-05 08:06:01.483  3771  3817 I jxcore-log: ok 1 Should throw
08-05 08:06:01.483  3771  3817 I jxcore-log: 
,08-05 08:06:01.486  3771  3817 I jxcore-log: # teardown
08-05 08:06:01.486  3771  3817 I jxcore-log: 
,08-05 08:06:01.566  3771  3817 I jxcore-log: # setup
08-05 08:06:01.566  3771  3817 I jxcore-log: 
,08-05 08:06:01.657  3771  3817 I jxcore-log: # 2. emits incomingConnectionState
08-05 08:06:01.657  3771  3817 I jxcore-log: 
,08-05 08:06:01.665   872  1316 D ConnectivityService: handlePromptUnvalidated 102
,08-05 08:06:01.793  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:01.793  3771  3817 I jxcore-log: 
,08-05 08:06:01.796  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 46263
08-05 08:06:01.796  3771  3817 I jxcore-log: 
,08-05 08:06:01.805  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:01.805  3771  3817 I jxcore-log: 
,08-05 08:06:01.808  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:01.808  3771  3817 I jxcore-log: 
,08-05 08:06:01.817  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:01.817  3771  3817 I jxcore-log: 
,08-05 08:06:01.823  3771  3817 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-05 08:06:01.823  3771  3817 I jxcore-log: 
,08-05 08:06:01.850  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:01.850  3771  3817 I jxcore-log: 
,08-05 08:06:01.851  3771  3817 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-05 08:06:01.851  3771  3817 I jxcore-log: 
,08-05 08:06:01.859  3771  3817 I jxcore-log: # teardown
08-05 08:06:01.859  3771  3817 I jxcore-log: 
,08-05 08:06:02.056  3771  3817 I jxcore-log: # setup
08-05 08:06:02.056  3771  3817 I jxcore-log: 
,08-05 08:06:02.125  3771  3817 I jxcore-log: # 3. emits routerPortConnectionFailed
08-05 08:06:02.125  3771  3817 I jxcore-log: 
,08-05 08:06:02.285  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:02.285  3771  3817 I jxcore-log: 
,08-05 08:06:02.288  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 44533
08-05 08:06:02.288  3771  3817 I jxcore-log: 
,08-05 08:06:02.296  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:02.296  3771  3817 I jxcore-log: 
,08-05 08:06:02.297  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:02.297  3771  3817 I jxcore-log: 
,08-05 08:06:02.299  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:02.299  3771  3817 I jxcore-log: 
,08-05 08:06:02.331  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:02.331  3771  3817 I jxcore-log: 
,08-05 08:06:02.334  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:02.334  3771  3817 I jxcore-log: 
,08-05 08:06:02.339  3771  3817 I jxcore-log: DEBUG createNativeListener: 
08-05 08:06:02.339  3771  3817 I jxcore-log: 
,08-05 08:06:02.340  3771  3817 I jxcore-log: ok 4 tried to connect to right port
08-05 08:06:02.340  3771  3817 I jxcore-log: 
08-05 08:06:02.341  3771  3817 I jxcore-log: ok 5 failed due to refused connection
08-05 08:06:02.341  3771  3817 I jxcore-log: 
08-05 08:06:02.341  3771  3817 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-05 08:06:02.341  3771  3817 I jxcore-log: 
,08-05 08:06:02.344  3771  3817 I jxcore-log: # teardown
08-05 08:06:02.344  3771  3817 I jxcore-log: 
,08-05 08:06:02.346  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:02.346  3771  3817 I jxcore-log: 
,08-05 08:06:02.501  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:02.501  3771  3817 I jxcore-log: 
,08-05 08:06:02.511  3771  3817 I jxcore-log: # setup
08-05 08:06:02.511  3771  3817 I jxcore-log: 
,08-05 08:06:02.513  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:02.513  3771  3817 I jxcore-log: 
,08-05 08:06:02.646  3771  3817 I jxcore-log: # 4. native server connections all up
08-05 08:06:02.646  3771  3817 I jxcore-log: 
,08-05 08:06:02.684  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:02.684  3771  3817 I jxcore-log: 
,08-05 08:06:02.687  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 44902
08-05 08:06:02.687  3771  3817 I jxcore-log: 
,08-05 08:06:02.701  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:02.701  3771  3817 I jxcore-log: 
,08-05 08:06:02.705  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:02.705  3771  3817 I jxcore-log: 
,08-05 08:06:02.711  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:02.711  3771  3817 I jxcore-log: 
,08-05 08:06:02.742  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:02.742  3771  3817 I jxcore-log: 
,08-05 08:06:02.745  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:02.745  3771  3817 I jxcore-log: 
,08-05 08:06:02.750  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:02.750  3771  3817 I jxcore-log: 
,08-05 08:06:02.752  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:02.752  3771  3817 I jxcore-log: 
,08-05 08:06:02.775  3771  3817 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-05 08:06:02.775  3771  3817 I jxcore-log: 
,08-05 08:06:02.775  3771  3817 I jxcore-log: ok 8 Send/recvd #1 should be same
08-05 08:06:02.775  3771  3817 I jxcore-log: 
,08-05 08:06:02.778  3771  3817 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-05 08:06:02.778  3771  3817 I jxcore-log: 
08-05 08:06:02.779  3771  3817 I jxcore-log: ok 10 Send/recvd #2 should be same
08-05 08:06:02.779  3771  3817 I jxcore-log: 
,08-05 08:06:02.781  3771  3817 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-05 08:06:02.781  3771  3817 I jxcore-log: 
,08-05 08:06:02.789  3771  3817 I jxcore-log: # teardown
08-05 08:06:02.789  3771  3817 I jxcore-log: 
,08-05 08:06:02.911  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:02.911  3771  3817 I jxcore-log: 
,08-05 08:06:02.917  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:02.917  3771  3817 I jxcore-log: 
,08-05 08:06:02.920  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:02.920  3771  3817 I jxcore-log: 
,08-05 08:06:02.924  3771  3817 I jxcore-log: # setup
08-05 08:06:02.924  3771  3817 I jxcore-log: 
,08-05 08:06:02.925  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:02.925  3771  3817 I jxcore-log: 
,08-05 08:06:03.040  3771  3817 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-05 08:06:03.040  3771  3817 I jxcore-log: 
,08-05 08:06:03.136  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:03.136  3771  3817 I jxcore-log: 
,08-05 08:06:03.144  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 40536
08-05 08:06:03.144  3771  3817 I jxcore-log: 
,08-05 08:06:03.159  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:03.159  3771  3817 I jxcore-log: 
,08-05 08:06:03.160  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:03.160  3771  3817 I jxcore-log: 
,08-05 08:06:03.162  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:03.162  3771  3817 I jxcore-log: 
,08-05 08:06:03.178  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:03.178  3771  3817 I jxcore-log: 
,08-05 08:06:03.181  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:03.181  3771  3817 I jxcore-log: 
,08-05 08:06:03.196  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:03.196  3771  3817 I jxcore-log: 
,08-05 08:06:03.209  3771  3817 I jxcore-log: ok 12 socket shouldn't close until after stream
08-05 08:06:03.209  3771  3817 I jxcore-log: 
,08-05 08:06:03.210  3771  3817 I jxcore-log: ok 13 incoming remains open
08-05 08:06:03.210  3771  3817 I jxcore-log: 
,08-05 08:06:03.213  3771  3817 I jxcore-log: # teardown
08-05 08:06:03.213  3771  3817 I jxcore-log: 
,08-05 08:06:03.319  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:03.319  3771  3817 I jxcore-log: 
,08-05 08:06:03.332  3771  3817 I jxcore-log: # setup
08-05 08:06:03.332  3771  3817 I jxcore-log: 
,08-05 08:06:03.336  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:03.336  3771  3817 I jxcore-log: 
,08-05 08:06:03.476  3771  3817 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-05 08:06:03.476  3771  3817 I jxcore-log: 
,08-05 08:06:03.558  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:03.558  3771  3817 I jxcore-log: 
,08-05 08:06:03.579  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 41000
08-05 08:06:03.579  3771  3817 I jxcore-log: 
,08-05 08:06:03.586  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:03.586  3771  3817 I jxcore-log: 
,08-05 08:06:03.588  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:03.588  3771  3817 I jxcore-log: 
,08-05 08:06:03.589  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:03.589  3771  3817 I jxcore-log: 
,08-05 08:06:03.605  3771  3817 I jxcore-log: ok 14 we should not have gotten an error
08-05 08:06:03.605  3771  3817 I jxcore-log: 
,08-05 08:06:03.614  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:03.614  3771  3817 I jxcore-log: 
,08-05 08:06:03.619  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:03.619  3771  3817 I jxcore-log: 
,08-05 08:06:03.631  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:03.631  3771  3817 I jxcore-log: 
,08-05 08:06:03.633  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:03.633  3771  3817 I jxcore-log: 
,08-05 08:06:03.643  3771  3817 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-05 08:06:03.643  3771  3817 I jxcore-log: 
,08-05 08:06:03.643  3771  3817 I jxcore-log: ok 16 incoming is cleaned up
08-05 08:06:03.643  3771  3817 I jxcore-log: 
,08-05 08:06:03.646  3771  3817 I jxcore-log: # teardown
08-05 08:06:03.646  3771  3817 I jxcore-log: 
,08-05 08:06:03.754  3771  3817 I jxcore-log: # setup
08-05 08:06:03.754  3771  3817 I jxcore-log: 
,08-05 08:06:03.798  3771  3817 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-05 08:06:03.798  3771  3817 I jxcore-log: 
,08-05 08:06:03.883  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:03.883  3771  3817 I jxcore-log: 
,08-05 08:06:03.890  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 39959
08-05 08:06:03.890  3771  3817 I jxcore-log: 
,08-05 08:06:03.898  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:03.898  3771  3817 I jxcore-log: 
,08-05 08:06:03.899  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:03.899  3771  3817 I jxcore-log: 
,08-05 08:06:03.902  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:03.902  3771  3817 I jxcore-log: 
,08-05 08:06:03.918  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:03.918  3771  3817 I jxcore-log: 
,08-05 08:06:03.923  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:03.923  3771  3817 I jxcore-log: 
,08-05 08:06:03.953  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:03.953  3771  3817 I jxcore-log: 
,08-05 08:06:03.969  3771  3817 I jxcore-log: ok 17 stream was closed
08-05 08:06:03.969  3771  3817 I jxcore-log: 
,08-05 08:06:03.970  3771  3817 I jxcore-log: ok 18 incoming should survive
08-05 08:06:03.970  3771  3817 I jxcore-log: 
,08-05 08:06:03.971  3771  3817 I jxcore-log: ok 19 mux should have no streams
08-05 08:06:03.971  3771  3817 I jxcore-log: 
,08-05 08:06:03.976  3771  3817 I jxcore-log: # teardown
08-05 08:06:03.976  3771  3817 I jxcore-log: 
,08-05 08:06:04.126  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:04.126  3771  3817 I jxcore-log: 
,08-05 08:06:04.133  3771  3817 I jxcore-log: # setup
08-05 08:06:04.133  3771  3817 I jxcore-log: 
,08-05 08:06:04.135  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:04.135  3771  3817 I jxcore-log: 
,08-05 08:06:04.232  3771  3817 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-05 08:06:04.232  3771  3817 I jxcore-log: 
,08-05 08:06:04.276  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:04.276  3771  3817 I jxcore-log: 
,08-05 08:06:04.279  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 39935
08-05 08:06:04.279  3771  3817 I jxcore-log: 
,08-05 08:06:04.285  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.285  3771  3817 I jxcore-log: 
,08-05 08:06:04.286  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.286  3771  3817 I jxcore-log: 
,08-05 08:06:04.288  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.288  3771  3817 I jxcore-log: 
,08-05 08:06:04.297  3771  3817 I jxcore-log: ok 20 we should not have gotten an error
08-05 08:06:04.297  3771  3817 I jxcore-log: 
,08-05 08:06:04.313  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.313  3771  3817 I jxcore-log: 
,08-05 08:06:04.316  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.316  3771  3817 I jxcore-log: 
,08-05 08:06:04.326  3771  3817 I jxcore-log: ok 21 Buffers are identical
08-05 08:06:04.326  3771  3817 I jxcore-log: 
,08-05 08:06:04.329  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.329  3771  3817 I jxcore-log: 
,08-05 08:06:04.331  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:04.331  3771  3817 I jxcore-log: 
,08-05 08:06:04.333  3771  3817 I jxcore-log: ok 22 native server is nulled out
08-05 08:06:04.333  3771  3817 I jxcore-log: 
,08-05 08:06:04.334  3771  3817 I jxcore-log: ok 23 native server should be closed
08-05 08:06:04.334  3771  3817 I jxcore-log: 
08-05 08:06:04.334  3771  3817 I jxcore-log: ok 24 incoming has been removed
08-05 08:06:04.334  3771  3817 I jxcore-log: 
,08-05 08:06:04.334  3771  3817 I jxcore-log: ok 25 Incoming should be done
08-05 08:06:04.334  3771  3817 I jxcore-log: 
,08-05 08:06:04.335  3771  3817 I jxcore-log: ok 26 The mux object should be closed
08-05 08:06:04.335  3771  3817 I jxcore-log: 
08-05 08:06:04.335  3771  3817 I jxcore-log: ok 27 The mux stream should be closed
08-05 08:06:04.335  3771  3817 I jxcore-log: 
08-05 08:06:04.336  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:04.336  3771  3817 I jxcore-log: 
,08-05 08:06:04.348  3771  3817 I jxcore-log: # teardown
08-05 08:06:04.348  3771  3817 I jxcore-log: 
,08-05 08:06:04.484  3771  3817 I jxcore-log: # setup
08-05 08:06:04.484  3771  3817 I jxcore-log: 
,08-05 08:06:04.552  3771  3817 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-05 08:06:04.552  3771  3817 I jxcore-log: 
,08-05 08:06:04.618  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:04.618  3771  3817 I jxcore-log: 
,08-05 08:06:04.621  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 38054
08-05 08:06:04.621  3771  3817 I jxcore-log: 
,08-05 08:06:04.643  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.643  3771  3817 I jxcore-log: ,
08-05 08:06:04.645  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.645  3771  3817 I jxcore-log: 
,08-05 08:06:04.646  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.646  3771  3817 I jxcore-log: 
,08-05 08:06:04.650  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.650  3771  3817 I jxcore-log: 
,08-05 08:06:04.651  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.651  3771  3817 I jxcore-log: 
,08-05 08:06:04.652  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.652  3771  3817 I jxcore-log: 
,08-05 08:06:04.655  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.655  3771  3817 I jxcore-log: 
,08-05 08:06:04.656  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.656  3771  3817 I jxcore-log: 
,08-05 08:06:04.661  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.661  3771  3817 I jxcore-log: 
,08-05 08:06:04.665  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.665  3771  3817 I jxcore-log: 
,08-05 08:06:04.666  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.666  3771  3817 I jxcore-log: 
,08-05 08:06:04.668  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.668  3771  3817 I jxcore-log: 
,08-05 08:06:04.671  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.671  3771  3817 I jxcore-log: 
,08-05 08:06:04.672  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.672  3771  3817 I jxcore-log: 
08-05 08:06:04.672  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.672  3771  3817 I jxcore-log: 
,08-05 08:06:04.674  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.674  3771  3817 I jxcore-log: 
,08-05 08:06:04.675  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.675  3771  3817 I jxcore-log: 
08-05 08:06:04.676  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.676  3771  3817 I jxcore-log: 
,08-05 08:06:04.681  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.681  3771  3817 I jxcore-log: 
,08-05 08:06:04.683  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.683  3771  3817 I jxcore-log: 
,08-05 08:06:04.684  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.684  3771  3817 I jxcore-log: 
,08-05 08:06:04.688  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.688  3771  3817 I jxcore-log: 
,08-05 08:06:04.689  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.689  3771  3817 I jxcore-log: 
08-05 08:06:04.689  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.689  3771  3817 I jxcore-log: 
,08-05 08:06:04.691  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.691  3771  3817 I jxcore-log: 
08-05 08:06:04.691  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.691  3771  3817 I jxcore-log: 
,08-05 08:06:04.692  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.692  3771  3817 I jxcore-log: 
,08-05 08:06:04.694  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:04.694  3771  3817 I jxcore-log: 
08-05 08:06:04.694  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:04.694  3771  3817 I jxcore-log: 
,08-05 08:06:04.695  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:04.695  3771  3817 I jxcore-log: 
,08-05 08:06:04.781  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.781  3771  3817 I jxcore-log: 
,08-05 08:06:04.783  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.783  3771  3817 I jxcore-log: 
,08-05 08:06:04.785  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.785  3771  3817 I jxcore-log: 
,08-05 08:06:04.787  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.787  3771  3817 I jxcore-log: 
,08-05 08:06:04.788  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.788  3771  3817 I jxcore-log: 
,08-05 08:06:04.790  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.790  3771  3817 I jxcore-log: 
,08-05 08:06:04.792  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.792  3771  3817 I jxcore-log: 
,08-05 08:06:04.794  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.794  3771  3817 I jxcore-log: 
,08-05 08:06:04.796  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.796  3771  3817 I jxcore-log: 
,08-05 08:06:04.798  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.798  3771  3817 I jxcore-log: 
,08-05 08:06:04.799  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.799  3771  3817 I jxcore-log: 
,08-05 08:06:04.801  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.801  3771  3817 I jxcore-log: 
,08-05 08:06:04.802  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.802  3771  3817 I jxcore-log: 
,08-05 08:06:04.803  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.803  3771  3817 I jxcore-log: 
,08-05 08:06:04.805  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.805  3771  3817 I jxcore-log: 
,08-05 08:06:04.806  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.806  3771  3817 I jxcore-log: 
,08-05 08:06:04.808  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.808  3771  3817 I jxcore-log: 
,08-05 08:06:04.810  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.810  3771  3817 I jxcore-log: 
,08-05 08:06:04.811  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.811  3771  3817 I jxcore-log: 
,08-05 08:06:04.813  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.813  3771  3817 I jxcore-log: 
,08-05 08:06:04.816  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.816  3771  3817 I jxcore-log: 
,08-05 08:06:04.817  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.817  3771  3817 I jxcore-log: 
,08-05 08:06:04.819  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.819  3771  3817 I jxcore-log: 
,08-05 08:06:04.821  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.821  3771  3817 I jxcore-log: 
,08-05 08:06:04.823  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.823  3771  3817 I jxcore-log: 
,08-05 08:06:04.824  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.824  3771  3817 I jxcore-log: 
,08-05 08:06:04.826  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.826  3771  3817 I jxcore-log: 
,08-05 08:06:04.827  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.827  3771  3817 I jxcore-log: 
,08-05 08:06:04.828  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.828  3771  3817 I jxcore-log: 
,08-05 08:06:04.830  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.830  3771  3817 I jxcore-log: 
08-05 08:06:04.831  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.831  3771  3817 I jxcore-log: 
,08-05 08:06:04.832  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.832  3771  3817 I jxcore-log: 
,08-05 08:06:04.834  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.834  3771  3817 I jxcore-log: 
,08-05 08:06:04.836  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.836  3771  3817 I jxcore-log: 
,08-05 08:06:04.837  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.837  3771  3817 I jxcore-log: 
,08-05 08:06:04.838  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.838  3771  3817 I jxcore-log: 
,08-05 08:06:04.839  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.839  3771  3817 I jxcore-log: 
,08-05 08:06:04.846  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.846  3771  3817 I jxcore-log: 
,08-05 08:06:04.849  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.849  3771  3817 I jxcore-log: 
,08-05 08:06:04.850  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.850  3771  3817 I jxcore-log: 
,08-05 08:06:04.852  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.852  3771  3817 I jxcore-log: 
,08-05 08:06:04.854  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.854  3771  3817 I jxcore-log: 
,08-05 08:06:04.855  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.855  3771  3817 I jxcore-log: 
,08-05 08:06:04.856  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.856  3771  3817 I jxcore-log: 
,08-05 08:06:04.857  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.857  3771  3817 I jxcore-log: 
,08-05 08:06:04.859  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.859  3771  3817 I jxcore-log: 
08-05 08:06:04.860  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.860  3771  3817 I jxcore-log: 
,08-05 08:06:04.861  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.861  3771  3817 I jxcore-log: 
,08-05 08:06:04.863  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.863  3771  3817 I jxcore-log: 
,08-05 08:06:04.864  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.864  3771  3817 I jxcore-log: 
,08-05 08:06:04.866  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.866  3771  3817 I jxcore-log: 
,08-05 08:06:04.867  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.867  3771  3817 I jxcore-log: 
,08-05 08:06:04.868  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.868  3771  3817 I jxcore-log: 
,08-05 08:06:04.869  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.869  3771  3817 I jxcore-log: 
08-05 08:06:04.870  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.870  3771  3817 I jxcore-log: 
,08-05 08:06:04.872  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.872  3771  3817 I jxcore-log: 
,08-05 08:06:04.874  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.874  3771  3817 I jxcore-log: 
,08-05 08:06:04.875  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.875  3771  3817 I jxcore-log: 
,08-05 08:06:04.876  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.876  3771  3817 I jxcore-log: 
,08-05 08:06:04.878  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.878  3771  3817 I jxcore-log: 
,08-05 08:06:04.879  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.879  3771  3817 I jxcore-log: 
08-05 08:06:04.880  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.880  3771  3817 I jxcore-log: 
,08-05 08:06:04.881  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.881  3771  3817 I jxcore-log: 
,08-05 08:06:04.882  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.882  3771  3817 I jxcore-log: 
,08-05 08:06:04.884  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.884  3771  3817 I jxcore-log: 
,08-05 08:06:04.886  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.886  3771  3817 I jxcore-log: 
08-05 08:06:04.887  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.887  3771  3817 I jxcore-log: 
,08-05 08:06:04.888  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.888  3771  3817 I jxcore-log: 
08-05 08:06:04.889  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.889  3771  3817 I jxcore-log: 
,08-05 08:06:04.891  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.891  3771  3817 I jxcore-log: 
,08-05 08:06:04.892  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.892  3771  3817 I jxcore-log: 
,08-05 08:06:04.893  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.893  3771  3817 I jxcore-log: 
,08-05 08:06:04.895  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.895  3771  3817 I jxcore-log: 
,08-05 08:06:04.896  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.896  3771  3817 I jxcore-log: 
,08-05 08:06:04.897  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.897  3771  3817 I jxcore-log: 
,08-05 08:06:04.899  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.899  3771  3817 I jxcore-log: 
,08-05 08:06:04.900  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.900  3771  3817 I jxcore-log: 
,08-05 08:06:04.901  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.901  3771  3817 I jxcore-log: 
08-05 08:06:04.902  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:04.902  3771  3817 I jxcore-log: 
,08-05 08:06:04.903  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:04.903  3771  3817 I jxcore-log: 
,08-05 08:06:04.982  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.982  3771  3817 I jxcore-log: 
,08-05 08:06:04.983  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.983  3771  3817 I jxcore-log: 
,08-05 08:06:04.985  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.985  3771  3817 I jxcore-log: 
,08-05 08:06:04.986  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.986  3771  3817 I jxcore-log: 
,08-05 08:06:04.987  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:04.987  3771  3817 I jxcore-log: 
08-05 08:06:04.989  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.989  3771  3817 I jxcore-log: 
,08-05 08:06:04.990  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.990  3771  3817 I jxcore-log: 
,08-05 08:06:04.991  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.991  3771  3817 I jxcore-log: 
08-05 08:06:04.992  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.992  3771  3817 I jxcore-log: 
,08-05 08:06:04.993  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:04.993  3771  3817 I jxcore-log: 
,08-05 08:06:04.994  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.994  3771  3817 I jxcore-log: 
,08-05 08:06:04.997  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.997  3771  3817 I jxcore-log: 
,08-05 08:06:04.998  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.998  3771  3817 I jxcore-log: 
,08-05 08:06:04.999  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:04.999  3771  3817 I jxcore-log: 
,08-05 08:06:05.001  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.001  3771  3817 I jxcore-log: 
,08-05 08:06:05.006  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.006  3771  3817 I jxcore-log: 
,08-05 08:06:05.008  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.008  3771  3817 I jxcore-log: 
,08-05 08:06:05.009  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.009  3771  3817 I jxcore-log: 
,08-05 08:06:05.010  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.010  3771  3817 I jxcore-log: 
08-05 08:06:05.011  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.011  3771  3817 I jxcore-log: 
,08-05 08:06:05.012  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.012  3771  3817 I jxcore-log: 
,08-05 08:06:05.013  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.013  3771  3817 I jxcore-log: 
08-05 08:06:05.014  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.014  3771  3817 I jxcore-log: 
,08-05 08:06:05.015  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.015  3771  3817 I jxcore-log: 
,08-05 08:06:05.016  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.016  3771  3817 I jxcore-log: 
08-05 08:06:05.017  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.017  3771  3817 I jxcore-log: 
,08-05 08:06:05.018  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.018  3771  3817 I jxcore-log: 
,08-05 08:06:05.019  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.019  3771  3817 I jxcore-log: 
08-05 08:06:05.020  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.020  3771  3817 I jxcore-log: 
,08-05 08:06:05.021  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.021  3771  3817 I jxcore-log: 
08-05 08:06:05.022  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.022  3771  3817 I jxcore-log: 
,08-05 08:06:05.022  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.022  3771  3817 I jxcore-log: 
,08-05 08:06:05.023  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.023  3771  3817 I jxcore-log: 
08-05 08:06:05.024  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.024  3771  3817 I jxcore-log: 
,08-05 08:06:05.025  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.025  3771  3817 I jxcore-log: 
08-05 08:06:05.026  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.026  3771  3817 I jxcore-log: 
,08-05 08:06:05.027  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.027  3771  3817 I jxcore-log: 
,08-05 08:06:05.028  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.028  3771  3817 I jxcore-log: 
08-05 08:06:05.028  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.028  3771  3817 I jxcore-log: 
,08-05 08:06:05.029  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.029  3771  3817 I jxcore-log: 
08-05 08:06:05.030  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.030  3771  3817 I jxcore-log: 
,08-05 08:06:05.031  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.031  3771  3817 I jxcore-log: 
,08-05 08:06:05.032  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.032  3771  3817 I jxcore-log: 
08-05 08:06:05.033  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.033  3771  3817 I jxcore-log: 
,08-05 08:06:05.034  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.034  3771  3817 I jxcore-log: 
08-05 08:06:05.034  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.034  3771  3817 I jxcore-log: 
,08-05 08:06:05.035  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.035  3771  3817 I jxcore-log: 
08-05 08:06:05.036  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.036  3771  3817 I jxcore-log: 
,08-05 08:06:05.037  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:05.037  3771  3817 I jxcore-log: 
,08-05 08:06:05.038  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:05.038  3771  3817 I jxcore-log: 
,08-05 08:06:05.041  3771  3817 I jxcore-log: ok 28 native server is nulled out
08-05 08:06:05.041  3771  3817 I jxcore-log: 
,08-05 08:06:05.041  3771  3817 I jxcore-log: ok 29 native server should be closed
08-05 08:06:05.041  3771  3817 I jxcore-log: 
08-05 08:06:05.042  3771  3817 I jxcore-log: ok 30 incoming has been removed
08-05 08:06:05.042  3771  3817 I jxcore-log: 
,08-05 08:06:05.043  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.043  3771  3817 I jxcore-log: 
08-05 08:06:05.044  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.044  3771  3817 I jxcore-log: 
08-05 08:06:05.044  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.044  3771  3817 I jxcore-log: 
,08-05 08:06:05.045  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.045  3771  3817 I jxcore-log: 
08-05 08:06:05.045  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.045  3771  3817 I jxcore-log: 
08-05 08:06:05.046  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.046  3771  3817 I jxcore-log: 
,08-05 08:06:05.046  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.046  3771  3817 I jxcore-log: 
08-05 08:06:05.047  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.047  3771  3817 I jxcore-log: 
08-05 08:06:05.047  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.047  3771  3817 I jxcore-log: 
,08-05 08:06:05.047  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:05.047  3771  3817 I jxcore-log: 
,08-05 08:06:05.157  3771  3817 I jxcore-log: # teardown
08-05 08:06:05.157  3771  3817 I jxcore-log: 
,08-05 08:06:05.303  3771  3817 I jxcore-log: # setup
08-05 08:06:05.303  3771  3817 I jxcore-log: 
,08-05 08:06:06.554  3771  3817 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-05 08:06:06.554  3771  3817 I jxcore-log: 
,08-05 08:06:06.726  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:06.726  3771  3817 I jxcore-log: 
,08-05 08:06:06.731  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 49623
08-05 08:06:06.731  3771  3817 I jxcore-log: 
,08-05 08:06:06.738  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:06.738  3771  3817 I jxcore-log: 
,08-05 08:06:06.740  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:06.740  3771  3817 I jxcore-log: 
,08-05 08:06:06.742  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:06.742  3771  3817 I jxcore-log: 
,08-05 08:06:06.750  3771  3817 I jxcore-log: ok 31 we should not have gotten an error
08-05 08:06:06.750  3771  3817 I jxcore-log: 
,08-05 08:06:06.761  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:06.761  3771  3817 I jxcore-log: 
,08-05 08:06:06.764  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:06.764  3771  3817 I jxcore-log: 
,08-05 08:06:06.772  3771  3817 I jxcore-log: ok 32 Buffers are identical
08-05 08:06:06.772  3771  3817 I jxcore-log: 
,08-05 08:06:06.773  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:06.773  3771  3817 I jxcore-log: 
,08-05 08:06:06.775  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:06.775  3771  3817 I jxcore-log: 
,08-05 08:06:06.786  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:06.786  3771  3817 I jxcore-log: 
,08-05 08:06:06.787  3771  3817 I jxcore-log: ok 33 server should be fine
08-05 08:06:06.787  3771  3817 I jxcore-log: 
,08-05 08:06:06.788  3771  3817 I jxcore-log: ok 34 server should be open
08-05 08:06:06.788  3771  3817 I jxcore-log: 
08-05 08:06:06.789  3771  3817 I jxcore-log: ok 35 incoming has been removed
08-05 08:06:06.789  3771  3817 I jxcore-log: 
,08-05 08:06:06.789  3771  3817 I jxcore-log: ok 36 The mux object should be closed
08-05 08:06:06.789  3771  3817 I jxcore-log: 
08-05 08:06:06.790  3771  3817 I jxcore-log: ok 37 The mux stream should be closed
08-05 08:06:06.790  3771  3817 I jxcore-log: 
,08-05 08:06:06.795  3771  3817 I jxcore-log: # teardown
08-05 08:06:06.795  3771  3817 I jxcore-log: 
,08-05 08:06:06.942  3771  3817 I jxcore-log: # setup
08-05 08:06:06.942  3771  3817 I jxcore-log: 
,08-05 08:06:07.052  3771  3817 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-05 08:06:07.052  3771  3817 I jxcore-log: 
,08-05 08:06:07.146  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:07.146  3771  3817 I jxcore-log: 
,08-05 08:06:07.152  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 48804
08-05 08:06:07.152  3771  3817 I jxcore-log: 
,08-05 08:06:07.158  3771  3817 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-05 08:06:07.158  3771  3817 I jxcore-log: 
,08-05 08:06:07.160  3771  3817 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-05 08:06:07.160  3771  3817 I jxcore-log: 
,08-05 08:06:07.162  3771  3817 I jxcore-log: DEBUG createNativeListener: new mux
08-05 08:06:07.162  3771  3817 I jxcore-log: 
,08-05 08:06:07.169  3771  3817 I jxcore-log: ok 38 we should not have gotten an error
08-05 08:06:07.169  3771  3817 I jxcore-log: 
,08-05 08:06:07.176  3771  3817 I jxcore-log: DEBUG createNativeListener: new stream: 
08-05 08:06:07.176  3771  3817 I jxcore-log: 
,08-05 08:06:07.179  3771  3817 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-05 08:06:07.179  3771  3817 I jxcore-log: 
,08-05 08:06:07.185  3771  3817 I jxcore-log: ok 39 Buffers are identical
08-05 08:06:07.185  3771  3817 I jxcore-log: 
,08-05 08:06:07.190  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-05 08:06:07.190  3771  3817 I jxcore-log: 
,08-05 08:06:07.191  3771  3817 I jxcore-log: DEBUG createNativeListener: stream close:
08-05 08:06:07.191  3771  3817 I jxcore-log: 
,08-05 08:06:07.193  3771  3817 I jxcore-log: DEBUG createNativeListener: mux close
08-05 08:06:07.193  3771  3817 I jxcore-log: 
,08-05 08:06:07.197  3771  3817 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-05 08:06:07.197  3771  3817 I jxcore-log: 
,08-05 08:06:07.198  3771  3817 I jxcore-log: ok 40 server should be fine
08-05 08:06:07.198  3771  3817 I jxcore-log: 
08-05 08:06:07.198  3771  3817 I jxcore-log: ok 41 server should be open
08-05 08:06:07.198  3771  3817 I jxcore-log: 
,08-05 08:06:07.199  3771  3817 I jxcore-log: ok 42 incoming has been removed
08-05 08:06:07.199  3771  3817 I jxcore-log: 
,08-05 08:06:07.200  3771  3817 I jxcore-log: ok 43 The mux object should be closed
08-05 08:06:07.200  3771  3817 I jxcore-log: 
08-05 08:06:07.200  3771  3817 I jxcore-log: ok 44 The mux stream should be closed
08-05 08:06:07.200  3771  3817 I jxcore-log: 
,08-05 08:06:07.207  3771  3817 I jxcore-log: # teardown
08-05 08:06:07.207  3771  3817 I jxcore-log: 
,08-05 08:06:07.312  3771  3817 I jxcore-log: # setup
08-05 08:06:07.312  3771  3817 I jxcore-log: 
,08-05 08:06:07.389  3771  3817 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-05 08:06:07.389  3771  3817 I jxcore-log: 
,08-05 08:06:07.570  3771  3817 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-05 08:06:07.570  3771  3817 I jxcore-log: 
08-05 08:06:07.571  3771  3817 I jxcore-log: ok 45 Got right error
08-05 08:06:07.571  3771  3817 I jxcore-log: 
,08-05 08:06:07.577  3771  3817 I jxcore-log: # teardown
08-05 08:06:07.577  3771  3817 I jxcore-log: 
,08-05 08:06:07.709  3771  3817 I jxcore-log: # setup
08-05 08:06:07.709  3771  3817 I jxcore-log: 
,08-05 08:06:07.758  3771  3817 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-05 08:06:07.758  3771  3817 I jxcore-log: 
,08-05 08:06:07.886  3771  3817 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-05 08:06:07.886  3771  3817 I jxcore-log: 
,08-05 08:06:07.887  3771  3817 I jxcore-log: ok 46 Got socket hang up
08-05 08:06:07.887  3771  3817 I jxcore-log: 
,08-05 08:06:07.891  3771  3817 I jxcore-log: # teardown
08-05 08:06:07.891  3771  3817 I jxcore-log: 
,08-05 08:06:07.961  3771  3817 I jxcore-log: # setup
08-05 08:06:07.961  3771  3817 I jxcore-log: 
,08-05 08:06:08.033  3771  3817 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-05 08:06:08.033  3771  3817 I jxcore-log: 
,08-05 08:06:08.216  3771  3817 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
08-05 08:06:08.216  3771  3817 I jxcore-log: 
,08-05 08:06:08.217  3771  3817 I jxcore-log: ok 47 Got 500 as expected
08-05 08:06:08.217  3771  3817 I jxcore-log: 
,08-05 08:06:08.220  3771  3817 I jxcore-log: # teardown
08-05 08:06:08.220  3771  3817 I jxcore-log: 
,08-05 08:06:08.298  3771  3817 I jxcore-log: # setup
08-05 08:06:08.298  3771  3817 I jxcore-log: 
,08-05 08:06:08.340  3771  3817 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
08-05 08:06:08.340  3771  3817 I jxcore-log: 
,08-05 08:06:10.443  3771  3817 I jxcore-log: ok 48 should be equal
08-05 08:06:10.443  3771  3817 I jxcore-log: 
,08-05 08:06:10.443  3771  3817 I jxcore-log: ok 49 revs are equal
08-05 08:06:10.443  3771  3817 I jxcore-log: 
,08-05 08:06:10.448  3771  3817 I jxcore-log: # teardown
08-05 08:06:10.448  3771  3817 I jxcore-log: 
,08-05 08:06:10.501  3771  3817 I jxcore-log: # setup
08-05 08:06:10.501  3771  3817 I jxcore-log: 
,08-05 08:06:10.744  3771  3817 I jxcore-log: # 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
08-05 08:06:10.744  3771  3817 I jxcore-log: 
,08-05 08:06:11.443  3771  3817 I jxcore-log: ok 50 should be equal
08-05 08:06:11.443  3771  3817 I jxcore-log: 
,08-05 08:06:11.443  3771  3817 I jxcore-log: ok 51 revs are equal
08-05 08:06:11.443  3771  3817 I jxcore-log: 
,08-05 08:06:11.447  3771  3817 I jxcore-log: # teardown
08-05 08:06:11.447  3771  3817 I jxcore-log: 
,08-05 08:06:11.581  3771  3817 I jxcore-log: # setup
08-05 08:06:11.581  3771  3817 I jxcore-log: 
,08-05 08:06:11.761  3771  3817 I jxcore-log: # 17. #_doImmediateSeqUpdate - update seq three times
08-05 08:06:11.761  3771  3817 I jxcore-log: 
,08-05 08:06:12.357  3771  3817 I jxcore-log: ok 52 should be equal
08-05 08:06:12.357  3771  3817 I jxcore-log: 
,08-05 08:06:12.357  3771  3817 I jxcore-log: ok 53 revs are equal
08-05 08:06:12.357  3771  3817 I jxcore-log: 
,08-05 08:06:12.493  3771  3817 I jxcore-log: ok 54 should be equal
08-05 08:06:12.493  3771  3817 I jxcore-log: 
,08-05 08:06:12.494  3771  3817 I jxcore-log: ok 55 revs are equal
08-05 08:06:12.494  3771  3817 I jxcore-log: 
,08-05 08:06:12.636  3771  3817 I jxcore-log: ok 56 should be equal
08-05 08:06:12.636  3771  3817 I jxcore-log: 
,08-05 08:06:12.637  3771  3817 I jxcore-log: ok 57 revs are equal
08-05 08:06:12.637  3771  3817 I jxcore-log: 
,08-05 08:06:12.641  3771  3817 I jxcore-log: # teardown
08-05 08:06:12.641  3771  3817 I jxcore-log: 
,08-05 08:06:12.713  1663  1786 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-05 08:06:12.713  1663  1786 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-05 08:06:12.758  1516  1516 I ConfigService: onCreate
,08-05 08:06:12.782  3771  3817 I jxcore-log: # setup
08-05 08:06:12.782  3771  3817 I jxcore-log: 
,08-05 08:06:12.867  3771  3817 I jxcore-log: # 18. #_doImmediateSeqUpdate - rev got changed under us
08-05 08:06:12.867  3771  3817 I jxcore-log: 
,08-05 08:06:13.540  3771  3817 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
08-05 08:06:13.540  3771  3817 I jxcore-log: 
,08-05 08:06:13.541  3771  3817 I jxcore-log: ok 58 Our rev is old so we should fail
08-05 08:06:13.541  3771  3817 I jxcore-log: 
,08-05 08:06:13.544  3771  3817 I jxcore-log: # teardown
08-05 08:06:13.544  3771  3817 I jxcore-log: 
,08-05 08:06:13.708  3771  3817 I jxcore-log: # setup
08-05 08:06:13.708  3771  3817 I jxcore-log: 
,08-05 08:06:13.789  3771  3817 I jxcore-log: # 19. #_doImmediateSeqUpdate - fail if stop is called
08-05 08:06:13.789  3771  3817 I jxcore-log: 
,08-05 08:06:13.938  3771  3817 I jxcore-log: ok 59 confirm stop caused failure
08-05 08:06:13.938  3771  3817 I jxcore-log: 
,08-05 08:06:13.945  3771  3817 I jxcore-log: # teardown
08-05 08:06:13.945  3771  3817 I jxcore-log: 
,08-05 08:06:14.037  3771  3817 I jxcore-log: # setup
08-05 08:06:14.037  3771  3817 I jxcore-log: 
,08-05 08:06:14.131  3771  3817 I jxcore-log: # 20. #_doImmediateSeqUpdate - stop after get but before put fails right
08-05 08:06:14.131  3771  3817 I jxcore-log: 
,08-05 08:06:14.568  3771  3817 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
08-05 08:06:14.568  3771  3817 I jxcore-log: 
08-05 08:06:14.570  3771  3817 I jxcore-log: ok 60 stop caused us to fail
08-05 08:06:14.570  3771  3817 I jxcore-log: 
,08-05 08:06:14.570  3771  3817 I jxcore-log: ok 61 We specifically failed on a stop before put
08-05 08:06:14.570  3771  3817 I jxcore-log: 
,08-05 08:06:14.574  3771  3817 I jxcore-log: # teardown
08-05 08:06:14.574  3771  3817 I jxcore-log: 
,08-05 08:06:14.618  3771  3817 I jxcore-log: # setup
08-05 08:06:14.618  3771  3817 I jxcore-log: 
,08-05 08:06:14.758  3771  3817 I jxcore-log: # 21. #update - fail if stop is called
08-05 08:06:14.758  3771  3817 I jxcore-log: 
,08-05 08:06:14.911  3771  3817 I jxcore-log: ok 62 failed due to stop
08-05 08:06:14.911  3771  3817 I jxcore-log: 
,08-05 08:06:14.912  3771  3817 I jxcore-log: ok 63 failed due to stop
08-05 08:06:14.912  3771  3817 I jxcore-log: 
,08-05 08:06:14.918  3771  3817 I jxcore-log: # teardown
08-05 08:06:14.918  3771  3817 I jxcore-log: 
,08-05 08:06:15.045  3771  3817 I jxcore-log: # setup
08-05 08:06:15.045  3771  3817 I jxcore-log: 
,08-05 08:06:15.140  3771  3817 I jxcore-log: # 22. #update - set seq for first time
08-05 08:06:15.140  3771  3817 I jxcore-log: 
,08-05 08:06:15.793  3771  3817 I jxcore-log: ok 64 should be equal
08-05 08:06:15.793  3771  3817 I jxcore-log: 
,08-05 08:06:15.799  3771  3817 I jxcore-log: # teardown
08-05 08:06:15.799  3771  3817 I jxcore-log: 
,08-05 08:06:15.863  3771  3817 I jxcore-log: # setup
08-05 08:06:15.863  3771  3817 I jxcore-log: 
,08-05 08:06:15.950  3771  3817 I jxcore-log: # 23. #update - Fail on bad seq value
08-05 08:06:15.950  3771  3817 I jxcore-log: 
,08-05 08:06:16.330  3771  3817 I jxcore-log: DEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
08-05 08:06:16.330  3771  3817 I jxcore-log: 
,08-05 08:06:16.332  3771  3817 I jxcore-log: ok 65 Expected bad seq error
08-05 08:06:16.332  3771  3817 I jxcore-log: 
,08-05 08:06:16.335  3771  3817 I jxcore-log: # teardown
08-05 08:06:16.335  3771  3817 I jxcore-log: 
,08-05 08:06:16.417  3771  3817 I jxcore-log: # setup
08-05 08:06:16.417  3771  3817 I jxcore-log: 
,08-05 08:06:16.494  3771  3817 I jxcore-log: # 24. #update - do we cancel timer properly on an immediate?
08-05 08:06:16.494  3771  3817 I jxcore-log: 
,08-05 08:06:16.924  3771  3817 I jxcore-log: ok 66 Different promises
08-05 08:06:16.924  3771  3817 I jxcore-log: 
,08-05 08:06:16.926  3771  3817 I jxcore-log: ok 67 Timer was cancelled
08-05 08:06:16.926  3771  3817 I jxcore-log: 
,08-05 08:06:17.072  3771  3817 I jxcore-log: ok 68 should be equal
08-05 08:06:17.072  3771  3817 I jxcore-log: 
,08-05 08:06:17.076  3771  3817 I jxcore-log: # teardown
08-05 08:06:17.076  3771  3817 I jxcore-log: 
,08-05 08:06:17.178  3771  3817 I jxcore-log: # setup
08-05 08:06:17.178  3771  3817 I jxcore-log: 
,08-05 08:06:17.240  3771  3817 I jxcore-log: # 25. #update - do we wait for blocked update
08-05 08:06:17.240  3771  3817 I jxcore-log: 
,08-05 08:06:17.325  3771  3817 I jxcore-log: ok 69 One go and one blocked
08-05 08:06:17.325  3771  3817 I jxcore-log: 
,08-05 08:06:17.325  3771  3817 I jxcore-log: ok 70 All blocked
08-05 08:06:17.325  3771  3817 I jxcore-log: 
,08-05 08:06:17.326  3771  3817 I jxcore-log: ok 71 Still blocked
08-05 08:06:17.326  3771  3817 I jxcore-log: 
,08-05 08:06:17.680  3771  3817 I jxcore-log: ok 72 should be equal
08-05 08:06:17.680  3771  3817 I jxcore-log: 
,08-05 08:06:17.684  3771  3817 I jxcore-log: # teardown
08-05 08:06:17.684  3771  3817 I jxcore-log: 
,08-05 08:06:17.833  1516  1516 I ConfigService: onDestroy
,08-05 08:06:17.862  3771  3817 I jxcore-log: # setup
08-05 08:06:17.862  3771  3817 I jxcore-log: 
,08-05 08:06:17.948  3771  3817 I jxcore-log: # 26. #update - test that we wait long enough
08-05 08:06:17.948  3771  3817 I jxcore-log: 
,08-05 08:06:19.200  3771  3817 I jxcore-log: ok 73 We waited long enough
08-05 08:06:19.200  3771  3817 I jxcore-log: 
,08-05 08:06:19.348  3771  3817 I jxcore-log: ok 74 should be equal
08-05 08:06:19.348  3771  3817 I jxcore-log: 
,08-05 08:06:19.351  3771  3817 I jxcore-log: # teardown
08-05 08:06:19.351  3771  3817 I jxcore-log: 
,08-05 08:06:19.767  3771  3817 I jxcore-log: # setup
08-05 08:06:19.767  3771  3817 I jxcore-log: 
,08-05 08:06:20.788  3771  3817 I jxcore-log: # 27. #update - test that we pick up new sequences while we wait
08-05 08:06:20.788  3771  3817 I jxcore-log: 
,08-05 08:06:21.239  3771  3817 I jxcore-log: ok 75 Should have gotten same timer promise
08-05 08:06:21.239  3771  3817 I jxcore-log: 
08-05 08:06:21.239  3771  3817 I jxcore-log: ok 76 Still same timer promise
08-05 08:06:21.239  3771  3817 I jxcore-log: 
,08-05 08:06:22.031  3771  3817 I jxcore-log: ok 77 We waited long enough
08-05 08:06:22.031  3771  3817 I jxcore-log: 
,08-05 08:06:22.110  3771  3817 I jxcore-log: ok 78 should be equal
08-05 08:06:22.110  3771  3817 I jxcore-log: 
,08-05 08:06:22.115  3771  3817 I jxcore-log: # teardown
08-05 08:06:22.115  3771  3817 I jxcore-log: 
,08-05 08:06:22.742  3771  3817 I jxcore-log: # setup
08-05 08:06:22.742  3771  3817 I jxcore-log: 
,08-05 08:06:22.853  3771  3817 I jxcore-log: # 28. Coordinated seq test
08-05 08:06:22.853  3771  3817 I jxcore-log: 
,08-05 08:06:23.064  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:06:23.064  3771  3817 I jxcore-log: 
08-05 08:06:23.065  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 46324
08-05 08:06:23.065  3771  3817 I jxcore-log: 
,08-05 08:06:23.071  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:06:23.075  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
08-05 08:06:23.075  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:06:23.075  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:06:23.075  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:06:23.075  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:06:23.075  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:06:23.076  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:06:23.082  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:06:23.082  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:06:23.085  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:06:23.086  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:06:23.086  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:06:23.093  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 08:06:23.097  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:06:23.097  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:06:23.097  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:06:23.103  4128  4167 D BtGatt.GattService: registerClient() - UUID=5af126f3-e712-4e49-8cf7-dab224af57ac
,08-05 08:06:23.104  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=5af126f3-e712-4e49-8cf7-dab224af57ac, clientIf=5
,08-05 08:06:23.105  3771  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:06:23.105  4128  4138 D BtGatt.GattService: start scan with filters
,08-05 08:06:23.112  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:06:23.112  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:06:23.112  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:06:23.113  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:06:23.113  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:06:23.122  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:06:23.122  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-05 08:06:23.122  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:06:23.128  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:06:23.132  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:06:23.134  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:06:23.134  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:06:23.135  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:06:23.151  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:06:23.151  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.152  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 08:06:23.152  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:06:23.185  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 08:06:23.185  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:06:23.203  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:06:23.203  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:06:23.623  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-05 08:06:23.623  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 08:06:23.624  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:06:23.632  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-05 08:06:23.632  3771  3817 I jxcore-log: 
,08-05 08:06:23.661  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:06:23.667  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 46324, start advertisements: true
,08-05 08:06:23.667  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:06:23.667  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 1
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-05 08:06:23.668  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:06:23.669  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:06:23.670  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:06:23.671  4128  4163 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:06:23.672  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:06:23.672  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 08:06:23.672  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:06:23.672  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:06:23.672  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:06:23.673  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:06:23.673  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:06:23.674  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:06:23.677  4128  4166 D BtGatt.GattService: registerClient() - UUID=c8146d30-ab7f-4637-99e7-a69c7c5a0f53
08-05 08:06:23.678  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=c8146d30-ab7f-4637-99e7-a69c7c5a0f53, clientIf=5
08-05 08:06:23.678  3771  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:06:23.679  4128  4138 D BtGatt.GattService: start scan with filters
,08-05 08:06:23.691  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 08:06:23.692  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:06:23.692  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 08:06:23.692  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-05 08:06:23.693  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:06:23.693  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:06:23.693  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:06:23.693  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.693  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:06:23.697  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 08:06:23.698  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:06:23.698  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-05 08:06:23.699  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:06:23.700  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:06:23.701  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-05 08:06:23.701  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:06:23.701  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:06:23.701  3771  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:06:23.702  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:06:23.702  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:06:23.702  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.703  4128  4167 D BtGatt.GattService: stopScan() - queue size =0
08-05 08:06:23.703  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:06:23.703  4128  4138 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:06:23.703  3771  4218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-05 08:06:23.704  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:06:23.704  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:06:23.704  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:06:23.704  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:06:23.704  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 08:06:23.705  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:06:23.707  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:06:23.708  4128  4128 D BtGatt.ScanManager: awakened up at time 452757
,08-05 08:06:23.713  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:06:23.714  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:06:23.714  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-05 08:06:23.715  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-05 08:06:23.716  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:06:23.716  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-05 08:06:23.717  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:06:23.719  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-05 08:06:23.719  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.720  4128  4144 D BtGatt.GattService: current time is 452769162093
08-05 08:06:23.720  4128  4144 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-05 08:06:23.722  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:06:23.723  4128  4138 D BtGatt.GattService: registerClient() - UUID=3957e616-0ea9-45f2-a8f1-7fd9c4330300
,08-05 08:06:23.728  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-05 08:06:23.730  4128  4144 E BtGatt.ContextMap: Context not found for ID 5
,08-05 08:06:23.731  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=3957e616-0ea9-45f2-a8f1-7fd9c4330300, clientIf=5
,08-05 08:06:23.732  3771  3781 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-05 08:06:23.734  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:06:23.736  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:06:23.738  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:06:23.738  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.739  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:06:23.752  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:06:23.758  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:06:23.758  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.758  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:06:23.758  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:06:23.764  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:06:23.765  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-05 08:06:23.765  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-05 08:06:23.768  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:06:23.771  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:06:23.771  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-05 08:06:23.771  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:06:23.771  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-05 08:06:23.771  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:06:23.771  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-05 08:06:23.772  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-05 08:06:23.772  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-05 08:06:23.775  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:06:23.775  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.776  3771  3771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-05 08:06:23.776  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:06:23.783  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 08:06:23.783  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:06:23.793  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:06:23.793  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.794  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:06:23.801  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:06:23.802  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:06:23.802  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:06:23.808  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 08:06:23.808  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:06:24.278  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-05 08:06:24.278  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:06:24.279  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:06:24.288  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-05 08:06:24.288  3771  3817 I jxcore-log: 
,08-05 08:06:59.802  3014  4221 V KeepSync: Connecting to GoogleApiClient
,08-05 08:06:59.803   872  1380 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:06:59.866  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:06:59.870  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:06:59.918  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:06:59.918  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 08:06:59.918  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:06:59.919  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:06:59.951  1974  4222 V BaseAuthAsyncOperation: access token request failed
,08-05 08:06:59.953  3014  4221 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:07:00.029  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 08:07:00.029  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 08:07:00.029  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:07:00.030  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:07:00.051  3014  4221 E KeepSync: IOException
08-05 08:07:00.051  3014  4221 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:07:00.051  3014  4221 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:07:00.051  3014  4221 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:07:00.051  3014  4221 E KeepSync: 	... 10 more
,08-05 08:07:00.052  3014  4221 W KeepSync: Sync result 2
,08-05 08:07:00.061   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 488688, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:07:33.059  3014  4224 V KeepSync: Connecting to GoogleApiClient
,08-05 08:07:33.060   872  1732 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:07:33.121  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:07:33.124  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:07:33.156  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:07:33.156  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 08:07:33.156  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:07:33.156  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:07:33.178  1974  4225 V BaseAuthAsyncOperation: access token request failed
,08-05 08:07:33.179  3014  4224 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:07:33.236  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-05 08:07:33.236  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 08:07:33.236  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:07:33.236  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:07:33.252  3014  4224 E KeepSync: IOException
08-05 08:07:33.252  3014  4224 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:07:33.252  3014  4224 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:07:33.252  3014  4224 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:07:33.252  3014  4224 E KeepSync: 	... 10 more
08-05 08:07:33.252  3014  4224 W KeepSync: Sync result 2
,08-05 08:07:33.265   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 521975, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:08:03.452  3515  4231 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:08:03.495  3515  4232 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:08:03.509  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:03.512  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:03.558  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:08:03.558  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:08:03.558  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:08:03.559  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:08:03.595  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:03.598  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:03.636  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:08:03.636  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:08:03.636  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:08:03.636  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:08:03.660  3515  4232 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:08:03.661  3515  4231 E BooksSync: Soft error
08-05 08:08:03.661  3515  4231 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:08:03.661  3515  4231 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 08:08:03.661  3515  4231 E BooksSync: Sync error
08-05 08:08:03.661  3515  4231 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:08:03.661  3515  4231 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:08:03.661  3515  4231 I BooksSync: Finished books sync
,08-05 08:08:03.678   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 542440, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:08:36.306  3515  4234 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:08:36.334  3515  4235 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:08:36.349  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:36.352  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:36.395  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:08:36.395  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:08:36.395  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:08:36.395  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:08:36.433  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:36.435  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:08:36.486  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:08:36.487  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:08:36.487  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:08:36.487  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:08:36.510  3515  4235 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:08:36.511  3515  4234 E BooksSync: Soft error
08-05 08:08:36.511  3515  4234 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
08-05 08:08:36.511  3515  4234 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:08:36.511  3515  4234 E BooksSync: Sync error
08-05 08:08:36.511  3515  4234 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:08:36.511  3515  4234 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:08:36.511  3515  4234 I BooksSync: Finished books sync
,08-05 08:08:36.525   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 585260, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:09:07.041  3014  4238 V KeepSync: Connecting to GoogleApiClient
,08-05 08:09:07.041   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:09:07.071  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:09:07.073  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:09:07.207  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:09:07.207  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:09:07.207  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:09:07.207  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-05 08:09:07.210  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:09:07.210  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 08:09:07.210  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:09:07.210  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:09:07.254  3423  4239 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:09:07.254  3423  4239 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:07.254  3423  4239 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	... 12 more
08-05 08:09:07.254  3423  4239 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at fal.a(PG:38)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:09:07.254  3423  4239 E HttpOperation: 	... 14 more
,08-05 08:09:07.259  1974  4240 V BaseAuthAsyncOperation: access token request failed
,08-05 08:09:07.260  3014  4238 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:09:07.357  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:09:07.357  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 08:09:07.357  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:09:07.358  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:09:07.400  3423  4239 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:09:07.400  3423  4239 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at hec.a(PG:42)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at hee.a(PG:102)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at czr.a(PG:65)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at kka.a(PG:108)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:07.400  3423  4239 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	... 15 more
08-05 08:09:07.400  3423  4239 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at fal.a(PG:38)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:09:07.400  3423  4239 E HttpOperation: 	... 17 more
,08-05 08:09:07.401  3423  4239 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:09:07.401  3423  4239 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	... 15 more
08-05 08:09:07.401  3423  4239 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:09:07.401  3423  4239 E ExperimentLoader: 	... 17 more
,08-05 08:09:07.486  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 08:09:07.486  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 08:09:07.486  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:09:07.486  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:09:07.509  3014  4238 E KeepSync: IOException
08-05 08:09:07.509  3014  4238 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:09:07.509  3014  4238 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:09:07.509  3014  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:09:07.509  3014  4238 E KeepSync: 	... 10 more
08-05 08:09:07.509  3014  4238 W KeepSync: Sync result 2
,08-05 08:09:07.532   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 588045, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:09:07.556   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 585980, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:09:37.829  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:09:37.833  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:09:37.881  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:09:37.882  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:09:37.882  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:09:37.882  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:09:37.912  3423  4248 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:09:37.912  3423  4248 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:37.912  3423  4248 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	... 12 more
08-05 08:09:37.912  3423  4248 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at fal.a(PG:38)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:09:37.912  3423  4248 E HttpOperation: 	... 14 more
,08-05 08:09:37.972  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:09:37.972  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 08:09:37.972  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:09:37.972  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:09:38.001  3423  4248 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:09:38.001  3423  4248 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at hec.a(PG:42)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at hee.a(PG:102)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at czr.a(PG:65)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at kka.a(PG:108)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:38.001  3423  4248 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	... 15 more
08-05 08:09:38.001  3423  4248 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at fal.a(PG:38)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:09:38.001  3423  4248 E HttpOperation: 	... 17 more
,08-05 08:09:38.001  3423  4248 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:09:38.001  3423  4248 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	... 15 more
08-05 08:09:38.001  3423  4248 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:09:38.001  3423  4248 E ExperimentLoader: 	... 17 more
,08-05 08:09:38.142   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 646686, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:10:08.286  3515  4251 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:10:08.319  3515  4252 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:10:08.332  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:08.335  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:08.368  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:10:08.368  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:10:08.368  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:10:08.368  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:10:08.399  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:08.404  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:08.433  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:10:08.433  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:10:08.433  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:10:08.433  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:10:08.453  3515  4252 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:10:08.454  3515  4251 E BooksSync: Soft error
08-05 08:10:08.454  3515  4251 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:10:08.454  3515  4251 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:10:08.454  3515  4251 E BooksSync: Sync error
08-05 08:10:08.454  3515  4251 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:10:08.454  3515  4251 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:10:08.454  3515  4251 I BooksSync: Finished books sync
,08-05 08:10:08.466   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 650639, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:10:38.910  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:38.915  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:10:38.947  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:10:38.947  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:10:38.947  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:10:38.948  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:10:38.965  3423  4256 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:10:38.965  3423  4256 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:10:38.965  3423  4256 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	... 12 more
08-05 08:10:38.965  3423  4256 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at fal.a(PG:38)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:10:38.965  3423  4256 E HttpOperation: 	... 14 more
,08-05 08:10:39.010  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:10:39.010  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 08:10:39.010  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:10:39.010  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:10:39.024  3423  4256 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:10:39.024  3423  4256 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at hec.a(PG:42)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at hee.a(PG:102)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at czr.a(PG:65)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at kka.a(PG:108)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:10:39.024  3423  4256 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	... 15 more
08-05 08:10:39.024  3423  4256 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at fal.a(PG:38)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:10:39.024  3423  4256 E HttpOperation: 	... 17 more
,08-05 08:10:39.024  3423  4256 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:10:39.024  3423  4256 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: ,	at jcs.o(PG:406)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	... 15 more
08-05 08:10:39.024  3423  4256 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:10:39.024  3423  4256 E ExperimentLoader: 	... 17 more
,08-05 08:10:39.151   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 707351, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:11:19.292  3014  4259 V KeepSync: Connecting to GoogleApiClient
08-05 08:11:19.292   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:11:19.323  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:11:19.325  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:11:19.341  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:11:19.341  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-05 08:11:19.341  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:11:19.341  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:11:19.353  1974  4260 V BaseAuthAsyncOperation: access token request failed
,08-05 08:11:19.354  3014  4259 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:11:19.388  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 08:11:19.388  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 08:11:19.388  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:11:19.388  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:11:19.401  3014  4259 E KeepSync: IOException
08-05 08:11:19.401  3014  4259 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:11:19.401  3014  4259 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:11:19.401  3014  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:11:19.401  3014  4259 E KeepSync: 	... 10 more
,08-05 08:11:19.402  3014  4259 W KeepSync: Sync result 2
,08-05 08:11:19.413   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 748042, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:11:22.960  3771  3817 I jxcore-log: not ok 79 We failed - Error: Test timed out
08-05 08:11:22.960  3771  3817 I jxcore-log: 
,08-05 08:11:22.961  3771  3817 I jxcore-log:   ---
08-05 08:11:22.961  3771  3817 I jxcore-log: 
,08-05 08:11:22.962  3771  3817 I jxcore-log:     operator: fail
08-05 08:11:22.962  3771  3817 I jxcore-log: 
08-05 08:11:22.963  3771  3817 I jxcore-log:   ...
08-05 08:11:22.963  3771  3817 I jxcore-log: 
,08-05 08:11:22.979  3771  3817 I jxcore-log: # teardown
08-05 08:11:22.979  3771  3817 I jxcore-log: 
,08-05 08:11:23.012  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:23.013  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:11:23.013  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-05 08:11:23.013  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:23.013  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 08:11:23.013  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:11:23.013  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 08:11:23.014  3771  4218 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 08:11:23.015  3771  4218 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:11:23.015  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:23.015  3771  4218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 08:11:23.015  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 08:11:23.015  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:11:23.016  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:11:23.016  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:11:23.016  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:11:23.016  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:23.017  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:11:23.017  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:11:23.019  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:23.019  3771  3817 D BluetoothLeScanner: could not find callback wrapper
08-05 08:11:23.020  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:23.020  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-05 08:11:23.022  4128  4146 D BtGatt.AdvertiseManager: message : 1
,08-05 08:11:23.023  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:23.038  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-05 08:11:23.038  4128  4144 D BtGatt.GattService: Client app is not null!
,08-05 08:11:23.041  4128  4163 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:23.042  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:23.043  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:23.043  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-05 08:11:23.044  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-05 08:11:23.045  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-05 08:11:23.048  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:23.048  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-05 08:11:23.049  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:11:23.059  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:11:23.060  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:11:23.060  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:23.061  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 08:11:23.061  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:23.061  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:23.078  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:23.078  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:11:23.078  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:23.078  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:23.082  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:23.082  3771  3817 I jxcore-log: 
,08-05 08:11:23.089  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:23.089  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-05 08:11:23.090  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:23.090  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:23.116  3771  3817 I jxcore-log: # setup
08-05 08:11:23.116  3771  3817 I jxcore-log: 
,08-05 08:11:23.483  3771  3817 I jxcore-log: # 29. closeAll can close even when connections open
08-05 08:11:23.483  3771  3817 I jxcore-log: 
,08-05 08:11:23.562  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:23.566  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:23.566  3771  3817 I jxcore-log: 
,08-05 08:11:23.690  3771  3817 I jxcore-log: ok 80 not possible to connect to the server anymore
08-05 08:11:23.690  3771  3817 I jxcore-log: 
,08-05 08:11:23.700  3771  3817 I jxcore-log: # teardown
08-05 08:11:23.700  3771  3817 I jxcore-log: 
,08-05 08:11:23.790  3771  3817 I jxcore-log: # setup
08-05 08:11:23.790  3771  3817 I jxcore-log: 
,08-05 08:11:23.863  3771  3817 I jxcore-log: # 30. closeAll with promise
08-05 08:11:23.863  3771  3817 I jxcore-log: 
,08-05 08:11:24.102  3771  3817 I jxcore-log: ok 81 not possible to connect to the server anymore
08-05 08:11:24.102  3771  3817 I jxcore-log: 
,08-05 08:11:24.106  3771  3817 I jxcore-log: # teardown
08-05 08:11:24.106  3771  3817 I jxcore-log: 
,08-05 08:11:24.212  3771  3817 I jxcore-log: # setup
08-05 08:11:24.212  3771  3817 I jxcore-log: 
,08-05 08:11:24.284  3771  3817 I jxcore-log: # 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
08-05 08:11:24.284  3771  3817 I jxcore-log: 
,08-05 08:11:24.487  3771  3817 I jxcore-log: ok 82 Got the right error
08-05 08:11:24.487  3771  3817 I jxcore-log: 
,08-05 08:11:24.498  3771  3817 I jxcore-log: # teardown
08-05 08:11:24.498  3771  3817 I jxcore-log: 
,08-05 08:11:24.585  3771  3817 I jxcore-log: # setup
08-05 08:11:24.585  3771  3817 I jxcore-log: 
,08-05 08:11:24.640  3771  3817 I jxcore-log: # 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
08-05 08:11:24.640  3771  3817 I jxcore-log: 
,08-05 08:11:24.854  3771  3817 I jxcore-log: # teardown
08-05 08:11:24.854  3771  3817 I jxcore-log: 
,08-05 08:11:24.938  3771  3817 I jxcore-log: # setup
08-05 08:11:24.938  3771  3817 I jxcore-log: 
,08-05 08:11:24.984  3771  3817 I jxcore-log: # 33. enqueue and run in order
08-05 08:11:24.984  3771  3817 I jxcore-log: 
,08-05 08:11:25.167  3771  3817 I jxcore-log: ok 83 firstPromise setTimeout
08-05 08:11:25.167  3771  3817 I jxcore-log: 
,08-05 08:11:25.171  3771  3817 I jxcore-log: ok 84 firstPromise result
08-05 08:11:25.171  3771  3817 I jxcore-log: 
,08-05 08:11:25.173  3771  3817 I jxcore-log: ok 85 firstPromise testValue
08-05 08:11:25.173  3771  3817 I jxcore-log: 
,08-05 08:11:25.278  3771  3817 I jxcore-log: ok 86 secondPromise setTimeout
08-05 08:11:25.278  3771  3817 I jxcore-log: 
,08-05 08:11:25.281  3771  3817 I jxcore-log: ok 87 secondPromise result
08-05 08:11:25.281  3771  3817 I jxcore-log: 
,08-05 08:11:25.283  3771  3817 I jxcore-log: ok 88 secondPromise testValue
08-05 08:11:25.283  3771  3817 I jxcore-log: 
,08-05 08:11:25.286  3771  3817 I jxcore-log: ok 89 thirdPromise in promise
08-05 08:11:25.286  3771  3817 I jxcore-log: 
,08-05 08:11:25.290  3771  3817 I jxcore-log: ok 90 thirdPromise result
08-05 08:11:25.290  3771  3817 I jxcore-log: 
,08-05 08:11:25.292  3771  3817 I jxcore-log: ok 91 thirdPromise testValue
08-05 08:11:25.292  3771  3817 I jxcore-log: 
,08-05 08:11:25.305  3771  3817 I jxcore-log: # teardown
08-05 08:11:25.305  3771  3817 I jxcore-log: 
,08-05 08:11:25.420  3771  3817 I jxcore-log: # setup
08-05 08:11:25.420  3771  3817 I jxcore-log: 
,08-05 08:11:25.495  3771  3817 I jxcore-log: # 34. enqueueAtTop and run backwards
08-05 08:11:25.495  3771  3817 I jxcore-log: 
,08-05 08:11:25.605  3771  3817 I jxcore-log: ok 92 thirdPromise - first to run
08-05 08:11:25.605  3771  3817 I jxcore-log: 
,08-05 08:11:25.606  3771  3817 I jxcore-log: ok 93 thirdPromise - in resolve
08-05 08:11:25.606  3771  3817 I jxcore-log: 
08-05 08:11:25.607  3771  3817 I jxcore-log: ok 94 secondPromise - second to run
08-05 08:11:25.607  3771  3817 I jxcore-log: 
08-05 08:11:25.608  3771  3817 I jxcore-log: ok 95 secondPromise - in catch
08-05 08:11:25.608  3771  3817 I jxcore-log: 
,08-05 08:11:25.609  3771  3817 I jxcore-log: ok 96 firstPromise - third to run
08-05 08:11:25.609  3771  3817 I jxcore-log: 
,08-05 08:11:25.610  3771  3817 I jxcore-log: ok 97 firstPromise - in then
08-05 08:11:25.610  3771  3817 I jxcore-log: 
,08-05 08:11:25.610  3771  3817 I jxcore-log: ok 98 testing promises
08-05 08:11:25.610  3771  3817 I jxcore-log: 
,08-05 08:11:25.613  3771  3817 I jxcore-log: # teardown
08-05 08:11:25.613  3771  3817 I jxcore-log: 
,08-05 08:11:25.746  3771  3817 I jxcore-log: # setup
08-05 08:11:25.746  3771  3817 I jxcore-log: 
,08-05 08:11:25.802  3771  3817 I jxcore-log: # 35. mix enqueue and enqueueAtTop
08-05 08:11:25.802  3771  3817 I jxcore-log: 
,08-05 08:11:25.856  3771  3817 I jxcore-log: ok 99 fourth
08-05 08:11:25.856  3771  3817 I jxcore-log: 
,08-05 08:11:25.859  3771  3817 I jxcore-log: ok 100 fourth
08-05 08:11:25.859  3771  3817 I jxcore-log: 
,08-05 08:11:25.860  3771  3817 I jxcore-log: ok 101 second
08-05 08:11:25.860  3771  3817 I jxcore-log: 
,08-05 08:11:25.862  3771  3817 I jxcore-log: ok 102 secondPromise - in then
08-05 08:11:25.862  3771  3817 I jxcore-log: 
,08-05 08:11:25.966  3771  3817 I jxcore-log: ok 103 first
08-05 08:11:25.966  3771  3817 I jxcore-log: 
,08-05 08:11:25.982  3771  3817 I jxcore-log: ok 104 firstPromise - in catch
08-05 08:11:25.982  3771  3817 I jxcore-log: 
,08-05 08:11:25.986  3771  3817 I jxcore-log: ok 105 third
08-05 08:11:25.986  3771  3817 I jxcore-log: 
,08-05 08:11:25.991  3771  3817 I jxcore-log: ok 106 thirdPromise - in then
08-05 08:11:25.991  3771  3817 I jxcore-log: 
,08-05 08:11:25.994  3771  3817 I jxcore-log: ok 107 testingPromises
08-05 08:11:25.994  3771  3817 I jxcore-log: 
,08-05 08:11:26.002  3771  3817 I jxcore-log: # teardown
08-05 08:11:26.002  3771  3817 I jxcore-log: 
,08-05 08:11:26.088  3771  3817 I jxcore-log: # setup
08-05 08:11:26.088  3771  3817 I jxcore-log: 
,08-05 08:11:26.183  3771  3817 I jxcore-log: # 36. queues handled independently
08-05 08:11:26.183  3771  3817 I jxcore-log: 
,08-05 08:11:26.280  3771  3817 I jxcore-log: ok 108 all short operations completed before the long resolves
08-05 08:11:26.280  3771  3817 I jxcore-log: 
,08-05 08:11:26.287  3771  3817 I jxcore-log: # teardown
08-05 08:11:26.287  3771  3817 I jxcore-log: 
,08-05 08:11:26.346  3771  3817 I jxcore-log: # setup
08-05 08:11:26.346  3771  3817 I jxcore-log: 
,08-05 08:11:26.458  3771  3817 I jxcore-log: # 37. basic
08-05 08:11:26.458  3771  3817 I jxcore-log: 
,08-05 08:11:26.520  3771  3817 I jxcore-log: ok 109 sane
08-05 08:11:26.520  3771  3817 I jxcore-log: 
,08-05 08:11:26.523  3771  3817 I jxcore-log: # teardown
08-05 08:11:26.523  3771  3817 I jxcore-log: 
,08-05 08:11:26.576  3771  3817 I jxcore-log: # setup
08-05 08:11:26.576  3771  3817 I jxcore-log: 
,08-05 08:11:26.666  3771  3817 I jxcore-log: # 38. another
08-05 08:11:26.666  3771  3817 I jxcore-log: 
,08-05 08:11:26.719  3771  3817 I jxcore-log: ok 110 sane
08-05 08:11:26.719  3771  3817 I jxcore-log: 
,08-05 08:11:26.721  3771  3817 I jxcore-log: # teardown
08-05 08:11:26.721  3771  3817 I jxcore-log: 
,08-05 08:11:26.842  3771  3817 I jxcore-log: # setup
08-05 08:11:26.842  3771  3817 I jxcore-log: 
,08-05 08:11:26.913  3771  3817 I jxcore-log: # 39. can pass data in setup
08-05 08:11:26.913  3771  3817 I jxcore-log: 
,08-05 08:11:26.989  3771  3817 I jxcore-log: [{"uuid":"bda10304-7616-484f-b58e-5814f76386b8","data":"custom data"},{"uuid":"d8d6cbe5-4f94-4cff-8df9-cfd0ea67f979","data":"custom data"},{"uuid":"cb212c96-b93c-4732-9a0d-83446d49dab5","data":"custom data"}]
08-05 08:11:26.989  3771  3817 I jxcore-log: 
,08-05 08:11:26.992  3771  3817 I jxcore-log: ok 111 test participant has uuid
08-05 08:11:26.992  3771  3817 I jxcore-log: 
,08-05 08:11:26.995  3771  3817 I jxcore-log: ok 112 participant data matches
08-05 08:11:26.995  3771  3817 I jxcore-log: 
,08-05 08:11:26.998  3771  3817 I jxcore-log: ok 113 test participant has uuid
08-05 08:11:26.998  3771  3817 I jxcore-log: 
,08-05 08:11:26.998  3771  3817 I jxcore-log: ok 114 participant data matches
08-05 08:11:26.998  3771  3817 I jxcore-log: 
,08-05 08:11:26.999  3771  3817 I jxcore-log: ok 115 test participant has uuid
08-05 08:11:26.999  3771  3817 I jxcore-log: 
,08-05 08:11:26.999  3771  3817 I jxcore-log: ok 116 participant data matches
08-05 08:11:26.999  3771  3817 I jxcore-log: 
08-05 08:11:27.000  3771  3817 I jxcore-log: ok 117 own UUID is found from the participants list
08-05 08:11:27.000  3771  3817 I jxcore-log: 
08-05 08:11:27.002  3771  3817 I jxcore-log: # teardown
08-05 08:11:27.002  3771  3817 I jxcore-log: 
,08-05 08:11:27.096  3771  3817 I jxcore-log: # setup
08-05 08:11:27.096  3771  3817 I jxcore-log: 
,08-05 08:11:27.152  3771  3817 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
08-05 08:11:27.152  3771  3817 I jxcore-log: 
,08-05 08:11:27.242  3771  3817 I jxcore-log: ok 118 specific error should be returned
08-05 08:11:27.242  3771  3817 I jxcore-log: 
,08-05 08:11:27.248  3771  3817 I jxcore-log: # teardown
08-05 08:11:27.248  3771  3817 I jxcore-log: 
,08-05 08:11:27.301  3771  3817 I jxcore-log: ok 119 error should be null
08-05 08:11:27.301  3771  3817 I jxcore-log: 
,08-05 08:11:27.302  3771  3817 I jxcore-log: ok 120 error should be null
08-05 08:11:27.302  3771  3817 I jxcore-log: 
,08-05 08:11:27.305  3771  3817 I jxcore-log: # setup
08-05 08:11:27.305  3771  3817 I jxcore-log: 
,08-05 08:11:27.397  3771  3817 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
08-05 08:11:27.397  3771  3817 I jxcore-log: 
,08-05 08:11:27.440  3771  3817 I jxcore-log: ok 121 specific error should be returned
08-05 08:11:27.440  3771  3817 I jxcore-log: 
,08-05 08:11:27.442  3771  3817 I jxcore-log: # teardown
08-05 08:11:27.442  3771  3817 I jxcore-log: 
,08-05 08:11:27.511  3771  3817 I jxcore-log: ok 122 error should be null
08-05 08:11:27.511  3771  3817 I jxcore-log: 
,08-05 08:11:27.513  3771  3817 I jxcore-log: ok 123 error should be null
08-05 08:11:27.513  3771  3817 I jxcore-log: 
,08-05 08:11:27.518  3771  3817 I jxcore-log: # setup
08-05 08:11:27.518  3771  3817 I jxcore-log: 
,08-05 08:11:27.601  3771  3817 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
08-05 08:11:27.601  3771  3817 I jxcore-log: 
,08-05 08:11:27.683  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:27.683  3771  3817 I jxcore-log: 
,08-05 08:11:27.686  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 43639
08-05 08:11:27.686  3771  3817 I jxcore-log: 
,08-05 08:11:27.691  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-05 08:11:27.691  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:27.692  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:27.692  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:27.695  3771  3817 I jxcore-log: ok 124 error should be null
08-05 08:11:27.695  3771  3817 I jxcore-log: 
,08-05 08:11:27.696  3771  3817 I jxcore-log: ok 125 error should be null
08-05 08:11:27.696  3771  3817 I jxcore-log: 
,08-05 08:11:27.699  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:27.699  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:27.699  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:27.699  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:27.703  3771  3817 I jxcore-log: ok 126 error should be null
08-05 08:11:27.703  3771  3817 I jxcore-log: 
,08-05 08:11:27.704  3771  3817 I jxcore-log: ok 127 error should be null
08-05 08:11:27.704  3771  3817 I jxcore-log: 
,08-05 08:11:27.712  3771  3817 I jxcore-log: # teardown
08-05 08:11:27.712  3771  3817 I jxcore-log: 
,08-05 08:11:27.804  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:27.804  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:27.804  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:27.804  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:27.806  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-05 08:11:27.807  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-05 08:11:27.807  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:27.807  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:27.814  3771  3817 I jxcore-log: ok 128 error should be null
08-05 08:11:27.814  3771  3817 I jxcore-log: 
,08-05 08:11:27.814  3771  3817 I jxcore-log: ok 129 error should be null
08-05 08:11:27.814  3771  3817 I jxcore-log: 
,08-05 08:11:27.822  3771  3817 I jxcore-log: # setup
08-05 08:11:27.822  3771  3817 I jxcore-log: 
,08-05 08:11:27.864  3771  3817 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
08-05 08:11:27.864  3771  3817 I jxcore-log: 
,08-05 08:11:27.968  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:27.968  3771  3817 I jxcore-log: 
,08-05 08:11:27.971  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 42480
08-05 08:11:27.971  3771  3817 I jxcore-log: 
,08-05 08:11:27.977  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:27.980  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 46324, start advertisements: false
08-05 08:11:27.980  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:27.981  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:27.981  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:11:27.981  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:11:27.981  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:27.981  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:11:27.986  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:11:27.987  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:11:27.997  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:11:27.999  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:11:27.999  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:28.008  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 08:11:28.008  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:11:28.009  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:11:28.011  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:28.016  4128  4167 D BtGatt.GattService: registerClient() - UUID=de2a6ada-32b4-4d23-a1ff-d02c564a569e
08-05 08:11:28.017  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=de2a6ada-32b4-4d23-a1ff-d02c564a569e, clientIf=5
,08-05 08:11:28.017  3771  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:28.018  4128  4166 D BtGatt.GattService: start scan with filters
,08-05 08:11:28.025  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:11:28.026  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:11:28.026  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:11:28.026  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-05 08:11:28.026  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:11:28.033  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:11:28.033  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:28.034  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:11:28.038  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:28.038  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:28.039  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:28.046  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:28.050  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:11:28.051  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:28.051  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:11:28.051  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:11:28.055  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:28.077  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:11:28.077  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:28.085  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:11:28.085  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:28.540  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-05 08:11:28.540  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:28.541  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:28.547  3771  3817 I jxcore-log: ok 130 error should be null
08-05 08:11:28.547  3771  3817 I jxcore-log: 
,08-05 08:11:28.549  3771  3817 I jxcore-log: ok 131 error should be null
08-05 08:11:28.549  3771  3817 I jxcore-log: 
,08-05 08:11:28.558  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:28.566  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 46324, start advertisements: false
,08-05 08:11:28.567  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:28.567  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 08:11:28.567  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:11:28.568  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:28.573  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-05 08:11:28.573  3771  3817 I jxcore-log: 
,08-05 08:11:28.578  3771  3817 I jxcore-log: ok 132 error should be null
08-05 08:11:28.578  3771  3817 I jxcore-log: 
,08-05 08:11:28.580  3771  3817 I jxcore-log: ok 133 error should be null
08-05 08:11:28.580  3771  3817 I jxcore-log: 
,08-05 08:11:28.592  3771  3817 I jxcore-log: # teardown
08-05 08:11:28.592  3771  3817 I jxcore-log: 
,08-05 08:11:29.592  4128  4128 D BtGatt.ScanManager: awakened up at time 758641
,08-05 08:11:29.595  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:29.626  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-05 08:11:29.626  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:29.627  4128  4144 D BtGatt.GattService: current time is 758676373087
08-05 08:11:29.628  4128  4144 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -111, 106, -71, 88, -82, -32, 1, -128, -105, 6, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, -118, 66, -51, 2, 2, -25, 21, 63, -69, -4, -16, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,08-05 08:11:29.629  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-05 08:11:29.630  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-05 08:11:29.631  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, -118, 66, -51, 2, 2, -25, 21, 63, -69, -4, -16]
08-05 08:11:29.634  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-05 08:11:31.129  4128  4128 D BtGatt.ScanManager: awakened up at time 760178
,08-05 08:11:31.132  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:31.163  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-05 08:11:31.164  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:31.164  4128  4144 D BtGatt.GattService: current time is 760214058553
,08-05 08:11:31.165  4128  4144 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-05 08:11:31.166  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-05 08:11:31.167  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-05 08:11:31.168  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-05 08:11:31.987  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-05 08:11:31.987  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:31.987  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:31.988  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:31.988  3771  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 08:11:31.988  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:31.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:11:31.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:11:31.988  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:31.988  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:11:31.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:11:31.988  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:11:31.990  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:31.990  4128  4167 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:11:31.992  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:31.993  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:31.993  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:31.993  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:11:31.994  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-05 08:11:31.994  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:11:31.995  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:31.995  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 08:11:31.995  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:11:31.995  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:11:32.005  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 08:11:32.006  4128  4128 D BtGatt.ScanManager: awakened up at time 761055
08-05 08:11:32.008  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 08:11:32.008  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:32.010  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:32.010  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:32.010  3771  3817 I jxcore-log: 
08-05 08:11:32.012  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:11:32.012  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:32.013  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:11:32.020  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 08:11:32.020  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:32.020  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:32.032  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-05 08:11:32.032  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:32.033  4128  4144 D BtGatt.GattService: current time is 761082225775
08-05 08:11:32.033  4128  4144 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-05 08:11:32.033  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-05 08:11:32.033  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-05 08:11:32.034  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-05 08:11:32.511  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:32.511  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:32.512  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:32.515  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:32.516  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:32.516  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:32.516  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:32.521  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:32.521  3771  3817 I jxcore-log: 
,08-05 08:11:32.533  3771  3817 I jxcore-log: ok 134 error should be null
08-05 08:11:32.533  3771  3817 I jxcore-log: 
,08-05 08:11:32.533  3771  3817 I jxcore-log: ok 135 error should be null
08-05 08:11:32.533  3771  3817 I jxcore-log: 
,08-05 08:11:32.537  3771  3817 I jxcore-log: # setup
08-05 08:11:32.537  3771  3817 I jxcore-log: 
,08-05 08:11:32.567  3771  3817 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
08-05 08:11:32.567  3771  3817 I jxcore-log: 
,08-05 08:11:33.824  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:33.824  3771  3817 I jxcore-log: 
,08-05 08:11:33.827  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 44975
08-05 08:11:33.827  3771  3817 I jxcore-log: 
,08-05 08:11:33.839  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:33.843  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44975, start advertisements: true
,08-05 08:11:33.843  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:33.843  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-05 08:11:33.843  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-05 08:11:33.846  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-05 08:11:33.846  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-05 08:11:33.846  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:11:33.846  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:33.848  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 08:11:33.849  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:11:33.849  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 08:11:33.849  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-05 08:11:33.849  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:11:33.850  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-05 08:11:33.850  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:33.850  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:11:33.851  3771  4262 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:11:33.858  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:11:33.858  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:11:33.861  3771  4262 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-05 08:11:33.864  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:11:33.864  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:11:33.865  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:33.867  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:11:33.867  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:11:33.867  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
08-05 08:11:33.868  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-05 08:11:33.868  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:33.868  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-05 08:11:33.869  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:33.873  4128  4139 D BtGatt.GattService: registerClient() - UUID=9840b58f-2f12-4786-8406-0d3f2a481700
,08-05 08:11:33.873  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=9840b58f-2f12-4786-8406-0d3f2a481700, clientIf=5
,08-05 08:11:33.874  3771  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:33.875  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:33.879  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:33.898  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:33.912  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:11:33.914  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-05 08:11:33.915  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:33.922  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:33.926  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-05 08:11:33.927  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:33.927  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-05 08:11:33.928  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-05 08:11:33.928  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-05 08:11:33.928  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING],
,08-05 08:11:33.929  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-05 08:11:33.939  3771  3771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-05 08:11:33.939  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:11:34.441  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-05 08:11:34.441  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:11:34.441  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:34.447  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-05 08:11:34.447  3771  3817 I jxcore-log: 
,08-05 08:11:34.454  3771  3817 I jxcore-log: ok 136 error should be null
08-05 08:11:34.454  3771  3817 I jxcore-log: 
,08-05 08:11:34.456  3771  3817 I jxcore-log: ok 137 error should be null
08-05 08:11:34.456  3771  3817 I jxcore-log: 
,08-05 08:11:34.462  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:34.466  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44975, start advertisements: true
,08-05 08:11:34.466  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:34.467  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-05 08:11:34.467  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-05 08:11:34.468  4128  4146 D BtGatt.AdvertiseManager: message : 1
08-05 08:11:34.468  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:34.483  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-05 08:11:34.483  4128  4144 D BtGatt.GattService: Client app is not null!
,08-05 08:11:34.485  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:34.487  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:34.488  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-05 08:11:34.488  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:11:34.488  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:11:34.488  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:11:34.488  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
,08-05 08:11:34.488  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:34.489  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:34.489  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-05 08:11:34.490  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:34.502  4128  4167 D BtGatt.GattService: registerClient() - UUID=2d8613fb-0186-45ed-b1ee-d7c78ef15d7d
,08-05 08:11:34.502  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=2d8613fb-0186-45ed-b1ee-d7c78ef15d7d, clientIf=5
08-05 08:11:34.503  3771  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:34.504  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:34.506  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:34.519  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:34.526  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:11:34.526  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-05 08:11:34.526  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-05 08:11:34.526  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:11:34.526  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:11:34.526  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-05 08:11:34.527  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:11:34.527  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-05 08:11:34.527  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:11:34.527  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK,
,08-05 08:11:34.535  3771  3817 I jxcore-log: ok 138 error should be null
08-05 08:11:34.535  3771  3817 I jxcore-log: 
,08-05 08:11:34.536  3771  3817 I jxcore-log: ok 139 error should be null
08-05 08:11:34.536  3771  3817 I jxcore-log: 
,08-05 08:11:34.541  3771  3817 I jxcore-log: # teardown
08-05 08:11:34.541  3771  3817 I jxcore-log: 
,08-05 08:11:35.074  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-05 08:11:35.074  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:11:35.075  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-05 08:11:35.075  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:35.076  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-05 08:11:35.076  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:11:35.076  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-05 08:11:35.077  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:35.078  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:11:35.078  3771  4262 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-05 08:11:35.078  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:11:35.078  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-05 08:11:35.078  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:35.078  3771  4262 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:11:35.079  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 08:11:35.078  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:11:35.079  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:11:35.079  3771  4262 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-05 08:11:35.080  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:35.080  3771  3817 D BluetoothLeScanner: could not find callback wrapper
08-05 08:11:35.081  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 08:11:35.081  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-05 08:11:35.081  4128  4146 D BtGatt.AdvertiseManager: message : 1
08-05 08:11:35.082  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:35.099  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-05 08:11:35.099  4128  4144 D BtGatt.GattService: Client app is not null!
08-05 08:11:35.100  4128  4163 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:11:35.101  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:35.101  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:35.101  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-05 08:11:35.101  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-05 08:11:35.102  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-05 08:11:35.103  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:35.103  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:11:35.103  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 08:11:35.107  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:11:35.111  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:11:35.111  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:35.112  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:35.112  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:35.112  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-05 08:11:35.112  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:35.114  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:35.114  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:35.114  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:35.114  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.119  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:35.119  3771  3817 I jxcore-log: 
,08-05 08:11:35.126  3771  3817 I jxcore-log: ok 140 error should be null
08-05 08:11:35.126  3771  3817 I jxcore-log: 
,08-05 08:11:35.127  3771  3817 I jxcore-log: ok 141 error should be null
08-05 08:11:35.127  3771  3817 I jxcore-log: 
,08-05 08:11:35.133  3771  3817 I jxcore-log: # setup
08-05 08:11:35.133  3771  3817 I jxcore-log: 
,08-05 08:11:35.192  3771  3817 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
08-05 08:11:35.192  3771  3817 I jxcore-log: 
,08-05 08:11:35.301  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:35.301  3771  3817 I jxcore-log: 
,08-05 08:11:35.304  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 38653
08-05 08:11:35.304  3771  3817 I jxcore-log: 
,08-05 08:11:35.308  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:35.308  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:35.308  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:35.308  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.312  3771  3817 I jxcore-log: ok 142 error should be null
08-05 08:11:35.312  3771  3817 I jxcore-log: 
,08-05 08:11:35.312  3771  3817 I jxcore-log: ok 143 error should be null
08-05 08:11:35.312  3771  3817 I jxcore-log: 
,08-05 08:11:35.314  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:35.315  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:35.315  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:35.315  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.317  3771  3817 I jxcore-log: ok 144 error should be null
08-05 08:11:35.317  3771  3817 I jxcore-log: 
,08-05 08:11:35.318  3771  3817 I jxcore-log: ok 145 error should be null
08-05 08:11:35.318  3771  3817 I jxcore-log: 
,08-05 08:11:35.324  3771  3817 I jxcore-log: # teardown
08-05 08:11:35.324  3771  3817 I jxcore-log: 
,08-05 08:11:35.439  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:35.439  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:35.440  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:35.440  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.443  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-05 08:11:35.444  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:35.444  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:35.444  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.449  3771  3817 I jxcore-log: ok 146 error should be null
08-05 08:11:35.449  3771  3817 I jxcore-log: 
,08-05 08:11:35.450  3771  3817 I jxcore-log: ok 147 error should be null
08-05 08:11:35.450  3771  3817 I jxcore-log: 
,08-05 08:11:35.455  3771  3817 I jxcore-log: # setup
08-05 08:11:35.455  3771  3817 I jxcore-log: 
,08-05 08:11:35.528  3771  3817 I jxcore-log: # 46. #start should fail if called twice in a row
08-05 08:11:35.528  3771  3817 I jxcore-log: 
,08-05 08:11:35.595  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:35.595  3771  3817 I jxcore-log: 
,08-05 08:11:35.604  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 41863
08-05 08:11:35.604  3771  3817 I jxcore-log: 
,08-05 08:11:35.607  3771  3817 I jxcore-log: ok 148 first call should succeed
08-05 08:11:35.607  3771  3817 I jxcore-log: 
,08-05 08:11:35.608  3771  3817 I jxcore-log: ok 149 first call should succeed
08-05 08:11:35.608  3771  3817 I jxcore-log: 
,08-05 08:11:35.610  3771  3817 I jxcore-log: ok 150 specific error should be returned
08-05 08:11:35.610  3771  3817 I jxcore-log: 
,08-05 08:11:35.613  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:35.613  3771  3817 I jxcore-log: # teardown
08-05 08:11:35.613  3771  3817 I jxcore-log: 
,08-05 08:11:35.615  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:35.615  3771  3817 I jxcore-log: 
,08-05 08:11:35.688  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:35.689  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:35.689  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:35.689  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.693  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:35.693  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:35.693  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:35.693  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:35.700  3771  3817 I jxcore-log: ok 151 error should be null
08-05 08:11:35.700  3771  3817 I jxcore-log: 
,08-05 08:11:35.701  3771  3817 I jxcore-log: ok 152 error should be null
08-05 08:11:35.701  3771  3817 I jxcore-log: 
,08-05 08:11:35.707  3771  3817 I jxcore-log: # setup
08-05 08:11:35.707  3771  3817 I jxcore-log: 
,08-05 08:11:35.776  3771  3817 I jxcore-log: # 47. does not emit duplicate discoveryAdvertisingStateUpdate
08-05 08:11:35.776  3771  3817 I jxcore-log: 
,08-05 08:11:35.826  3771  3817 I jxcore-log: DEBUG createNativeListener: creating native server
08-05 08:11:35.826  3771  3817 I jxcore-log: 
,08-05 08:11:35.829  3771  3817 I jxcore-log: DEBUG createNativeListener: listening 44763
08-05 08:11:35.829  3771  3817 I jxcore-log: 
,08-05 08:11:35.833  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:35.836  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44975, start advertisements: false
08-05 08:11:35.836  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:35.836  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:35.836  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:11:35.836  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 08:11:35.836  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:35.837  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:11:35.841  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:11:35.841  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:11:35.845  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:11:35.846  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:11:35.847  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:35.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 08:11:35.853  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:11:35.853  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:11:35.854  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:35.856  4128  4163 D BtGatt.GattService: registerClient() - UUID=b93ca5eb-b1de-4fd5-9ebe-116084902071
,08-05 08:11:35.857  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=b93ca5eb-b1de-4fd5-9ebe-116084902071, clientIf=5
08-05 08:11:35.858  3771  3782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:35.858  4128  4167 D BtGatt.GattService: start scan with filters
,08-05 08:11:35.862  4128  4147 D BtGatt.ScanManager: handling starting scan
,08-05 08:11:35.862  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:11:35.862  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 08:11:35.863  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:11:35.863  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:11:35.868  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:35.868  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:11:35.868  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:35.871  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:35.873  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:35.880  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 08:11:35.880  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:35.881  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:11:35.896  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:11:35.896  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:35.896  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:11:35.896  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:11:35.910  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 08:11:35.910  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:35.918  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:11:35.918  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:36.369  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-05 08:11:36.370  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:36.370  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:36.399  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:36.403  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44763, start advertisements: true
,08-05 08:11:36.403  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:36.403  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,08-05 08:11:36.403  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-05 08:11:36.404  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:11:36.404  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:11:36.405  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:36.406  4128  4139 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:11:36.409  4128  4138 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:36.411  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 08:11:36.412  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-05 08:11:36.412  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:11:36.412  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:11:36.413  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 08:11:36.414  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 08:11:36.416  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 08:11:36.417  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.417  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-05 08:11:36.418  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:36.428  4128  4128 D BtGatt.ScanManager: awakened up at time 765477
,08-05 08:11:36.430  4128  4163 D BtGatt.GattService: registerClient() - UUID=78eb48df-a176-4373-95c5-0c4919156a56
08-05 08:11:36.430  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=78eb48df-a176-4373-95c5-0c4919156a56, clientIf=5
08-05 08:11:36.431  3771  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 08:11:36.431  4128  4166 D BtGatt.GattService: start scan with filters
,08-05 08:11:36.434  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:11:36.434  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 08:11:36.435  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 08:11:36.435  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-05 08:11:36.435  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:11:36.435  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:36.435  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-05 08:11:36.436  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:11:36.436  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 08:11:36.436  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:11:36.436  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:11:36.436  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-05 08:11:36.436  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:11:36.436  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:11:36.437  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 08:11:36.437  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.437  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 08:11:36.437  3771  4264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:11:36.437  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:36.438  4128  4163 D BtGatt.GattService: stopScan() - queue size =0
08-05 08:11:36.439  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:11:36.439  3771  4264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-05 08:11:36.439  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:36.439  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:36.440  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:11:36.440  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:11:36.440  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:11:36.441  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:36.442  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:11:36.444  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:11:36.444  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:11:36.445  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-05 08:11:36.445  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:36.445  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:36.445  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-05 08:11:36.446  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:36.449  4128  4166 D BtGatt.GattService: registerClient() - UUID=edfe9155-5fa4-4a16-a9f5-4ca86af39c3f
,08-05 08:11:36.449  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=edfe9155-5fa4-4a16-a9f5-4ca86af39c3f, clientIf=5
08-05 08:11:36.449  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-05 08:11:36.450  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.450  4128  4144 D BtGatt.GattService: current time is 765499352569
,08-05 08:11:36.450  4128  4144 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-05 08:11:36.450  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-05 08:11:36.450  3771  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:36.451  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:36.452  4128  4147 D BtGatt.ScanManager: handling starting scan
,08-05 08:11:36.454  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:36.458  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:11:36.458  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.458  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:11:36.468  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:36.473  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:11:36.473  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.473  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan,
08-05 08:11:36.474  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:11:36.478  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:11:36.479  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-05 08:11:36.479  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:36.482  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:36.484  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-05 08:11:36.484  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:36.484  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-05 08:11:36.484  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:11:36.484  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-05 08:11:36.484  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-05 08:11:36.484  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-05 08:11:36.485  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:36.487  3771  3771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-05 08:11:36.487  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:11:36.490  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 08:11:36.490  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:36.493  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-05 08:11:36.493  3771  3817 I jxcore-log: 
,08-05 08:11:36.498  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:11:36.498  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:36.506  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:11:36.506  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.506  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:11:36.512  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 08:11:36.512  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.512  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:36.528  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-05 08:11:36.528  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:36.529  4128  4144 D BtGatt.GattService: current time is 765578326067
08-05 08:11:36.529  4128  4144 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-05 08:11:36.529  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-05 08:11:36.987  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-05 08:11:36.988  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-05 08:11:36.988  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:36.994  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-05 08:11:36.994  3771  3817 I jxcore-log: 
,08-05 08:11:37.011  3771  3817 I jxcore-log: ok 153 called only once
08-05 08:11:37.011  3771  3817 I jxcore-log: 
,08-05 08:11:37.011  3771  3817 I jxcore-log: ok 154 discovery state matches
08-05 08:11:37.011  3771  3817 I jxcore-log: 
,08-05 08:11:37.012  3771  3817 I jxcore-log: ok 155 advertising state matches
08-05 08:11:37.012  3771  3817 I jxcore-log: 
,08-05 08:11:37.017  3771  3817 I jxcore-log: # teardown
08-05 08:11:37.017  3771  3817 I jxcore-log: 
,08-05 08:11:37.575  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:37.576  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 08:11:37.576  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-05 08:11:37.576  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:37.576  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 08:11:37.577  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:11:37.577  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-05 08:11:37.577  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:37.578  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:11:37.578  3771  4264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 08:11:37.578  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:11:37.578  3771  4264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:11:37.578  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:11:37.578  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:11:37.578  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:37.578  3771  4264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-05 08:11:37.579  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:11:37.579  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:11:37.581  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:37.581  3771  3817 D BluetoothLeScanner: could not find callback wrapper
08-05 08:11:37.582  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:37.582  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-05 08:11:37.584  4128  4146 D BtGatt.AdvertiseManager: message : 1
08-05 08:11:37.585  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:37.605  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-05 08:11:37.605  4128  4144 D BtGatt.GattService: Client app is not null!
08-05 08:11:37.606  4128  4167 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:11:37.607  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:37.607  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:37.607  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-05 08:11:37.608  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-05 08:11:37.608  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-05 08:11:37.610  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:37.611  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:11:37.611  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:11:37.612  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:11:37.615  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:11:37.616  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:37.616  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-05 08:11:37.616  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 08:11:37.617  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 08:11:37.618  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:37.619  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:37.619  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:37.619  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:37.620  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:11:37.630  3771  3817 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
08-05 08:11:37.630  3771  3817 I jxcore-log: 
08-05 08:11:37.632  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:37.632  3771  3817 I jxcore-log: 
,08-05 08:11:37.635  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:37.635  3771  3817 I jxcore-log: 
,08-05 08:11:37.643  3771  3817 I jxcore-log: ok 156 error should be null
08-05 08:11:37.643  3771  3817 I jxcore-log: 
,08-05 08:11:37.644  3771  3817 I jxcore-log: ok 157 error should be null
08-05 08:11:37.644  3771  3817 I jxcore-log: 
,08-05 08:11:37.650  3771  3817 I jxcore-log: # setup
08-05 08:11:37.650  3771  3817 I jxcore-log: 
,08-05 08:11:37.742  3771  3817 I jxcore-log: # 48. does not send duplicate availability changes
08-05 08:11:37.742  3771  3817 I jxcore-log: 
,08-05 08:11:37.801  3771  3817 I jxcore-log: ok 158 should be called once
08-05 08:11:37.801  3771  3817 I jxcore-log: 
,08-05 08:11:37.804  3771  3817 I jxcore-log: ok 159 should not have been called more than once
08-05 08:11:37.804  3771  3817 I jxcore-log: 
,08-05 08:11:37.806  3771  3817 I jxcore-log: # teardown
08-05 08:11:37.806  3771  3817 I jxcore-log: 
,08-05 08:11:37.888  3771  3817 I jxcore-log: ok 160 error should be null
08-05 08:11:37.888  3771  3817 I jxcore-log: 
,08-05 08:11:37.890  3771  3817 I jxcore-log: ok 161 error should be null
08-05 08:11:37.890  3771  3817 I jxcore-log: 
,08-05 08:11:37.895  3771  3817 I jxcore-log: # setup
08-05 08:11:37.895  3771  3817 I jxcore-log: 
,08-05 08:11:37.945  3771  3817 I jxcore-log: # 49. can get the network status
08-05 08:11:37.945  3771  3817 I jxcore-log: 
,08-05 08:11:38.003  3771  3817 I jxcore-log: ok 162 network status should have certain non-empty properties
08-05 08:11:38.003  3771  3817 I jxcore-log: 
,08-05 08:11:38.006  3771  3817 I jxcore-log: # teardown
08-05 08:11:38.006  3771  3817 I jxcore-log: 
,08-05 08:11:38.067  3771  3817 I jxcore-log: ok 163 error should be null
08-05 08:11:38.067  3771  3817 I jxcore-log: 
,08-05 08:11:38.068  3771  3817 I jxcore-log: ok 164 error should be null
08-05 08:11:38.068  3771  3817 I jxcore-log: 
,08-05 08:11:38.071  3771  3817 I jxcore-log: # setup
08-05 08:11:38.071  3771  3817 I jxcore-log: 
,08-05 08:11:38.119  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:38.128  3771  3817 I jxcore-log: # 50. wifi peer is marked unavailable if announcements stop
08-05 08:11:38.128  3771  3817 I jxcore-log: 
,08-05 08:11:38.131  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:38.131  3771  3817 I jxcore-log: 
,08-05 08:11:38.236  3771  3817 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
08-05 08:11:38.236  3771  3817 I jxcore-log: 
,08-05 08:11:38.264  3771  3817 I jxcore-log: ok 165 host address should match
08-05 08:11:38.264  3771  3817 I jxcore-log: 
,08-05 08:11:38.264  3771  3817 I jxcore-log: ok 166 port should match
08-05 08:11:38.264  3771  3817 I jxcore-log: 
,08-05 08:11:40.237  3771  3817 I jxcore-log: ok 167 host address should be null
08-05 08:11:40.237  3771  3817 I jxcore-log: 
,08-05 08:11:40.239  3771  3817 I jxcore-log: ok 168 port should should be null
08-05 08:11:40.239  3771  3817 I jxcore-log: 
,08-05 08:11:40.256  3771  3817 I jxcore-log: # teardown
08-05 08:11:40.256  3771  3817 I jxcore-log: 
,08-05 08:11:40.346  3771  3817 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-05 08:11:40.346  3771  3817 I jxcore-log: 
,08-05 08:11:40.352  3771  3817 I jxcore-log: ok 169 error should be null
08-05 08:11:40.352  3771  3817 I jxcore-log: 
,08-05 08:11:40.353  3771  3817 I jxcore-log: ok 170 error should be null
08-05 08:11:40.353  3771  3817 I jxcore-log: 
,08-05 08:11:40.356  3771  3817 I jxcore-log: # setup
08-05 08:11:40.356  3771  3817 I jxcore-log: 
,08-05 08:11:40.435  3771  3817 I jxcore-log: # 51. Can call start/stopListeningForAdvertisements
08-05 08:11:40.435  3771  3817 I jxcore-log: 
,08-05 08:11:40.492  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:40.498  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44763, start advertisements: false
,08-05 08:11:40.499  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:40.499  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 08:11:40.499  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-05 08:11:40.499  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 08:11:40.500  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:40.500  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 08:11:40.510  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:11:40.511  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:11:40.523  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:11:40.525  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:11:40.525  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:40.534  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:11:40.535  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 08:11:40.535  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:11:40.540  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:40.548  4128  4167 D BtGatt.GattService: registerClient() - UUID=1033c04a-8e50-4f88-b1d8-ca44508e28e9
,08-05 08:11:40.549  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=1033c04a-8e50-4f88-b1d8-ca44508e28e9, clientIf=5
08-05 08:11:40.550  3771  3782 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:40.551  4128  4163 D BtGatt.GattService: start scan with filters
,08-05 08:11:40.561  4128  4147 D BtGatt.ScanManager: handling starting scan
,08-05 08:11:40.561  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:11:40.562  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 08:11:40.562  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:11:40.563  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 08:11:40.572  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:11:40.573  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:40.573  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:11:40.578  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:40.579  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:40.580  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:40.586  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:40.593  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 08:11:40.593  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:40.594  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-05 08:11:40.594  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:11:40.593  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:40.630  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:11:40.630  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:40.648  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 08:11:40.648  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:41.079  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-05 08:11:41.080  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:41.080  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:41.085  3771  3817 I jxcore-log: ok 171 Can call startListeningForAdvertisements without error
08-05 08:11:41.085  3771  3817 I jxcore-log: 
,08-05 08:11:41.087  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:41.087  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:41.088  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:41.088  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
08-05 08:11:41.088  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:11:41.089  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-05 08:11:41.092  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:41.094  4128  4167 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:11:41.097  4128  4163 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:41.098  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:41.099  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:41.099  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:11:41.099  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 08:11:41.100  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:11:41.102  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:41.103  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:41.108  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-05 08:11:41.108  3771  3817 I jxcore-log: 
,08-05 08:11:41.117  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:11:41.118  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:41.119  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:11:41.144  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 08:11:41.144  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:41.145  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:41.154  4128  4128 D BtGatt.ScanManager: awakened up at time 770203
,08-05 08:11:41.184  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-05 08:11:41.184  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:41.188  4128  4144 D BtGatt.GattService: current time is 770237489656
,08-05 08:11:41.188  4128  4144 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -69, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-05 08:11:41.189  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-05 08:11:41.190  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-05 08:11:41.603  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:41.604  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:41.604  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:41.608  3771  3817 I jxcore-log: ok 172 Can call stopListeningForAdvertisements without error
08-05 08:11:41.608  3771  3817 I jxcore-log: ,
,08-05 08:11:41.620  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:41.620  3771  3817 I jxcore-log: 
,08-05 08:11:41.625  3771  3817 I jxcore-log: # teardown
08-05 08:11:41.625  3771  3817 I jxcore-log: 
,08-05 08:11:41.824  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:41.824  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:41.825  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:41.825  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:41.830  3771  3817 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisements in teardown,
08-05 08:11:41.830  3771  3817 I jxcore-log: 
08-05 08:11:41.831  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-05 08:11:41.831  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:41.831  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:41.831  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:41.833  3771  3817 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
08-05 08:11:41.833  3771  3817 I jxcore-log: 
,08-05 08:11:41.841  3771  3817 I jxcore-log: # setup
08-05 08:11:41.841  3771  3817 I jxcore-log: 
,08-05 08:11:41.912  3771  3817 I jxcore-log: # 52. Calling startListeningForAdvertisements twice is NOT an error
08-05 08:11:41.912  3771  3817 I jxcore-log: 
,08-05 08:11:41.955  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:41.959  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44763, start advertisements: false
08-05 08:11:41.960  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:41.960  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:41.960  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 08:11:41.960  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 08:11:41.962  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:11:41.968  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 08:11:41.968  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 08:11:41.969  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 08:11:41.970  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:41.974  4128  4167 D BtGatt.GattService: registerClient() - UUID=337388a3-9af4-4469-84e4-287b0840488d
,08-05 08:11:41.975  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=337388a3-9af4-4469-84e4-287b0840488d, clientIf=5
,08-05 08:11:41.975  3771  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:41.976  4128  4166 D BtGatt.GattService: start scan with filters
,08-05 08:11:41.983  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 08:11:41.983  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 08:11:41.983  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 08:11:41.983  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-05 08:11:41.984  4128  4147 D BtGatt.ScanManager: handling starting scan
08-05 08:11:41.988  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 08:11:41.989  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-05 08:11:41.989  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 08:11:41.991  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:41.999  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 08:11:42.003  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 08:11:42.003  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:42.004  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 08:11:42.020  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 08:11:42.021  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:42.021  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 08:11:42.021  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 08:11:42.054  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 08:11:42.054  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:42.071  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 08:11:42.071  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 08:11:42.490  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-05 08:11:42.491  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 08:11:42.491  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:42.496  3771  3817 I jxcore-log: ok 175 Can call startListeningForAdvertisements without error
08-05 08:11:42.496  3771  3817 I jxcore-log: 
,08-05 08:11:42.501  3771  3817 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-05 08:11:42.508  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 44763, start advertisements: false
,08-05 08:11:42.508  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:42.509  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 08:11:42.509  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:42.510  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:11:42.513  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-05 08:11:42.513  3771  3817 I jxcore-log: 
,08-05 08:11:42.517  3771  3817 I jxcore-log: ok 176 Can call startListeningForAdvertisements twice without error
08-05 08:11:42.517  3771  3817 I jxcore-log: 
,08-05 08:11:42.530  3771  3817 I jxcore-log: # teardown
08-05 08:11:42.530  3771  3817 I jxcore-log: 
,08-05 08:11:42.788  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:42.788  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:42.789  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:42.789  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
08-05 08:11:42.789  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 08:11:42.790  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 08:11:42.792  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:42.795  4128  4163 D BtGatt.GattService: stopScan() - queue size =1
,08-05 08:11:42.798  4128  4139 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 08:11:42.799  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:42.800  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-05 08:11:42.801  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 08:11:42.801  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-05 08:11:42.801  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 08:11:42.805  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:42.806  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:42.811  4128  4128 D BtGatt.ScanManager: awakened up at time 771860
,08-05 08:11:42.821  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-05 08:11:42.822  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:42.822  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-05 08:11:42.837  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 08:11:42.838  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:42.838  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 08:11:42.868  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-05 08:11:42.868  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 08:11:42.869  4128  4144 D BtGatt.GattService: current time is 771918223469
,08-05 08:11:42.869  4128  4144 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -64, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -70, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 50, -35, 86, -77, -92, -11, 1, -128, -84, 1, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -74, 67, -51, 2, 2, -33, 21, 61, 84, 51, -95, 0]
08-05 08:11:42.870  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-05 08:11:42.870  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-05 08:11:42.871  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-05 08:11:42.871  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-05 08:11:42.871  4128  4144 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -74, 67, -51, 2, 2, -33, 21, 61, 84, 51, -95]
,08-05 08:11:43.307  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-05 08:11:43.308  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:43.308  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:43.312  3771  3817 I jxcore-log: ok 177 Should be able to call stopListeningForAdvertisements in teardown
08-05 08:11:43.312  3771  3817 I jxcore-log: 
,08-05 08:11:43.316  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:43.316  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:43.317  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:43.317  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:43.321  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:43.321  3771  3817 I jxcore-log: 
,08-05 08:11:43.324  3771  3817 I jxcore-log: ok 178 Should be able to call stopAdvertisingAndListening in teardown
08-05 08:11:43.324  3771  3817 I jxcore-log: 
,08-05 08:11:43.336  3771  3817 I jxcore-log: # setup
08-05 08:11:43.336  3771  3817 I jxcore-log: 
,08-05 08:11:43.466  3771  3817 I jxcore-log: # 53. Calling stopListeningForAdvertisements without calling start is NOT an error
08-05 08:11:43.466  3771  3817 I jxcore-log: 
,08-05 08:11:43.543  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:43.543  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:43.543  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:43.543  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:43.546  3771  3817 I jxcore-log: ok 179 Can call stopListeningForAdvertisements without error
08-05 08:11:43.546  3771  3817 I jxcore-log: 
,08-05 08:11:43.548  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-05 08:11:43.548  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-05 08:11:43.549  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:43.549  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:43.553  3771  3817 I jxcore-log: ok 180 Can call stopListeningForAdvertisements without error
08-05 08:11:43.553  3771  3817 I jxcore-log: 
,08-05 08:11:43.565  3771  3817 I jxcore-log: # teardown
08-05 08:11:43.565  3771  3817 I jxcore-log: 
,08-05 08:11:43.651  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-05 08:11:43.651  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:43.652  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 08:11:43.652  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:43.656  3771  3817 I jxcore-log: ok 181 Should be able to call stopListeningForAdvertisements in teardown
08-05 08:11:43.656  3771  3817 I jxcore-log: 
,08-05 08:11:43.659  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:43.659  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:43.659  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:43.660  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:43.663  3771  3817 I jxcore-log: ok 182 Should be able to call stopAdvertisingAndListening in teardown
08-05 08:11:43.663  3771  3817 I jxcore-log: 
,08-05 08:11:43.673  3771  3817 I jxcore-log: # setup
08-05 08:11:43.673  3771  3817 I jxcore-log: 
,08-05 08:11:43.765  3771  3817 I jxcore-log: # 54. Can call start/stopUpdateAdvertisingAndListening
08-05 08:11:43.765  3771  3817 I jxcore-log: 
,08-05 08:11:43.820  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:43.825  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,08-05 08:11:43.825  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:43.825  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
08-05 08:11:43.826  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-05 08:11:43.831  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:11:43.831  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:11:43.832  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:43.832  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-05 08:11:43.832  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-05 08:11:43.833  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-05 08:11:43.833  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:11:43.836  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-05 08:11:43.838  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:11:43.839  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 08:11:43.841  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-05 08:11:43.842  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:11:43.843  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-05 08:11:43.845  3771  4267 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 08:11:43.847  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 08:11:43.848  3771  4267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-05 08:11:43.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:11:43.854  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 08:11:43.854  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
08-05 08:11:43.855  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-05 08:11:43.855  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:43.855  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-05 08:11:43.856  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:43.861  4128  4139 D BtGatt.GattService: registerClient() - UUID=09082c81-d2b2-407a-9b61-2c73fca27286
,08-05 08:11:43.862  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=09082c81-d2b2-407a-9b61-2c73fca27286, clientIf=5
,08-05 08:11:43.863  3771  3782 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-05 08:11:43.864  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:43.868  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:43.889  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:43.900  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:11:43.902  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-05 08:11:43.902  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:43.905  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:43.908  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:11:43.908  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-05 08:11:43.908  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-05 08:11:43.909  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:11:43.909  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-05 08:11:43.909  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-05 08:11:43.910  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-05 08:11:43.921  3771  3771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:11:43.921  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:11:44.422  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-05 08:11:44.423  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:11:44.423  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-05 08:11:44.428  3771  3817 I jxcore-log: ok 183 Can call startUpdateAdvertisingAndListening without error
08-05 08:11:44.428  3771  3817 I jxcore-log: 
,08-05 08:11:44.430  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:44.431  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:44.431  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-05 08:11:44.432  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:44.432  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 08:11:44.432  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:11:44.433  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-05 08:11:44.433  3771  4267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-05 08:11:44.433  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:44.434  3771  4267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:11:44.434  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:11:44.434  3771  4267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 08:11:44.435  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-05 08:11:44.435  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 08:11:44.436  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:11:44.436  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:44.436  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:11:44.437  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 08:11:44.439  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:44.440  3771  3817 D BluetoothLeScanner: could not find callback wrapper
08-05 08:11:44.440  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:44.440  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-05 08:11:44.443  4128  4146 D BtGatt.AdvertiseManager: message : 1
08-05 08:11:44.444  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:44.460  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-05 08:11:44.460  4128  4144 D BtGatt.GattService: Client app is not null!
,08-05 08:11:44.463  4128  4167 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:44.466  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:44.466  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:44.466  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-05 08:11:44.466  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-05 08:11:44.466  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-05 08:11:44.468  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:44.469  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:11:44.469  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:11:44.471  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:11:44.475  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:11:44.475  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:44.475  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 08:11:44.475  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:44.475  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:44.476  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:44.480  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-05 08:11:44.480  3771  3817 I jxcore-log: 
,08-05 08:11:44.483  3771  3817 I jxcore-log: ok 184 Can call stopAdvertisingAndListening without error
08-05 08:11:44.483  3771  3817 I jxcore-log: 
,08-05 08:11:44.488  3771  3817 I jxcore-log: # teardown
08-05 08:11:44.488  3771  3817 I jxcore-log: 
,08-05 08:11:44.706  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:44.707  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-05 08:11:44.708  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 08:11:44.708  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:44.712  3771  3817 I jxcore-log: ok 185 Should be able to call stopListeningForAdvertisements in teardown
08-05 08:11:44.712  3771  3817 I jxcore-log: 
08-05 08:11:44.714  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-05 08:11:44.714  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:44.715  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 08:11:44.715  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:44.721  3771  3817 I jxcore-log: ok 186 Should be able to call stopAdvertisingAndListening in teardown
08-05 08:11:44.721  3771  3817 I jxcore-log: 
,08-05 08:11:44.730  3771  3817 I jxcore-log: # setup
08-05 08:11:44.730  3771  3817 I jxcore-log: 
,08-05 08:11:44.815  3771  3817 I jxcore-log: # 55. Calling startUpdateAdvertisingAndListening twice is NOT an error
08-05 08:11:44.815  3771  3817 I jxcore-log: 
,08-05 08:11:44.976  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:45.241  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:45.241  3771  3817 I jxcore-log: 
,08-05 08:11:45.268  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:45.272  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
08-05 08:11:45.272  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-05 08:11:45.272  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
08-05 08:11:45.272  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
08-05 08:11:45.272  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-05 08:11:45.272  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-05 08:11:45.272  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 08:11:45.272  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 08:11:45.273  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 08:11:45.273  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 08:11:45.273  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-05 08:11:45.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 08:11:45.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-05 08:11:45.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 08:11:45.274  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 08:11:45.274  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 08:11:45.281  3771  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 08:11:45.282  3771  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 08:11:45.284  3771  4268 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 08:11:45.290  3771  4268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-05 08:11:45.295  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 08:11:45.296  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 08:11:45.296  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 08:11:45.300  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-05 08:11:45.301  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 08:11:45.301  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
08-05 08:11:45.301  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:45.301  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:45.301  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-05 08:11:45.302  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:45.304  4128  4139 D BtGatt.GattService: registerClient() - UUID=2423fd9d-dcf3-4d41-bb47-fdfa731695d4
08-05 08:11:45.305  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=2423fd9d-dcf3-4d41-bb47-fdfa731695d4, clientIf=5
08-05 08:11:45.306  3771  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-05 08:11:45.308  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:45.309  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:45.320  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:45.326  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-05 08:11:45.327  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-05 08:11:45.327  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 08:11:45.329  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 08:11:45.330  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:11:45.330  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-05 08:11:45.330  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-05 08:11:45.330  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:11:45.330  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-05 08:11:45.331  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-05 08:11:45.331  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-05 08:11:45.333  3771  3771 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-05 08:11:45.333  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-05 08:11:45.834  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-05 08:11:45.835  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:11:45.835  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:45.841  3771  3817 I jxcore-log: ok 187 Can call startUpdateAdvertisingAndListening without error
08-05 08:11:45.841  3771  3817 I jxcore-log: 
,08-05 08:11:45.844  3771  3817 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-05 08:11:45.852  3771  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,08-05 08:11:45.852  3771  3817 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-05 08:11:45.852  3771  3817 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 7
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 6 -> 7
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 7
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-05 08:11:45.853  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-05 08:11:45.856  4128  4146 D BtGatt.AdvertiseManager: message : 1
,08-05 08:11:45.859  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:45.887  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-05 08:11:45.887  4128  4144 D BtGatt.GattService: Client app is not null!
08-05 08:11:45.889  4128  4138 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:45.890  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:45.890  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-05 08:11:45.890  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 08:11:45.891  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-05 08:11:45.891  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 08:11:45.891  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 07 F8 CF C5 D9 E5 61
08-05 08:11:45.892  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[7, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-05 08:11:45.892  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[7, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-05 08:11:45.892  3771  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-05 08:11:45.893  3771  3817 D BluetoothAdapter: STATE_ON
,08-05 08:11:45.899  4128  4138 D BtGatt.GattService: registerClient() - UUID=1bd8b940-42aa-4165-ab99-a528102a5162
08-05 08:11:45.900  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=1bd8b940-42aa-4165-ab99-a528102a5162, clientIf=5
,08-05 08:11:45.901  3771  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-05 08:11:45.903  4128  4146 D BtGatt.AdvertiseManager: message : 0
,08-05 08:11:45.906  4128  4146 D BtGatt.AdvertiseManager: starting multi advertising
,08-05 08:11:45.921  4128  4144 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-05 08:11:45.930  4128  4144 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-05 08:11:45.931  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-05 08:11:45.931  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-05 08:11:45.932  3771  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-05 08:11:45.932  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 08:11:45.932  3771  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-05 08:11:45.932  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 08:11:45.932  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 08:11:45.932  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 08:11:45.933  3771  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-05 08:11:45.936  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-05 08:11:45.936  3771  3817 I jxcore-log: 
,08-05 08:11:45.938  3771  3817 I jxcore-log: ok 188 Can call startUpdateAdvertisingAndListening twice without error
08-05 08:11:45.938  3771  3817 I jxcore-log: 
,08-05 08:11:45.948  3771  3817 I jxcore-log: # teardown
08-05 08:11:45.948  3771  3817 I jxcore-log: 
,08-05 08:11:46.416  3771  3817 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-05 08:11:46.416  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-05 08:11:46.417  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
08-05 08:11:46.418  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 08:11:46.423  3771  3817 I jxcore-log: ok 189 Should be able to call stopListeningForAdvertisements in teardown
08-05 08:11:46.423  3771  3817 I jxcore-log: 
,08-05 08:11:46.426  3771  3817 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening,
08-05 08:11:46.426  3771  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 08:11:46.427  3771  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-05 08:11:46.428  3771  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 08:11:46.428  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-05 08:11:46.428  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 08:11:46.428  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 08:11:46.429  3771  4268 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 08:11:46.430  3771  4268 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 08:11:46.430  3771  4268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 08:11:46.430  3771  3771 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-05 08:11:46.431  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 08:11:46.431  3771  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 08:11:46.432  3771  3771 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 08:11:46.432  3771  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-05 08:11:46.432  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 08:11:46.432  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 08:11:46.432  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 08:11:46.433  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-05 08:11:46.435  3771  3817 D BluetoothAdapter: STATE_ON
08-05 08:11:46.435  3771  3817 D BluetoothLeScanner: could not find callback wrapper
08-05 08:11:46.435  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 08:11:46.435  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-05 08:11:46.437  4128  4146 D BtGatt.AdvertiseManager: message : 1
08-05 08:11:46.438  4128  4146 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-05 08:11:46.449  4128  4144 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-05 08:11:46.449  4128  4144 D BtGatt.GattService: Client app is not null!
,08-05 08:11:46.451  4128  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 08:11:46.452  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 08:11:46.453  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-05 08:11:46.453  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-05 08:11:46.453  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-05 08:11:46.453  3771  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-05 08:11:46.456  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 08:11:46.456  3771  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 08:11:46.457  3771  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 08:11:46.458  3771  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 08:11:46.461  3771  3771 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 08:11:46.461  3771  3771 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 08:11:46.461  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:46.461  3771  3771 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 08:11:46.461  3771  3771 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 08:11:46.465  3771  3817 I jxcore-log: ok 190 Should be able to call stopAdvertisingAndListening in teardown
08-05 08:11:46.465  3771  3817 I jxcore-log: 
,08-05 08:11:46.482  3771  3817 I jxcore-log: # setup
08-05 08:11:46.482  3771  3817 I jxcore-log: 
,08-05 08:11:46.718  3771  3817 I jxcore-log: # 56. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
08-05 08:11:46.718  3771  3817 I jxcore-log: 
,08-05 08:11:46.961  3771  3771 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 08:11:46.965  3771  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 08:11:46.965  3771  3817 I jxcore-log: 
,08-05 08:12:18.656  3515  4270 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:12:18.695  3515  4271 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:12:18.713  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:18.719  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:18.751  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-05 08:12:18.751  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:12:18.751  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:12:18.751  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:12:18.786  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:18.800  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:18.833  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:12:18.834  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:12:18.834  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:12:18.834  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:12:18.852  3515  4271 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:12:18.853  3515  4270 E BooksSync: Soft error
08-05 08:12:18.853  3515  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:12:18.853  3515  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 08:12:18.853  3515  4270 E BooksSync: Sync error
08-05 08:12:18.853  3515  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:12:18.853  3515  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 08:12:18.853  3515  4270 I BooksSync: Finished books sync,
,08-05 08:12:18.875   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 807643, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:12:49.289  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:49.291  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:12:49.331  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:12:49.331  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:12:49.331  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:12:49.331  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:12:49.346  3423  4275 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:12:49.346  3423  4275 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:12:49.346  3423  4275 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	... 12 more
08-05 08:12:49.346  3423  4275 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at fal.a(PG:38)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:12:49.346  3423  4275 E HttpOperation: 	... 14 more
,08-05 08:12:49.415  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:12:49.415  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:12:49.415  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:12:49.415  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:12:49.430  3423  4275 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:12:49.430  3423  4275 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:12:49.430  3423  4275 E HttpOperation: ,	at jdm.a(PG:82)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at hec.a(PG:42)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at hee.a(PG:102)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at czr.a(PG:65)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at kka.a(PG:108)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:12:49.430  3423  4275 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	... 15 more
08-05 08:12:49.430  3423  4275 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at fal.a(PG:38)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:12:49.430  3423  4275 E HttpOperation: 	... 17 more
,08-05 08:12:49.430  3423  4275 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:12:49.430  3423  4275 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	... 15 more
08-05 08:12:49.430  3423  4275 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:12:49.430  3423  4275 E ExperimentLoader: 	... 17 more
,08-05 08:12:49.598   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 828521, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:13:50.362   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=899410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:14:00.802   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:14:15.428   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=924477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:14:25.869   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=934917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:14:40.495   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=949544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:14:50.922   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:15:05.562   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=974610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:15:15.975   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=985023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:15:30.628   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=999677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:15:41.028   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1010077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:15:42.392   872   872 I ActivityManager: Start proc 4284:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-05 08:15:42.481  4284  4284 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-05 08:15:42.503  4284  4284 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-05 08:15:42.503  4284  4284 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-05 08:15:42.503  4284  4284 I GAv4    :   adb logcat -s GAv4
,08-05 08:15:42.518  4284  4284 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:15:42.523  4284  4284 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:15:42.527  3014  4295 V KeepSync: Connecting to GoogleApiClient
,08-05 08:15:42.527   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:15:42.549  4284  4300 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-05 08:15:42.568  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:15:42.570  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:15:42.593  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:15:42.593  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-05 08:15:42.593  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:15:42.593  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:15:42.611  1974  4301 V BaseAuthAsyncOperation: access token request failed
,08-05 08:15:42.612  3014  4295 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:15:42.656  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 08:15:42.657  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-05 08:15:42.657  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:15:42.657  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:15:42.669  3014  4295 E KeepSync: IOException
08-05 08:15:42.669  3014  4295 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:15:42.669  3014  4295 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:15:42.669  3014  4295 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:15:42.669  3014  4295 E KeepSync: 	... 10 more
,08-05 08:15:42.669  3014  4295 W KeepSync: Sync result 2
,08-05 08:15:42.680   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1011382, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:15:43.126   872  1531 I ActivityManager: Killing 3557:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-05 08:15:55.641   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1024690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:16:06.095   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1035144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:16:20.708   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1049757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:16:31.148   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1060197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:16:39.195  3515  4304 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:16:39.241  3515  4305 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:16:39.265  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:16:39.271  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:16:39.323  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:16:39.323  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 08:16:39.323  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:16:39.323  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:16:39.374  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:16:39.377  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:16:39.415  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:16:39.415  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:16:39.416  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:16:39.416  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:16:39.442  3515  4305 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:16:39.443  3515  4304 E BooksSync: Soft error
08-05 08:16:39.443  3515  4304 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:16:39.443  3515  4304 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:16:39.443  3515  4304 E BooksSync: Sync error
08-05 08:16:39.443  3515  4304 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:16:39.443  3515  4304 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 08:16:39.444  3515  4304 I BooksSync: Finished books sync
,08-05 08:16:39.459   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1068181, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:16:45.775   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1074823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:16:56.215   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:17:09.901  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:17:09.905  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:17:09.939  1516  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:17:09.939  1516  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 08:17:09.939  1516  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 08:17:09.940  1516  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:17:09.960  3423  4310 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:17:09.960  3423  4310 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:17:09.960  3423  4310 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	... 12 more
08-05 08:17:09.960  3423  4310 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at fal.a(PG:38)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:17:09.960  3423  4310 E HttpOperation: 	... 14 more
,08-05 08:17:10.017  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:17:10.018  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 08:17:10.018  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:17:10.018  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:17:10.043  3423  4310 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:17:10.043  3423  4310 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at hec.a(PG:42)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at hee.a(PG:102)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at czr.a(PG:65)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at kka.a(PG:108)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:17:10.043  3423  4310 E HttpOperation: ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:17:10.043  3423  4310 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	... 15 more
08-05 08:17:10.043  3423  4310 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at fal.a(PG:38)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:17:10.043  3423  4310 E HttpOperation: 	... 17 more
,08-05 08:17:10.043  3423  4310 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:17:10.043  3423  4310 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	... 15 more
08-05 08:17:10.043  3423  4310 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:17:10.043  3423  4310 E ExperimentLoader: 	... 17 more
,08-05 08:17:10.175   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1079288, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:17:10.841   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1099890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:17:21.268   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:17:35.909   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1124957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:17:46.335   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:18:00.975   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1150024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:18:11.388   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:18:26.042   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1175090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:18:36.441   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:18:52.335   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1201384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:19:01.495   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:19:09.648   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,08-05 08:19:17.402   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1226450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:19:26.575   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:19:42.468   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1251517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:19:51.642   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:20:07.535   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1276583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:20:16.681   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:20:32.601   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1301650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:20:41.748   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:20:57.615   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1326664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:21:06.802   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1335850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:21:22.682   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1351731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:21:31.855   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1360903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:21:47.748   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1376797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:21:56.908   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1385957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:22:12.815   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1401864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:22:21.975   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1411024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:22:37.881   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1426930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:22:47.028   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1436077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:23:02.895   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1451943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:23:12.068   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1461117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:23:27.962   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:23:37.135   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:23:44.601   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1493650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:24:02.202   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:24:09.641   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1518690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:24:27.255   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1536303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:24:28.722  3014  4330 V KeepSync: Connecting to GoogleApiClient
,08-05 08:24:28.723   872  1732 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 08:24:28.803  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:24:28.806  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:24:28.838  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 08:24:28.839  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-05 08:24:28.839  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:24:28.839  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:24:28.865  1974  4332 V BaseAuthAsyncOperation: access token request failed
,08-05 08:24:28.866   872   881 I art     : Background partial concurrent mark sweep GC freed 46681(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 29MB/43MB, paused 1.502ms total 109.748ms
,08-05 08:24:28.867  3014  4330 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 08:24:28.929  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 08:24:28.929  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 08:24:28.929  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:24:28.929  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:24:28.944  3014  4330 E KeepSync: IOException
08-05 08:24:28.944  3014  4330 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 08:24:28.944  3014  4330 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 08:24:28.944  3014  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 08:24:28.944  3014  4330 E KeepSync: 	... 10 more
,08-05 08:24:28.944  3014  4330 W KeepSync: Sync result 2
,08-05 08:24:28.959   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1537569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:24:34.708   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1543757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:24:52.309   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1561357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:24:59.775   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1568823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:25:11.694  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:11.698  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:11.748  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:25:11.749  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
08-05 08:25:11.749  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:11.749  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:11.773  3423  4335 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:25:11.773  3423  4335 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at czp.a(PG:9087)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:11.773  3423  4335 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	... 12 more
08-05 08:25:11.773  3423  4335 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at fal.a(PG:38)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:25:11.773  3423  4335 E HttpOperation: 	... 14 more
,08-05 08:25:12.039  1516  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-05 08:25:12.039  1516  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:25:12.039  1516  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:12.040  1516  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:12.053  3423  4338 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:25:12.053  3423  4338 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:12.053  3423  4338 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	... 12 more
08-05 08:25:12.053  3423  4338 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at fal.a(PG:38)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:25:12.053  3423  4338 E HttpOperation: 	... 14 more
,08-05 08:25:12.145  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-05 08:25:12.145  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:25:12.145  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:12.145  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:12.165  3423  4338 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:25:12.165  3423  4338 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at hec.a(PG:42)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at hee.a(PG:102)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at czr.a(PG:65)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at kka.a(PG:108)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:12.165  3423  4338 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	... 15 more
08-05 08:25:12.165  3423  4338 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at fal.a(PG:38)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:25:12.165  3423  4338 E HttpOperation: 	... 17 more
08-05 08:25:12.165  3423  4338 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:25:12.165  3423  4338 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	... 15 more
08-05 08:25:12.165  3423  4338 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:25:12.165  3423  4338 E ExperimentLoader: 	... 17 more
,08-05 08:25:12.288   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1099228, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:25:17.375   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1586423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:25:24.815   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1593863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:25:42.428   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1611477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:25:42.529  3515  4340 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 08:25:42.545  3515  4341 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 08:25:42.552  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.556  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.579  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:25:42.579  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:25:42.579  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:42.579  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:42.609  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.611  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.640  1516  1961 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 08:25:42.640  1516  1961 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 08:25:42.640  1516  1961 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:42.640  1516  1961 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:42.662  3515  4341 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 08:25:42.663  3515  4340 E BooksSync: Soft error
08-05 08:25:42.663  3515  4340 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:25:42.663  3515  4340 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:25:42.663  3515  4340 E BooksSync: Sync error
08-05 08:25:42.663  3515  4340 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 08:25:42.663  3515  4340 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 08:25:42.663  3515  4340 I BooksSync: Finished books sync
,08-05 08:25:42.673   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1589020, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:25:42.812  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.815  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:25:42.859  1516  3571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:25:42.859  1516  3571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:25:42.859  1516  3571 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:42.859  1516  3571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:42.887  3423  4343 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:25:42.887  3423  4343 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:42.887  3423  4343 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	... 12 more
08-05 08:25:42.887  3423  4343 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at fal.a(PG:38)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:25:42.887  3423  4343 E HttpOperation: 	... 14 more
,08-05 08:25:42.970  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-05 08:25:42.970  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:25:42.970  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:25:42.970  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:25:42.987  3423  4343 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:25:42.987  3423  4343 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at hec.a(PG:42)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at hee.a(PG:102)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at czr.a(PG:65)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at kka.a(PG:108)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:42.987  3423  4343 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	... 15 more
08-05 08:25:42.987  3423  4343 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at fal.a(PG:38)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:25:42.987  3423  4343 E HttpOperation: 	... 17 more
,08-05 08:25:42.988  3423  4343 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:25:42.988  3423  4343 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	... 15 more
08-05 08:25:42.988  3423  4343 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:25:42.988  3423  4343 E ExperimentLoader: 	... 17 more
,08-05 08:25:43.137   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1611666, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:25:49.881   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1618930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:26:07.482   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1636531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:26:14.949   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1643997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:26:32.548   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1661597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:26:39.989   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1669037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:26:44.060  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:26:44.062  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 08:26:44.099  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:26:44.099  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:26:44.099  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:26:44.099  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:26:44.114  3423  4350 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 08:26:44.114  3423  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at blb.a(PG:3937)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at czp.a(PG:18188)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:26:44.114  3423  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	... 12 more
08-05 08:26:44.114  3423  4350 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at fal.a(PG:38)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:26:44.114  3423  4350 E HttpOperation: 	... 14 more
,08-05 08:26:44.192  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 08:26:44.192  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 08:26:44.193  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 08:26:44.193  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 08:26:44.211  3423  4350 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 08:26:44.211  3423  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jdm.a(PG:82)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jcs.o(PG:406)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jcn.a(PG:1379)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jcs.i(PG:143)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at hec.a(PG:42)
,08-05 08:26:44.211  3423  4350 E HttpOperation: 	at hee.a(PG:102)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at czr.a(PG:65)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at kka.a(PG:108)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at czp.a(PG:19176)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at czp.a(PG:9081)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at czq.run(PG:1686)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423),
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:26:44.211  3423  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jdj.a(PG:4091)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jdj.a(PG:1125)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jdm.a(PG:77)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	... 15 more
08-05 08:26:44.211  3423  4350 E HttpOperation: Caused by: faj: BadAuthentication
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at fal.a(PG:38)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	at jdj.a(PG:4089)
08-05 08:26:44.211  3423  4350 E HttpOperation: 	... 17 more
08-05 08:26:44.211  3423  4350 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 08:26:44.211  3423  4350 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at hec.a(PG:42)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at hee.a(PG:102)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at czr.a(PG:65)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at kka.a(PG:108)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	... 15 more
08-05 08:26:44.211  3423  4350 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at fal.a(PG:38)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 08:26:44.211  3423  4350 E ExperimentLoader: 	... 17 more
,08-05 08:26:44.388   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1672843, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 08:26:57.602   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1686650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:27:05.055   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1694103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:27:22.655   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1711703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:27:30.094   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1719143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:27:47.722   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1736770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:27:55.161   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1744210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:28:12.775   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1761824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 08:28:20.228   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1769277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 08:28:37.828   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1786877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),08-05 08:28:43.116  4356  4356 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 08:28:43.121  4356  4356 D AndroidRuntime: CheckJNI is OFF
08-05 08:28:43.164  4356  4356 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 08:28:43.212  4356  4356 I Radio-JNI: register_android_hardware_Radio DONE
08-05 08:28:43.237  4356  4356 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-05 08:28:43.249   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-05 08:28:43.250   872   885 I ActivityManager: Killing 3771:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-05 08:28:43.352   872  1732 D GraphicsStats: Buffer count: 2
08-05 08:28:43.352   872  1766 I WindowState: WIN DEATH: Window{46be97f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 08:28:43.353   872  1315 D WifiService: Client connection lost with reason: 4
08-05 08:28:43.398   872   895 W PackageSettings: Skipping PackageSetting{b78cb1e com.example.hello/10273} due to missing metadata
08-05 08:28:43.436   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-05 08:28:43.437   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-05 08:28:43.439   872   895 I art     : Starting a blocking GC Explicit
08-05 08:28:43.441   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-05 08:28:43.441   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-05 08:28:43.441   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.441   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.441   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.441   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 08:28:43.443   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4ffa7d8 u0 com.test.thalitest/.MainActivity t2}
08-05 08:28:43.461   872  1732 W ActivityManager: Spurious death for ProcessRecord{667c36c 0:com.test.thalitest/u0a0}, curProc for 3771: null
08-05 08:28:43.515   872   895 I art     : Explicit concurrent mark sweep GC freed 47976(3MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 1.219ms total 74.129ms
08-05 08:28:43.539   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-05 08:28:43.544  4356  4356 I art     : System.exit called, status: 0
08-05 08:28:43.545  4356  4356 I AndroidRuntime: VM exiting with result code 0.
08-05 08:28:43.563   872   895 I ActivityManager: Start proc 4367:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-05 08:28:43.564   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-05 08:28:43.601   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-05 08:28:43.608  4128  4128 D BluetoothMapAppObserver: onReceive
08-05 08:28:43.608  1663  1663 I Keyboard.Facilitator: resetDictionaries() : en_US
08-05 08:28:43.608  4128  4128 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-05 08:28:43.608  1861  2030 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 08:28:43.610   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 08:28:43.616  3582  3582 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-05 08:28:43.632  1663  4381 I Keyboard.Facilitator.DecoderInitializer: run()
08-05 08:28:43.634  1663  4381 I Decoder : createOrResetDecoder
08-05 08:28:43.639  1739  1739 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-05 08:28:43.659   872  1747 I ActivityManager: Start proc 4383:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-05 08:28:43.671   872  1531 I ActivityManager: Killing 3634:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-05 08:28:43.707   872  1777 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3771 uid 10000
08-05 08:28:43.708  1663  1663 I Keyboard.Facilitator: onFinishInput()
08-05 08:28:43.708   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 08:28:43.723  1516  1516 I ConfigService: onCreate
08-05 08:28:43.741  1758  1832 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-05 08:28:43.745   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-05 08:28:43.751   872   884 E PackageManager: Failed to write settings, restoring backup
08-05 08:28:43.751   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-05 08:28:43.751   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-05 08:28:43.751   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-05 08:28:43.751   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-05 08:28:43.751   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-05 08:28:43.751   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.751   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.751   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.754   872   882 I ActivityManager: Start proc 4396:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-05 08:28:43.755  1758  1832 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-05 08:28:43.755  1758  1832 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1758
08-05 08:28:43.755  1758  1832 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.755  1758  1832 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.755   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-05 08:28:43.755   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 08:28:43.755   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 08:28:43.755   872   885 E DropBoxManagerService: 	... 13 more
08-05 08:28:43.757   872  1747 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 08:28:43.757   872  4402 E DropBoxManagerService: Can't write: system_app_crash
08-05 08:28:43.757   872  4402 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 08:28:43.757   872  4402 E DropBoxManagerService: 	... 5 more
08-05 08:28:43.761  1758  1832 I Process : Sending signal. PID: 1758 SIG: 9
08-05 08:28:43.804  4383  4383 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-05 08:28:43.817  1516  4395 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-05 08:28:43.820  1516  4395 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-05 08:28:43.829   872  1304 W InputDispatcher: channel '7cfc69f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-05 08:28:43.829   872  1304 E InputDispatcher: channel '7cfc69f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-05 08:28:43.830  1516  4395 W SQLiteOpenHelper: Opened config.db in read-only mode
08-05 08:28:43.831   872  1766 D GraphicsStats: Buffer count: 1
08-05 08:28:43.831   872  1380 I WindowState: WIN DEATH: Window{7cfc69f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-05 08:28:43.831   872  1380 W InputDispatcher: Attempted to unregister already unregistered input channel '7cfc69f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-05 08:28:43.857   872  1766 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1758) has died
08-05 08:28:43.858   872  1766 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-05 08:28:43.859   872  1766 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-05 08:28:43.873   872   885 I ActivityManager: Start proc 4413:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 08:28:43.884  1663  4381 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-05 08:28:43.912  4383  4383 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-05 08:28:43.927  4383  4428 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:28:43.929  4413  4413 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:28:43.929  1663  4381 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-05 08:28:43.929  4413  4413 D AndroidRuntime: Shutting down VM
08-05 08:28:43.934  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-05 08:28:43.934  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-05 08:28:43.936  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-05 08:28:43.937  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-05 08:28:43.939   872   882 I ActivityManager: Start proc 4429:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-05 08:28:43.946  4413  4413 E AndroidRuntime: FATAL EXCEPTION: main
08-05 08:28:43.946  4413  4413 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4413
08-05 08:28:43.946  4413  4413 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 08:28:43.946  4413  4413 E AndroidRuntime: 	... 10 more
08-05 08:28:43.950   872  1766 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 08:28:43.955  4413  4413 I Process : Sending signal. PID: 4413 SIG: 9
08-05 08:28:43.955   872  4441 E DropBoxManagerService: Can't write: system_app_crash
08-05 08:28:43.955   872  4441 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 08:28:43.955   872  4441 E DropBoxManagerService: 	... 5 more
08-05 08:28:43.965  1974  4424 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-05 08:28:43.966  1974  4424 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-05 08:28:43.969  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-05 08:28:43.969  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-05 08:28:43.970  1663  4381 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-05 08:28:43.970  1663  4381 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-05 08:28:43.971  1663  4381 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-05 08:28:43.971  1663  4381 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-05 08:28:43.971  1663  4381 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-05 08:28:43.972  1663  4381 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-05 08:28:43.973  1974  4424 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-05 08:28:43.974  1974  4424 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-05 08:28:43.978   872  1747 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4413) has died
08-05 08:28:43.979   872  1747 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.991  4383  4428 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-05 08:28:43.992  4383  4428 E AndroidRuntime: Process: android.process.acore, PID: 4383
08-05 08:28:43.992  4383  4428 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 08:28:43.992  4383  4428 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 08:28:43.996   872   885 I ActivityManager: Start proc 4442:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 08:28:43.998   872  4448 E DropBoxManagerService: Can't write: system_app_crash
08-05 08:28:43.998   872  4448 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 08:28:43.998   872  4448 E DropBoxManagerService: 	... 5 more
08-05 08:28:44.027  4383  4428 I Process : Sending signal. PID: 4383 SIG: 9
08-05 08:28:44.029  4429  4429 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm

```
