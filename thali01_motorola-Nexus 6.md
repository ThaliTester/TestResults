#### Test 845006541a293f3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 16:43:57.427   874  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:43:58.097  3845  3845 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 16:43:58.102  3845  3845 D AndroidRuntime: CheckJNI is OFF
09-09 16:43:58.128  2693  2822 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:43:58.178  3845  3845 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 16:43:58.244  3845  3845 I Radio-JNI: register_android_hardware_Radio DONE
09-09 16:43:58.274  3845  3845 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 16:43:58.279   874  2192 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 16:43:58.332   874  2192 I ActivityManager: Start proc 3854:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 16:43:58.343  3845  3845 D AndroidRuntime: Shutting down VM
09-09 16:43:58.449  3854  3854 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 16:43:58.476  3854  3854 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 16:43:58.483  3854  3854 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6118-6121)
09-09 16:43:58.483  3854  3854 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:43:58.496  3854  3854 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7331634}
09-09 16:43:58.496  3854  3854 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:43:58.497  3854  3854 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 16:43:58.505  3854  3854 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 16:43:58.506  3854  3854 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 16:43:58.527  3854  3854 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 16:43:58.539  3854  3854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:43:58.539  3854  3854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:43:58.539  3854  3854 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:43:58.539  3854  3854 I Adreno  : Build Date                       : 10/20/15
09-09 16:43:58.539  3854  3854 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:43:58.539  3854  3854 I Adreno  : Local Branch                     : M14
09-09 16:43:58.539  3854  3854 I Adreno  : Remote Branch                    : 
09-09 16:43:58.539  3854  3854 I Adreno  : Remote Branch                    : 
09-09 16:43:58.539  3854  3854 I Adreno  : Reconstruct Branch               : 
,09-09 16:43:58.611   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f35dcdd:true
,09-09 16:43:58.650  3854  3854 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 16:43:58.661  3854  3854 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-09 16:43:58.715  3854  3891 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-09 16:43:58.728  3854  3878 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-09 16:43:58.771  3854  3891 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 16:43:58.797  1888  1888 I Keyboard.Facilitator: onFinishInput()
09-09 16:43:58.837   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +443ms (total +525ms)
09-09 16:43:58.872  3854  3854 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3854
09-09 16:43:59.025  3854  3854 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-09 16:43:59.126  3854  3893 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1699219152
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 16:43:59.134  3854  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@572eadb added. We now have 1 listener(s)
09-09 16:43:59.137  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-09 16:43:59.138  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:43:59.139  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:43:59.139  3854  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 16:43:59.143  3854  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac08b6 added. We now have 1 listener(s)
09-09 16:43:59.143  3854  3893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:43:59.147  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:43:59.147  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 16:43:59.147  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 16:43:59.147  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 16:43:59.147   874  1317 D WifiService: New client listening to asynchronous messages
09-09 16:43:59.147  3854  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 16:43:59.151  3854  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:43:59.152  3854  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-09 16:43:59.160  3854  3893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:43:59.160  3854  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:43:59.161  3854  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 16:43:59.161  3854  3893 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:43:59.161  3854  3893 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 16:43:59.173  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:43:59.180  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:43:59.186  3854  3854 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 16:44:00.311  3854  3901 W jxcore-log: Initializing JXcore engine
,09-09 16:44:00.311  3854  3901 W jxcore-log: JXcore engine is ready
,09-09 16:44:00.347  3901  3901 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 16:44:00.347  3901  3901 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11606]" dev="sockfs" ino=11606 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 16:44:00.347  3901  3901 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 16:44:00.347  3901  3901 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25396]" dev="sockfs" ino=25396 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 16:44:00.363  3854  3901 W jxcore-log: Starting JXcore engine
,09-09 16:44:00.440  3854  3901 W jxcore-log: Platform android
09-09 16:44:00.440  3854  3901 W jxcore-log: 
09-09 16:44:00.440  3854  3901 W jxcore-log: Process ARCH arm
09-09 16:44:00.440  3854  3901 W jxcore-log: 
,09-09 16:44:00.680  3854  3901 I jxcore-log: JXcore Cordova bridge is ready!
09-09 16:44:00.680  3854  3901 I jxcore-log: 
09-09 16:44:00.680  3854  3901 W jxcore-log: JXcore engine is started
,09-09 16:44:00.689  3854  3893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 16:44:00.695  3854  3854 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 16:44:14.057  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 16:44:14.057  3854  3901 I jxcore-log: 
,09-09 16:44:14.059  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 16:44:14.059  3854  3901 I jxcore-log: 
,09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.075  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:44:14.078  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:44:14.081  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 16:44:14.081  3854  3901 I jxcore-log: 
,09-09 16:44:14.083  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 16:44:14.083  3854  3901 I jxcore-log: 
,09-09 16:44:14.427  3854  3901 D ExecuteNativeTests: Running unit tests
,09-09 16:44:14.496  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:44:14.496  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d added. We now have 2 listener(s)
,09-09 16:44:14.500  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:14.500  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:14.500  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:14.500  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:14.500  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 added. We now have 2 listener(s)
,09-09 16:44:14.500  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:14.501  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:44:14.517  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.529  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:44:14.534  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:44:14.534  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:44:14.536  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.537  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.541  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 16:44:14.541  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:44:14.542  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 16:44:14.546  3854  3901 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 16:44:14.546  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
09-09 16:44:14.547  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:44:14.547  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 16:44:14.547  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 16:44:14.548  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:14.549  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.550  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.551  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:14.552  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.552  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.552  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:14.552  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d removed from the list
09-09 16:44:14.552  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.553  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 removed from the list
09-09 16:44:14.553  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.553  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.553  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.553  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.554  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:14.554  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.554  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.554  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
,09-09 16:44:14.556  3854  3901 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 16:44:14.556  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.557  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 16:44:14.557  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.557  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.557  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.557  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.557  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.557  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.557  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.557  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:14.557  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.557  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.557  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.557  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.558  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.558  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:14.558  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.558  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
,09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 16:44:14.564  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 16:44:14.565  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:44:14.566  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 16:44:14.566  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.566  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.566  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.566  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.566  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.566  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.567  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.567  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.567  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.567  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.567  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.567  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.567  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.567  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.568  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:14.568  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.568  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.568  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.568  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:44:14.569  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.572  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:44:14.573  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.574  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:44:14.575  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.575  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:14.575  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:44:14.575  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:44:14.575  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.575  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.577  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.579  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.579  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:44:14.582  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:44:14.583  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:44:14.584  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:44:14.585  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 16:44:14.589  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 16:44:14.589  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:44:14.589  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:14.589  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:44:14.590  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:14.595  2693  2823 D BtGatt.GattService: registerClient() - UUID=ac7b618d-4af3-4834-8a05-d5106a01d4aa
,09-09 16:44:14.596  2693  2715 D BtGatt.GattService: onClientRegistered() - UUID=ac7b618d-4af3-4834-8a05-d5106a01d4aa, clientIf=5
09-09 16:44:14.596  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:44:14.597  2693  2706 D BtGatt.GattService: start scan with filters
,09-09 16:44:14.599  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:44:14.599  2693  2721 D BtGatt.ScanManager: handling starting scan
09-09 16:44:14.600  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:44:14.600  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:44:14.600  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:44:14.600  2693  2721 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:14.601  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.602  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:44:14.602  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.603  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:44:14.605  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 16:44:14.607  2693  2715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:44:14.607  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.608  2693  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:44:14.608  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.608  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:44:14.609  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.609  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:44:14.609  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.609  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:14.609  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:44:14.609  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:14.609  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:14.609  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:14.610  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:14.610  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:44:14.610  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.611  2693  2823 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:44:14.611  2693  2706 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:44:14.612  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.612  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:44:14.612  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:14.612  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:44:14.612  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:44:14.612  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.612  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:44:14.613  2693  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:44:14.613  2693  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:44:14.615  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.616  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.616  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:44:14.616  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.616  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.617  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.617  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.617  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.619  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.619  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:14.622  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.622  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.622  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:14.622  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.622  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.622  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:14.622  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.622  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.622  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.623  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:14.623  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:44:14.623  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.623  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:44:14.624  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.625  2693  2715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:44:14.625  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.625  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.626  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.626  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.626  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.629  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:44:14.629  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.629  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:14.630  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.630  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.631  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.636  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:44:14.636  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.636  2693  2721 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:44:14.636  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.638  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.639  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:44:14.640  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:14.640  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:44:14.640  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:44:14.640  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:44:14.640  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.640  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.640  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.641  2693  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:44:14.642  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.645  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.645  2693  2715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:44:14.645  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.646  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:14.649  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:44:14.649  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:14.649  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:44:14.650  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.652  2693  2706 D BtGatt.GattService: registerClient() - UUID=80170d9b-d1a5-4f24-9b8e-ab22bf1237be
09-09 16:44:14.652  2693  2715 D BtGatt.GattService: onClientRegistered() - UUID=80170d9b-d1a5-4f24-9b8e-ab22bf1237be, clientIf=5
09-09 16:44:14.653  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:44:14.653  2693  2823 D BtGatt.GattService: start scan with filters
09-09 16:44:14.655  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:44:14.655  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:44:14.655  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:44:14.655  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:44:14.656  2693  2721 D BtGatt.ScanManager: handling starting scan
09-09 16:44:14.657  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.657  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.657  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:44:14.659  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 16:44:14.661  2693  2715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:44:14.661  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.662  2693  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:44:14.662  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:44:14.664  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.664  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:44:14.664  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.664  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:44:14.664  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.664  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:14.665  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:44:14.665  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:14.665  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:14.665  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:14.665  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:14.665  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:44:14.665  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:44:14.665  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.666  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.666  2693  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:44:14.666  2693  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:44:14.666  2693  2706 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:44:14.666  2693  2704 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:44:14.666  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.667  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:44:14.667  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:14.667  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:44:14.667  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:44:14.667  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.667  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.667  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:44:14.667  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.668  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.669  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.669  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.669  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.669  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.669  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.669  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:14.669  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.669  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.669  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.670  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.670  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.672  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.672  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:14.674  2693  2715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:44:14.674  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.675  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:14.675  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:14.675  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:44:14.675  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.676  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.679  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.679  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.679  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.679  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:44:14.679  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.681  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.681  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.682  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.683  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.683  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.683  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.687  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:44:14.687  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.687  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.687  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.687  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.688  2693  2721 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:44:14.689  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.689  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.689  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.689  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.689  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.690  3854  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:44:14.692  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.694  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:44:14.694  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.694  2693  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.695  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:14.698  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.698  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:44:14.698  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:14.698  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:44:14.698  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:44:14.698  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.698  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.699  2693  2715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:44:14.699  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.700  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.700  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.703  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.705  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:44:14.705  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:14.705  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:44:14.706  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.709  2693  2706 D BtGatt.GattService: registerClient() - UUID=c5911e36-5153-42c1-889d-64c5d67fe005
09-09 16:44:14.710  2693  2715 D BtGatt.GattService: onClientRegistered() - UUID=c5911e36-5153-42c1-889d-64c5d67fe005, clientIf=5
09-09 16:44:14.710  3854  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:44:14.710  2693  2823 D BtGatt.GattService: start scan with filters
09-09 16:44:14.712  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:44:14.712  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:44:14.712  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:44:14.712  2693  2721 D BtGatt.ScanManager: handling starting scan
09-09 16:44:14.713  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:44:14.715  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.715  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:44:14.715  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:14.716  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 16:44:14.718  2693  2715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:44:14.718  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.718  2693  2721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:44:14.719  3854  3901 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:44:14.719  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:14.719  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:44:14.719  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.719  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:44:14.719  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.719  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:14.719  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:44:14.719  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 16:44:14.719  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:14.719  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:14.719  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:14.720  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:44:14.720  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.720  2693  2823 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:44:14.721  2693  2704 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:44:14.721  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.721  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:44:14.721  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:14.721  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 16:44:14.721  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:44:14.722  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:44:14.722  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:14.722  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.722  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.722  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 16:44:14.722  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.722  2693  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:44:14.723  2693  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:44:14.723  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.723  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.723  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:14.723  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.725  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.725  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:14.727  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:14.727  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:44:14.728  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:44:14.728  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.728  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.729  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.729  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:44:14.729  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.729  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.729  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:14.729  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.729  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.729  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.729  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.729  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.729  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.729  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.730  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.730  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:14.730  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.731  2693  2715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:44:14.731  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.732  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.732  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.732  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.734  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.734  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.734  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.735  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.735  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.735  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.736  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:14.736  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.736  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.736  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.736  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:44:14.736  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.736  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.737  3854  3901 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 16:44:14.737  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.737  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.737  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.737  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.737  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.737  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.737  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.737  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.737  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
,09-09 16:44:14.737  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.737  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.737  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.738  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.738  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.738  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.738  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.738  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.739  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:14.739  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.739  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:44:14.739  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.739  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.740  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 16:44:14.740  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.740  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.740  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.740  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:14.740  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.740  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.740  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.740  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.740  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.740  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:14.740  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.740  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.741  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.741  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.741  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.741  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.741  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.742  3854  3901 D BluetoothAdapter: STATE_ON,
09-09 16:44:14.742  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.742  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.742  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.742  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.742  2693  2715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:44:14.742  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.742  3854  3901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 16:44:14.742  2693  2721 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:44:14.742  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:14.742  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.742  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.743  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:14.743  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.743  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.743  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.743  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.743  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.743  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.743  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.743  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.743  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.743  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.744  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.744  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.744  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.744  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.744  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.744  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.744  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.744  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.745  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.745  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.745  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.745  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.745  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.745  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.745  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.745  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.745  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.745  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.745  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.745  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.746  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.746  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.746  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.746  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.746  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.746  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:14.747  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.747  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.747  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.747  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.747  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.747  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:44:14.747  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 16:44:14.747  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:44:14.747  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:44:14.748  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:44:14.748  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:44:14.748  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.748  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:14.748  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.748  2693  2715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:44:14.748  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.748  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.748  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.748  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.748  2693  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:44:14.748  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.748  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.748  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.748  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.748  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.748  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.748  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.748  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.749  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.749  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.749  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.750  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.750  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.750  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.750  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.750  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.750  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:44:14.750  3854  3901 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:44:14.750  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 16:44:14.753  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:44:14.753  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 16:44:14.753  2693  2715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 16:44:14.753  2693  2715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 16:44:14.753  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:44:14.754  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:44:14.755  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 16:44:14.755  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 16:44:14.755  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:44:14.756  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 16:44:14.756  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:44:14.756  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:44:14.756  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 16:44:14.756  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:44:14.756  3854  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 16:44:14.756  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 16:44:14.758  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 16:44:14.759  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 16:44:14.759  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 16:44:14.759  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 16:44:14.759  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 16:44:14.759  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 16:44:14.759  3854  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:44:14.760  3854  3901 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-09 16:44:14.760  3854  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-09 16:44:14.760  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.760  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.760  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.760  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.760  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.761  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.761  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-09 16:44:14.761  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.761  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.761  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.761  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.761  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.761  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.761  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.761  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.761  3854  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
,09-09 16:44:14.762  3854  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:44:14.762  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.762  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.762  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.762  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.763  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.763  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.763  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.763  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.763  3854  3901 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 16:44:14.763  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.764  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.764  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.764  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.764  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.764  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.764  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.764  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.764  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.764  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.764  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.764  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.764  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.764  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.765  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.765  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.765  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.766  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.766  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.766  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.766  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.766  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.766  3854  3901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 16:44:14.766  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:14.766  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.767  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.767  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.767  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.767  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.767  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.767  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.767  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
,09-09 16:44:14.767  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.767  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.767  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.767  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.767  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.768  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.768  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.768  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.769  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:14.769  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.769  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.769  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.769  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.769  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 16:44:14.769  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 16:44:14.769  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:44:14.769  3854  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 16:44:14.770  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-09 16:44:14.770  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 16:44:14.770  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:44:14.770  3854  3901 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 16:44:14.770  3854  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 16:44:14.770  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:44:14.770  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:44:14.770  3854  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 16:44:14.770  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:14.770  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.770  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.770  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.770  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.770  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.770  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.771  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.771  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.771  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:14.771  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.771  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.771  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.771  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.771  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.772  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.772  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.772  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.772  3854  3901 D BluetoothLeScanner: could not find callback wrapper
,09-09 16:44:14.772  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.772  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.772  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.773  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.773  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.773  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.773  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.773  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.773  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.773  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.773  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.773  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.773  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.773  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.773  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.773  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.774  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:14.774  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.774  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.774  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.774  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.774  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.774  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.774  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.774  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.774  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.774  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.774  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.774  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.774  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.774  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.774  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.775  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.775  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.775  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.775  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.775  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.775  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.775  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.776  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.776  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 16:44:14.777  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:14.777  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 16:44:14.778  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 16:44:14.778  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 16:44:14.778  3854  3854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 16:44:14.778  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 16:44:14.778  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 16:44:14.779  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 16:44:14.779  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.779  3854  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 16:44:14.779  3854  3854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 16:44:14.779  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:14.779  3854  3907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:14.779  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:14.779  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:14.779  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:14.780  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.780  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.780  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.780  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.780  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 16:44:14.780  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.780  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.781  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.781  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.781  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.781  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.782  3854  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 16:44:14.782  3854  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 16:44:14.782  3854  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 16:44:14.783  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:14.783  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:14.784  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.784  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.784  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.784  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.784  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:14.784  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.785  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:14.785  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.785  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.785  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.785  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.785  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.785  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:44:14.786  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:14.786  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:14.786  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:44:14.787  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.787  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.789  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:14.789  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:14.789  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:14.791  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:14.791  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:14.791  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.793  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:14.793  3854  3854 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 16:44:14.793  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.793  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.794  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:14.794  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.794  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:14.794  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.795  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.795  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:44:14.795  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.795  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.796  3854  3901 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 16:44:14.796  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
09-09 16:44:14.796  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:44:14.796  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:44:14.796  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.796  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.796  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.797  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.797  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.797  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.797  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.797  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.797  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.797  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.797  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.797  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.797  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.797  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.798  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.798  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:14.798  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.798  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.798  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.798  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.798  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:14.799  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.801  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.801  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.801  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:14.801  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.801  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:14.802  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.802  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
09-09 16:44:14.802  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.802  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
,09-09 16:44:14.802  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.802  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.802  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.802  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.802  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.803  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:14.803  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.803  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.803  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.803  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.803  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:44:14.803  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.803  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.804  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:14.804  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:14.804  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:14.804  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:14.804  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.804  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.804  3854  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83fcb6d not in the list
,09-09 16:44:14.804  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.804  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.804  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:14.805  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.805  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.805  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:14.805  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:14.805  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:14.805  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:14.805  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:14.806  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:14.806  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:14.806  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:14.806  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:14.806  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67303a2 not in the list
09-09 16:44:14.807  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 16:44:14.807  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:44:14.807  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 16:44:14.807  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:44:14.807  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 16:44:14.807  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:44:14.808  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 16:44:14.808  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 16:44:14.809  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 16:44:14.809  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 16:44:14.809  3854  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 16:44:14.809  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 16:44:14.809  3854  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 16:44:14.809  3854  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 16:44:14.809  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 16:44:14.809  3854  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 16:44:14.810  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 16:44:14.810  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 16:44:14.810  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 16:44:14.810  3854  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 16:44:14.810  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:14.810  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1afa038 added. We now have 2 listener(s)
09-09 16:44:14.811  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:14.812  3854  3901 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 16:44:14.812   874   884 D WifiService: setWifiEnabled: true pid=3854, uid=10000
09-09 16:44:14.812   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:14.812  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:14.813  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de87811 added. We now have 3 listener(s)
09-09 16:44:14.813  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:14.817  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:44:14.817  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb67d76 added. We now have 4 listener(s)
09-09 16:44:14.817  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:14.818  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:14.818  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d318f77 added. We now have 5 listener(s)
09-09 16:44:14.818  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:14.819   874  1533 D WifiService: setWifiEnabled: false pid=3854, uid=10000
09-09 16:44:14.819   874  1533 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:14.823  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:14.825  2693  2711 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 16:44:14.825  2693  2711 D BluetoothAdapterProperties: Setting state to 13
09-09 16:44:14.825  2693  2711 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 16:44:14.825  2693  2711 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 16:44:14.827  2693  2711 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:44:14.828  2693  2693 D BluetoothMapService: onReceive
09-09 16:44:14.828  2693  2693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:44:14.828  2693  2693 D BluetoothMapService: STATE_TURNING_OFF
09-09 16:44:14.828  2693  2693 D BluetoothMapService: MAP Service closeService in
09-09 16:44:14.829  2693  2693 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 16:44:14.829  2693  2693 D ObexServerSockets0: shutdown(block = true)
09-09 16:44:14.829  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:44:14.829  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:44:14.829  2693  2819 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 16:44:14.830  2693  2831 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 16:44:14.830  2693  2832 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 16:44:14.830  2693  2693 I BtOppRfcommListener: stopping Accept Thread
09-09 16:44:14.831  2693  3442 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 16:44:14.831  2693  3442 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 16:44:14.832  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.832  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:14.833  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.833  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.833  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:44:14.836  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.837  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.839  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:14.839  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:14.839  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.839  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:14.842  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.847  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 16:44:14.849   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 16:44:14.849   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 16:44:14.849   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:44:14.849   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:44:14.852   874   887 I ActivityManager: Start proc 3910:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 16:44:14.854  2693  2715 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:44:14.854  2693  2711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 16:44:14.856  2693  2693 D HeadsetService: Received stop request...Stopping profile...
09-09 16:44:14.858   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:14.858  1962  3236 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:14.858  2693  2693 D A2dpService: Received stop request...Stopping profile...
09-09 16:44:14.859  2693  2825 D A2dpStateMachine: Exit Disconnected: -1
09-09 16:44:14.859  1370  2058 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:14.859  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-09 16:44:14.859   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:14.859   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:14.860   874   874 D BluetoothA2dp: Proxy object disconnected
,09-09 16:44:14.860  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.861  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.861  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:14.861  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:14.861  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:14.861  2693  2693 D HidService: Received stop request...Stopping profile...
09-09 16:44:14.861  2693  2693 D HidService: Stopping Bluetooth HidService
09-09 16:44:14.862   874  1316 E native  : do suspend true
09-09 16:44:14.863  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.863  1370  1370 D BluetoothA2dp: Proxy object disconnected
09-09 16:44:14.863  1370  1370 D BluetoothInputDevice: Proxy object disconnected
09-09 16:44:14.863  1370  1370 D HidProfile: Bluetooth service disconnected
,09-09 16:44:14.864  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 16:44:14.864  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 16:44:14.864  2693  2715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:44:14.864  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:14.864  2693  2693 D HealthService: Received stop request...Stopping profile...
09-09 16:44:14.864  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:14.865  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:14.865  2693  2715 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 16:44:14.865  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.865  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:14.865  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:14.865  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:14.866  2693  2693 D PanService: Received stop request...Stopping profile...
,09-09 16:44:14.866  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:44:14.866  1370  1370 D PanProfile: Bluetooth service disconnected
09-09 16:44:14.867  2693  2715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 16:44:14.867  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:14.867  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 16:44:14.867  2693  2802 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:44:14.867  2693  2802 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:44:14.868  2693  2802 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 16:44:14.868  2693  2802 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:44:14.868  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.868  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:14.868  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:14.868  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:14.868  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 16:44:14.869  2693  2715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:44:14.869  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 16:44:14.869  2693  2693 D BluetoothMapService: Received stop request...Stopping profile...
09-09 16:44:14.869  2693  2693 D BluetoothMapService: stop()
,09-09 16:44:14.870  2693  2693 D BluetoothMapAppObserver: deinitObservers()
09-09 16:44:14.870  2693  2693 D BluetoothMapAppObserver: removeReceiver()
09-09 16:44:14.871  1370  1370 D BluetoothMap: Proxy object disconnected
09-09 16:44:14.871  1370  1370 D MapProfile: Bluetooth service disconnected
,09-09 16:44:14.871  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.871  2693  2693 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:44:14.871  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:14.871  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:14.871  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 16:44:14.871  2693  2715 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 16:44:14.872  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 16:44:14.872  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.872  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:14.872  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:14.872  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:14.873  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 16:44:14.873  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 16:44:14.873  2693  2693 D BluetoothMapService: MAP Service closeService in
09-09 16:44:14.873  2693  2693 V BluetoothAdapterState: isTurningOff()=true
09-09 16:44:14.874   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:44:14.874   874  1901 D DhcpClient: Clearing IP address
09-09 16:44:14.874  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:14.875  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:14.875  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:14.875  2693  2711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 16:44:14.875  2693  2711 D BluetoothAdapterProperties: Setting state to 15
09-09 16:44:14.875  2693  2711 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 16:44:14.875  2693  2693 D BluetoothMapService: cleanup()
09-09 16:44:14.875  2693  2693 D BluetoothMapService: MAP Service closeService in
,09-09 16:44:14.876   373   872 D CommandListener: Setting iface cfg
09-09 16:44:14.876  1370  1384 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 16:44:14.877  2693  2711 I BluetoothAdapterState: Entering BleOnState
09-09 16:44:14.878   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:14.878  1962  1980 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:14.879   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:44:14.880   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:44:14.880  1370  2058 D BluetoothMap: onBluetoothStateChange: up=false
09-09 16:44:14.881   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 16:44:14.882   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:44:14.882   874  1316 E native  : do suspend true
,09-09 16:44:14.885   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 16:44:14.885   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 16:44:14.886   404   404 E Parcel  : Reading a NULL string not supported here.
09-09 16:44:14.890  1370  1387 D BluetoothPan: onBluetoothStateChange on: false
,09-09 16:44:14.891   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 16:44:14.893   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:44:14.893  1370  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:44:14.893   874  1905 D DhcpClient: Receive thread stopped
09-09 16:44:14.894  1370  2058 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 16:44:14.897  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:44:14.898  2693  2711 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 16:44:14.898  2693  2711 D BluetoothAdapterProperties: Setting state to 16
09-09 16:44:14.898  2693  2711 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 16:44:14.900  2693  2711 D BluetoothAdapterProperties: onBleDisable
09-09 16:44:14.901  2693  2712 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:44:14.901  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:14.901  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:14.902  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.902  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:14.902  3854  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
09-09 16:44:14.903  2693  2802 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 16:44:14.903  2693  2715 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:44:14.903  2693  2802 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:14.904  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:14.904  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:14.904  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.904  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:14.901  2693  2711 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:44:14.905  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.909  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.909  1518  2487 V NativeCrypto: Read error: ssl=0x9abce600: I/O error during system call, Connection timed out
09-09 16:44:14.911  1518  2487 V NativeCrypto: SSL shutdown failed: ssl=0x9abce600: I/O error during system call, Broken pipe
09-09 16:44:14.927   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:14.933  3910  3910 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 16:44:14.943  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:44:14.948  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:14.950   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9fd736:true
,09-09 16:44:14.958   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:14.958   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:44:14.959   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 16:44:14.959   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:14.963   874   885 I ActivityManager: Start proc 3926:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 16:44:14.964   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:44:14.967   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 16:44:14.969  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:14.972  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:14.986   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:44:14.990  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:14.990  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:14.990  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.990  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:14.991   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 16:44:14.992  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:14.992  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:14.992  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:14.992  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:14.994  1919  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 16:44:14.996  3910  3910 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 16:44:15.000  3910  3910 D BluetoothMap: Create BluetoothMap proxy object
,09-09 16:44:15.008  3910  3910 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 16:44:15.013  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 16:44:15.022  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:44:15.024   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:44:15.034   874  1993 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 16:44:15.112  2693  2715 I bt_hci  : shut_down
,09-09 16:44:15.113  2693  2722 D bt_hwcfg: hw_epilog_process
,09-09 16:44:15.116  2693  2722 I bt_vendor: low_power_mode_cb
,09-09 16:44:15.144  2693  2722 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 16:44:15.144  2693  2722 I bt_vendor: epilog_cb
,09-09 16:44:15.144  2693  2722 I bt_hci  : epilog_finished_callback
09-09 16:44:15.147  2693  2715 I bt_hci_h4: hal_close
09-09 16:44:15.147  2693  2715 I bt_userial_vendor: device fd = 51 close
,09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-,09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:44:15.178  3926  3926 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:44:15.178  3926  3926 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:44:15.189  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:44:15.197  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:15.234   874   885 I ActivityManager: Start proc 3961:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-09 16:44:15.240  3910  3910 D DockEventReceiver: finishStartingService: stopping service
09-09 16:44:15.243   874   884 I ActivityManager: Killing 3616:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-09 16:44:15.297  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:44:15.299  2693  2712 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:44:15.300  2693  2711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:44:15.302  2693  2693 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:44:15.302  2693  2711 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 16:44:15.303  2693  2693 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 16:44:15.303  2693  2693 D BtGatt.GattService: stop()
09-09 16:44:15.303  2693  2693 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:44:15.305  2693  2693 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:15.305  2693  2693 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:15.305  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:15.305  2693  2693 V BluetoothAdapterState: isBleTurningOff()=true
09-09 16:44:15.306  2693  2711 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 16:44:15.306  2693  2711 D BluetoothAdapterProperties: Setting state to 10
09-09 16:44:15.306  2693  2711 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 16:44:15.307  2693  2711 I BluetoothAdapterState: Entering OffState
,09-09 16:44:15.308   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 16:44:15.310  3961  3961 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 16:44:15.334  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:44:15.334  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 16:44:15.335  2693  2693 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:44:15.335  2693  2712 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:44:15.338  2693  2712 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:44:15.346  2693  2693 I art     : System.exit called, status: 0
,09-09 16:44:15.346  2693  2693 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:44:15.410   874  1741 I ActivityManager: Process com.android.bluetooth (pid 2693) has died
,09-09 16:44:15.535  3961  3979 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 16:44:15.535  3961  3979 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 16:44:15.540  3961  3979 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 16:44:15.540  3961  3979 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 16:44:15.619  3961  3979 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 16:44:15.619  3961  3979 I Babel_SMS: MmsConfig.loadFromResources
,09-09 16:44:15.620  3961  3979 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 16:44:15.622  3961  3979 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 16:44:15.655  3961  3961 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 16:44:15.658  3961  3961 I Babel_Crash: startup - clean
,09-09 16:44:15.746  3961  3961 I Babel_telephony: TeleModule.launchCompleted
,09-09 16:44:15.821   874  1385 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 16:44:15.836  3961  3961 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 16:44:15.850  3961  3961 W Babel   : BAM#gBA: invalid account id: -1
,09-09 16:44:15.850  3961  3961 W Babel   : BAM#gBA: invalid account id: -1
09-09 16:44:15.850  3961  3961 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 16:44:15.853  3961  3986 I Babel   : deleted: false for 0
,09-09 16:44:15.936   874  1993 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 16:44:15.974  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:44:15.979  3926  3948 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 16:44:15.997  1727  1727 D SystemUpdateService: onCreate
,09-09 16:44:16.010  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:44:16.031  1727  3988 I SystemUpdateService: active receiver: enabled
,09-09 16:44:16.035  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-09 16:44:16.036  1727  2463 I iu.UploadsManager: num queued entries: 0
09-09 16:44:16.037  1727  3988 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 16:44:16.042  1727  2463 I iu.UploadsManager: num updated entries: 0
,09-09 16:44:16.043  1727  2463 I iu.SyncManager: NEXT; no task
,09-09 16:44:16.044  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:44:16.046  1727  3988 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 16:44:16.046  1727  3988 I SystemUpdateService: now status is 0 (complete)
09-09 16:44:16.046  1727  3988 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:44:16.046  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 16:44:16.046  1727  3988 I SystemUpdateService: file has been verified
,09-09 16:44:16.047  1727  3988 I SystemUpdateService: OTA package size = 12249756
,09-09 16:44:16.052  1727  3988 I SystemUpdateService: showing system update notification
,09-09 16:44:16.060   874  3134 I ActivityManager: Start proc 3990:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 16:44:16.068  3961  3961 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 16:44:16.076  1727  1727 D SystemUpdateService: onDestroy
,09-09 16:44:16.106  3990  3990 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 16:44:16.112  3990  3990 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:16.115   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58dfd88:true
,09-09 16:44:16.121  3990  3990 D SprintDMHelper: simOperator: 
,09-09 16:44:16.121  3990  3990 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:44:16.123  3961  3961 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 16:44:16.129  3961  3961 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 16:44:16.131  3961  3961 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 16:44:16.133  3961  3961 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 16:44:16.138  3961  3961 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 16:44:16.142   874  1385 I ActivityManager: Start proc 4002:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 16:44:16.146   874  2007 I ActivityManager: Killing 3634:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-09 16:44:16.177  3961  3961 I vclib   : onServiceConnected
,09-09 16:44:16.282   874  2000 I ActivityManager: Start proc 4017:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 16:44:16.285  3961  4016 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 16:44:16.291   874  1741 I ActivityManager: Killing 3457:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 16:44:16.369  4017  4017 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 16:44:16.443  4017  4017 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 16:44:16.443  4017  4017 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:44:16.443  4017  4017 I GAv4    :   adb logcat -s GAv4
,09-09 16:44:16.467  4017  4017 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:44:16.472  4017  4017 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:44:16.506  4017  4034 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:44:16.603  4017  4017 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 16:44:16.643  4017  4017 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 16:44:16.658  4017  4017 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4293-4295)
,09-09 16:44:16.658  4017  4017 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 16:44:16.670  4017  4017 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79ba0a8}
,09-09 16:44:16.670  4017  4017 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:44:16.670  4017  4017 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:44:16.676  4017  4017 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 16:44:16.677  4017  4017 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:44:16.701  4017  4017 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 16:44:16.712  4017  4017 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:44:16.712  4017  4017 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 16:44:16.712  4017  4017 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:44:16.712  4017  4017 I Adreno  : Build Date                       : 10/20/15
09-09 16:44:16.712  4017  4017 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:44:16.712  4017  4017 I Adreno  : Local Branch                     : M14
09-09 16:44:16.712  4017  4017 I Adreno  : Remote Branch                    : 
09-09 16:44:16.712  4017  4017 I Adreno  : Remote Branch                    : 
09-09 16:44:16.712  4017  4017 I Adreno  : Reconstruct Branch               : 
,09-09 16:44:16.775  4017  4017 I NSApplication: Starting up...
,09-09 16:44:16.783  4017  4063 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 16:44:16.797   874  1385 I ActivityManager: Start proc 4068:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 16:44:16.801   874  1385 I ActivityManager: Killing 1697:android.process.acore/u0a5 (adj 15): empty #17
,09-09 16:44:16.877  4068  4068 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 16:44:17.087   874  3134 I ActivityManager: Killing 3665:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-09 16:44:17.146   874   885 I ActivityManager: Start proc 4082:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 16:44:17.212  4082  4082 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 16:44:17.260  4082  4082 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 16:44:17.281   874  1984 I ActivityManager: Killing 3699:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 16:44:17.836   874  1994 D WifiService: setWifiEnabled: true pid=3854, uid=10000
09-09 16:44:17.836   874  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:17.847   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:44:17.857  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:17.857  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:17.857  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:17.858  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:17.861  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:17.861  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:17.861  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:17.862  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:17.882   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-09 16:44:17.883   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 16:44:17.884   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 16:44:17.885   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 16:44:17.885   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 16:44:17.885   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 16:44:17.885   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:44:17.901   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 16:44:17.902   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 16:44:17.904   373   872 D CommandListener: Setting iface cfg
,09-09 16:44:17.912   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 16:44:17.913   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 16:44:17.913   874  1316 E native  : do suspend true
,09-09 16:44:17.928   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:44:17.929   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:44:17.932   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:44:19.224   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:44:19.336   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.50 rxSuccessRate=9.69 delta 1000 -> 994
,09-09 16:44:19.338   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 16:44:19.338   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:44:19.360   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:44:19.421   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:44:19.424  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:44:19.857  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 16:44:19.897  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:44:19.899  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 16:44:19.909   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:44:19.922   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:44:19.923   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:44:19.923   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 16:44:19.948   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:44:19.965   373   872 D CommandListener: Setting iface cfg
,09-09 16:44:19.966   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 16:44:19.971   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:44:20.009   874  4117 D DhcpClient: Receive thread started
,09-09 16:44:20.094   874  1316 E native  : do suspend false
,09-09 16:44:20.105   874  1901 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:44:20.120   874  4117 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172594, domain null
,09-09 16:44:20.121   874  1901 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172594 seconds
,09-09 16:44:20.124   874  1901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 16:44:20.143   874  4117 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 16:44:20.144   874  1901 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 16:44:20.149   373   872 D CommandListener: Setting iface cfg
,09-09 16:44:20.156   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:44:20.159   874  1901 D DhcpClient: Scheduling renewal in 86399s
,09-09 16:44:20.159   874  1316 E native  : do suspend true
,09-09 16:44:20.177   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 16:44:20.178   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
09-09 16:44:20.179   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 16:44:20.182   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 16:44:20.191   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 16:44:20.246   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 16:44:20.247   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 16:44:20.252   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 16:44:20.253   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 16:44:20.256   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 16:44:20.269   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:44:20.274   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-09 16:44:20.275   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 16:44:20.275   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 16:44:20.275   874  1318 D ConnectivityService:    accepting network in place of null
,09-09 16:44:20.275   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 16:44:20.277   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:44:20.277   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:44:20.337   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:20.344   874  4116 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227981, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:44:20.407   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:20.410   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 16:44:20.411   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:20.415   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 16:44:20.419  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:20.412   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:20.419  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:20.419  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:20.419  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:20.420  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:20.421  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:44:20.421  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:20.421  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:44:20.437  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:44:20.440  1727  1727 D SystemUpdateService: onCreate
,09-09 16:44:20.442   874  4115 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 16:44:20.443  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:44:20.447  1727  4129 I SystemUpdateService: active receiver: enabled
,09-09 16:44:20.451  1727  4129 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:44:20.457  1727  4129 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 16:44:20.458  1727  4129 I SystemUpdateService: now status is 0 (complete)
09-09 16:44:20.458  1727  4129 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:44:20.458  1727  4129 I SystemUpdateService: file has been verified
,09-09 16:44:20.458  1727  4129 I SystemUpdateService: OTA package size = 12249756
,09-09 16:44:20.467  1727  4129 I SystemUpdateService: showing system update notification
,09-09 16:44:20.469  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:44:20.474  1727  2463 I iu.UploadsManager: num queued entries: 0
,09-09 16:44:20.474  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 16:44:20.474  1727  2463 I iu.UploadsManager: num updated entries: 0
09-09 16:44:20.475  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 16:44:20.477  1727  4134 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 16:44:20.477  1727  4134 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 16:44:20.478  3990  3990 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:20.479  1727  2463 I iu.SyncManager: NEXT; no task
09-09 16:44:20.479  1727  4134 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:44:20.484  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:44:20.484  3990  3990 D SprintDMHelper: simOperator: 
,09-09 16:44:20.484  3990  3990 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 16:44:20.486  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:44:20.501  1727  1727 D SystemUpdateService: onDestroy
,09-09 16:44:20.507   874  4115 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:44:20 GMT], X-Android-Received-Millis=[1473432260506], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473432260479]}
09-09 16:44:20.509   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 16:44:20.509   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-09 16:44:20.509   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:44:20.510   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 16:44:20.530  1518  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 16:44:20.530  1518  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 16:44:20.530  1518  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:44:20.530  1518  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:44:20.543  1727  4134 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-09 16:44:20.604  3961  4136 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:44:20.843   874  1742 D WifiService: setWifiEnabled: false pid=3854, uid=10000
,09-09 16:44:20.843   874  1742 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:20.880  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 16:44:20.892   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 16:44:20.892   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 16:44:20.892   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:44:20.893   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:44:20.913   874  1316 E native  : do suspend true
,09-09 16:44:20.931   874  1901 D DhcpClient: Clearing IP address
,09-09 16:44:20.932   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:44:20.949   373   872 D CommandListener: Setting iface cfg
,09-09 16:44:20.952   874  4117 D DhcpClient: Receive thread stopped
09-09 16:44:20.957   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 16:44:20.958   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 16:44:20.968   404   404 E Parcel  : Reading a NULL string not supported here.
09-09 16:44:20.969   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 16:44:20.974   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:44:20.974   874  1316 E native  : do suspend true
,09-09 16:44:20.976   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 16:44:21.013   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:21.071   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:21.072   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:44:21.072   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 16:44:21.072   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:21.075   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:44:21.092  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:21.092  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:21.092  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:21.092  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:21.093  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:21.093  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:21.093  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:21.093  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:21.105  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:44:21.117  1727  1727 D SystemUpdateService: onCreate
,09-09 16:44:21.121  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:44:21.140  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 16:44:21.144  1727  2463 I iu.UploadsManager: num queued entries: 0
,09-09 16:44:21.153  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:44:21.155  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:44:21.160  1727  4151 I SystemUpdateService: active receiver: enabled
,09-09 16:44:21.165  1727  2463 I iu.UploadsManager: num updated entries: 0
,09-09 16:44:21.169   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:44:21.172   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 16:44:21.173  3990  3990 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 16:44:21.173   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:44:21.177  1727  2463 I iu.SyncManager: NEXT; no task
,09-09 16:44:21.178  1727  4151 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:44:21.182  1727  4151 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 16:44:21.182  1727  4151 I SystemUpdateService: now status is 0 (complete)
09-09 16:44:21.182  1727  4151 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:44:21.182  1727  4151 I SystemUpdateService: file has been verified
,09-09 16:44:21.182  3990  3990 D SprintDMHelper: simOperator: 
09-09 16:44:21.182  3990  3990 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 16:44:21.182  1727  4151 I SystemUpdateService: OTA package size = 12249756
,09-09 16:44:21.189  1727  4151 I SystemUpdateService: showing system update notification
,09-09 16:44:21.193   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.,
09-09 16:44:21.196  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:21.196  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:21.197  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:21.197  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:21.198   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 16:44:21.199  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:21.199  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:21.199  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:21.199  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:21.199  1919  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 16:44:21.224  3961  4155 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 16:44:21.293  1727  1727 D SystemUpdateService: onDestroy
,09-09 16:44:21.296   874  2000 I ActivityManager: Killing 3715:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 16:44:21.412   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 16:44:23.885   874   891 I ActivityManager: Start proc 4158:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 16:44:24.003  4158  4158 D AdapterServiceConfig: Adding HeadsetService
,09-09 16:44:24.004  4158  4158 D AdapterServiceConfig: Adding A2dpService
,09-09 16:44:24.004  4158  4158 D AdapterServiceConfig: Adding HidService
,09-09 16:44:24.004  4158  4158 D AdapterServiceConfig: Adding HealthService
,09-09 16:44:24.004  4158  4158 D AdapterServiceConfig: Adding PanService
,09-09 16:44:24.005  4158  4158 D AdapterServiceConfig: Adding GattService
,09-09 16:44:24.005  4158  4158 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:44:24.021   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f66caf:true
,09-09 16:44:24.021  4158  4158 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 16:44:24.026  4158  4158 I bt_bluedroid: init
,09-09 16:44:24.027  4158  4170 I BluetoothAdapterState: Entering OffState
,09-09 16:44:24.032  4158  4171 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:44:24.033  4158  4171 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 16:44:24.033  4158  4171 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 16:44:24.033  4158  4171 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 16:44:24.036  4158  4158 I bt_bluedroid: get_profile_interface socket
,09-09 16:44:24.039  4158  4174 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 16:44:24.039  4158  4158 I bt_bluedroid: get_profile_interface sdp
09-09 16:44:24.041  4158  4174 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:44:24.044  4158  4169 I bt_bluedroid: config_hci_snoop_log
09-09 16:44:24.045   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 16:44:24.052  4158  4170 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 16:44:24.053  4158  4170 D BluetoothAdapterProperties: Setting state to 14
09-09 16:44:24.053  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 16:44:24.057  4158  4170 D BluetoothBondStateMachine: make
,09-09 16:44:24.062  4158  4175 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:44:24.072  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:44:24.072  4158  4158 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:44:24.080  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:24.082  4158  4158 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:44:24.083  4158  4158 D BtGatt.GattService: Received start request. Starting profile...
,09-09 16:44:24.084  4158  4158 D BtGatt.GattService: start()
09-09 16:44:24.084  4158  4158 I bt_bluedroid: get_profile_interface gatt
,09-09 16:44:24.086  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:24.086  4158  4158 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:44:24.095  4158  4158 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:24.095  4158  4158 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:24.095  4158  4158 V BluetoothAdapterState: isBleTurningOn()=true
09-09 16:44:24.096  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:24.096  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 16:44:24.097  4158  4170 I bt_bluedroid: enable
09-09 16:44:24.097  4158  4171 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 16:44:24.098  4158  4171 I bt_hci  : start_up
,09-09 16:44:24.117  4158  4171 I bt_vendor: alloc value 0xb39a0189
,09-09 16:44:24.118  4158  4171 I bt_vendor: init
,09-09 16:44:24.118  4158  4171 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 16:44:24.118  4158  4171 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:44:24.227  4158  4171 D bt_hci  : start_up starting async portion
,09-09 16:44:24.228  4158  4178 I bt_hci  : event_finish_startup
09-09 16:44:24.228  4158  4178 I bt_hci_h4: hal_open
,09-09 16:44:24.229  4158  4178 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 16:44:24.240  4158  4178 I bt_userial_vendor: device fd = 51 open
,09-09 16:44:24.269  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:44:24.301  4158  4178 D bt_hwcfg: Chipset BCM4354A2
,09-09 16:44:24.301  4158  4178 D bt_hwcfg: Target name = [BCM4354A2]
09-09 16:44:24.302  4158  4178 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:44:24.957  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 16:44:24.958  4158  4178 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 16:44:24.958  4158  4178 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:44:25.075  4158  4178 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:44:25.076  4158  4178 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:44:25.106  4158  4178 I bt_hwcfg: vendor lib fwcfg completed
,09-09 16:44:25.106  4158  4178 I bt_vendor: firmware callback
,09-09 16:44:25.106  4158  4178 I bt_hci  : firmware_config_callback
,09-09 16:44:25.118  4158  4180 I bt_btu  : btu_task pending for preload complete event
,09-09 16:44:25.118  4158  4180 I bt_btu_task: Bluetooth chip preload is complete
09-09 16:44:25.118  4158  4180 I bt_btu  : btu_task received preload complete event
,09-09 16:44:25.130  4158  4180 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 16:44:25.130  4158  4180 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 16:44:25.131  4158  4180 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 16:44:25.131  4158  4180 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 16:44:25.131  4158  4180 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 16:44:25.132  4158  4180 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:44:25.132  4158  4180 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 16:44:25.132  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 16:44:25.132  4158  4180 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:44:25.133  4158  4180 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 16:44:25.133  4158  4180 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:44:25.133  4158  4180 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 16:44:25.133  4158  4180 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:44:25.134  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:44:25.134  4158  4180 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:44:25.268  4158  4180 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391dd9d
,09-09 16:44:25.269  4158  4180 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391dd9d 
,09-09 16:44:25.281  4158  4174 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 16:44:25.283  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:44:25.284  4158  4174 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:44:25.287  4158  4174 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:44:25.291  4158  4174 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:44:25.291  4158  4174 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:44:25.291  4158  4174 D bt_hci  : do_postload posting postload work item
09-09 16:44:25.292  4158  4178 I bt_hci  : event_postload
09-09 16:44:25.292  4158  4178 I bt_vendor: sco_config_cb
09-09 16:44:25.292  4158  4178 I bt_hci  : sco_config_callback postload finished.
09-09 16:44:25.294  4158  4174 D bt_bte_conf: Device ID record 1 : primary
,09-09 16:44:25.295  4158  4174 D bt_bte_conf:   vendorId            = 000f
09-09 16:44:25.296  4158  4174 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 16:44:25.297  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:25.298  4158  4178 I bt_vendor: low_power_mode_cb
,09-09 16:44:25.296  4158  4174 D bt_bte_conf:   product             = 1200
09-09 16:44:25.299  4158  4174 D bt_bte_conf:   version             = 1436
09-09 16:44:25.300  4158  4174 D bt_bte_conf:   clientExecutableURL = 
09-09 16:44:25.300  4158  4174 D bt_bte_conf:   serviceDescription  = 
09-09 16:44:25.300  4158  4174 D bt_bte_conf:   documentationURL    = 
09-09 16:44:25.300  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:25.300  4158  4174 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 16:44:25.301  4158  4171 D bt_stack_manager: event_start_up_stack finished
09-09 16:44:25.302  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 16:44:25.303  4158  4170 D BluetoothAdapterProperties: Setting state to 15
,09-09 16:44:25.303  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 16:44:25.305  4158  4170 I BluetoothAdapterState: Entering BleOnState
09-09 16:44:25.311  4158  4170 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 16:44:25.311  4158  4170 D BluetoothAdapterProperties: Setting state to 11
09-09 16:44:25.311  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 16:44:25.318  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:25.321  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:25.322  4158  4158 D HeadsetService: Received start request. Starting profile...
09-09 16:44:25.322  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:25.326  4158  4158 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 16:44:25.326  4158  4158 D HeadsetStateMachine: make
09-09 16:44:25.328  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:44:25.335  4158  4158 D HeadsetStateMachine: max_hf_connections = 1
,09-09 16:44:25.335  4158  4158 I bt_bluedroid: get_profile_interface handsfree
09-09 16:44:25.335  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 16:44:25.335  4158  4174 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 16:44:25.338  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:25.338  4158  4158 D A2dpService: Received start request. Starting profile...
,09-09 16:44:25.339  4158  4158 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 16:44:25.339  4158  4158 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:44:25.345  4158  4158 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 16:44:25.345  4158  4158 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 16:44:25.345  4158  4158 D A2dpStateMachine: make
,09-09 16:44:25.346  4158  4158 I bt_bluedroid: get_profile_interface a2dp
,09-09 16:44:25.347  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 16:44:25.349  4158  4190 D A2dpStateMachine: Enter Disconnected: -2
,09-09 16:44:25.350  4158  4158 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 16:44:25.350  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:25.352  3910  3910 D BluetoothInputDevice: Proxy object connected
,09-09 16:44:25.352  4158  4158 D HidService: Received start request. Starting profile...
09-09 16:44:25.352  4158  4158 I bt_bluedroid: get_profile_interface hidhost
09-09 16:44:25.352  3910  3910 D HidProfile: Bluetooth service connected
09-09 16:44:25.352  4158  4174 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ff3e5
09-09 16:44:25.352  4158  4158 D HidService: setHidService(): set to: null
09-09 16:44:25.353  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 16:44:25.353  4158  4158 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 16:44:25.354  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:25.356  4158  4158 D HealthService: Received start request. Starting profile...
,09-09 16:44:25.357  4158  4158 I bt_bluedroid: get_profile_interface health
,09-09 16:44:25.358  4158  4158 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:44:25.359  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:25.360  3910  3910 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 16:44:25.360  4158  4158 D PanService: Received start request. Starting profile...
09-09 16:44:25.361  4158  4158 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 16:44:25.361  4158  4158 I bt_bluedroid: get_profile_interface pan
09-09 16:44:25.361  4158  4174 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 16:44:25.364  4158  4158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:25.365  4158  4158 D BluetoothMapService: Received start request. Starting profile...
09-09 16:44:25.366  4158  4158 D BluetoothMapService: start()
,09-09 16:44:25.368  4158  4158 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 16:44:25.369  4158  4158 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 16:44:25.369  4158  4158 D BluetoothMapAppObserver: createReceiver()
,09-09 16:44:25.370  4158  4158 D BluetoothMapAppObserver: initObservers()
09-09 16:44:25.370  4158  4158 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:44:25.379  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:25.381  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:25.381  4158  4158 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:25.381  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:25.381  3910  3910 D PanProfile: Bluetooth service connected
09-09 16:44:25.381  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:25.381  3910  3910 D BluetoothMap: Proxy object connected
,09-09 16:44:25.383  3910  3910 D MapProfile: Bluetooth service connected
09-09 16:44:25.383  3910  3910 D BluetoothMap: getConnectedDevices()
09-09 16:44:25.384  3910  3910 D BluetoothMap: Bluetooth is Not enabled
09-09 16:44:25.384  4158  4188 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:44:25.384  4158  4158 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:25.384  4158  4158 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:25.385  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:25.386  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:25.387  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 16:44:25.387  4158  4170 D BluetoothAdapterProperties: ScanMode =  20
09-09 16:44:25.387  4158  4170 D BluetoothAdapterProperties: State =  11
09-09 16:44:25.387  4158  4170 D BluetoothAdapterProperties: Setting state to 12
09-09 16:44:25.387  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 16:44:25.388  4158  4170 I BluetoothAdapterState: Entering OnState
,09-09 16:44:25.389  1370  1387 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 16:44:25.390  4158  4174 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:44:25.390  4158  4174 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:44:25.390   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:25.391  1962  1974 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:25.391   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 16:44:25.392  3910  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:44:25.392   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:25.393  1370  2058 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:44:25.393   874   874 D BluetoothA2dp: Proxy object connected
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:25.394  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:25.395  1370  1370 D BluetoothMap: Proxy object connected
09-09 16:44:25.395  1370  1370 D MapProfile: Bluetooth service connected
09-09 16:44:25.395  1370  1370 D BluetoothMap: getConnectedDevices()
09-09 16:44:25.395  1370  1387 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:44:25.397  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:25.398  4158  4158 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 16:44:25.398  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:44:25.398  1370  1370 D PanProfile: Bluetooth service connected
09-09 16:44:25.398  3910  3921 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:44:25.399  4158  4158 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 16:44:25.399   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:44:25.399  3910  3920 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:44:25.399  1370  2058 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:25.400  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:25.400  4158  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:25.400  3910  3921 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 16:44:25.401  1370  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:44:25.402  4158  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:25.402  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:25.403  4158  4158 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:44:25.403  4158  4158 D ObexServerSockets0: startAccept()
09-09 16:44:25.403  4158  4158 D ObexServerSockets0: prepareForNewConnect()
09-09 16:44:25.403  1370  1370 D BluetoothInputDevice: Proxy object connected
09-09 16:44:25.403  1370  1370 D HidProfile: Bluetooth service connected
09-09 16:44:25.404  1370  2058 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 16:44:25.405  4158  4158 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 16:44:25.405  4158  4158 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 16:44:25.406  4158  4196 D ObexServerSockets0: Accepting socket connection...
09-09 16:44:25.406  4158  4197 D ObexServerSockets0: Accepting socket connection...
09-09 16:44:25.406  1370  1370 D BluetoothA2dp: Proxy object connected
,09-09 16:44:25.409   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 16:44:25.410  4158  4158 D BluetoothMapService: onReceive
09-09 16:44:25.410  4158  4158 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 16:44:25.410  4158  4158 D BluetoothMapService: STATE_ON
,09-09 16:44:25.411  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:25.412  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:25.413  3910  3910 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 16:44:25.415  3910  3910 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 16:44:25.420  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:44:25.421  3910  3910 D BluetoothA2dp: Proxy object connected
,09-09 16:44:25.425  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:25.430  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:44:25.433  3910  3910 D BluetoothPbap: Proxy object connected
09-09 16:44:25.433  3910  3910 D PbapServerProfile: Bluetooth service connected
,09-09 16:44:25.434  1370  1370 D BluetoothPbap: Proxy object connected
09-09 16:44:25.434  1370  1370 D PbapServerProfile: Bluetooth service connected
,09-09 16:44:25.439  4158  4158 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:44:25.440  4158  4158 D ObexServerSockets0: prepareForNewConnect()
,09-09 16:44:25.441  4158  4203 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:25.455  4158  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:25.456  4158  4207 I BtOppRfcommListener: Accept thread started.
,09-09 16:44:25.491   874   874 D BluetoothHeadset: Proxy object connected
,09-09 16:44:25.491  1962  3236 D BluetoothHeadset: Proxy object connected
09-09 16:44:25.491  1962  2080 D BluetoothHeadset: Proxy object connected
09-09 16:44:25.491  1370  1387 D BluetoothHeadset: Proxy object connected
09-09 16:44:25.492  1370  1370 D HeadsetProfile: Bluetooth service connected
09-09 16:44:25.492   874   891 D BluetoothHeadset: Proxy object connected
09-09 16:44:25.492   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:44:25.492   874   874 D BluetoothHeadset: Proxy object connected
,09-09 16:44:25.499   874   891 D BluetoothHeadset: Proxy object connected
,09-09 16:44:25.500  1370  2058 D BluetoothHeadset: Proxy object connected
,09-09 16:44:25.500  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-09 16:44:25.519  3910  3921 D BluetoothHeadset: Proxy object connected
,09-09 16:44:25.521  3910  3910 D HeadsetProfile: Bluetooth service connected
,09-09 16:44:26.866  4158  4170 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 16:44:26.867  4158  4170 D BluetoothAdapterProperties: Setting state to 13
,09-09 16:44:26.867  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,09-09 16:44:26.869  4158  4170 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 16:44:26.871  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:44:26.877  4158  4174 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:44:26.878  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 16:44:26.885  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:26.885  4158  4158 D HeadsetService: Received stop request...Stopping profile...
,09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:26.885  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:26.889  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:44:26.889  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:26.893   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:44:26.894  1962  1980 D BluetoothHeadset: Proxy object disconnected
,09-09 16:44:26.895  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:26.895  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:26.897  4158  4158 D A2dpService: Received stop request...Stopping profile...
,09-09 16:44:26.897  3910  3920 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:26.897  3854  3854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:44:26.897  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:26.898  1370  1384 D BluetoothHeadset: Proxy object disconnected
,09-09 16:44:26.899  4158  4190 D A2dpStateMachine: Exit Disconnected: -1
09-09 16:44:26.899   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:44:26.899  3910  3910 D HeadsetProfile: Bluetooth service disconnected
09-09 16:44:26.899   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 16:44:26.900  1370  1370 D HeadsetProfile: Bluetooth service disconnected
09-09 16:44:26.900   874   874 D BluetoothA2dp: Proxy object disconnected
,09-09 16:44:26.901  1370  1370 D BluetoothA2dp: Proxy object disconnected
09-09 16:44:26.902  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.902  4158  4158 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:44:26.902  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:26.902  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:26.902  3910  3910 D BluetoothA2dp: Proxy object disconnected
09-09 16:44:26.902  4158  4158 D HidService: Received stop request...Stopping profile...
,09-09 16:44:26.902  4158  4158 D HidService: Stopping Bluetooth HidService
09-09 16:44:26.904  3910  3910 D BluetoothInputDevice: Proxy object disconnected
,09-09 16:44:26.904  3910  3910 D HidProfile: Bluetooth service disconnected
,09-09 16:44:26.905  1370  1370 D BluetoothInputDevice: Proxy object disconnected
,09-09 16:44:26.905  1370  1370 D HidProfile: Bluetooth service disconnected
,09-09 16:44:26.906  4158  4158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 16:44:26.906  4158  4158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 16:44:26.906  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:44:26.906  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 16:44:26.906  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-09 16:44:26.906  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:26.906  4158  4174 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-09 16:44:26.908  4158  4158 D HealthService: Received stop request...Stopping profile...
,09-09 16:44:26.911  4158  4158 D PanService: Received stop request...Stopping profile...
09-09 16:44:26.912  3910  3910 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:44:26.912  3910  3910 D PanProfile: Bluetooth service disconnected
09-09 16:44:26.912  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:44:26.912  1370  1370 D PanProfile: Bluetooth service disconnected
09-09 16:44:26.913  4158  4158 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 16:44:26.913  4158  4158 D BluetoothMapService: stop()
09-09 16:44:26.913  4158  4158 D BluetoothMapAppObserver: deinitObservers()
09-09 16:44:26.914  4158  4158 D BluetoothMapAppObserver: removeReceiver()
,09-09 16:44:26.915  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.915  3910  3910 D BluetoothMap: Proxy object disconnected
09-09 16:44:26.915  4158  4158 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:26.915  3910  3910 D MapProfile: Bluetooth service disconnected
09-09 16:44:26.915  1370  1370 D BluetoothMap: Proxy object disconnected
,09-09 16:44:26.915  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:26.915  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:26.915  1370  1370 D MapProfile: Bluetooth service disconnected
,09-09 16:44:26.917  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 16:44:26.918  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 16:44:26.918  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:26.918  4158  4180 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:44:26.918  4158  4180 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 16:44:26.918  4158  4180 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:44:26.918  4158  4180 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 16:44:26.923  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.923  4158  4158 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:44:26.923  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:26.923  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:26.924  4158  4158 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 16:44:26.924  4158  4158 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 16:44:26.924  4158  4174 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 16:44:26.925  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.925  4158  4158 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:44:26.925  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:26.925  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:26.925  4158  4158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 16:44:26.927  4158  4158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 16:44:26.929  4158  4174 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-09 16:44:26.929  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:26.929  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.929  4158  4158 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:26.929  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:26.930  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:26.931  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:26.931  4158  4158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 16:44:26.931  4158  4158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 16:44:26.935  4158  4158 D BluetoothMapService: MAP Service closeService in
09-09 16:44:26.935  4158  4158 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 16:44:26.936  4158  4158 D ObexServerSockets0: shutdown(block = true)
,09-09 16:44:26.936  4158  4196 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 16:44:26.938  4158  4158 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 16:44:26.938  4158  4197 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 16:44:26.938  4158  4182 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 16:44:26.939  4158  4158 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:44:26.939  4158  4158 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:44:26.940  4158  4158 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:26.940  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:26.940  4158  4158 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:26.942  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 16:44:26.942  4158  4170 D BluetoothAdapterProperties: Setting state to 15
,09-09 16:44:26.942  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-09 16:44:26.943  4158  4170 I BluetoothAdapterState: Entering BleOnState
,09-09 16:44:26.944  1370  1384 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 16:44:26.931  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:44:26.946   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:26.946  1962  1974 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:26.947  4158  4158 D BluetoothMapService: cleanup()
,09-09 16:44:26.947  4158  4158 D BluetoothMapService: MAP Service closeService in
09-09 16:44:26.947  4158  4158 I BtOppRfcommListener: stopping Accept Thread
,09-09 16:44:26.948  4158  4207 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 16:44:26.949  4158  4207 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 16:44:26.949  3910  3921 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:26.951  3910  3921 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:44:26.952   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 16:44:26.952  3910  3920 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 16:44:26.953   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:44:26.953  1370  2058 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 16:44:26.956  1370  1387 D BluetoothPan: onBluetoothStateChange on: false
09-09 16:44:26.956  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:26.957  3910  3921 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 16:44:26.959   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:44:26.960  3910  3920 D BluetoothPan: onBluetoothStateChange on: false
,09-09 16:44:26.961  1370  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:44:26.961  3910  3920 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 16:44:26.965  1370  2058 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 16:44:26.968  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:44:26.969  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 16:44:26.969  4158  4170 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 16:44:26.970  4158  4170 D BluetoothAdapterProperties: Setting state to 16
09-09 16:44:26.970  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 16:44:26.970  4158  4170 D BluetoothAdapterProperties: onBleDisable
09-09 16:44:26.971  4158  4170 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:44:26.971  4158  4171 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:44:26.972  4158  4180 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 16:44:26.972  4158  4180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:44:26.975  4158  4174 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:44:26.976  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:26.977  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:26.978  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:44:26.978  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:26.979  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:26.982  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:26.985  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:44:27.172  4158  4174 I bt_hci  : shut_down
09-09 16:44:27.173  4158  4178 D bt_hwcfg: hw_epilog_process
,09-09 16:44:27.184  4158  4178 I bt_vendor: low_power_mode_cb
,09-09 16:44:27.211  4158  4178 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 16:44:27.211  4158  4178 I bt_vendor: epilog_cb
09-09 16:44:27.212  4158  4178 I bt_hci  : epilog_finished_callback
,09-09 16:44:27.217  4158  4174 I bt_hci_h4: hal_close
,09-09 16:44:27.218  4158  4174 I bt_userial_vendor: device fd = 51 close
,09-09 16:44:27.342  4158  4171 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:44:27.344  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:44:27.350  4158  4158 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:44:27.351  4158  4170 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 16:44:27.352  4158  4158 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 16:44:27.355  4158  4158 D BtGatt.GattService: stop()
,09-09 16:44:27.356  4158  4158 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:44:27.362  4158  4158 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:27.362  4158  4158 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:27.363  4158  4158 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:27.363  4158  4158 V BluetoothAdapterState: isBleTurningOff()=true
09-09 16:44:27.365  4158  4170 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 16:44:27.365  4158  4170 D BluetoothAdapterProperties: Setting state to 10
,09-09 16:44:27.366  4158  4170 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 16:44:27.367  4158  4170 I BluetoothAdapterState: Entering OffState
,09-09 16:44:27.369   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 16:44:27.392  4158  4158 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:44:27.392  4158  4158 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-09 16:44:27.398  4158  4171 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:44:27.406  4158  4158 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:44:27.407  4158  4171 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:44:27.409  4158  4158 I art     : System.exit called, status: 0
,09-09 16:44:27.409  4158  4158 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:44:27.474   874   885 I ActivityManager: Process com.android.bluetooth (pid 4158) has died
,09-09 16:44:28.282   874  1318 D ConnectivityService: handlePromptUnvalidated 101
,09-09 16:44:29.864  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:29.864  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:32.872  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:32.873  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cb844d added. We now have 6 listener(s)
,09-09 16:44:32.873  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:32.877  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:44:32.878  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d84fb02 added. We now have 7 listener(s)
09-09 16:44:32.878  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:32.880  3854  3901 I System.out: IsBluetoothEnabled
,09-09 16:44:32.893  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:32.945   874   891 I ActivityManager: Start proc 4217:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 16:44:33.090  4217  4217 D AdapterServiceConfig: Adding HeadsetService
09-09 16:44:33.090  4217  4217 D AdapterServiceConfig: Adding A2dpService
,09-09 16:44:33.090  4217  4217 D AdapterServiceConfig: Adding HidService
09-09 16:44:33.090  4217  4217 D AdapterServiceConfig: Adding HealthService
09-09 16:44:33.091  4217  4217 D AdapterServiceConfig: Adding PanService
09-09 16:44:33.091  4217  4217 D AdapterServiceConfig: Adding GattService
09-09 16:44:33.091  4217  4217 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:44:33.110   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@de5c050:true
,09-09 16:44:33.111  4217  4217 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 16:44:33.119  4217  4217 I bt_bluedroid: init
,09-09 16:44:33.119  4217  4229 I BluetoothAdapterState: Entering OffState
,09-09 16:44:33.124  4217  4230 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:44:33.124  4217  4230 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 16:44:33.124  4217  4230 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 16:44:33.125  4217  4230 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 16:44:33.126  4217  4217 I bt_bluedroid: get_profile_interface socket
,09-09 16:44:33.131  4217  4217 I bt_bluedroid: get_profile_interface sdp
,09-09 16:44:33.133  4217  4233 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:44:33.136  4217  4233 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:44:33.139  4217  4228 I bt_bluedroid: config_hci_snoop_log
,09-09 16:44:33.144   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 16:44:33.157  4217  4229 D BluetoothAdapterState: Current state: OFF, message: 0
09-09 16:44:33.158  4217  4229 D BluetoothAdapterProperties: Setting state to 14
,09-09 16:44:33.158  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 16:44:33.163  4217  4229 D BluetoothBondStateMachine: make
,09-09 16:44:33.169  4217  4234 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:44:33.178  4217  4229 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:44:33.180  4217  4217 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:44:33.189  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:33.191  4217  4217 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:44:33.193  4217  4217 D BtGatt.GattService: Received start request. Starting profile...
09-09 16:44:33.194  4217  4217 D BtGatt.GattService: start()
09-09 16:44:33.194  4217  4217 I bt_bluedroid: get_profile_interface gatt
,09-09 16:44:33.197  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:33.198  4217  4217 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:44:33.226  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:33.226  4217  4217 V BluetoothAdapterState: isTurningOn()=false
09-09 16:44:33.226  4217  4217 V BluetoothAdapterState: isBleTurningOn()=true
09-09 16:44:33.227  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:33.229  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 16:44:33.230  4217  4229 I bt_bluedroid: enable
09-09 16:44:33.230  4217  4230 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 16:44:33.231  4217  4230 I bt_hci  : start_up
,09-09 16:44:33.247  4217  4230 I bt_vendor: alloc value 0xb39a0189
,09-09 16:44:33.247  4217  4230 I bt_vendor: init
09-09 16:44:33.247  4217  4230 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 16:44:33.248  4217  4230 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:44:33.358  4217  4230 D bt_hci  : start_up starting async portion
,09-09 16:44:33.358  4217  4237 I bt_hci  : event_finish_startup
09-09 16:44:33.359  4217  4237 I bt_hci_h4: hal_open
09-09 16:44:33.359  4217  4237 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 16:44:33.369  4217  4237 I bt_userial_vendor: device fd = 51 open
,09-09 16:44:33.400  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:44:33.432  4217  4237 D bt_hwcfg: Chipset BCM4354A2
09-09 16:44:33.432  4217  4237 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 16:44:33.433  4217  4237 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:44:34.282  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 16:44:34.283  4217  4237 D bt_hwcfg: Settlement delay -- 100 ms
09-09 16:44:34.284  4217  4237 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:44:34.402  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:44:34.403  4217  4237 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:44:34.431  4217  4237 I bt_hwcfg: vendor lib fwcfg completed
,09-09 16:44:34.432  4217  4237 I bt_vendor: firmware callback
09-09 16:44:34.432  4217  4237 I bt_hci  : firmware_config_callback
,09-09 16:44:34.444  4217  4239 I bt_btu  : btu_task pending for preload complete event
,09-09 16:44:34.444  4217  4239 I bt_btu_task: Bluetooth chip preload is complete
09-09 16:44:34.444  4217  4239 I bt_btu  : btu_task received preload complete event
,09-09 16:44:34.452  4217  4239 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 16:44:34.452  4217  4239 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 16:44:34.452  4217  4239 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 16:44:34.452  4217  4239 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 16:44:34.452  4217  4239 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:44:34.453  4217  4239 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:44:34.602  4217  4239 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391dd9d
,09-09 16:44:34.602  4217  4239 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391dd9d 
,09-09 16:44:34.631  4217  4233 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-09 16:44:34.633  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:44:34.634  4217  4233 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:44:34.639  4217  4233 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:44:34.642  4217  4233 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:44:34.642  4217  4233 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:44:34.642  4217  4233 D bt_hci  : do_postload posting postload work item
09-09 16:44:34.643  4217  4237 I bt_hci  : event_postload
09-09 16:44:34.643  4217  4237 I bt_vendor: sco_config_cb
09-09 16:44:34.643  4217  4237 I bt_hci  : sco_config_callback postload finished.
,09-09 16:44:34.647  4217  4233 D bt_bte_conf: Device ID record 1 : primary
,09-09 16:44:34.647  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:34.648  4217  4233 D bt_bte_conf:   vendorId            = 000f
09-09 16:44:34.648  4217  4233 D bt_bte_conf:   vendorIdSource      = 0001
09-09 16:44:34.648  4217  4233 D bt_bte_conf:   product             = 1200
09-09 16:44:34.648  4217  4233 D bt_bte_conf:   version             = 1436
09-09 16:44:34.648  4217  4233 D bt_bte_conf:   clientExecutableURL = 
,09-09 16:44:34.649  4217  4233 D bt_bte_conf:   serviceDescription  = 
09-09 16:44:34.649  4217  4233 D bt_bte_conf:   documentationURL    = 
09-09 16:44:34.649  4217  4233 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 16:44:34.650  4217  4230 D bt_stack_manager: event_start_up_stack finished
09-09 16:44:34.650  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 16:44:34.651  4217  4229 D BluetoothAdapterProperties: Setting state to 15
09-09 16:44:34.651  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 16:44:34.653  4217  4237 I bt_vendor: low_power_mode_cb
09-09 16:44:34.653  4217  4229 I BluetoothAdapterState: Entering BleOnState
,09-09 16:44:34.658  4217  4229 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 16:44:34.658  4217  4229 D BluetoothAdapterProperties: Setting state to 11
09-09 16:44:34.658  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 16:44:34.664  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:34.669  4217  4217 D HeadsetService: Received start request. Starting profile...
09-09 16:44:34.670  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:34.675  4217  4217 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 16:44:34.675  4217  4217 D HeadsetStateMachine: make
,09-09 16:44:34.678  4217  4229 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:44:34.685  4217  4217 D HeadsetStateMachine: max_hf_connections = 1
,09-09 16:44:34.685  4217  4217 I bt_bluedroid: get_profile_interface handsfree
09-09 16:44:34.685  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 16:44:34.685  4217  4233 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 16:44:34.690  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:34.690  4217  4217 D A2dpService: Received start request. Starting profile...
09-09 16:44:34.691  4217  4217 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 16:44:34.692  4217  4217 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:44:34.701  4217  4217 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 16:44:34.701  4217  4217 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 16:44:34.701  4217  4217 D A2dpStateMachine: make
,09-09 16:44:34.703  4217  4217 I bt_bluedroid: get_profile_interface a2dp
,09-09 16:44:34.704  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 16:44:34.706  4217  4217 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 16:44:34.707  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:34.707  4217  4247 D A2dpStateMachine: Enter Disconnected: -2
09-09 16:44:34.708  4217  4217 D HidService: Received start request. Starting profile...
09-09 16:44:34.708  4217  4217 I bt_bluedroid: get_profile_interface hidhost
09-09 16:44:34.708  4217  4233 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ff3e5
09-09 16:44:34.708  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 16:44:34.708  4217  4217 D HidService: setHidService(): set to: null
,09-09 16:44:34.711  4217  4217 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 16:44:34.712  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:34.714  4217  4217 D HealthService: Received start request. Starting profile...
,09-09 16:44:34.716  4217  4217 I bt_bluedroid: get_profile_interface health
,09-09 16:44:34.717  4217  4217 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:44:34.719  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
,09-09 16:44:34.720  4217  4217 D PanService: Received start request. Starting profile...
,09-09 16:44:34.720  4217  4217 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 16:44:34.720  4217  4217 I bt_bluedroid: get_profile_interface pan
09-09 16:44:34.722  4217  4233 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 16:44:34.723  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 16:44:34.726  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:34.726  4217  4217 D BluetoothMapService: Received start request. Starting profile...
,09-09 16:44:34.727  4217  4217 D BluetoothMapService: start()
,09-09 16:44:34.731  4217  4217 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 16:44:34.732  4217  4217 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 16:44:34.732  4217  4217 D BluetoothMapAppObserver: createReceiver()
,09-09 16:44:34.733  4217  4217 D BluetoothMapAppObserver: initObservers()
,09-09 16:44:34.733  4217  4217 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:44:34.745  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:34.745  4217  4217 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:34.745  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:34.745  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:34.745  4217  4245 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:44:34.747  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:34.747  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:44:34.747  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:34.747  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isTurningOff()=false
09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:34.748  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:44:34.749  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:34.749  4217  4217 V BluetoothAdapterState: isTurningOn()=true
09-09 16:44:34.749  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:44:34.749  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:34.750  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:44:34.750  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:44:34.750  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:44:34.750  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:44:34.750  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 16:44:34.751  4217  4229 D BluetoothAdapterProperties: ScanMode =  20
09-09 16:44:34.751  4217  4229 D BluetoothAdapterProperties: State =  11
,09-09 16:44:34.755  4217  4233 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:44:34.755  4217  4229 D BluetoothAdapterProperties: Setting state to 12
09-09 16:44:34.756  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 16:44:34.756  4217  4233 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:44:34.756  4217  4229 I BluetoothAdapterState: Entering OnState
,09-09 16:44:34.756  1370  1387 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 16:44:34.760   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:34.760  1962  2080 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:34.761  3910  3920 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:34.762  3910  3921 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 16:44:34.763  4217  4217 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:44:34.764  4217  4217 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:34.765  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:34.766   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:44:34.766  3910  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:44:34.767  4217  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:34.768   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:34.768  1370  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:44:34.770  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:34.770  4217  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:34.770  1370  2058 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:44:34.772  4217  4217 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:44:34.772  4217  4217 D ObexServerSockets0: startAccept()
09-09 16:44:34.772  4217  4217 D ObexServerSockets0: prepareForNewConnect()
09-09 16:44:34.774  3910  3921 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 16:44:34.776   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:44:34.777  3910  3920 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:44:34.777  4217  4217 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 16:44:34.778  4217  4217 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 16:44:34.778  4217  4253 D ObexServerSockets0: Accepting socket connection...
09-09 16:44:34.779  1370  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:44:34.780  4217  4254 D ObexServerSockets0: Accepting socket connection...
,09-09 16:44:34.780  3910  3910 D BluetoothA2dp: Proxy object connected
,09-09 16:44:34.780   874   874 D BluetoothA2dp: Proxy object connected
09-09 16:44:34.781  3910  3920 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:44:34.783  1370  2058 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:44:34.784  1370  1370 D BluetoothMap: Proxy object connected
09-09 16:44:34.784  1370  1370 D MapProfile: Bluetooth service connected
,09-09 16:44:34.784  1370  1370 D BluetoothMap: getConnectedDevices()
09-09 16:44:34.785  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:44:34.786  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:44:34.786  1370  1370 D PanProfile: Bluetooth service connected
,09-09 16:44:34.786  1370  1370 D BluetoothInputDevice: Proxy object connected
09-09 16:44:34.786  1370  1370 D HidProfile: Bluetooth service connected
,09-09 16:44:34.789   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 16:44:34.790  1370  1370 D BluetoothA2dp: Proxy object connected
09-09 16:44:34.791  4217  4217 D BluetoothMapService: onReceive
09-09 16:44:34.791  4217  4217 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:44:34.791  4217  4217 D BluetoothMapService: STATE_ON
,09-09 16:44:34.794  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:34.795  3910  3910 D BluetoothInputDevice: Proxy object connected
09-09 16:44:34.795  3910  3910 D HidProfile: Bluetooth service connected
,09-09 16:44:34.797  3910  3910 D BluetoothMap: Proxy object connected
09-09 16:44:34.797  3910  3910 D MapProfile: Bluetooth service connected
,09-09 16:44:34.797  3910  3910 D BluetoothMap: getConnectedDevices()
,09-09 16:44:34.799  3910  3910 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:44:34.799  3910  3910 D PanProfile: Bluetooth service connected
,09-09 16:44:34.807  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:44:34.812  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:44:34.812  4217  4217 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:44:34.812  4217  4217 D ObexServerSockets0: prepareForNewConnect()
,09-09 16:44:34.829  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:44:34.832  3910  3910 D BluetoothPbap: Proxy object connected
,09-09 16:44:34.832  3910  3910 D PbapServerProfile: Bluetooth service connected
09-09 16:44:34.831  1370  1370 D BluetoothPbap: Proxy object connected
09-09 16:44:34.832  1370  1370 D PbapServerProfile: Bluetooth service connected
,09-09 16:44:34.835  4217  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:34.869   874   874 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.870  1962  1980 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.870  3910  3921 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.871  3910  3910 D HeadsetProfile: Bluetooth service connected
09-09 16:44:34.871  1370  1384 D BluetoothHeadset: Proxy object connected
09-09 16:44:34.871  1370  1370 D HeadsetProfile: Bluetooth service connected
09-09 16:44:34.872   874   874 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.872   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:44:34.876   874   891 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.878  4217  4265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:44:34.880  1370  2058 D BluetoothHeadset: Proxy object connected
,09-09 16:44:34.880  4217  4265 I BtOppRfcommListener: Accept thread started.
09-09 16:44:34.881  1370  1370 D HeadsetProfile: Bluetooth service connected
,09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:34.908  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:34.911  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:34.912  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:44:34.912  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba5ac13 added. We now have 8 listener(s)
09-09 16:44:34.912  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:34.915   874  1742 D WifiService: setWifiEnabled: false pid=3854, uid=10000
09-09 16:44:34.915   874  1742 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:34.924  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:34.924   874  2007 D WifiService: setWifiEnabled: true pid=3854, uid=10000
09-09 16:44:34.924   874  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:44:34.932   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:34.934  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:34.937  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:34.948   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-09 16:44:34.950   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 16:44:34.951   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 16:44:34.952   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 16:44:34.952   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 16:44:34.952   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 16:44:34.952   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:44:34.967   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 16:44:34.968   373   872 D CommandListener: Setting iface cfg
,09-09 16:44:34.971   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 16:44:34.972   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 16:44:34.972   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:44:34.976   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:44:34.976   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:44:35.033   874  1316 E native  : do suspend true
,09-09 16:44:35.085   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:35.942  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:35.949  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:35.962  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 16:44:35.965  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 16:44:35.972  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@708712a Bundle[{}]
,09-09 16:44:35.975  3854  3901 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 16:44:35.976  3854  3901 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 16:44:35.980  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 16:44:35.981  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 16:44:35.984  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 16:44:35.986  3854  3901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 16:44:35.998  3854  3901 I System.out: Running OutgoingSocketThread
,09-09 16:44:36.002  3854  4273 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 425)
,09-09 16:44:36.004  3854  4273 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38159
,09-09 16:44:36.005  3854  4273 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 16:44:36.363   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:44:36.509   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=10.62 delta 1000 -> 994
,09-09 16:44:36.511   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 16:44:36.511   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:44:36.526   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:44:36.589   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:44:36.590  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:44:37.003  3854  3901 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 426)
,09-09 16:44:37.003  3854  3901 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 426)
,09-09 16:44:37.013  3854  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
09-09 16:44:37.015  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 16:44:37.016  3854  3901 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 16:44:37.016  3854  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 432)
09-09 16:44:37.021  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.021  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9aa3e50 added. We now have 2 listener(s)
,09-09 16:44:37.027  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:37.027  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.027  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:37.027  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.027  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e591849 added. We now have 9 listener(s)
,09-09 16:44:37.027  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:37.029  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:44:37.033  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:37.037  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:37.040  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:37.040  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:44:37.040  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.040  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f34f66f added. We now have 3 listener(s)
09-09 16:44:37.042  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:37.042  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.042  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:44:37.043  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.043  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57cef7c added. We now have 10 listener(s)
09-09 16:44:37.043  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.043  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:37.043  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:37.043  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:37.043  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.043  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.043  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:37.043  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.044  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.044  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9aa3e50 removed from the list
09-09 16:44:37.044  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.044  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e591849 removed from the list
,09-09 16:44:37.046  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:37.047  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:37.047  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.047  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.047  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.048  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:37.049  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.049  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:37.049  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e591849 not in the list
09-09 16:44:37.049  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.049  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.050  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:37.050  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.050  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:37.051  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57cef7c removed from the list
,09-09 16:44:37.051  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:37.051  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.051  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 16:44:37.051  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:44:37.051  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f34f66f removed from the list
,09-09 16:44:37.052  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.052  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d11f005 added. We now have 2 listener(s)
09-09 16:44:37.054  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:37.054  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.054  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:44:37.054  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:44:37.054  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2e85a added. We now have 9 listener(s)
,09-09 16:44:37.054  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:37.055  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:44:37.059  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:37.065  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:37.069  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:37.070  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:44:37.070  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:44:37.070  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3678768 added. We now have 3 listener(s)
,09-09 16:44:37.072  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.074  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.076  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:37.076  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.077  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:44:37.077  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:44:37.077  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c68781 added. We now have 10 listener(s)
09-09 16:44:37.078  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:37.078  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.079  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 16:44:37.079  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:44:37.079  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.079  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.082  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:44:37.082  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-09 16:44:37.086   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 16:44:37.088  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:37.088  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:44:37.093  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:37.093  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.094  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:44:37.097  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:44:37.097  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:37.097  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:44:37.098   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:44:37.098  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:37.098   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:44:37.099   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 16:44:37.101  4217  4227 D BtGatt.GattService: registerClient() - UUID=3b9363c1-81d5-40ca-97ce-0da49e778b93
09-09 16:44:37.102  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=3b9363c1-81d5-40ca-97ce-0da49e778b93, clientIf=5
09-09 16:44:37.103  3854  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:44:37.104  4217  4256 D BtGatt.GattService: start scan with filters
,09-09 16:44:37.108  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:44:37.109  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 16:44:37.109  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:44:37.109  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:44:37.109  4217  4236 D BtGatt.ScanManager: handling starting scan
,09-09 16:44:37.111  4217  4236 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b611e
09-09 16:44:37.112  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-09 16:44:37.112  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:44:37.112  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-09 16:44:37.114  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:44:37.114   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:44:37.118  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,09-09 16:44:37.118  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.119  3854  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:44:37.119  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:37.119  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 16:44:37.119  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.119  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:37.120  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:44:37.120  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:37.120  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:37.120  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:37.120  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:37.120  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:44:37.120  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:44:37.123  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:37.124  4217  4227 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:44:37.125  4217  4256 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:44:37.125  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:37.125  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:44:37.125  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:37.125  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:44:37.125  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:44:37.126  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.127  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:37.127  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 16:44:37.127  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.128  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.129  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:37.129  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.129  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:37.132  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:37.132  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:37.132  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 16:44:37.132  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.133  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:44:37.133  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:37.133  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:44:37.133  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:37.134   373   872 D CommandListener: Setting iface cfg
09-09 16:44:37.135   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
09-09 16:44:37.136  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:44:37.136  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:37.136  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.136  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.136  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:44:37.136  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.137  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d11f005 removed from the list
09-09 16:44:37.137  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.137  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.137  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:44:37.137  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.137  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.140  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:37.140  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.140  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.142  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2e85a removed from the list
,09-09 16:44:37.142  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:37.142  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:44:37.142  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.142  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:37.142  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-09 16:44:37.142  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.143  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:44:37.143  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.143   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:44:37.143  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.144  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:37.144  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.144  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 16:44:37.144  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2e85a not in the list
,09-09 16:44:37.145  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.145  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.145  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.146  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.147  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:37.147  3854  3901 D BluetoothLeScanner: could not find callback wrapper
,09-09 16:44:37.147  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:37.147  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.147  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:37.147  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.148  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c68781 removed from the list
09-09 16:44:37.148  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:37.148  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.148  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.148  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:44:37.148  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3678768 removed from the list
09-09 16:44:37.149  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.149  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba5b9 added. We now have 2 listener(s)
,09-09 16:44:37.151  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:44:37.151  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.151  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:37.151  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.151  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5a1dfe added. We now have 9 listener(s)
,09-09 16:44:37.151  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.152  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:44:37.152  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 16:44:37.152  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.153   874  4276 D DhcpClient: Receive thread started
09-09 16:44:37.154  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:37.157  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:44:37.158  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:44:37.158  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.160  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:37.161  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-09 16:44:37.161  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.161  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3992fac added. We now have 3 listener(s)
09-09 16:44:37.163  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.163  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:44:37.163  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.163  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:37.163  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.163  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc7e475 added. We now have 10 listener(s)
09-09 16:44:37.163  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.163  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.164  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:37.164  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.164  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:44:37.164  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:44:37.164  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.164  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-09 16:44:37.166  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:44:37.166  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.166  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:44:37.167  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:37.167  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-09 16:44:37.170  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:44:37.171  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.171  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-09 16:44:37.171  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:44:37.171  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.171  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
09-09 16:44:37.174  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:44:37.174  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:37.174  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:44:37.175  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:37.176  4217  4252 D BtGatt.GattService: registerClient() - UUID=17d0bc47-ecf0-4fb0-97a9-e80d23bda967
,09-09 16:44:37.177  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=17d0bc47-ecf0-4fb0-97a9-e80d23bda967, clientIf=5
09-09 16:44:37.177  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:44:37.177  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.177  3854  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:44:37.177  4217  4257 D BtGatt.GattService: start scan with filters
,09-09 16:44:37.179  4217  4236 D BtGatt.ScanManager: handling starting scan
09-09 16:44:37.179  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:44:37.179  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:44:37.180  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:44:37.180  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 16:44:37.182  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:37.183  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:44:37.183  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:44:37.184  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:44:37.185  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:44:37.185  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.186  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:44:37.187  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.187  3854  3901 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 16:44:37.187  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:37.187  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:37.187  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:37.187  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:37.187  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.187  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:44:37.187  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.188  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba5b9 removed from the list
09-09 16:44:37.188  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.188  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5a1dfe removed from the list
09-09 16:44:37.188  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:37.188  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.188  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.188  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 16:44:37.188  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.188  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:44:37.189  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.189  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.189  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:37.189  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5a1dfe not in the list
09-09 16:44:37.189  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:37.189  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:37.190  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:44:37.190  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:37.190  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:44:37.190  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 16:44:37.190  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:37.190  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.191  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 16:44:37.191  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:44:37.191  4217  4257 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:44:37.191  4217  4228 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:44:37.192  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:37.192  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:44:37.192  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:37.192  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:44:37.192  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
09-09 16:44:37.193  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.193  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:44:37.193  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:44:37.193  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.193  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.194  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:44:37.194  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.194  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.196  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:37.196  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:37.200  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:44:37.200  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.200  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:44:37.200  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:44:37.201  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.201  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:44:37.201  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.203  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:44:37.203  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.204  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.206  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:37.206  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.206  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.207  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:44:37.207  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.208  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.209  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:37.209  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:37.209  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:37.209  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:44:37.209  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.210  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:37.210  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.210  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc7e475 removed from the list
09-09 16:44:37.210  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.210  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.210  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.210  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.210  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3992fac removed from the list
09-09 16:44:37.211  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.211  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e52d2d added. We now have 2 listener(s)
09-09 16:44:37.213  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:44:37.213  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.213  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:44:37.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:44:37.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.213  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:44:37.214  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.214  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8262262 added. We now have 9 listener(s)
09-09 16:44:37.214  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.214  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:44:37.217  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.219  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:44:37.219  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.219  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:37.219  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:37.221  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:44:37.221  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:44:37.221  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.222  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23324b0 added. We now have 3 listener(s)
09-09 16:44:37.223  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.224  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:44:37.224  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.224  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.225  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:44:37.225  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.225  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:37.225  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.225  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5146f29 added. We now have 10 listener(s)
09-09 16:44:37.225  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:44:37.225  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.226  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:44:37.226  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:44:37.226  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.226  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.228  3854  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:37.228  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:44:37.231  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:44:37.232  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.232  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:44:37.234  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:44:37.235  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:44:37.235   874  1316 E native  : do suspend false
09-09 16:44:37.235  3854  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:44:37.235  3854  3901 D BluetoothAdapter: STATE_ON
,09-09 16:44:37.237  4217  4257 D BtGatt.GattService: registerClient() - UUID=81a05bb4-2e79-402e-98e8-93a3217cc7a2
,09-09 16:44:37.237  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=81a05bb4-2e79-402e-98e8-93a3217cc7a2, clientIf=5
09-09 16:44:37.238  3854  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:44:37.238  4217  4256 D BtGatt.GattService: start scan with filters
,09-09 16:44:37.240  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:44:37.240  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:44:37.240  4217  4236 D BtGatt.ScanManager: handling starting scan
09-09 16:44:37.240  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:44:37.240  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 16:44:37.242  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:44:37.243  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:44:37.243  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:44:37.244   874  1901 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:44:37.244  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:44:37.245  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:44:37.246  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.246  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:44:37.249  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:44:37.249  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:37.250  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:44:37.250  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:44:37.250  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.250  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:44:37.250  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:44:37.250  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e52d2d removed from the list
09-09 16:44:37.250  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.250  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8262262 removed from the list
09-09 16:44:37.250  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:44:37.251  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.251  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:44:37.251  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.251  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:44:37.251  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.251  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:44:37.251  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 16:44:37.251  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.251  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:44:37.252  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:37.252  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.252  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.252  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8262262 not in the list
,09-09 16:44:37.252  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:44:37.252  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:44:37.252  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:44:37.253  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:44:37.253  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:44:37.253  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:37.254  4217  4228 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:44:37.254  4217  4257 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:44:37.254  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:37.255  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:44:37.255  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:44:37.255  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:44:37.255  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:44:37.256  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.256  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:37.256  3854  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:44:37.256  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.256  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.258   874  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
09-09 16:44:37.258  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:37.258  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.258  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:44:37.258   874  1901 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
09-09 16:44:37.258   874  1901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
09-09 16:44:37.260  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:44:37.260  3854  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:44:37.260  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:44:37.260  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.264  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:44:37.265  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:44:37.265  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:44:37.265  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.265  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:44:37.265  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:44:37.265  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:44:37.267  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:44:37.267  3854  3901 D BluetoothAdapter: STATE_ON
09-09 16:44:37.268  3854  3901 D BluetoothLeScanner: could not find callback wrapper
09-09 16:44:37.268  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:44:37.268  3854  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:44:37.268  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:44:37.268  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:44:37.270   874  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-09 16:44:37.270  3854  3854 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:44:37.270  3854  3854 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:44:37.270   874  1901 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-09 16:44:37.271  3854  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.271   373   872 D CommandListener: Setting iface cfg
09-09 16:44:37.274   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:44:37.275  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:44:37.275  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.276  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:44:37.276  3854  3854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:44:37.276  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.276  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:44:37.276  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.276  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5146f29 removed from the list
,09-09 16:44:37.277  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.277   874  1316 E native  : do suspend true
09-09 16:44:37.277  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.277  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.277  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.278  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23324b0 removed from the list
09-09 16:44:37.277   874  1901 D DhcpClient: Scheduling renewal in 86399s
,09-09 16:44:37.278  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.279  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef9da61 added. We now have 2 listener(s)
,09-09 16:44:37.281  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:44:37.281  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:44:37.281  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.281  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.281  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:44:37.281  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:44:37.281  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.282  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f1b986 added. We now have 9 listener(s)
09-09 16:44:37.282  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.282  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:44:37.284  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:44:37.288  3854  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:44:37.288   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-09 16:44:37.288  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:44:37.288  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:44:37.289   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 16:44:37.289   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 16:44:37.290  3854  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:44:37.290  3854  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:44:37.290   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 16:44:37.290   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
09-09 16:44:37.291  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:44:37.292  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:44:37.291  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:44:37.293  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b67ca74 added. We now have 3 listener(s)
,09-09 16:44:37.295  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:44:37.295  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:44:37.295  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:44:37.295  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:44:37.295  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@498bb9d added. We now have 10 listener(s),
09-09 16:44:37.295  3854  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:44:37.296  3854  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:44:37.296  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:44:37.296  3854  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-09 16:44:37.296  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.296  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.296  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:44:37.296  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:44:37.296  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef9da61 removed from the list
09-09 16:44:37.296  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:44:37.296  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f1b986 removed from the list
09-09 16:44:37.296  3854  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:44:37.297  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.297  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.297  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.298  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:44:37.298  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.298  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.298  3854  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f1b986 not in the list
09-09 16:44:37.298  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:44:37.298  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.299  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:44:37.299  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:44:37.299  3854  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:44:37.299  3854  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@498bb9d removed from the list
,09-09 16:44:37.299  3854  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:44:37.299  3854  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:44:37.299  3854  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:44:37.299  3854  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:44:37.299  3854  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b67ca74 removed from the list
09-09 16:44:37.300  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 16:44:37.300  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 16:44:37.300  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 16:44:37.300  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:44:37.300  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 16:44:37.301  3854  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:44:37.305  3854  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,09-09 16:44:37.306  3854  4278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
09-09 16:44:37.306  3854  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 16:44:37.307  3854  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
09-09 16:44:37.308  3854  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
09-09 16:44:37.308  3854  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 16:44:37.309  3854  3901 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-09 16:44:37.309  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 16:44:37.309  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 16:44:37.310  3854  3901 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 16:44:37.310  3854  3901 D com.test.thalitest.ThaliTestRunner: Total duration: 22816 ms
,09-09 16:44:37.311  3854  3901 I jxcore-log: Total number of executed tests:  80
09-09 16:44:37.311  3854  3901 I jxcore-log: 
,09-09 16:44:37.311  3854  3901 I jxcore-log: Number of passed tests:  80
09-09 16:44:37.311  3854  3901 I jxcore-log: 
09-09 16:44:37.312  3854  3901 I jxcore-log: Number of failed tests:  0
09-09 16:44:37.312  3854  3901 I jxcore-log: 
09-09 16:44:37.312  3854  3901 I jxcore-log: Number of ignored tests:  0
09-09 16:44:37.312  3854  3901 I jxcore-log: 
09-09 16:44:37.312  3854  3901 I jxcore-log: Total duration:  22816
09-09 16:44:37.312  3854  3901 I jxcore-log: 
,09-09 16:44:37.314  3854  3901 I jxcore-log: Unit Test app is loaded
09-09 16:44:37.314  3854  3901 I jxcore-log: 
,09-09 16:44:37.321  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.321  3854  3901 I jxcore-log: 
,09-09 16:44:37.325   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 16:44:37.325   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 16:44:37.325  3854  3854 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
09-09 16:44:37.326  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.326  3854  3901 I jxcore-log: 
,09-09 16:44:37.327   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 16:44:37.327  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.327  3854  3901 I jxcore-log: 
,09-09 16:44:37.328  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.328  3854  3901 I jxcore-log: 
,09-09 16:44:37.328   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 16:44:37.329  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.329  3854  3901 I jxcore-log: 
09-09 16:44:37.329   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 16:44:37.330  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.330  3854  3901 I jxcore-log: 
,09-09 16:44:37.332  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 16:44:37.332  3854  3901 I jxcore-log: 
09-09 16:44:37.334  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.334  3854  3901 I jxcore-log: 
,09-09 16:44:37.335  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.335  3854  3901 I jxcore-log: 
09-09 16:44:37.336  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.336  3854  3901 I jxcore-log: 
09-09 16:44:37.336   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 16:44:37.337  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.337  3854  3901 I jxcore-log: 
09-09 16:44:37.338  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:44:37.338  3854  3901 I jxcore-log: 
,09-09 16:44:37.339  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.339  3854  3901 I jxcore-log: 
,09-09 16:44:37.340  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.340  3854  3901 I jxcore-log: 
,09-09 16:44:37.341  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.341  3854  3901 I jxcore-log: 
,09-09 16:44:37.341   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 16:44:37.341   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 16:44:37.341  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:44:37.341  3854  3901 I jxcore-log: 
09-09 16:44:37.341   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 16:44:37.342   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 16:44:37.341   874  1318 D ConnectivityService:    accepting network in place of null
09-09 16:44:37.342   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:44:37.343   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:44:37.343  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.343  3854  3901 I jxcore-log: 
,09-09 16:44:37.344  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.344  3854  3901 I jxcore-log: 
,09-09 16:44:37.344  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.344  3854  3901 I jxcore-log: 
,09-09 16:44:37.345  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.345  3854  3901 I jxcore-log: 
,09-09 16:44:37.346  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.346  3854  3901 I jxcore-log: 
,09-09 16:44:37.346  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.346  3854  3901 I jxcore-log: 
09-09 16:44:37.347  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.347  3854  3901 I jxcore-log: 
09-09 16:44:37.348  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.348  3854  3901 I jxcore-log: 
09-09 16:44:37.348  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.348  3854  3901 I jxcore-log: 
09-09 16:44:37.349  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:44:37.349  3854  3901 I jxcore-log: 
,09-09 16:44:37.350  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.350  3854  3901 I jxcore-log: 
,09-09 16:44:37.350  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.350  3854  3901 I jxcore-log: 
,09-09 16:44:37.351  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.351  3854  3901 I jxcore-log: 
,09-09 16:44:37.352  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.352  3854  3901 I jxcore-log: 
,09-09 16:44:37.353  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.353  3854  3901 I jxcore-log: 
,09-09 16:44:37.353  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.353  3854  3901 I jxcore-log: 
,09-09 16:44:37.354  3854  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:44:37.354  3854  3901 I jxcore-log: 
,09-09 16:44:37.356  3854  3901 I jxcore-log: My device name is: motorola-Nexus 6
09-09 16:44:37.356  3854  3901 I jxcore-log: 
,09-09 16:44:37.357   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244995, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:44:37.368   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:37.395   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:44:37.399   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 16:44:37.399   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 16:44:37.400   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 16:44:37.403   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:44:37.407  3854  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:44:37.411  3854  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:44:37.418  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:44:37.424   874  4274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 16:44:37.425  1727  1727 D SystemUpdateService: onCreate
09-09 16:44:37.427  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:44:37.447  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:44:37.450  1727  2463 I iu.UploadsManager: num queued entries: 0
,09-09 16:44:37.450  1727  2463 I iu.UploadsManager: num updated entries: 0
09-09 16:44:37.450  1727  2463 I iu.SyncManager: NEXT; no task
,09-09 16:44:37.457  1727  4287 I SystemUpdateService: active receiver: enabled
,09-09 16:44:37.460  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:44:37.462  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:44:37.464  3990  3990 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:44:37.471  1727  4289 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 16:44:37.471  1727  4289 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 16:44:37.473  3990  3990 D SprintDMHelper: simOperator: 
09-09 16:44:37.473  3990  3990 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 16:44:37.479  1727  4289 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:44:37.488   874  4274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:44:37 GMT], X-Android-Received-Millis=[1473432277487], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473432277461]}
,09-09 16:44:37.492   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 16:44:37.492   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-09 16:44:37.492   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 16:44:37.493   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 16:44:37.494  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:44:37.508  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:44:37.518  1727  4287 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:44:37.525  1727  4287 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 16:44:37.525  1727  4287 I SystemUpdateService: now status is 0 (complete)
09-09 16:44:37.525  1727  4287 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:44:37.525  1727  4287 I SystemUpdateService: file has been verified
,09-09 16:44:37.525  1727  4287 I SystemUpdateService: OTA package size = 12249756
,09-09 16:44:37.559  1727  4287 I SystemUpdateService: showing system update notification
,09-09 16:44:37.580  1518  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 16:44:37.580  1518  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 16:44:37.580  1518  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:44:37.580  1518  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:44:37.600  1727  4289 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-09 16:44:37.611  1727  1727 D SystemUpdateService: onDestroy
,09-09 16:44:37.615  3961  4292 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:44:37.645  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:44:37.708  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:44:37.777  3854  3854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:44:39.912  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 16:44:39.912  3854  3901 I jxcore-log: 
,09-09 16:44:40.367  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 16:44:40.367  3854  3901 I jxcore-log: 
,09-09 16:44:40.391  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 16:44:40.391  3854  3901 I jxcore-log: 
,09-09 16:44:41.770  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 16:44:41.770  3854  3901 I jxcore-log: 
,09-09 16:44:42.001  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 16:44:42.001  3854  3901 I jxcore-log: 
,09-09 16:44:42.006  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 16:44:42.006  3854  3901 I jxcore-log: 
,09-09 16:44:42.025  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 16:44:42.025  3854  3901 I jxcore-log: 
,09-09 16:44:42.030  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 16:44:42.030  3854  3901 I jxcore-log: 
,09-09 16:44:42.902  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 16:44:42.902  3854  3901 I jxcore-log: 
,09-09 16:44:42.915  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js
09-09 16:44:42.915  3854  3901 I jxcore-log: 
,09-09 16:44:43.096  3854  3901 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 16:44:43.096  3854  3901 I jxcore-log: 
,09-09 16:44:43.317  3854  3901 W jxcore-log: !!! js_ReportOverRecursed called !!!
,09-09 16:44:43.387  4301  3901 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,09-09 16:44:43.388  4301  3901 W google-breakpad: O A arm 04 armv7l 3.10.40-geb6cc9d #1 SMP PREEMPT Wed Apr 20 00:05:01 UTC 2016
,09-09 16:44:43.388  4301  3901 W google-breakpad: S 0 96A80300 96A80000 00008000
,09-09 16:44:43.485  4301  3901 W google-breakpad: S 96A80000 2004A8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,09-09 16:44:43.485  4301  3901 W google-breakpad: S 96A80180 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086F313F7C05ECBB61802A89600830DABC802A8962802A8960824D8918402A8963412259700000000000000000000000040B052962802A89601000000100FA896F6FFFFFF0C830DAB0050219900830DAB1802A8960300000008000000403F579688FFFFFF40B0529688FFFFFF9072599585FFFFFF88AB1F9D0024D891005021994803A8960CE3CBB680AB1F9D9415CBB688AB1F9D0024D8915B42C9B6040000006C02A8960100000000830DAB8402A896E4A815979405A896B40EA89600830DAB00000000B402A896ACFC14970024D891D002A89640B052966909000030CA749910709196DC02A89660EBF596000000004803A8962C000000F802A896D002A8960700000058DB65977C06509700830DAB0000000085FFFFFF0080B7983403A89670F0F59600000000F802A89600830DAB00000000740650974803A8967C0650973403A896
,09-09 16:44:43.485  4301  3901 W google-breakpad: S 96A80300 07000000000000000000000090B8E0E6C072599585FFFFFFE01D619600830DABB803A8966403A8963C03A89685FFFFFF5C03A89670D5149700000000E01D6196220000002804A8966403A896B803A8967C065097C07259958403A896887E36979C97C191000000000000000082FFFFFFB803A8962804A896A803A89600830DABEC03A8966C122F97ECC74F9758CB4F9758DB6597220000009C97C1916CEB8B9100000000BC03A896C072599585FFFFFF00830DAB00000000C072599585FFFFFF7004A8964005A896C0C366973804A89600000000010000002804A8961804A8962200000000830DAB7C05A896783B3297F023D891F6FFFFFF0C830DAB0000000000830DAB5004A896020000007004A89680ED189188FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF00830DAB000000000000000000830DAB01000000A005A896B005A89601000000F023D891070000000700000001000000307159950000000000830DAB000000000000000006000000E4C36697E4C36697
,09-09 16:44:43.485  4301  3901 W google-breakpad: S 96A80480 06000000C0C3669700000000FFFFFFFF00000000F823D89122000000387159950700000000000000010000001800609650B2339681FFFFFFDC04A89630521F97070000003071599500830DAB0000000010006096E804A8961C05A89638941F97000000000000000000000000DC5433995005A896010000000000000010DFDA92E01B61963071599500000000FFFFFFFF50B2339681FFFFFFB805A896805533991006A8962C05A8967805A8960000000000000000485533994003000001000000FFFFFFFF81FFFFFF3071599585FFFFFF1000609685FFFFFFB005A8964049569688FFFFFF9092319900000000FFFFFFFFC0B2339681FFFFFFB805A896383F7999000000008C05A8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFF3071599585FFFFFF1406A896C0B2339690923199010500003071599585FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296
,09-09 16:44:43.486  4301  3901 W google-breakpad: S 96A80600 F0D9619685FFFFFF4406A8965C06A896000000003806A8968C4979998201000060865696010000000000000082FFFFFF3071599585FFFFFFE406A896C0AA0F96A4B53099010A00003071599585FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB090C09802000000000000001007A8968C49799902020000A04C569602000000A0C6559688FFFFFF3071599585FFFFFF20341E9188FFFFFF8407A89680898792CCD0C09881060000F0D9619685FFFFFF3071599585FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300006807A8960000000083FFFFFF68000000A05C3792387159950100000030000000A05C3792
,09-09 16:44:43.486  4301  3901 W google-breakpad: S 96A80780 00000000A807A8968C4979998201000080194E95010000000000000082FFFFFF3071599585FFFFFF2C08A8967082879204C9C098810700003071599585FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF4808A8964008A8963808A896AC08A89678000000A05C3792000000001698C19458DB659700830DAB000000005008A8968C49799982010000C0194E95010000000000000082FFFFFF3071599585FFFFFFBC08A89698034E92E4BEC098010600003071599585FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D55396C808A896E008A8960400000060000000A05C3792E0F04B9281FFFFFF4C09A896F8FF789900000000E008A8968C49799982010000E0194E95010000000000000082FFFFFF3071599585FFFFFF4C09A89698FB4B92F0B5C098010600003071599585FFFFFF0000000082FFFFFF
09-09 16:44:43.486  4301  3901 W google-breakpad: S 96A80900 E0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000080DEDA92000000005806A29260000000E0DEDA9204000000B090C0985C09A896C8AB0197040000007009A8968C49799982010000001A4E95010000000000000082FFFFFF80DEDA9288FFFFFFEC09A896909F2E92FCACC0980107000080DEDA9288FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFF3071599585FFFFFF00000000E009A896DC09A89688FFFFFF7000000050DEDA92F061E895D4881497000000000000000004000000100AA8968C49799982010000801A4E9501000000D0ECDB9288FFFFFF90DADA9288FFFFFF6C0AA89660912E9268A6C0980105000090DADA9288FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFFF061E895010000009C0AA896B40AA89650000000701FDE920200000070F40F958C0AA89618AB019700000000A00AA8960C75BA988202000040FAB09403000000
09-09 16:44:43.486  4301  3901 W google-breakpad: S 96A80A80 0000000082FFFFFF90DADA9288FFFFFF0000000081FFFFFFF061E89588FFFFFF3C0BA896D068259200B1809701090000F061E89588FFFFFF0000000081FFFFFF90DADA9288FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF9028969388FFFFFF0000000082FFFFFF0900000081FFFFFFF061E89588FFFFFF4062E895000000006C0BA896C0D652969000000020C05296B090C0980200000070FA0B9281FFFFFF00000000600BA8968C49799982010000B002539601000000F061E89588FFFFFF40FAB09488FFFFFFE40BA8962860259238A0C0988107000040FAB09488FFFFFFF061E89588FFFFFFB002539688FFFFFF4062E89588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFF4062E89588FFFFFF0000000082FFFFFF080CA896383F799900000000CC0BA89678000000701FDE9200000000EC96C098420300000300000000000000100CA8968C4979990202000060FAB09402000000D0A6949488FFFFFF
09-09 16:44:43.487  4301  3901 W google-breakpad: S 96A80C00 80ED189188FFFFFFF061E89588FFFFFF7C0CA89678BFEA91B89BC09801060000F061E89588FFFFFF80ED189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFF480CA896D0B052968035549688FFFFFF60000000701FDE92801860969018BB9885FFFFFF7C0CA89600000000E03654966423BB98000C0000A0FAB09402000000E036549688FFFFFF80ED189188FFFFFF008BE09588FFFFFF7072599585FFFFFFA061E89588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFFC0CA896B0DBDA92008BE09580355496908B36928A00000090DDDA9270725995008BE09588FFFFFFA061E895008BE095803554966072599580186096F08B369209000000C0331E91D0B05296D0B05296008BE09588FFFFFF090000004011619609000000E036549680ED189160DADA92C0331E9188FFFFFF00000000BC9FEC9160A1EC91000400006036549601000000E036549688FFFFFF80ED189188FFFFFF0000000082FFFFFF982D6F9780ED1891
09-09 16:44:43.487  4301  3901 W google-breakpad: S 96A80D80 30DADA9200DADA920000000087FFFFFFA00F5396D0D9DA9200DADA92A0331E919002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFFD0D9DA9288FFFFFFC05ECBB6D0D9DA9270D9DA92A0D9DA929C81339980020000E03654960000000070D9DA9288FFFFFF0000000000000000E0544B938A0000000700000040B05296808B3692E03654962078789903020000403F57960100000040B0529688FFFFFF808B369285FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB6D80FA8960100000081FFFFFF300FA8969C0FA896646B0797403F57960000000000000000000FA896B40EA8963877789958DB659700830DAB00C24C962420A896000000000000000000000000010000000417A89600830DAB00010000000000005080339,900000000403F57969013A89602000000010000000000000000000000
09-09 16:44:43.487  4301  3901 W google-breakpad: S 96A80F00 0100000081FFFFFF00000000000000006813A896F6FFFFFF0C830DAB0100000000830DAB300FA896000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000D80FA89600830DAB203E6F9700525B9600000000E823D8919C0FA89686F313F70000000000830DABD80FA896A00FA896403F579600525B9600000000E823D891C40FA8967C0C2597000000000000000000000000C05ECBB60100000000830DAB9813A896D00FA8964C13A896740D259700000000000000009813A89601000000780B65970100000000525B96D00FA8960000000000000000905EA394CE5EA3940200000002000000010000000000000010B964975C0000000600000000000000101FA89600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.487  4301  3901 W google-breakpad: S 96A81080 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000054A3940000000000000000010000000200000000331E9100535B96A5820FAB000000000000000086F313F700000000C05ECBB60000000000830DAB186217977011A896EC14A896F80D259700000000000000009015A8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.488  4301  3901 W google-breakpad: S 96A81200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086F313F7C05ECBB68813A89600830DAB3814A8969813A896E823D891F413A8963412259700000000000000000000000040B052969813A896010000008020A896F6FFFFFF0C830DAB0000000000830DAB8813A896
,09-09 16:44:43.488  4301  3901 W google-breakpad: S 96A81380 0300000008000000403F579688FFFFFF40B0529688FFFFFF808B369285FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DAB4814A8963814A8964014A8963414A89682FFFFFFE023D8912414A89688FC1497E023D8914014A89640B0529688FFFFFFA814A896B814A8969815A896010000005014A896000000008414A896509236974014A896000000001800000040B05296403F579688FFFFFF0000000082FFFFFF01000000E023D8910000000082FFFFFF00830DAB0000000074065097B814A896A814A896800B4F99180E4F9900830DAB9815A89674065097F414A89608A22D97B814A8960C15A896070000004F0000003C2308924C97C191000000004097C19140B0529688FFFFFF00830DAB00000000808B369285FFFFFF00830DAB000000000815A896205F51976D97C1912815A8969815A8961815A89600830DAB0C15A89622000000800B4F995C15A8963C122F97ECC74F9758CB4F97
,09-09 16:44:43.488  4301  3901 W google-breakpad: S 96A81500 58DB6597220000004C97C1913CEB8B91000000002C15A8962200000000000000B016A896000000004415A89664DCEC96E015A896B016A896C0C36697A815A89600000000010000009815A8968815A8962200000000830DABEC16A896783B3297D023D891F6FFFFFF0C830DAB0000000000830DABC015A89602000000E015A89630ED189188FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000830DAB010000001017A8962017A89601000000D023D891070000000700000001000000208A36920000000000830DAB000000000000000006000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF00000000D823D89122000000288A36920700000000000000010000001800609650B2339681FFFFFF4C16A89630521F9707000000208A369200830DAB00000000100060965816A8968C16A89638941F97000000000000000000000000DC543399C016A896010000000000000040D9DA92E01B6196208A369200000000FFFFFFFF
,09-09 16:44:43.488  4301  3901 W google-breakpad: S 96A81680 50B2339681FFFFFF2817A896805533998017A8969C16A896E816A8960000000000000000485533994003000001000000FFFFFFFF81FFFFFF208A369285FFFFFF1000609685FFFFFF2017A8964049569688FFFFFF9092319900000000FFFFFFFFC0B2339681FFFFFF2817A896383F799900000000FC16A8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFF208A369285FFFFFF8417A896C0B233969092319901050000208A369285FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFFB417A896CC17A89600000000A817A8968C4979998201000060865696010000000000000082FFFFFF208A369285FFFFFF5418A896C0AA0F96A4B53099010A0000208A369285FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
,09-09 16:44:43.488  4301  3901 W google-breakpad: S 96A81800 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB090C09802000000000000008018A8968C49799902020000A04C569602000000A0C6559688FFFFFF208A369285FFFFFF80331E9188FFFFFFF418A89680898792CCD0C09881060000F0D9619685FFFFFF208A369285FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D818A8960000000083FFFFFF68000000A05C3792288A36920100000030000000A05C3792000000001819A8968C4979998201000080194E95010000000000000082FFFFFF208A369285FFFFFF9C19A8967082879204C9C09881070000208A369285FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB819A896B019A896A819A8961C1AA896
,09-09 16:44:43.489  4301  3901 W google-breakpad: S 96A81980 78000000A05C3792000000001698C19458DB659700830DAB00000000C019A8968C49799982010000C0194E95010000000000000082FFFFFF208A369285FFFFFF2C1AA89698034E92E4BEC09801060000208A369285FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D55396381AA896501AA8960400000060000000A05C3792E0F04B9281FFFFFFBC1AA896F8FF789900000000501AA8968C49799982010000E0194E95010000000000000082FFFFFF208A369285FFFFFFBC1AA89698FB4B92F0B5C09801060000208A369285FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E0D8DA92000000005806A2926000000010D9DA9204000000B090C098CC1AA896C8AB019704000000E01AA8968C49799982010000001A4E95010000000000000082FFFFFFE0D8DA9288FFFFFF5C1BA896909F2E92FCACC09801070000E0D8DA9288FFFFFF0000000082FFFFFF
,09-09 16:44:43.489  4301  3901 W google-breakpad: S 96A81B00 001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFF208A369285FFFFFF00000000501BA8964C1BA89688FFFFFF70000000B0D8DA92608AE095D4881497000000000000000004000000801BA8968C49799982010000801A4E9501000000D0ECDB9288FFFFFFF0D4DA9288FFFFFFDC1BA89660912E9268A6C09801050000F0D4DA9288FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFF608AE095010000000C1CA896241CA89650000000701FDE920200000070F40F95FC1BA89618AB019700000000101CA8960C75BA988202000040FAB094030000000000000082FFFFFFF0D4DA9288FFFFFF0000000081FFFFFF608AE09588FFFFFFAC1CA896D068259200B1809701090000608AE09588FFFFFF0000000081FFFFFFF0D4DA9288FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF4027969388FFFFFF0000000082FFFFFF0900000081FFFFFF608AE09588FFFFFF
,09-09 16:44:43.489  4301  3901 W google-breakpad: S 96A81C80 B08AE09500000000DC1CA896C0D652969000000020C05296B090C0980200000070FA0B9281FFFFFF00000000D01CA8968C49799982010000B002539601000000608AE09588FFFFFF40FAB09488FFFFFF541DA8962860259238A0C0988107000040FAB09488FFFFFF608AE09588FFFFFFB002539688FFFFFFB08AE09588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFFB08AE09588FFFFFF0000000082FFFFFF781DA896383F7999000000003C1DA89678000000701FDE9200000000EC96C098420300000300000000000000801DA8968C4979990202000060FAB09402000000D0A6949488FFFFFF30ED189188FFFFFF608AE09588FFFFFFEC1DA89678BFEA91B89BC09801060000608AE09588FFFFFF30ED189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFFB81DA896D0B052968035549688FFFFFF60000000701FDE92801860969018BB9885FFFFFFEC1DA89600000000E03654966423BB98000C0000A0FAB09402000000
09-09 16:44:43.489  4301  3901 W google-breakpad: S 96A81E00 E036549688FFFFFF30ED189188FFFFFF7084E09588FFFFFF608B369285FFFFFF108AE09588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF6C1EA89610D6DA927084E09580355496E0544B938A000000C0D7DA92608B36927084E09588FFFFFF108AE0957084E09580355496508B36928018609640554B930900000020331E91D0B05296D0B052967084E09588FFFFFF090000004011619609000000E036549630ED1891C0D4DA9220331E9188FFFFFF00000000BC9FEC9160A1EC91000400006036549601000000E036549688FFFFFF30ED189188FFFFFF0000000082FFFFFF982D6F9730ED189190D4DA9260D4DA920000000087FFFFFFA00F539630D4DA9260D4DA9200331E919002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFF30D4DA9288FFFFFFC05ECBB630D4DA92D0D3DA9200D4DA929C81339980020000E036549600000000D0D3DA9288FFFFFF000000000000000030AFB7948A0000000700000040B05296D0544B93E0365496
09-09 16:44:43.490  4301  3901 W google-breakpad: S 96A81F80 2078789903020000403F57960100000040B0529688FFFFFFD0544B9385FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB64821A8960100000081FFFFFFA020A8960C21A896646B0797403F579600000000000000007020A8962420A8963877789958DB659700830DAB00C24C969431A896000000000000000000000000010000007428A89600830DAB00010000000000005080339900000000403F57960025A896020000000100000000000000000000000100000081FFFFFF0000000000000000D824A896F6FFFFFF0C830DAB0100000000830DABA020A8960000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000004821A89600830DAB203E6F9700525B9600000000C823D8910C21A89686F313F70000000000830DAB4821A8961021A896403F579600525B96
09-09 16:44:43.490  4301  3901 W google-breakpad: S 96A82100 00000000C823D8913421A8967C0C2597000000000000000000000000C05ECBB60100000000830DAB0825A8964021A896BC24A896740D259700000000000000000825A89601000000780B65970100000000525B964021A8960000000000000000905EA394CE5EA3940200000002000000010000000000000010B964975C00000006000000000000008030A89600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.490  4301  3901 W google-breakpad: S 96A82280 0000000000000000000000000054A3940000000000000000010000000200000060321E9100535B96A5820FAB000000000000000086F313F700000000C05ECBB60000000000830DAB18621797E022A8965C26A896F80D259700000000000000000027A8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.490  4301  3901 W google-breakpad: S 96A82400 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086F313F7C05ECBB6F824A89600830DABA825A8960825A896C823D8916425A8963412259700000000000000000000000040B052960825A89601000000F031A896F6FFFFFF0C830DAB0000000000830DABF824A8960300000008000000403F579688FFFFFF40B0529688FFFFFFD0544B9385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DABB825A896A825A896B025A896A425A89682FFFFFFC023D8919425A89688FC1497C023D891B025A89640B0529688FFFFFF1826A8962826A896
09-09 16:44:43.490  4301  3901 W google-breakpad: S 96A82580 0827A89601000000C025A89600000000F425A89650923697B025A896000000001800000040B05296403F579688FFFFFF0000000082FFFFFF01000000C023D8910000000082FFFFFF00830DAB00000000740650972826A8961826A896800B4F99180E4F9900830DAB0827A896740650976426A89608A22D972826A8967C26A896070000004F0000003C230892FC96C19100000000F096C19140B0529688FFFFFF00830DAB00000000D0544B9385FFFFFF00830DAB000000007826A896205F51971D97C1919826A8960827A8968826A89600830DAB7C26A89622000000800B4F99CC26A8963C122F97ECC74F9758CB4F9758DB659722000000FC96C1910CEB8B91000000009C26A89622000000000000002028A89600000000B426A89664DCEC965027A8962028A896C0C366971827A89600000000010000000827A896F826A8962200000000830DAB5C28A896783B3297B023D891F6FFFFFF0C830DAB0000000000830DAB3027A896020000005027A896E0EC189188FFFFFF0000000082FFFFFF
09-09 16:44:43.491  4301  3901 W google-breakpad: S 96A82700 0000000000010000220000000000000000000000000000000000000000830DAB010000008028A8969028A89601000000B023D89107000000070000000100000070534B930000000000830DAB000000000000000006000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF00000000B823D8912200000078534B930700000000000000010000001800609650B2339681FFFFFFBC27A89630521F970700000070534B9300830DAB0000000010006096C827A896FC27A89638941F97000000000000000000000000DC5433993028A8960100000000000000A0D3DA92E01B619670534B9300000000FFFFFFFF50B2339681FFFFFF9828A89680553399F028A8960C28A8965828A8960000000000000000485533994003000001000000FFFFFFFF81FFFFFF70534B9385FFFFFF1000609685FFFFFF9028A8964049569688FFFFFF9092319900000000FFFFFFFFC0B2339681FFFFFF9828A896383F7999000000006C28A8968C4979990000000000000000909231994202000001000000
09-09 16:44:43.491  4301  3901 W google-breakpad: S 96A82880 4049569688FFFFFF00EA529688FFFFFF70534B9385FFFFFFF428A896C0B23396909231990105000070534B9385FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFF2429A8963C29A896000000001829A8968C4979998201000060865696010000000000000082FFFFFF70534B9385FFFFFFC429A896C0AA0F96A4B53099010A000070534B9385FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB090C0980200000000000000F029A8968C49799902020000A04C569602000000A0C6559688FFFFFF70534B9385FFFFFFE0321E9188FFFFFF642AA89680898792CCD0C09881060000
09-09 16:44:43.491  4301  3901 W google-breakpad: S 96A82A00 F0D9619685FFFFFF70534B9385FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000482AA8960000000083FFFFFF68000000A05C379278534B930100000030000000A05C379200000000882AA8968C4979998201000080194E95010000000000000082FFFFFF70534B9385FFFFFF0C2BA8967082879204C9C0988107000070534B9385FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF282BA896202BA896182BA8968C2BA89678000000A05C3792000000001698C19458DB659700830DAB00000000302BA8968C49799982010000C0194E95010000000000000082FFFFFF70534B9385FFFFFF9C2BA89698034E92E4BEC0980106000070534B9385FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D55396A82BA896C02BA89604000000
09-09 16:44:43.491  4301  3901 W google-breakpad: S 96A82B80 60000000A05C3792E0F04B9281FFFFFF2C2CA896F8FF789900000000C02BA8968C49799982010000E0194E95010000000000000082FFFFFF70534B9385FFFFFF2C2CA89698FB4B92F0B5C0980106000070534B9385FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000040D3DA92000000005806A2926000000070D3DA9204000000B090C0983C2CA896C8AB019704000000502CA8968C49799982010000001A4E95010000000000000082FFFFFF40D3DA9288FFFFFFCC2CA896909F2E92FCACC0980107000040D3DA9288FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFF70534B9385FFFFFF00000000C02CA896BC2CA89688FFFFFF7000000010D3DA92D083E095D4881497000000000000000004000000F02CA8968C49799982010000801A4E9501000000D0ECDB9288FFFFFF406F699388FFFFFF4C2DA89660912E9268A6C09801050000
09-09 16:44:43.492  4301  3901 W google-breakpad: S 96A82D00 406F699388FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFFD083E095010000007C2DA896942DA89650000000701FDE920200000070F40F956C2DA89618AB019700000000802DA8960C75BA988202000040FAB094030000000000000082FFFFFF406F699388FFFFFF0000000081FFFFFFD083E09588FFFFFF1C2EA896D068259200B1809701090000D083E09588FFFFFF0000000081FFFFFF406F699388FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFD026969388FFFFFF0000000082FFFFFF0900000081FFFFFFD083E09588FFFFFF2084E095000000004C2EA896C0D652969000000020C05296B090C0980200000070FA0B9281FFFFFF00000000402EA8968C49799982010000B002539601000000D083E09588FFFFFF40FAB09488FFFFFFC42EA8962860259238A0C0988107000040FAB09488FFFFFFD083E09588FFFFFFB002539688FFFFFF2084E09588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF
09-09 16:44:43.492  4301  3901 W google-breakpad: S 96A82E80 0000000082FFFFFF2084E09588FFFFFF0000000082FFFFFFE82EA896383F799900000000AC2EA89678000000701FDE9200000000EC96C098420300000300000000000000F02EA8968C4979990202000060FAB09402000000D0A6949488FFFFFFE0EC189188FFFFFFD083E09588FFFFFF5C2FA89678BFEA91B89BC09801060000D083E09588FFFFFFE0EC189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFF282FA896D0B052968035549688FFFFFF60000000701FDE92801860969018BB9885FFFFFF5C2FA89600000000E03654966423BB98000C0000A0FAB09402000000E036549688FFFFFFE0EC189188FFFFFF801DEA9588FFFFFFB0544B9385FFFFFF8083E09588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFDC2FA896A0D0DA92801DEA958035549630AFB7948A00000050D2DA92B0544B93801DEA9588FFFFFF8083E095801DEA9580355496A0544B938018609690AFB7940900000080321E91D0B05296D0B05296
09-09 16:44:43.492  4301  3901 W google-breakpad: S 96A83000 801DEA9588FFFFFF090000004011619609000000E0365496E0EC1891106F699380321E9188FFFFFF00000000BC9FEC9160A1EC91000400006036549601000000E036549688FFFFFFE0EC189188FFFFFF0000000082FFFFFF982D6F97E0EC1891E06E6993B06E69930000000087FFFFFFA00F5396806E6993B06E699360321E919002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFF806E699388FFFFFFC05ECBB6806E6993206E6993506E69939C81339980020000E036549600000000206E699388FFFFFF000000000000000040AA40958A0000000700000040B0529620AFB794E03654962078789903020000403F57960100000040B0529688FFFFFF20AFB79485FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB6B832A8960100000081FFFFFF1032A8967C32A896646B0797403F579600000000
09-09 16:44:43.492  4301  3901 W google-breakpad: S 96A83180 00000000E031A8969431A8963877789958DB659700830DAB00C24C960443A89600000000000000000000000001000000E439A89600830DAB00010000000000005080339900000000403F57967036A896020000000100000000000000000000000100000081FFFFFF00000000000000004836A896F6FFFFFF0C830DAB0100000000830DAB1032A896000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B832A89600830DAB203E6F9700525B9600000000A823D8917C32A89686F313F70000000000830DABB832A8968032A896403F579600525B9600000000A823D891A432A8967C0C2597000000000000000000000000C05ECBB60100000000830DAB7836A896B032A8962C36A896740D259700000000000000007836A89601000000780B65970100000000525B96B032A8960000000000000000905EA394CE5EA3940200000002000000010000000000000010B964975C0000000600000000000000F041A89600000000
09-09 16:44:43.492  4301  3901 W google-breakpad: S 96A83300 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000054A39400000000000000000100000002000000C0311E9100535B96A5820FAB000000000000000086F313F700000000C05ECBB60000000000830DAB186217975034A896CC37A896F80D259700000000000000007038A8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.493  4301  3901 W google-breakpad: S 96A83480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.493  4301  3901 W google-breakpad: S 96A83600 00000000000000000000000086F313F7C05ECBB66836A89600830DAB1837A8967836A896A823D891D436A8963412259700000000000000000000000040B052967836A896010000006043A896F6FFFFFF0C830DAB0000000000830DAB6836A8960300000008000000403F579688FFFFFF40B0529688FFFFFF20AFB79485FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DAB2837A8961837A8962037A8961437A89682FFFFFFA023D8910437A89688FC1497A023D8912037A89640B0529688FFFFFF8837A8969837A8967838A896010000003037A896000000006437A896509236972037A896000000001800000040B05296403F579688FFFFFF0000000082FFFFFF01000000A023D8910000000082FFFFFF00830DAB00000000740650979837A8968837A896800B4F99180E4F9900830DAB7838A89674065097D437A89608A22D979837A896EC37A896070000004F0000003C230892AC96C191
09-09 16:44:43.493  4301  3901 W google-breakpad: S 96A83780 00000000A096C19140B0529688FFFFFF00830DAB0000000020AFB79485FFFFFF00830DAB00000000E837A896205F5197CD96C1910838A8967838A896F837A89600830DABEC37A89622000000800B4F993C38A8963C122F97ECC74F9758CB4F9758DB659722000000AC96C191DCEA8B91000000000C38A89622000000000000009039A896000000002438A89664DCEC96C038A8969039A896C0C366978838A89600000000010000007838A8966838A8962200000000830DABCC39A896783B32979023D891F6FFFFFF0C830DAB0000000000830DABA038A89602000000C038A89690EC189188FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000830DAB01000000F039A896003AA896010000009023D891070000000700000001000000C0ADB7940000000000830DAB00000000F80D289506000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF000000009823D89122000000C8ADB79407000000000000000100000018006096
09-09 16:44:43.493  4301  3901 W google-breakpad: S 96A83900 50B2339681FFFFFF2C39A89630521F9707000000C0ADB79400830DAB00000000100060963839A8966C39A89638941F97000000000000000000000000DC543399A039A8960100000000000000F06D6993E01B6196C0ADB79400000000FFFFFFFF50B2339681FFFFFF083AA89680553399603AA8967C39A896C839A8960000000000000000485533994003000001000000FFFFFFFF81FFFFFFC0ADB79485FFFFFF1000609685FFFFFF003AA8964049569688FFFFFF9092319900000000FFFFFFFFC0B2339681FFFFFF083AA896383F799900000000DC39A8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFFC0ADB79485FFFFFF643AA896C0B233969092319901050000C0ADB79485FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFF943AA896AC3AA89600000000883AA8968C4979998201000060865696010000000000000082FFFFFF
09-09 16:44:43.494  4301  3901 W google-breakpad: S 96A83A80 C0ADB79485FFFFFF343BA896C0AA0F96A4B53099010A0000C0ADB79485FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB090C0980200000000000000603BA8968C49799902020000A04C569602000000A0C6559688FFFFFFC0ADB79485FFFFFF40321E9188FFFFFFD43BA89680898792CCD0C09881060000F0D9619685FFFFFFC0ADB79485FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B83BA8960000000083FFFFFF68000000A05C3792C8ADB7940100000030000000A05C379200000000F83BA8968C4979998201000080194E95010000000000000082FFFFFFC0ADB79485FFFFFF7C3CA89670828792
09-09 16:44:43.494  4301  3901 W google-breakpad: S 96A83C00 04C9C09881070000C0ADB79485FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF983CA896903CA896883CA896FC3CA89678000000A05C3792000000001698C19458DB659700830DAB00000000A03CA8968C49799982010000C0194E95010000000000000082FFFFFFC0ADB79485FFFFFF0C3DA89698034E92E4BEC09801060000C0ADB79485FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D55396183DA896303DA8960400000060000000A05C3792E0F04B9281FFFFFF9C3DA896F8FF789900000000303DA8968C49799982010000E0194E95010000000000000082FFFFFFC0ADB79485FFFFFF9C3DA89698FB4B92F0B5C09801060000C0ADB79485FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000906D6993000000005806A292
09-09 16:44:43.494  4301  3901 W google-breakpad: S 96A83D80 60000000C06D699304000000B090C098AC3DA896C8AB019704000000C03DA8968C49799982010000001A4E95010000000000000082FFFFFF906D699388FFFFFF3C3EA896909F2E92FCACC09801070000906D699388FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFFC0ADB79485FFFFFF00000000303EA8962C3EA89688FFFFFF70000000606D6993401CEA95D4881497000000000000000004000000603EA8968C49799982010000801A4E9501000000D0ECDB9288FFFFFF7069699388FFFFFFBC3EA89660912E9268A6C098010500007069699388FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFF401CEA9501000000EC3EA896043FA89650000000701FDE920200000070F40F95DC3EA89618AB019700000000F03EA8960C75BA988202000040FAB094030000000000000082FFFFFF7069699388FFFFFF0000000081FFFFFF401CEA9588FFFFFF8C3FA896D068259200B1809701090000
09-09 16:44:43.494  4301  3901 W google-breakpad: S 96A83F00 401CEA9588FFFFFF0000000081FFFFFF7069699388FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF6026969388FFFFFF0000000082FFFFFF0900000081FFFFFF401CEA9588FFFFFF301DEA9500000000BC3FA896C0D652969000000020C05296B090C0980200000070FA0B9281FFFFFF00000000B03FA8968C49799982010000B002539601000000401CEA9588FFFFFF40FAB09488FFFFFF3440A8962860259238A0C0988107000040FAB09488FFFFFF401CEA9588FFFFFFB002539688FFFFFF301DEA9588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFF301DEA9588FFFFFF0000000082FFFFFF5840A896383F7999000000001C40A89678000000701FDE9200000000EC96C0984203000003000000000000006040A8968C4979990202000060FAB09402000000D0A6949488FFFFFF90EC189188FFFFFF401CEA9588FFFFFFCC40A89678BFEA91B89BC09801060000401CEA9588FFFFFF90EC189188FFFFFF
09-09 16:44:43.494  4301  3901 W google-breakpad: S 96A84080 D0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFF9840A896D0B052968035549688FFFFFF60000000701FDE92801860969018BB9885FFFFFFCC40A89600000000E03654966423BB98000C0000A0FAB09402000000E036549688FFFFFF90EC189188FFFFFF5016EA9588FFFFFF00AFB79485FFFFFFF01BEA9588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF4C41A896C06A69935016EA958035549640AA40958A000000A06C699300AFB7945016EA9588FFFFFFF01BEA955016EA9580355496F0AEB79480186096A0AA409509000000E0311E91D0B05296D0B052965016EA9588FFFFFF090000004011619609000000E036549690EC189140696993E0311E9188FFFFFF00000000BC9FEC9160A1EC91000400006036549601000000E036549688FFFFFF90EC189188FFFFFF0000000082FFFFFF982D6F9790EC189110696993E06869930000000087FFFFFFA00F5396B0686993E0686993C0311E919002C29880020000A036549602000000
09-09 16:44:43.495  4301  3901 W google-breakpad: S 96A84200 0000000082FFFFFFA00F539688FFFFFFB068699388FFFFFFC05ECBB6B068699350686993806869939C81339980020000E0365496000000005068699388FFFFFF0000000000000000A0559D918A0000000700000040B0529630AA4095E03654962078789903020000403F57960100000040B0529688FFFFFF30AA409585FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB62844A8960100000081FFFFFF8043A896EC43A896646B0797403F579600000000000000005043A8960443A8963877789958DB659700830DAB00C24C967454A89600000000000000000000000001000000544BA89600830DAB0001A896000000005080339900000000403F5796E047A8960200000001000000D410EA91000000000100000081FFFFFF0048A89600001000B847A896F6FFFFFF0C830DAB0100000000830DAB8043A8960000000008000000
09-09 16:44:43.495  4301  3901 W google-breakpad: S 96A84380 3C0082E000000000AC43A896644B2B9700008000200000003046A896D8445B9600001000010000002844A89600830DAB203E6F9700525B96000000008823D891EC43A89686F313F70000000000830DAB2844A896F043A896403F579600525B96000000008823D8911444A8967C0C25970000000040EC18912444A896C05ECBB60100000000830DABE847A8962044A8969C47A896740D25972848A896000000E0E847A89601000000780B65970100000000525B962044A89600000000000000056444A8969C422B970200000038000000C410EA917C412B971144A896380000002848A8961146A8963C000000000000E0C05ECBB63046A896C844A896D8445B9640EC1891000000009410EA91405F2B97D810EA91A444A89601000000B444A896B444A896FFFFFF0001000000C444A89608000000DC10EA91B010EA9144E0C09850E0C09870272B9728E0C098F0FFFFFFFFFFFFFF000000003046A89644EF156E88AB1F9D0010EA91005021994848A89688AB1F9D7023D891005021993046A896
09-09 16:44:43.495  4301  3901 W google-breakpad: S 96A84500 0CE3CBB680AB1F9D9415CBB688AB1F9D7023D8915B42C9B604000000DC45A896E84990946045A8965445A89698AF0A9744E0C09854E0C098F82ED091F82ED0916445A8964848A89601000000F82ED09100830DAB3046A89601000000F82ED09100830DAB40EC189140EC1891000000008445A8967C6AF796604DA8963046A8969445A8967412069700000000C05ECBB61C51A896ACE40A970020D091C4AF50970D00000064ADC99203000000000000000000000050520B970020D0916CB25097A037BB983046A896010000000020D091E845A896D8445B9640EC1891B8C9639741B052968422BB9810000000280000001C0000002C00000000000000F82ED0910D00000064ADC99203000000000000000D0000001C222B9702000000010000003046A8960000000000000000000000004046A89600000000000000000000000000000000000000005846A89600000000000000000000000000000000000000007046A89600000000000000000000000000000000000000008846A89600000000
09-09 16:44:43.495  4301  3901 W google-breakpad: S 96A84680 00000000000000009846A896000000000100000000000000A846A8960000000000000000000000000800000000000000C046A896000000000800000000000000D046A89600000000080000000000000008000000000000000800000000000000F046A8960000000000000000000000000047A8960000000000000000050000001047A89600000000000000000200000002000000000000007023D89101000000010000000000000000000000010000004047A89600000000000000000000000020000000000000005847A8960000000020000000000000006847A89600000000200000000500000001000000050000008047A896020000000100000086F313F7C05ECBB6D847A89600830DAB8848A896E847A8968823D8914448A896341225970100000000000000B847A89640B05296E847A89601000000D054A896F6FFFFFF0C830DAB0000000000830DABD847A8960300000008000000403F579688FFFFFF40B0529688FFFFFF30AA409585FFFFFF0048A896000000002000000000000000
09-09 16:44:43.496  4301  3901 W google-breakpad: S 96A84800 1048A8960000000020000000B010EA910114EA910000EA910029639786F313F70400000000830DAB9848A8968848A8969048A8968448A89682FFFFFF8023D8917448A89688FC14978023D8919048A89640B0529688FFFFFFF848A8960849A896E849A89601000000A048A89600000000D448A896509236979048A896080000001800000040B05296403F579688FFFFFF0000000082FFFFFF010000008023D8910000000082FFFFFF00830DAB00000000740650970849A896F848A896800B4F99180E4F9900830DABE849A896740650974449A89608A22D970849A8965C49A896070000004F0000003C2308925C96C191000000005096C19140B0529688FFFFFF00830DAB0000000030AA409585FFFFFF00830DAB000000005849A896205F51977D96C1917849A896E849A8966849A89600830DAB5C49A89622000000800B4F99AC49A8963C122F97ECC74F9758CB4F9758DB6597220000005C96C191ACEA8B91000000007C49A8962200000000000000004BA896000000009449A89664DCEC96
09-09 16:44:43.496  4301  3901 W google-breakpad: S 96A84980 304AA896004BA896C0C36697F849A8960000000001000000E849A896D849A8962200000000830DAB3C4BA896783B32977023D891F6FFFFFF0C830DAB0000000000830DAB104AA89602000000304AA89640EC189188FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000830DAB01000000604BA896704BA896010000007023D891070000000700000001000000D0A840950000000000830DAB000000000000000006000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF000000007823D89122000000D8A840950700000000000000010000001800609650B2339681FFFFFF9C4AA89630521F9707000000D0A8409500830DAB0000000010006096A84AA896DC4AA89638941F974C0E9C98A853D5B4F4E2CBB6DC543399104BA896010000002C018C9820686993E01B6196D0A8409500000000FFFFFFFF50B2339681FFFFFF784BA89680553399D04BA896EC4AA896384BA8960000000000000000485533994003000001000000
09-09 16:44:43.496  4301  3901 W google-breakpad: S 96A84B00 FFFFFFFF81FFFFFFD0A8409585FFFFFF1000609685FFFFFF804BA8964049569688FFFFFF9092319900000000FFFFFFFFC0B2339681FFFFFF784BA896383F7999000000004C4BA8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFFD0A8409585FFFFFFD44BA896C0B233969092319901050000D0A8409585FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFF044CA8961C4CA89600000000F84BA8968C4979998201000060865696010000000000000082FFFFFFD0A8409585FFFFFFA44CA896C0AA0F96A4B53099010A0000D0A8409585FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97
09-09 16:44:43.496  4301  3901 W google-breakpad: S 96A84C80 F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB090C0980200000000000000D04CA8968C49799902020000A04C569602000000A0C6559688FFFFFFD0A8409585FFFFFFA0311E9188FFFFFF444DA89680898792CCD0C09881060000F0D9619685FFFFFFD0A8409585FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000284DA8960000000083FFFFFF68000000A05C3792D8A840950100000030000000A05C379200000000684DA8968C4979998201000080194E95010000000000000082FFFFFFD0A8409585FFFFFFEC4DA8967082879204C9C09881070000D0A8409585FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF084EA896004EA896F84DA8966C4EA89678000000A05C3792000000001698C19458DB659700830DAB00000000104EA8968C49799982010000C0194E9501000000
09-09 16:44:43.496  4301  3901 W google-breakpad: S 96A84E00 0000000082FFFFFFD0A8409585FFFFFF7C4EA89698034E92E4BEC09801060000D0A8409585FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D55396884EA896A04EA8960400000060000000A05C3792E0F04B9281FFFFFF0C4FA896F8FF789900000000A04EA8968C49799982010000E0194E95010000000000000082FFFFFFD0A8409585FFFFFF0C4FA89698FB4B92F0B5C09801060000D0A8409585FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000C0676993000000005806A29260000000F067699304000000B090C0981C4FA896C8AB019704000000304FA8968C49799982010000001A4E95010000000000000082FFFFFFC067699388FFFFFFAC4FA896909F2E92FCACC09801070000C067699388FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFFD0A8409585FFFFFF
09-09 16:44:43.497  4301  3901 W google-breakpad: S 96A84F80 00000000A04FA8969C4FA89688FFFFFF7000000090676993B015EA95D4881497000000000000000004000000D04FA8968C49799982010000801A4E9501000000D0ECDB9288FFFFFF0064699388FFFFFF2C50A89660912E9268A6C098010500000064699388FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFFB015EA95010000005C50A8967450A89650000000701FDE920200000070F40F954C50A89618AB0197000000006050A8960C75BA988202000040FAB094030000000000000082FFFFFF0064699388FFFFFF0000000081FFFFFFB015EA9588FFFFFFFC50A896D068259200B1809701090000B015EA9588FFFFFF0000000081FFFFFF0064699388FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFF025969388FFFFFF0000000082FFFFFF0900000081FFFFFFB015EA9588FFFFFF0016EA95000000002C51A896C0D652969000000020C05296B090C0980200000070FA0B9281FFFFFF000000002051A896
09-09 16:44:43.497  4301  3901 W google-breakpad: S 96A85100 8C49799982010000B002539601000000B015EA9588FFFFFF40FAB09488FFFFFFA451A8962860259238A0C0988107000040FAB09488FFFFFFB015EA9588FFFFFFB002539688FFFFFF0016EA9588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFF0016EA9588FFFFFF0000000082FFFFFFC851A896383F7999000000008C51A89678000000701FDE9200000000EC96C098420300000300000000000000D051A8968C4979990202000060FAB09402000000D0A6949488FFFFFF40EC189188FFFFFFB015EA9588FFFFFF3C52A89678BFEA91B89BC09801060000B015EA9588FFFFFF40EC189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFF0852A896D0B052968035549688FFFFFF60000000701FDE92801860969018BB9885FFFFFF3C52A89600000000E03654966423BB98000C0000A0FAB09402000000E036549688FFFFFF40EC189188FFFFFFB0DFE99588FFFFFF10AA409585FFFFFF6015EA9588FFFFFF0900000081FFFFFF
09-09 16:44:43.497  4301  3901 W google-breakpad: S 96A85280 0900000081FFFFFF0900000081FFFFFFBC52A89620656993B0DFE99580355496A0559D918A000000D066699310AA4095B0DFE99588FFFFFF6015EA95B0DFE9958035549600AA40958018609600569D910900000040311E91D0B05296D0B05296B0DFE99588FFFFFF090000004011619609000000E036549640EC1891D063699340311E9188FFFFFF00000000BC9FEC9160A1EC91000400006036549601000000E036549688FFFFFF40EC189188FFFFFF0000000082FFFFFF982D6F9740EC1891A0636993706369930000000087FFFFFFA00F5396406369937063699320311E919002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFF4063699388FFFFFF0000000040636993E0626993106369939C81339980020000E036549600000000E062699388FFFFFF885DA89648000000CC53A896985BA8964800000040B0529690559D91E03654962078789903020000403F57960100000040B0529688FFFFFF90559D9185FFFFFF00000000000000000000000000000000
09-09 16:44:43.497  4301  3901 W google-breakpad: S 96A85400 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB69855A8960100000081FFFFFFF054A8965C55A896646B0797403F57960000000000000000C054A8967454A8963877789958DB659700830DAB00C24C96DC65A89600000000000000000000000001000000C45CA89600830DAB00010A95000000005080339900000000403F57965059A8960200000001000000884AA993000000000100000081FFFFFF00502199987C84922859A896F6FFFFFF0C830DAB0100000000830DABF054A896000000000800000050790A9530790A95D84AA9939F010000C840A99330790A95A0790A952A04000048310291010000009855A89600830DAB203E6F9700525B96000000006823D8915C55A89686F313F70000000000830DAB9855A8966055A896403F579600525B96000000006823D8918455A8967C0C259700000000E0B8C99200000000C05ECBB60100000000830DAB5859A8969055A896
09-09 16:44:43.498  4301  3901 W google-breakpad: S 96A85580 0C59A896740D2597525CA394FB5DA3945859A89601000000780B65970100000000525B969055A89600000000005EA3940200000002000000010000000000000010B964975C0000000600000000000000C864A896000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000054A3940000000000000000010000000200000080301E9100535B96A5820FAB000000000000000086F313F7
09-09 16:44:43.498  4301  3901 W google-breakpad: S 96A85700 00000000C05ECBB60000000000830DAB186217972857A896A45AA896F80D25970000000000000000485BA89600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000D4004892901248920000000000800000901248929753C8B6A058A8968858A89690124892A453D5B4A853D5B490124892
09-09 16:44:43.498  4301  3901 W google-breakpad: S 96A85880 00000000C355C8B6C8042092010000002C018C980100000080015093FFFFFFFFA80C809201000000F80DDC98FFFFFFFF24036895FFFFFFFF7005A893FFFFFFFF6807C892FFFFFFFF2C018492FFFFFFFFA853D5B4FFFFFFFFA853D5B4FFFFFFFF2802089201000000BC070C9286F313F7C05ECBB64859A89600830DABF859A8965859A8966823D891B459A8963412259700000000000000000000000040B052965859A896010000003866A896F6FFFFFF0C830DAB0000000000830DAB4859A8960300000008000000403F579688FFFFFF40B0529688FFFFFF90559D9185FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DAB085AA896F859A896005AA896F459A89682FFFFFF6023D891E459A89688FC14976023D891005AA89640B0529688FFFFFF685AA896785AA896585BA89601000000105AA89600000000445AA89650923697005AA896000000001800000040B05296403F579688FFFFFF
09-09 16:44:43.498  4301  3901 W google-breakpad: S 96A85A00 0000000082FFFFFF010000006023D8910000000082FFFFFF00830DAB0000000074065097785AA896685AA896800B4F99180E4F9900830DAB585BA89674065097B45AA89608A22D97785AA896CC5AA896070000004F0000003C2308926C95C191000000006095C19140B0529688FFFFFF00830DAB0000000090559D9185FFFFFF00830DAB00000000C85AA896205F51978D95C191E85AA896585BA896D85AA89600830DABCC5AA89622000000800B4F991C5BA8963C122F97ECC74F9758CB4F9758DB6597220000006C95C1917CEA8B91C0BBE291EC5AA8962200000000000000705CA89600000000045BA89664DCEC96A05BA896705CA896C0C36697685BA8960000000001000000585BA896485BA8962200000000830DABAC5CA896783B32974823D8910000000038724B920000000000000000805BA8969C5BA896A05BA896B85BA896000000000000000082FFFFFF000000000001000022000000000000000000000000000000005BA89600830DAB01000000D05CA896E05CA89601100000
09-09 16:44:43.498  4301  3901 W google-breakpad: S 96A85B80 4823D89107000000070000000100000030549D910000002000830DAB4C55A896987C849206000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF000000004023D8912200000038549D910700000000000000010000001800609650B23396010000000C5CA89630521F970700000030549D9100830DAB0000000010006096185CA8964C5CA89638941F97F018CA924819CA92A019CA92DC543399805CA89601000000001BCA92B0626993E01B619630549D9100000000FFFFFFFF50B2339601000000E85CA89680553399405DA8965C5CA896A85CA8960000000000000000485533994003000001000000FFFFFFFF81FFFFFF30549D9185FFFFFF1000609685FFFFFF4023CA924049569688FFFFFF9092319900000000FFFFFFFFC0B2339601000000E85CA896383F799900000000BC5CA8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFF30549D9185FFFFFF445DA896C0B23396909231990105000030549D9185FFFFFF
09-09 16:44:43.499  4301  3901 W google-breakpad: S 96A85D00 00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFF745DA8968C5DA89600000000685DA8968C4979998201000060865696010000000000000082FFFFFF30549D9185FFFFFF145EA896C0AA0F96A4B53099010A000030549D9185FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFF606169930302000000000000405EA8968C49799902020000A04C569602000000A0C6559688FFFFFF30549D9185FFFFFF00311E9188FFFFFFB45EA89680898792CCD0C09881060000F0D9619685FFFFFF30549D9185FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF
09-09 16:44:43.499  4301  3901 W google-breakpad: S 96A85E80 0000000082FFFFFFC1030000985EA8960000000083FFFFFF68000000A05C379238549D910100000030000000A05C379200000000D85EA8968C4979998201000080194E95010000000000000082FFFFFF30549D9185FFFFFF5C5FA8967082879204C9C0988107000030549D9185FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF785FA896705FA896685FA896DC5FA89678000000A05C3792000000001698C19458DB659700830DAB00000000805FA8968C49799982010000C0194E95010000000000000082FFFFFF30549D9185FFFFFFEC5FA89698034E92E4BEC0980106000030549D9185FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F85FA8961060A8960400000060000000A05C3792E0F04B92010000007C60A896F8FF7899000000001060A8968C49799982010000E0194E9501000000
09-09 16:44:43.499  4301  3901 W google-breakpad: S 96A86000 0000000082FFFFFF30549D9185FFFFFF7C60A89698FB4B92F0B5C0980106000030549D9185FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000050626993000000005806A292600000008062699304000000606169938C60A896C8AB019704000000A060A8968C49799982010000001A4E95010000000000000082FFFFFF5062699388FFFFFF1C61A896909F2E92FCACC098010700005062699388FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFF30549D9185FFFFFF000000001061A8960C61A89688FFFFFF700000002062699310DFE995D48814970000000000000000040000004061A8968C49799982010000801A4E9501000000D0ECDB9288FFFFFF503E3E9588FFFFFF9C61A89660912E9268A6C09801050000503E3E9588FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFF10DFE99501000000CC61A896E461A896
09-09 16:44:43.499  4301  3901 W google-breakpad: S 96A86180 50000000701FDE920302000070F40F95BC61A89618AB019700000000D061A8960C75BA988202000040FAB094030000000000000082FFFFFF503E3E9588FFFFFF0000000081FFFFFF10DFE99588FFFFFF6C62A896D068259200B180970109000010DFE99588FFFFFF0000000081FFFFFF503E3E9588FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF8025969388FFFFFF0000000082FFFFFF0900000081FFFFFF10DFE99588FFFFFF60DFE995000000009C62A896C0D652969000000020C05296606169930302000070FA0B9201000000000000009062A8968C49799982010000B00253960100000010DFE99588FFFFFF40FAB09488FFFFFF1463A8962860259238A0C0988107000040FAB09488FFFFFF10DFE99588FFFFFFB002539688FFFFFF60DFE99588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFF60DFE99588FFFFFF0000000082FFFFFF3863A896383F799900000000FC62A89678000000701FDE92
09-09 16:44:43.500  4301  3901 W google-breakpad: S 96A86300 00000000EC96C0984203000003000000000000004063A8968C4979990202000060FAB09402000000D0A6949488FFFFFFF0EB189188FFFFFF10DFE99588FFFFFFAC63A89678BFEA91B89BC0980106000010DFE99588FFFFFFF0EB189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFFCC617999F463A896F863A89670559D9160000000701FDE92E063A89670559D91606169930302000000000000D863A8968C49799902020000A0FAB09402000000E036549688FFFFFFF0EB189188FFFFFF30D8E99588FFFFFF7464A89688AF2A95B48A49990109000030D8E99588FFFFFFF0EB189188FFFFFFE036549688FFFFFFA0FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFF70559D9185FFFFFFC0DEE99588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFA0301E9188FFFFFF6061699388FFFFFF403F57960100000090000000203E3E957C64A8966C64A896B0276F970000000004000000C466A89660A1EC9100040000
09-09 16:44:43.500  4301  3901 W google-breakpad: S 96A86480 6036549601000000E036549688FFFFFFF0EB189188FFFFFF0000000082FFFFFF982D6F97F0EB1891F03D3E95C03D3E950000000087FFFFFFA00F5396903D3E95C03D3E9580301E919002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFF903D3E9588FFFFFF2865A896903D3E95303D3E95603D3E959C81339980020000E036549600000000303D3E9588FFFFFF20FF84948A0000000700000030FF849400830DAB40B0529610323D95E03654962078789903020000403F57960100000040B0529688FFFFFF10323D9585FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB60067A8960100000081FFFFFF5866A896C466A896646B0797403F579600000000000000002866A896DC65A8963877789958DB659700830DAB00C24C964477A896000000000000000000000000010000002C6EA89600830DAB
09-09 16:44:43.500  4301  3901 W google-breakpad: S 96A86600 00010000000000005080339900000000403F5796B86AA896020000000100000000000000000000000100000081FFFFFF0000000000000000906AA896F6FFFFFF0C830DAB0100000000830DAB5866A8960000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000000067A89600830DAB203E6F9700525B96000000004023D891C466A89686F313F70000000000830DAB0067A896C866A896403F579600525B96000000004023D891EC66A8967C0C2597000000000000000000000000C05ECBB60100000000830DABC06AA896F866A896746AA896740D2597525CA394FB5DA394C06AA89601000000780B65970100000000525B96F866A89600000000005EA3940200000002000000010000000000000010B964975C00000006000000000000003076A8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.500  4301  3901 W google-breakpad: S 96A86780 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000054A39400000000000000000100000002000000C0AF379500535B96A5820FAB000000000000000086F313F700000000C05ECBB60000000000830DAB186217979068A8960C6CA896F80D25970000000000000000B06CA896000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.500  4301  3901 W google-breakpad: S 96A86900 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086F313F7C05ECBB6B06AA89600830DAB606BA896C06AA8964023D8911C6BA896341225970000000000000000
09-09 16:44:43.501  4301  3901 W google-breakpad: S 96A86A80 0000000040B05296C06AA89601000000A077A896F6FFFFFF0C830DAB0000000000830DABB06AA8960300000008000000403F579688FFFFFF40B0529688FFFFFF10323D9585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DAB706BA896606BA896686BA8965C6BA89682FFFFFF3823D8914C6BA89688FC14973823D891686BA89640B0529688FFFFFFD06BA896E06BA896C06CA89601000000786BA89600000000AC6BA89650923697686BA896000000001800000040B05296403F579688FFFFFF0000000082FFFFFF010000003823D8910000000082FFFFFF00830DAB0000000074065097E06BA896D06BA896800B4F99180E4F9900830DABC06CA896740650971C6CA89608A22D97E06BA896346CA896070000004F0000003C230892CC94C19100000000C094C19140B0529688FFFFFF00830DAB0000000010323D9585FFFFFF00830DAB00000000306CA896205F5197ED94C191506CA896
09-09 16:44:43.501  4301  3901 W google-breakpad: S 96A86C00 C06CA896406CA89600830DAB346CA89622000000800B4F99846CA8963C122F97ECC74F9758CB4F9758DB659722000000CC94C1914CEA8B9100000000546CA8962200000000000000D86DA896000000006C6CA89664DCEC96086DA896D86DA896C0C36697D06CA8960000000001000000C06CA896B06CA8962200000000830DAB146EA896783B32972023D8910000000000830DABA06CA89602000000E86CA896A0EB1891086DA89680383E9588FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000830DAB01000000386EA896486EA896010000002023D891070000000700000001000000B0303D950000000000830DAB000000000000000006000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF000000003023D89122000000B8303D950700000000000000010000001800609650B2339601000000746DA89630521F9707000000B0303D9500830DAB0000000010006096806DA896B46DA89638941F97F4E2CBB6BB54C8B6
09-09 16:44:43.501  4301  3901 W google-breakpad: S 96A86D80 C8042092DC543399E86DA8960100000080015093003D3E95E01B6196B0303D9500000000FFFFFFFF50B2339601000000506EA89680553399A86EA896C46DA896106EA8960000000000000000485533994003000001000000FFFFFFFF81FFFFFFB0303D9585FFFFFF1000609685FFFFFFA453D5B44049569688FFFFFF9092319900000000FFFFFFFFC0B2339601000000506EA896383F799900000000246EA8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFFB0303D9585FFFFFFAC6EA896C0B233969092319901050000B0303D9585FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296F0D9619685FFFFFFDC6EA896F46EA89600000000D06EA8968C4979998201000060865696010000000000000082FFFFFFB0303D9585FFFFFF7C6FA896C0AA0F96A4B53099010A0000B0303D9585FFFFFF0000000082FFFFFF6086569688FFFFFF0000000082FFFFFF
09-09 16:44:43.501  4301  3901 W google-breakpad: S 96A86F00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007609685FFFFFFF0D9619685FFFFFF82FFFFFF001B6F97F0FB6196BC8FC098A000000030BD52960000000083FFFFFFB03B3E950302000000000000A86FA8968C49799902020000A04C569602000000A0C6559688FFFFFFB0303D9585FFFFFF60301E9188FFFFFF1C70A89680898792CCD0C09881060000F0D9619685FFFFFFB0303D9585FFFFFFA0C6559688FFFFFFA04C569688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300000070A8960000000083FFFFFF68000000A05C3792B8303D950100000030000000A05C3792000000004070A8968C4979998201000080194E95010000000000000082FFFFFFB0303D9585FFFFFFC470A8967082879204C9C09881070000B0303D9585FFFFFF0000000082FFFFFF80194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-09 16:44:43.502  4301  3901 W google-breakpad: S 96A87080 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE070A896D870A896D070A8964471A89678000000A05C3792000000001698C19458DB659700830DAB00000000E870A8968C49799982010000C0194E95010000000000000082FFFFFFB0303D9585FFFFFF5471A89698034E92E4BEC09801060000B0303D9585FFFFFF0000000082FFFFFFC0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000006071A8967871A8960400000060000000A05C3792E0F04B9201000000E471A896F8FF7899000000007871A8968C49799982010000E0194E95010000000000000082FFFFFFB0303D9585FFFFFFE471A89698FB4B92F0B5C09801060000B0303D9585FFFFFF0000000082FFFFFFE0194E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A03C3E95000000005806A29260000000D03C3E9504000000B03B3E95F471A896C8AB0197040000000872A8968C49799982010000001A4E95010000000000000082FFFFFF
09-09 16:44:43.502  4301  3901 W google-breakpad: S 96A87200 A03C3E9588FFFFFF8472A896909F2E92FCACC09801070000A03C3E9588FFFFFF0000000082FFFFFF001A4E9588FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013619685FFFFFFB0303D9585FFFFFF000000007872A8967472A89688FFFFFF70000000703C3E9590D7E995D4881497000000000000000004000000A872A8968C49799982010000801A4E9501000000D0ECDB9288FFFFFFE0383E9588FFFFFF0473A89660912E9268A6C09801050000E0383E9588FFFFFFD0ECDB9288FFFFFF801A4E9588FFFFFFC0D3619685FFFFFF90D7E995010000003473A8964C73A89650000000701FDE920302000070F40F952473A89618AB0197000000003873A8960C75BA988202000040FAB094030000000000000082FFFFFFE0383E9588FFFFFF0000000081FFFFFF90D7E99588FFFFFFD473A896D068259200B180970109000090D7E99588FFFFFF0000000081FFFFFFE0383E9588FFFFFF0000000082FFFFFF40FAB09488FFFFFF0900000084FFFFFF0000000082FFFFFF
09-09 16:44:43.502  4301  3901 W google-breakpad: S 96A87380 0000000081FFFFFF1025969388FFFFFF0000000082FFFFFF0900000081FFFFFF90D7E99588FFFFFFE0D7E995000000000474A896C0D652969000000020C05296B03B3E950302000070FA0B920100000000000000F873A8968C49799982010000B00253960100000090D7E99588FFFFFF40FAB09488FFFFFF7C74A8962860259238A0C0988107000040FAB09488FFFFFF90D7E99588FFFFFFB002539688FFFFFFE0D7E99588FFFFFFC0D6529688FFFFFFC0D0529688FFFFFF0000000082FFFFFFE0D7E99588FFFFFF0000000082FFFFFFA074A896383F7999000000006474A89678000000701FDE9200000000EC96C098420300000300000000000000A874A8968C4979990202000060FAB09402000000D0A6949488FFFFFFA0EB189188FFFFFF90D7E99588FFFFFF1475A89678BFEA91B89BC0980106000090D7E99588FFFFFFA0EB189188FFFFFFD0A6949488FFFFFF60FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFFCC6179995C75A8966075A896F0313D9560000000701FDE92
09-09 16:44:43.502  4301  3901 W google-breakpad: S 96A87500 4875A896F0313D95B03B3E9503020000000000004075A8968C49799902020000A0FAB09402000000E036549688FFFFFFA0EB189188FFFFFFA0D1E99588FFFFFFDC75A89688AF2A95B48A499901090000A0D1E99588FFFFFFA0EB189188FFFFFFE036549688FFFFFFA0FAB09488FFFFFF0000000082FFFFFF0000000082FFFFFFF0313D9585FFFFFF40D7E99588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFE0AF379588FFFFFFB03B3E9588FFFFFF403F57960100000090000000B0383E95E475A896D475A896B0276F9700000000040000002C78A89660A1EC91000400006036549601000000E036549688FFFFFFA0EB189188FFFFFF0000000082FFFFFF982D6F97A0EB189180383E9550383E950000000087FFFFFFA00F539620383E9550383E95C0AF37959002C29880020000A0365496020000000000000082FFFFFFA00F539688FFFFFF20383E9588FFFFFF9076A89620383E95C0373E95F0373E959C81339980020000E036549600000000C0373E9588FFFFFF
09-09 16:44:43.502  4301  3901 W google-breakpad: S 96A87680 A09C09948A00000007000000B09C099400830DAB40B0529610FF8494E03654962078789903020000403F57960100000040B0529688FFFFFF10FF849485FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000830DABC05ECBB66878A8960100000081FFFFFFC077A8962C78A896646B0797403F579600000000000000009077A8964477A8963877789958DB659700830DAB00C24C96AC88A89600000000000000000000000001000000947FA89600830DAB00010000000000005080339900000000403F5796207CA896020000000100000000000000000000000100000081FFFFFF0000000000000000F87BA896F6FFFFFF0C830DAB0100000000830DABC077A8960000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000006878A89600830DAB203E6F9700525B96000000001823D891
09-09 16:44:43.503  4301  3901 W google-breakpad: S 96A87800 2C78A89686F313F70000000000830DAB6878A8963078A896403F579600525B96000000001823D8915478A8967C0C2597000000000000000000000000C05ECBB60100000000830DAB287CA8966078A896DC7BA896740D2597525CA394FB5DA394287CA89601000000780B65970100000000525B966078A89600000000005EA3940200000002000000010000000000000010B964975C00000006000000000000009887A89600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.503  4301  3901 W google-breakpad: S 96A87980 0000000000000000000000000000000000000000000000000000000000000000000000000054A3940000000000000000010000000200000020AF379500535B96A5820FAB000000000000000086F313F700000000C05ECBB60000000000830DAB18621797F879A896747DA896F80D25970000000000000000187EA8960000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.503  4301  3901 W google-breakpad: S 96A87B00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086F313F7C05ECBB6187CA89600830DABC87CA896287CA8961823D891847CA8963412259700000000000000000000000040B05296287CA896010000000889A896F6FFFFFF0C830DAB0000000000830DAB187CA8960300000008000000403F579688FFFFFF40B0529688FFFFFF10FF849485FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000086F313F70400000000830DABD87CA896C87CA896D07CA896C47CA89682FFFFFF1023D891
09-09 16:44:43.503  4301  3901 W google-breakpad: S 96A87C80 B47CA89688FC14971023D891D07CA89640B0529688FFFFFF387DA896487DA896287EA89601000000E07CA89600000000147DA89650923697D07CA896000000001800000040B05296403F579688FFFFFF0000000082FFFFFF010000001023D8910000000082FFFFFF00830DAB0000000074065097487DA896387DA896800B4F99180E4F9900830DAB287EA89674065097847DA89608A22D97487DA8969C7DA896070000004F0000003C2308927C94C191000000007094C19140B0529688FFFFFF00830DAB0000000010FF849485FFFFFF00830DAB00000000987DA896205F51979D94C191B87DA896287EA896A87DA89600830DAB9C7DA89622000000800B4F99EC7DA8963C122F97ECC74F9758CB4F9758DB6597220000007C94C1911CEA8B9100000000BC7DA8962200000000000000407FA89600000000D47DA89664DCEC96707EA896407FA896C0C36697387EA8960000000001000000287EA896187EA8962200000000830DAB7C7FA896783B32970023D8910000000000830DAB087EA896
09-09 16:44:43.503  4301  3901 W google-breakpad: S 96A87E00 02000000507EA89650EB1891707EA896E0323E9588FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000000830DAB01000000A07FA896B07FA896010000000023D891070000000700000001000000B0FD84940000000000830DAB000000000000000006000000E4C36697E4C3669706000000C0C3669700000000FFFFFFFF000000000823D89122000000B8FD84940700000000000000010000001800609650B2339601000000DC7EA89630521F9707000000B0FD849400830DAB0000000010006096E87EA8961C7FA89638941F97F4E2CBB6BB54C8B6C8042092DC543399507FA896010000008C13E09490373E95E01B6196B0FD849400000000FFFFFFFF50B2339601000000B87FA896805533991080A8962C7FA896787FA8960000000000000000485533994003000001000000FFFFFFFF81FFFFFFB0FD849485FFFFFF1000609685FFFFFFA453D5B44049569688FFFFFF9092319900000000FFFFFFFFC0B2339601000000B87FA896383F7999
09-09 16:44:43.504  4301  3901 W google-breakpad: S 96A87F80 000000008C7FA8968C49799900000000000000009092319942020000010000004049569688FFFFFF00EA529688FFFFFFB0FD849485FFFFFF1480A896C0B233969092319901050000B0FD849485FFFFFF00EA529688FFFFFF4049569688FFFFFF0000000082FFFFFF00000000E80C699140020000000000005000000030BD5296
09-09 16:44:43.504  4301  3901 W google-breakpad: C 060000400040B798000000003C03A896B803A8961003A8966403A89600830DAB3C03A896C072599585FFFFFF800B4F993403A896F802A8960003A896C8D01497CCD0149710000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:44:43.504  4301  3901 W google-breakpad: M B6F0E000 00000000 00005000 E72F8FF84F6E260968CCE78B856F06B70 app_process32
09-09 16:44:43.504  4301  3901 W google-breakpad: M 96C05000 00000000 00A66000 886ECA16DD42F6E0428F775A7DA9BFB00 libjxcore.so
09-09 16:44:43.504  4301  3901 W google-breakpad: M A2525000 007F2000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8925000 00000000 00006000 0D31362517BA6979AC917A35D240E1210 libwebviewchromium_loader.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A89C9000 00000000 00005000 590854A6A5B5D59683870D00EAE455310 libjnigraphics.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A89CE000 00000000 0000A000 4AE1FB560051D628B937E5D0F75C69F30 libcompiler_rt.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A89D8000 00000000 00011000 4CBE9A6CCCBDC8B3EF8B751BC123CEE50 libandroid.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A89E9000 00000000 0000C000 AFC34749768B41E8D431AF946E23577B0 libqservice.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A89F5000 00000000 0000B000 356C1D2029892384AFE121956A0BB4EA0 libqdutils.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A00000 00000000 00005000 95E7634C1A490462E66752EC8939C4530 libqdMetaData.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A05000 00000000 00008000 9997EA703403C3035DE00C7EE7880E430 libmemalloc.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A0D000 00000000 00008000 3FE99556F2945012B0CB1BE7C353A6540 gralloc.msm8084.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A15000 00000000 0000C000 A1BCE730F0644DAE1C5CBC146CD02BD90 eglSubDriverAndroid.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A21000 00000000 00027000 2A6DCFEF23E3A32055F90972FCABFED60 libGLESv1_CM_adreno.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A8A48000 00000000 0073D000 2003920CF0749EC2675D7EE282DE502B0 libllvm-glnext.so
09-09 16:44:43.505  4301  3901 W google-breakpad: M A9196000 00000000 004AD000 3082CAE2C0BC6E87686AEAA07100FEDE0 libGLESv2_adreno.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M A9645000 00000000 0003D000 44E63552D97113055F6017F152FAF0340 libgsl.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M A9682000 00000000 00007000 417C9A0548EF994318FDD8293BD2B4A90 libadreno_utils.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M A968B000 00000000 00013000 B4DF6A0A447291C436FE548566C498C00 libEGL_adreno.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB117000 00000000 0001B000 B0EFA02804790BBB6DE8B2B9095BE9CB0 libkeymaster1.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB132000 00000000 0000B000 D13E1014D51DECF5BF9D21E7C67666130 libkeymaster_messages.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB13D000 00000000 00017000 6658C7A49E3552941CE5496BFD2B34980 libsoftkeymasterdevice.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB154000 00000000 0000E000 25D7B988B89B18BC0429BB562FA2DE990 libkeystore_binder.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB162000 00000000 00006000 B33B16D8A7ED9B8FFB7AA215D6923C4B0 libkeystore-engine.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB168000 00000000 00018000 CEF05C42255586B6905B0AF681C33D8C0 libjavacrypto.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB1C0000 00000000 00010000 0C521B6A6E9E39A0E22193BB5D5525130 libstagefright_amrnb_common.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB1D0000 00000000 0002C000 582DF60B6AA35307BD7198E3A18119AB0 libexif.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB1FC000 00000000 0000D000 7CD678568D893C8FE9A4676BCD58F2AD0 libjhead.so
09-09 16:44:43.506  4301  3901 W google-breakpad: M AB20A000 00000000 00018000 ADA21AF62918F8A878B3FE4F2F0456580 libmtp.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M AB222000 00000000 00048000 0262207412DD5679BF20EB25407B7B440 libmedia_jni.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M AF050000 00000000 00006000 B37EB6398BB0DBE353FE8B1F1DEAB2EB0 memtrack.msm8084.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B06C6000 00000000 00036000 E15D31AAB91199642EB180D3D4160C520 libjavacore.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B3653000 00000000 00007000 79903F128710C73A4159E0E685663A550 libwebviewchromium_plat_support.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B4825000 00000000 00459000 D1BC38C6D191DBFC4B3B8BE9676A2FBB0 libart.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B4D8A000 00000000 00005000 68126D6F94C506C8BE6DAA402968ABD50 libsigchain.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B4DB2000 00000000 00A5C000 0B64AEBAA12EA3FC8CB4E80A5310D9A20 libLLVM.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B5817000 00000000 00038000 EB0128750F7A47E1274CC11D426A63840 libbcinfo.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B584F000 00000000 0005B000 8D9A857B04F62EBCFEC94FC226C49F600 libbcc.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B58AA000 00000000 0000E000 BD9845C69DC7ADC5D6D7E1756D34DD830 libcommon_time_client.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B58B9000 00000000 0001A000 9AC4BF2FD171753488B9C5DB621A9A240 libprotobuf-cpp-lite.so
09-09 16:44:43.507  4301  3901 W google-breakpad: M B58D3000 00000000 00009000 9B164CEF29D3AA5EAF47FA86862586FF0 libstagefright_avc_common.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B58DC000 00000000 00005000 4AA290A61993A8A5677655D665763B3D0 libstagefright_enc_common.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B58E1000 00000000 00007000 5146A8AEEE822B0CE87F523ABAE749F50 libpowermanager.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B58E8000 00000000 0001F000 EF15E47D9893659F6C584D4542F099490 libvorbisidec.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B5907000 00000000 00007000 9C90BE63E61A2127D39B214E6F43AF350 libstagefright_yuv.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B590F000 00000000 00032000 C3AC584E1FF634156E2797138D35375E0 libstagefright_omx.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B5941000 00000000 0003D000 B85FA71D8415B28DE38A933B1508D9F00 libopus.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B597E000 00000000 0000A000 5BEFFA75C748ED7D23421EF091D1F1300 libmediautils.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B5988000 00000000 0001A000 64DF194390054DFAFF82926D89B359340 libdrmframework.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B59A2000 00000000 00021000 A395A730CEF4C5A1BB47058DE0D9186E0 libRScpp.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B59C3000 00000000 00042000 70A461E7FEC54E6D7E1E5C66F936CE350 libRS.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B5A05000 00000000 00009000 FDC63F080EB6155F934F885DEB37E94E0 libspeexresampler.so
09-09 16:44:43.508  4301  3901 W google-breakpad: M B5A0E000 00000000 0000B000 FFD2B97AE5B754AC2E9678225D23B75A0 libnbaio.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5A19000 00000000 00014000 669F5236C39ADF5E46701FF6C9F768980 libpcre.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5A2F000 00000000 00007000 21F0774A2FE026AA52F7480655D27ABE0 libwpa_client.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5A36000 00000000 00071000 C8703400FE46F435C2134FB0F3FDE9390 libGLES_trace.so
,09-09 16:44:43.509  4301  3901 W google-breakpad: M B5AA7000 00000000 00067000 1821F1842FA60DF842F94DF364C495A10 libft2.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5B0E000 00000000 00027000 C5A689AFC30DE04B5E7E5ACBF12CA9330 libpng.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5B35000 00000000 00005000 E0AD90DEBEAFB376EBAA5415267856B40 libsync.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5B3A000 00000000 00007000 F5424CDA56569E38CF2903ECFAFF296E0 libstdc++.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5B41000 00000000 00012000 B4E430E8258C544A786360668D84BE8B0 libunwind.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5B99000 00000000 0000B000 96BB8488669F21FEDA8649403EB8BB0E0 libbase.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5BA4000 00000000 00007000 D32E249CC58B3A22906A78EDFDD545460 libeffects.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5BAC000 00000000 00006000 1964BC7CB1EF496E207C18FC55A57E6C0 libstagefright_http_support.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5BB2000 00000000 0001B000 4E010519E1AA1D9D10F586E0C0490F120 libstagefright_foundation.so
09-09 16:44:43.509  4301  3901 W google-breakpad: M B5BCD000 00000000 0015B000 009817DD6F2FD8255E5AAE0FDE05646B0 libstagefright.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5D28000 00000000 00070000 4054B4690025F8746C0DC28CC9D69D870 libhwui.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5D98000 00000000 00005000 9CA9EF8816A2E0C106C15197423A91AE0 libradio_metadata.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5D9D000 00000000 00006000 F1863EB76C05E59645A8AA848D1624570 libnativebridge.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DA3000 00000000 00006000 1D210F6A59079D7FD7F258724A88DEA70 libprocessgroup.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DA9000 00000000 00011000 FDCAD8835C0C336BEB30CF765069FC3A0 libminikin.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DBA000 00000000 0000E000 238BED0ADF305646BB994A7A676D0A1E0 libsoundtrigger.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DC9000 00000000 0000E000 00FDCB77534A86A2594207ABA92E7FBF0 libradio.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DD7000 00000000 00006000 BBCF64A69A9F42E7BC0E0BD423E728790 libnetd_client.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DDD000 00000000 00010000 727E80AEB01F5239858F79470BB43E850 libimg_utils.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B5DED000 00000000 00420000 2D9D72FD541F8A7DFBF9302532B5F3870 libpdfium.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B620E000 00000000 00009000 25B29975558839100CC6E366D29212350 libaudioutils.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B6217000 00000000 0001D000 DFED0D6F37875A07335517F4E69925120 libz.so
09-09 16:44:43.510  4301  3901 W google-breakpad: M B6235000 00000000 0004E000 66D92DD691765147492F9C21B6AD68960 libharfbuzz_ng.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6283000 00000000 00007000 9008C23BFACF1EF1DDF142956BF976490 libusbhost.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B628A000 00000000 0003A000 2D00674AA1DD3C58C05B175DD18EE6050 libjpeg.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B62C5000 00000000 000AD000 A52E62FD0AC67AE14A01E7E4847F17620 libmedia.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6372000 00000000 0017F000 14D5DC468D2218AA5F70C2F6FC6EBBF90 libicui18n.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B64F1000 00000000 00123000 0990D8BD31465D945F9282189239AB8F0 libicuuc.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6618000 00000000 00026000 C4AA0ABF6C41A8583C0E373BD8CA4EE70 libssl.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B663E000 00000000 0009D000 A14F571CD9F3F8B6362ACC34BB5E42CA0 libcrypto.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B66DB000 00000000 00056000 23B95E0161A14BC00A49FE4C0126E1CF0 libsonivox.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6736000 00000000 00011000 87F28481D7D1980E2971DFAD611952AA0 libselinux.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6747000 00000000 00008000 4E213F2F80F006F539A0A0DBEC2228870 libhardware_legacy.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6750000 00000000 00005000 4025C8440BDADD37826842A415EF9BFF0 libhardware.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B6755000 00000000 00006000 0CBDCDD7DFB535EB3876F8035637EAC00 libETC1.so
09-09 16:44:43.511  4301  3901 W google-breakpad: M B675B000 00000000 0000F000 A7B07D10AF426644931390FF2ABC2FEC0 libGLESv2.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B676A000 00000000 0000A000 1B33374FB686F15B59530546D8DB39640 libGLESv1_CM.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6774000 00000000 00068000 DAD11DC7527BFB7648299C3DE956986E0 libEGL.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B67DF000 00000000 00065000 E94A253EBAA34A7F995352FCEE8DD0D50 libsqlite.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6845000 00000000 0026E000 71785D4C7316B73D74AB9E39653907830 libskia.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6AB7000 00000000 0000A000 306A2E96AB94641A8076D9195DA933FF0 libcamera_metadata.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6AC1000 00000000 0002D000 7CA8B61C54BAAABF07F3C7847D490E9F0 libcamera_client.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6AEE000 00000000 00040000 6C63D1A1ED4626296733EE132307BF6E0 libinputflinger.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6B2E000 00000000 0001F000 112B3314840A32B638874B51553126190 libinput.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6B4D000 00000000 0005A000 D55348C7DD771E9409BFBF09AB5AAD720 libgui.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6BA7000 00000000 00010000 10F3AFD84F2FA6D8D59A78E2331D8AC50 libui.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6BB7000 00000000 00009000 8AAEFDEA9747BCF61A977E5DDA0D22620 libnetutils.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6BC0000 00000000 00009000 6C034766ACADC7459DB1EE108B8DDDC70 libnativehelper.so
09-09 16:44:43.512  4301  3901 W google-breakpad: M B6BC9000 00000000 00017000 410352CE283FD8305E8A2FD783B3C8160 libexpat.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6BE0000 00000000 0002A000 41777DBC877E41A9712DDD4792610E7A0 libandroidfw.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6C0A000 00000000 00005000 EC03C38C8A2A3C11A25493EEEE8E58C20 libmemtrack.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6C0F000 00000000 0000B000 6AC6874E2835174DF0B2E6A2BB3511ED0 libbacktrace.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6C1A000 00000000 00022000 771243F4B38A04911D7E2EFFC103E81F0 libm.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6C3C000 00000000 00079000 C45DDC3AA3778947F27583335C11C7260 libc.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6CBF000 00000000 0008E000 4F01D021AD7772AE25722B88EF500DF60 libc++.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6D4E000 00000000 0002D000 C02C38CB58D679FECB52E59A954B4AAD0 libwilhelm.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6D7B000 00000000 000DC000 ACD6E6927F2247CE8E5F68E6F5579F0E0 libandroid_runtime.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6E5C000 00000000 0002E000 1E5AD4B0BC139C0D5814F52EEC059E2E0 libbinder.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6E8A000 00000000 0000A000 F2FDFCED2E85559AC020655D564D0FFC0 liblog.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6E94000 00000000 0001B000 4E3DF0460B95A69E7A1D4ABE2D8C0A690 libutils.so
09-09 16:44:43.513  4301  3901 W google-breakpad: M B6EAF000 00000000 00011000 78F0BD9C3BF5DE7183A84BD26875408C0 libcutils.so
09-09 16:44:43.514  4301  3901 W google-breakpad: M B6EEC000 00000000 00020000 C98C597B4AE800CFB3F0589DF3EDED980 linker
09-09 16:44:43.514  4301  3901 W google-breakpad: -----END BREAKPAD MICRODUMP-----
09-09 16:44:43.535  3854  3901 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-09 16:44:43.535  3854  3901 W google-breakpad: Chrome build fingerprint:
09-09 16:44:43.535  3854  3901 W google-breakpad: 0.0.1
09-09 16:44:43.535  3854  3901 W google-breakpad: 19
09-09 16:44:43.535  3854  3901 W google-breakpad: 6ec9b36e-71c4-4d7b-882c-6b145c858100
09-09 16:44:43.535  3854  3901 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-09 16:44:43.536  3854  3901 E chromium: ### WebView Version 44.0.2403.117 (code 246011700)
--------- beginning of crash
09-09 16:44:43.536  3854  3901 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 3901 (Thread-330)
,09-09 16:44:43.648   374   374 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,09-09 16:44:43.648   374   374 F DEBUG   : Build fingerprint: 'google/shamu/shamu:6.0.1/MOB30M/2862625:user/release-keys'
,09-09 16:44:43.649   374   374 F DEBUG   : Revision: '0'
,09-09 16:44:43.649   374   374 F DEBUG   : ABI: 'arm'
,09-09 16:44:43.650   374   374 F DEBUG   : pid: 3854, tid: 3901, name: Thread-330  >>> com.test.thalitest <<<
,09-09 16:44:43.651   374   374 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,09-09 16:44:43.682   374   374 F DEBUG   :     r0 98b74000  r1 00000000  r2 96a8033c  r3 96a803b8
,09-09 16:44:43.682   374   374 F DEBUG   :     r4 96a80310  r5 96a80364  r6 ab0d8300  r7 96a8033c
,09-09 16:44:43.683   374   374 F DEBUG   :     r8 955972c0  r9 ffffff85  sl 994f0b80  fp 96a80334
,09-09 16:44:43.683   374   374 F DEBUG   :     ip 96a802f8  sp 96a80300  lr 9714d0c8  pc 9714d0cc  cpsr 200f0010
,09-09 16:44:43.687   374   374 F DEBUG   : 
09-09 16:44:43.687   374   374 F DEBUG   : backtrace:
,09-09 16:44:43.688   374   374 F DEBUG   :     #00 pc 005480cc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
,09-09 16:44:43.688   374   374 F DEBUG   :     #01 pc 0054856c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
,09-09 16:44:43.688   374   374 F DEBUG   :     #02 pc 00762e84  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,09-09 16:44:44.162   874   890 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,09-09 16:44:44.171   874  4303 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-09 16:44:44.179   874  4303 I ActivityManager: Killing 2150:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 16:44:44.198  4302  4302 I         : debuggerd: starting
,09-09 16:44:45.349   874  1318 D ConnectivityService: handlePromptUnvalidated 102
,09-09 16:44:54.253   874   887 W ActivityManager: Activity destroy timeout for ActivityRecord{fa35eee u0 com.test.thalitest/.MainActivity t4 f}
,09-09 16:44:58.838  1888  1915 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-09 16:44:58.838  1888  1915 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 16:44:58.898  1518  1518 I ConfigService: onCreate
,09-09 16:45:03.984  1518  1518 I ConfigService: onDestroy
,09-09 16:45:07.468   874   874 I ActivityManager: Start proc 4306:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-09 16:45:07.527  4306  4306 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-09 16:45:07.540  3579  4318 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:45:07.567  1888  1888 I Keyboard.Facilitator: onFinishInput()
,09-09 16:45:07.577  4306  4306 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-09 16:45:07.577  4306  4306 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:45:07.577  4306  4306 I GAv4    :   adb logcat -s GAv4
,09-09 16:45:07.595  3579  4320 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:45:07.603  4306  4306 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:45:07.615  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:07.617  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:07.646  4306  4306 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:45:07.662  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:45:07.662  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 16:45:07.663  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:45:07.663  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:45:07.688  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:07.689  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:07.707  4306  4323 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:45:07.713  1518  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:45:07.713  1518  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:45:07.713  1518  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:45:07.713  1518  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:45:07.732  3579  4320 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:45:07.735  3579  4318 E BooksSync: Soft error
09-09 16:45:07.735  3579  4318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:45:07.735  3579  4318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:45:07.735  3579  4318 E BooksSync: Sync error
09-09 16:45:07.735  3579  4318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:45:07.735  3579  4318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:45:07.735  3579  4318 I BooksSync: Finished books sync
,09-09 16:45:07.756   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248513, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:45:07.762   874   884 I ActivityManager: Killing 3737:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 16:45:18.141   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285778, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:45:38.272  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:38.277  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:45:38.324  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:45:38.324  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 16:45:38.324  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:45:38.324  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:45:38.345  3538  4332 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:45:38.345  3538  4332 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:45:38.345  3538  4332 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	... 12 more
09-09 16:45:38.345  3538  4332 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at fal.a(PG:38)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:45:38.345  3538  4332 E HttpOperation: 	... 14 more
,09-09 16:45:38.413  1518  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:45:38.413  1518  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:45:38.413  1518  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:45:38.413  1518  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:45:38.437  3538  4332 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:45:38.437  3538  4332 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at hec.a(PG:42)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at hee.a(PG:102)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at czr.a(PG:65)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at kka.a(PG:108)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:45:38.437  3538  4332 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	... 15 more
09-09 16:45:38.437  3538  4332 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at fal.a(PG:38)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:45:38.437  3538  4332 E HttpOperation: 	... 17 more
,09-09 16:45:38.438  3538  4332 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:45:38.438  3538  4332 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	... 15 more
09-09 16:45:38.438  3538  4332 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:45:38.438  3538  4332 E ExperimentLoader: 	... 17 more
,09-09 16:45:38.600   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 282683, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:46:07.609  1888  1915 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-09 16:46:07.609  1888  1915 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 16:46:07.643  1518  1518 I ConfigService: onCreate
,09-09 16:46:08.843  3579  4337 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:46:08.897  3579  4339 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:46:08.908  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:08.911  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:08.969  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:46:08.969  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:46:08.969  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:46:08.969  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 16:46:08.970  3027  4338 V KeepSync: Connecting to GoogleApiClient
,09-09 16:46:08.970   874  2007 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:46:09.045  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:09.049  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:09.095  1518  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:46:09.095  1518  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:46:09.095  1518  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:46:09.095  1518  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:09.108  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:46:09.108  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:46:09.108  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:46:09.108  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:09.131  3579  4339 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:46:09.132  3579  4337 E BooksSync: Soft error
09-09 16:46:09.132  3579  4337 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:46:09.132  3579  4337 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:46:09.132  3579  4337 E BooksSync: Sync error
09-09 16:46:09.132  3579  4337 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:46:09.132  3579  4337 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:46:09.132  3579  4337 I BooksSync: Finished books sync
,09-09 16:46:09.153   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 306579, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:46:09.159  1727  4340 V BaseAuthAsyncOperation: access token request failed
,09-09 16:46:09.162  3027  4338 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:46:09.231  1518  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 16:46:09.231  1518  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:46:09.231  1518  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:46:09.231  1518  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:09.247  3027  4338 E KeepSync: IOException
09-09 16:46:09.247  3027  4338 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:46:09.247  3027  4338 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:46:09.247  3027  4338 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:46:09.247  3027  4338 E KeepSync: 	... 10 more
,09-09 16:46:09.247  3027  4338 W KeepSync: Sync result 2
,09-09 16:46:09.264   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 320050, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:46:12.683  1518  1518 I ConfigService: onDestroy
,09-09 16:46:14.476  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:14.496  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:14.504  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:14.573  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 16:46:14.573  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-09 16:46:14.573  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:46:14.574  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:14.615  1518  1529 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 16:46:14.615  1518  1529 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 16:46:14.633  3500  3530 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 16:46:14.633  3500  3530 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 16:46:14.633  3500  3530 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 16:46:14.633  3500  3530 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 16:46:14.633  3500  3530 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 16:46:14.633  3500  3530 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 16:46:14.633  3500  3530 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 16:46:19.679   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:46:39.596  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:39.597  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:46:39.641  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:46:39.641  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:46:39.641  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:46:39.642  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:39.676  3538  4346 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:46:39.676  3538  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:46:39.676  3538  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	... 12 more
09-09 16:46:39.676  3538  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at fal.a(PG:38)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:46:39.676  3538  4346 E HttpOperation: 	... 14 more
,09-09 16:46:39.749  1518  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:46:39.749  1518  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:46:39.749  1518  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:46:39.749  1518  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:46:39.768  3538  4346 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:46:39.768  3538  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at hec.a(PG:42)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at hee.a(PG:102)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at czr.a(PG:65)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at kka.a(PG:108)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:46:39.768  3538  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	... 15 more
09-09 16:46:39.768  3538  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at fal.a(PG:38)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:46:39.768  3538  4346 E HttpOperation: 	... 17 more
09-09 16:46:39.769  3538  4346 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:46:39.769  3538  4346 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	... 15 more
09-09 16:46:39.769  3538  4346 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:46:39.769  3538  4346 E ExperimentLoader: 	... 17 more
,09-09 16:46:39.934   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 339113, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:46:55.346   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=382984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:47:07.744  1518  2129 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 16:47:10.088  3027  4350 V KeepSync: Connecting to GoogleApiClient
,09-09 16:47:10.089   874  2192 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:47:10.148  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:10.150  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:10.192  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:47:10.193  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:47:10.193  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:47:10.193  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:47:10.224  1727  4351 V BaseAuthAsyncOperation: access token request failed
,09-09 16:47:10.226  3027  4350 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:47:10.292  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:47:10.292  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:47:10.293  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:47:10.293  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:47:10.317  3027  4350 E KeepSync: IOException
09-09 16:47:10.317  3027  4350 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:47:10.317  3027  4350 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:47:10.317  3027  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:47:10.317  3027  4350 E KeepSync: 	... 10 more
,09-09 16:47:10.318  3027  4350 W KeepSync: Sync result 2
,09-09 16:47:10.332   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 368369, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:47:22.373   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:47:40.513  3579  4353 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:47:40.563  3579  4354 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:47:40.580  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:40.584  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:40.632  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:47:40.632  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:47:40.633  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:47:40.633  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:47:40.684  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:40.690  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:47:40.737  1518  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:47:40.738  1518  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 16:47:40.738  1518  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:47:40.738  1518  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:47:40.764  3579  4354 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:47:40.766  3579  4353 E BooksSync: Soft error
09-09 16:47:40.766  3579  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:47:40.766  3579  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:47:40.766  3579  4353 E BooksSync: Sync error
09-09 16:47:40.766  3579  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:47:40.766  3579  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:47:40.766  3579  4353 I BooksSync: Finished books sync
,09-09 16:47:40.779   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 399161, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:48:02.656   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=450293, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:48:11.208  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:48:11.209  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:48:11.241  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:48:11.241  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:48:11.241  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:48:11.241  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:48:11.266  3538  4358 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:48:11.266  3538  4358 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:48:11.266  3538  4358 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	... 12 more
09-09 16:48:11.266  3538  4358 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at fal.a(PG:38)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:48:11.266  3538  4358 E HttpOperation: 	... 14 more
,09-09 16:48:11.399  1518  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 16:48:11.399  1518  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 16:48:11.399  1518  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:48:11.400  1518  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:48:11.426  3538  4358 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:48:11.426  3538  4358 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at hec.a(PG:42)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at hee.a(PG:102)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at czr.a(PG:65)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at kka.a(PG:108)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:48:11.426  3538  4358 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	... 15 more
09-09 16:48:11.426  3538  4358 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at fal.a(PG:38)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:48:11.426  3538  4358 E HttpOperation: 	... 17 more
,09-09 16:48:11.426  3538  4358 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:48:11.426  3538  4358 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	... 15 more
09-09 16:48:11.426  3538  4358 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:48:11.426  3538  4358 E ExperimentLoader: 	... 17 more
,09-09 16:48:11.560   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 433320, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:48:25.642   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=473279, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:48:41.832  3027  4362 V KeepSync: Connecting to GoogleApiClient
,09-09 16:48:41.832   874  1385 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:48:41.898  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:48:41.904  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:48:41.959  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:48:41.959  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:48:41.960  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:48:41.960  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:48:41.998  1727  4363 V BaseAuthAsyncOperation: access token request failed
,09-09 16:48:42.000  3027  4362 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:48:42.083  1518  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:48:42.084  1518  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:48:42.084  1518  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:48:42.084  1518  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:48:42.121  3027  4362 E KeepSync: IOException
09-09 16:48:42.121  3027  4362 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:48:42.121  3027  4362 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:48:42.121  3027  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:48:42.121  3027  4362 E KeepSync: 	... 10 more
,09-09 16:48:42.121  3027  4362 W KeepSync: Sync result 2
,09-09 16:48:42.134   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 460905, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:49:05.909   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513546, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:49:42.496   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=550134, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:49:45.579  3579  4366 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:49:45.605  3579  4367 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:49:45.622  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:49:45.627  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:49:45.674  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:49:45.674  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:49:45.674  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:49:45.674  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:49:45.726  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:49:45.731  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:49:45.784  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:49:45.784  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:49:45.784  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:49:45.785  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:49:45.821  3579  4367 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:49:45.823  3579  4366 E BooksSync: Soft error
09-09 16:49:45.823  3579  4366 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:49:45.823  3579  4366 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:49:45.827  3579  4366 E BooksSync: Sync error
09-09 16:49:45.827  3579  4366 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:49:45.827  3579  4366 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:49:45.827  3579  4366 I BooksSync: Finished books sync
,09-09 16:49:45.840   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 553158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:50:22.709   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590346, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:50:23.360  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:50:23.362  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:50:23.405  1518  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:50:23.405  1518  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:50:23.405  1518  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:50:23.406  1518  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:50:23.427  3538  4370 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:50:23.427  3538  4370 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:50:23.427  3538  4370 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	... 12 more
09-09 16:50:23.427  3538  4370 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at fal.a(PG:38)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:50:23.427  3538  4370 E HttpOperation: 	... 14 more
,09-09 16:50:23.509  1518  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:50:23.509  1518  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:50:23.509  1518  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:50:23.509  1518  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:50:23.532  3538  4370 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:50:23.532  3538  4370 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at hec.a(PG:42)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at hee.a(PG:102)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at czr.a(PG:65)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at kka.a(PG:108)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:50:23.532  3538  4370 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	... 15 more
09-09 16:50:23.532  3538  4370 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at fal.a(PG:38)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:50:23.532  3538  4370 E HttpOperation: 	... 17 more
,09-09 16:50:23.532  3538  4370 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:50:23.532  3538  4370 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	... 15 more
09-09 16:50:23.532  3538  43,70 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:50:23.532  3538  4370 E ExperimentLoader: 	... 17 more
,09-09 16:50:23.700   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 590694, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:50:41.587   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=609224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:50:53.884  3027  4373 V KeepSync: Connecting to GoogleApiClient
,09-09 16:50:53.885   874  2000 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:50:53.959  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:50:53.964  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:50:54.003  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:50:54.004  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:50:54.004  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:50:54.004  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:50:54.030  1727  4374 V BaseAuthAsyncOperation: access token request failed
,09-09 16:50:54.032  3027  4373 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:50:54.106  1518  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:50:54.107  1518  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:50:54.107  1518  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:50:54.107  1518  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:50:54.131  3027  4373 E KeepSync: IOException
09-09 16:50:54.131  3027  4373 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:50:54.131  3027  4373 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:50:54.131  3027  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:50:54.131  3027  4373 E KeepSync: 	... 10 more
,09-09 16:50:54.131  3027  4373 W KeepSync: Sync result 2
,09-09 16:50:54.142   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 615641, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:51:21.907   874  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=649544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 17:00:50.587   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
