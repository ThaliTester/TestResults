#### Test 83070177a758936_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 13:51:47.417  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:51:47.431  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:51:47.436  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:51:47.481  1522  2216 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 13:51:47.481  1522  2216 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:51:47.481  1522  2216 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:51:47.481  1522  2216 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:51:47.530  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 13:51:47.531  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:51:47.531  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
09-12 13:51:48.099  3969  3969 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 13:51:48.104  3969  3969 D AndroidRuntime: CheckJNI is OFF
09-12 13:51:48.147  3969  3969 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 13:51:48.197  3969  3969 I Radio-JNI: register_android_hardware_Radio DONE
09-12 13:51:48.219  3969  3969 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 13:51:48.224   873  1933 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 13:51:48.291   873  1933 I ActivityManager: Start proc 3978:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 13:51:48.298  3969  3969 D AndroidRuntime: Shutting down VM
09-12 13:51:48.412  3978  3978 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 13:51:48.442  3978  3978 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 13:51:48.449  3978  3978 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3070-3073)
09-12 13:51:48.449  3978  3978 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:51:48.461  3978  3978 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9472ae9}
09-12 13:51:48.462  3978  3978 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:51:48.463  3978  3978 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:51:48.471  3978  3978 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 13:51:48.472  3978  3978 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 13:51:48.495  3978  3978 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 13:51:48.518  3978  3978 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:51:48.519  3978  3978 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:51:48.519  3978  3978 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:51:48.519  3978  3978 I Adreno  : Build Date                       : 10/20/15
09-12 13:51:48.519  3978  3978 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:51:48.519  3978  3978 I Adreno  : Local Branch                     : M14
09-12 13:51:48.519  3978  3978 I Adreno  : Remote Branch                    : 
09-12 13:51:48.519  3978  3978 I Adreno  : Remote Branch                    : 
09-12 13:51:48.519  3978  3978 I Adreno  : Reconstruct Branch               : 
,09-12 13:51:48.564   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aee757:true
,09-12 13:51:48.601  3978  3978 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:51:48.613  3978  3978 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 13:51:48.677  3978  4015 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 13:51:48.696  3978  4002 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 13:51:48.735  3978  4015 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:51:48.782   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +428ms (total +533ms)
,09-12 13:51:48.785  1870  1870 I Keyboard.Facilitator: onFinishInput()
,09-12 13:51:48.823  3978  3978 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3978
,09-12 13:51:48.894  3978  3978 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:51:49.084  3978  4017 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1683490512
,09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:51:49.092  3978  4017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca1f4 added. We now have 1 listener(s)
,09-12 13:51:49.096  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 13:51:49.097  3978  4017 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:51:49.097  3978  4017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:51:49.098  3978  4017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 13:51:49.101  3978  4017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@655d963 added. We now have 1 listener(s)
09-12 13:51:49.101  3978  4017 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:51:49.109   873  1307 D WifiService: New client listening to asynchronous messages
,09-12 13:51:49.110  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:51:49.110  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 13:51:49.110  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 13:51:49.110  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:51:49.110  3978  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 13:51:49.114  3978  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:51:49.114  3978  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 13:51:49.125  3978  4017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:51:49.127  3978  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:51:49.127  3978  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 13:51:49.127  3978  4017 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:51:49.130  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:51:49.130  3978  4017 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:51:49.132  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:51:49.186  3978  3978 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:51:50.046  3978  4025 W jxcore-log: Initializing JXcore engine
,09-12 13:51:50.046  3978  4025 W jxcore-log: JXcore engine is ready
,09-12 13:51:50.083  4025  4025 W Thread-346: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9328 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 13:51:50.083  4025  4025 W Thread-346: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10563]" dev="sockfs" ino=10563 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 13:51:50.083  4025  4025 W Thread-346: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 13:51:50.083  4025  4025 W Thread-346: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27718]" dev="sockfs" ino=27718 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 13:51:50.099  3978  4025 W jxcore-log: Starting JXcore engine
,09-12 13:51:50.180  3978  4025 W jxcore-log: Platform android
09-12 13:51:50.180  3978  4025 W jxcore-log: 
09-12 13:51:50.180  3978  4025 W jxcore-log: Process ARCH arm
09-12 13:51:50.180  3978  4025 W jxcore-log: 
,09-12 13:51:50.371  3978  4025 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:51:50.371  3978  4025 I jxcore-log: 
,09-12 13:51:50.372  3978  4025 W jxcore-log: JXcore engine is started
,09-12 13:51:50.382  3978  4017 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:51:50.388  3978  3978 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:52:00.188  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:52:00.188  3978  4025 I jxcore-log: 
,09-12 13:52:00.190  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:52:00.190  3978  4025 I jxcore-log: 
,09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:00.200  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:52:00.205  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:52:00.207  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:52:00.207  3978  4025 I jxcore-log: 
,09-12 13:52:00.209  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:52:00.209  3978  4025 I jxcore-log: 
,09-12 13:52:00.603   873  3935 D NetlinkSocketObserver: NeighborEvent{elapsedMs=215227, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:52:00.716  3978  4025 D executeNativeTests: Running unit tests
,09-12 13:52:00.774  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:52:00.774  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 added. We now have 2 listener(s)
09-12 13:52:00.775  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:52:00.775  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:52:00.775  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:52:00.775  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:00.776  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad added. We now have 2 listener(s)
,09-12 13:52:00.776  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:00.777  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:52:00.780  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:00.800  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:52:00.802  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:52:00.802  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:00.804  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:52:00.805  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:52:00.805  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:52:00.806  3978  4025 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 13:52:00.806  3978  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 13:52:00.806  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:52:00.806  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:52:00.806  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:52:00.807  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:00.807  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:00.807  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:00.808  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:00.808  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.808  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:00.808  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:00.808  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 removed from the list
,09-12 13:52:00.808  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.808  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad removed from the list
09-12 13:52:00.810  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.816  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.817  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:00.817  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.818  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:00.818  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.819  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:00.819  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:00.819  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.819  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:00.821  3978  4025 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 13:52:00.822  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:00.822  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:00.822  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:00.822  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:00.822  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.822  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.822  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:00.822  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.823  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:00.823  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:00.823  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.823  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.823  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.823  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.825  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:52:00.825  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:00.825  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:00.825  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:52:00.830  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:52:00.831  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:52:00.832  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:00.832  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:00.832  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:00.832  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:00.832  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 13:52:00.832  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:00.832  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:00.832  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:00.832  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:00.832  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:00.832  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.832  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:00.832  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.832  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:00.834  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:00.834  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:00.835  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:00.835  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:00.835  3978  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:52:00.837  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:00.843  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:00.846  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.846  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:00.846  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:00.847  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:52:00.847  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:52:00.847  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:00.847  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:00.856  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:00.856  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:52:00.858  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.879  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 13:52:00.880  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:52:00.882  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:52:00.882  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:52:00.884  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 13:52:00.886  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 13:52:00.886  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:52:00.887  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:52:00.887  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:52:00.890  3978  4025 D BluetoothAdapter: STATE_ON
,09-12 13:52:00.895  2617  2629 D BtGatt.GattService: registerClient() - UUID=9a097f9e-0bdf-4107-bb4d-869f27d301aa
,09-12 13:52:00.896  2617  2649 D BtGatt.GattService: onClientRegistered() - UUID=9a097f9e-0bdf-4107-bb4d-869f27d301aa, clientIf=5
09-12 13:52:00.897  3978  3988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:52:00.898  2617  2744 D BtGatt.GattService: start scan with filters
,09-12 13:52:00.901  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:52:00.901  2617  2652 D BtGatt.ScanManager: handling starting scan
09-12 13:52:00.901  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:52:00.901  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:52:00.901  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:52:00.902  2617  2652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:00.904  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:52:00.904  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:52:00.905  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:52:00.906  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:52:00.909  3978  4025 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:52:00.910  2617  2649 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:00.910  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.911  2617  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:52:00.913  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:00.913  3978  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:52:00.914  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:00.914  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:52:00.914  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:00.914  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:52:00.914  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:52:00.914  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:52:00.914  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:00.914  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:52:00.914  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:52:00.914  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:52:00.915  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:00.916  2617  2627 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:52:00.917  2617  2629 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:52:00.918  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:52:00.918  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:52:00.918  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:00.918  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:52:00.918  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:00.918  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:52:00.919  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.919  2617  2652 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:52:00.919  2617  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:52:00.920  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:52:00.921  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:52:00.921  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:00.921  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:52:00.922  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:52:00.924  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:00.924  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:00.924  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:00.924  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:00.925  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.925  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:00.925  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
,09-12 13:52:00.925  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.925  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:00.926  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:00.926  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:00.927  3978  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:52:00.930  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:00.932  2617  2649 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:52:00.932  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:00.936  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:52:00.939  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.939  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:52:00.939  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:00.939  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:00.939  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:00.939  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:52:00.939  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:52:00.939  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:00.939  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:00.942  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.943  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:00.943  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:52:00.944  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.947  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:52:00.948  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:52:00.948  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:52:00.948  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:00.948  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.949  2617  2652 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:52:00.954  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:52:00.954  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:52:00.954  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:52:00.955  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:00.955  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:52:00.956  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.956  2617  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:52:00.958  2617  2745 D BtGatt.GattService: registerClient() - UUID=3cb0d570-b012-4693-92cf-a2fa318f4dd6
,09-12 13:52:00.959  2617  2649 D BtGatt.GattService: onClientRegistered() - UUID=3cb0d570-b012-4693-92cf-a2fa318f4dd6, clientIf=5
,09-12 13:52:00.959  3978  3988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:52:00.959  2617  2732 D BtGatt.GattService: start scan with filters
,09-12 13:52:00.962  2617  2649 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:00.962  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:00.963  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:52:00.963  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:52:00.963  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:52:00.963  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:52:00.964  2617  2652 D BtGatt.ScanManager: handling starting scan
09-12 13:52:00.966  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:00.966  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:00.966  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:52:00.968  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:52:00.971  3978  4025 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:52:00.971  2617  2649 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:00.971  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.971  2617  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:52:00.974  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:00.974  3978  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:52:00.974  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:00.974  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:52:00.974  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:00.974  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:52:00.974  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:52:00.974  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:52:00.974  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:00.974  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:52:00.975  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:52:00.975  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:52:00.975  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:00.976  2617  2744 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:52:00.977  2617  2745 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:52:00.977  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:52:00.977  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:52:00.977  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:52:00.977  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:00.977  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:00.977  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:52:00.977  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:00.977  2617  2652 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:52:00.978  2617  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:52:00.979  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:52:00.979  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:52:00.979  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:00.979  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:52:00.980  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:00.981  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:00.981  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:52:00.981  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:00.981  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:00.981  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:00.981  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:00.981  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:00.982  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.982  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:00.982  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:00.982  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.982  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:00.982  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:00.983  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:00.984  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:00.984  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:00.984  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:00.984  3978  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:52:00.986  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:00.990  2617  2649 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:52:00.990  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:00.991  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:52:00.993  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:52:00.993  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:00.994  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:00.994  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:52:00.994  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:52:00.994  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:00.994  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:00.996  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:00.997  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:52:00.997  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:00.998  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:00.998  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:52:01.001  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:01.004  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:52:01.005  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:52:01.005  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:52:01.006  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:01.006  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.006  2617  2652 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:52:01.009  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:52:01.009  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:52:01.010  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:52:01.010  3978  4025 D BluetoothAdapter: STATE_ON
,09-12 13:52:01.012  2617  2744 D BtGatt.GattService: registerClient() - UUID=ebbb180a-c6b9-42c1-8327-90f11b74c48c
,09-12 13:52:01.013  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:52:01.013  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.013  2617  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:52:01.013  2617  2649 D BtGatt.GattService: onClientRegistered() - UUID=ebbb180a-c6b9-42c1-8327-90f11b74c48c, clientIf=5
,09-12 13:52:01.014  3978  3989 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:52:01.015  2617  2732 D BtGatt.GattService: start scan with filters
,09-12 13:52:01.019  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:52:01.019  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:52:01.019  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:52:01.019  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:52:01.020  2617  2649 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:01.020  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:01.021  2617  2652 D BtGatt.ScanManager: handling starting scan
,09-12 13:52:01.022  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:52:01.022  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:01.023  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:52:01.025  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:52:01.028  3978  4025 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:52:01.028  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:01.028  3978  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:52:01.028  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:01.028  2617  2649 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:01.029  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:52:01.029  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.029  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.029  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:52:01.029  2617  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:52:01.029  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:52:01.029  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:52:01.029  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:01.029  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:52:01.029  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:52:01.030  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:52:01.030  3978  4025 D BluetoothAdapter: STATE_ON
,09-12 13:52:01.031  2617  2744 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:52:01.032  2617  2732 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:52:01.032  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:52:01.032  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:52:01.033  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:01.033  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:52:01.033  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:01.034  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:01.035  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:52:01.035  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:01.035  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:52:01.035  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:52:01.036  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:52:01.036  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.036  2617  2652 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:52:01.036  2617  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:52:01.037  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:52:01.037  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:01.037  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:01.037  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.038  3978  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:52:01.038  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.038  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:01.038  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.038  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.038  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:01.038  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.038  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.039  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.039  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:01.039  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.039  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.039  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.040  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:52:01.040  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.040  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.041  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.041  3978  4025 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 13:52:01.042  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.042  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.042  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.042  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.042  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.042  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.042  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.043  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.043  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:01.043  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.043  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.043  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.043  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.043  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.044  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.044  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:01.044  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.044  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.045  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:52:01.045  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.045  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.045  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.046  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.046  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.046  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.046  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.046  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.046  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.047  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.047  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.047  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.047  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.047  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.048  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.048  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.048  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.048  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:01.049  3978  4025 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:52:01.049  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.049  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.049  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:01.049  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:52:01.050  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.050  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:01.050  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.050  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:01.050  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.050  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.050  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.050  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:01.050  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.050  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.051  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.051  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:01.051  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.051  2617  2649 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:52:01.051  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.051  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:01.052  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:52:01.052  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.053  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:01.053  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:01.053  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.053  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.053  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.053  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
,09-12 13:52:01.054  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:01.054  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:01.054  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.054  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.054  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.054  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.054  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.055  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:52:01.055  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.055  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:01.056  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
,09-12 13:52:01.057  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:52:01.058  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:52:01.059  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 13:52:01.059  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:52:01.059  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
,09-12 13:52:01.059  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:52:01.059  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.060  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:52:01.060  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:01.060  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:01.061  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.061  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.063  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.063  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:01.063  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
,09-12 13:52:01.063  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.063  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.063  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.064  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.064  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.064  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.064  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.065  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.065  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:01.065  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.065  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.066  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:52:01.067  3978  4025 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-12 13:52:01.068  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:52:01.068  2617  2649 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:01.068  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.068  2617  2652 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:52:01.074  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 13:52:01.074  3978  4025 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:52:01.074  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:52:01.075  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:52:01.076  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-12 13:52:01.076  2617  2649 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:52:01.077  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:52:01.077  2617  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-12 13:52:01.077  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:52:01.077  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:52:01.078  3978  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:52:01.078  3978  4025 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:52:01.078  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:52:01.078  3978  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:52:01.078  3978  4025 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:52:01.078  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:52:01.078  3978  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-12 13:52:01.078  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:52:01.082  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:52:01.083  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:52:01.083  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 13:52:01.083  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-12 13:52:01.083  2617  2649 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:01.083  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:52:01.084  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-12 13:52:01.084  2617  2649 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:01.084  3978  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:52:01.084  3978  4025 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:52:01.084  3978  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 410)
,09-12 13:52:01.084  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:01.084  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.084  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.085  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.085  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:01.085  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:01.085  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:52:01.085  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.085  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.086  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.086  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:01.086  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.086  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:01.086  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.086  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.086  3978  4027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:52:01.086  3978  4028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 410
09-12 13:52:01.086  3978  4028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 410)
09-12 13:52:01.087  3978  4028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 410)
09-12 13:52:01.087  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.087  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.087  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:01.087  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.088  3978  4027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 410)
,09-12 13:52:01.089  3978  4025 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:52:01.090  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.090  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.090  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.090  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.090  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.090  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.090  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.090  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.090  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.090  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.090  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.090  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.091  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.091  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.091  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.092  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.092  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.092  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.092  3978  4025 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:52:01.092  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.093  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.093  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.093  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.093  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.093  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.093  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.C,onnectionManager@64513c4 not in the list
09-12 13:52:01.093  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.093  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.093  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.093  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.093  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.093  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.093  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.095  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.095  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.095  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.096  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.097  3978  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:52:01.097  3978  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:52:01.097  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:52:01.097  3978  4025 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:52:01.097  3978  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:52:01.098  3978  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:52:01.098  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:52:01.098  3978  4025 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:52:01.098  3978  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:52:01.098  3978  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:52:01.098  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:52:01.098  3978  4025 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:52:01.099  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.099  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.099  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.099  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.099  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.099  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.099  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.100  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.100  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.100  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.100  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.100  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.100  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.100  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.101  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.101  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.102  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.102  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.102  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.102  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.102  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.102  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.102  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.103  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.103  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.103  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.103  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.103  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.103  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.103  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.103  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.103  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.103  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.103  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.103  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.103  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.104  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.104  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.104  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.104  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.104  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.104  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.104  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.104  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.104  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.104  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.104  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.105  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.105  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.105  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.105  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.106  3978  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:52:01.106  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:01.106  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:52:01.107  3978  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:52:01.107  3978  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:52:01.107  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:52:01.107  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:52:01.107  3978  3978 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:52:01.108  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.108  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:52:01.108  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:52:01.108  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.108  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.108  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:52:01.108  3978  3978 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:52:01.108  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.108  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.109  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:01.109  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.109  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.109  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:01.109  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.109  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.109  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:01.109  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.109  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.109  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:01.110  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.110  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.110  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.110  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.110  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.110  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.110  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.110  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.110  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.110  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.111  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.111  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.111  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.111  3978  4029 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:52:01.111  3978  4029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:52:01.112  3978  4025 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:52:01.112  3978  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:52:01.112  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:52:01.112  3978  3978 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:52:01.113  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:52:01.113  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.113  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.113  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.113  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.113  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.113  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.113  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.113  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.114  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.114  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.114  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.114  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.114  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.114  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.115  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.115  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.115  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.115  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.117  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.117  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.117  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.117  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.118  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.118  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.118  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.118  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.118  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.118  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.118  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.118  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.118  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.118  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.119  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.119  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.119  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.119  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.119  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:01.120  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:01.120  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:01.120  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:01.120  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.120  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.120  3978  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64513c4 not in the list
09-12 13:52:01.120  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.120  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.120  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:01.120  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.120  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.120  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:01.120  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:01.121  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:01.121  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:01.121  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:01.121  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50752ad not in the list
09-12 13:52:01.122  3978  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:52:01.122  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:52:01.122  3978  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:52:01.122  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:52:01.122  3978  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:52:01.122  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:52:01.123  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:52:01.123  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 13:52:01.124  3978  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:52:01.124  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:52:01.124  3978  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:52:01.124  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:52:01.124  3978  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:52:01.124  3978  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:52:01.125  3978  4025 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:52:01.126  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:01.126  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@981abc7 added. We now have 2 listener(s)
09-12 13:52:01.126  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:01.127  3978  4025 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 13:52:01.127   873  1709 D WifiService: setWifiEnabled: true pid=3978, uid=10000
09-12 13:52:01.127   873  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:52:01.128  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:01.128  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@176f5f4 added. We now have 3 listener(s)
09-12 13:52:01.128  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:01.131  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:01.131  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4f411d added. We now have 4 listener(s)
09-12 13:52:01.131  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:01.133  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:01.133  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a03bf92 added. We now have 5 listener(s)
09-12 13:52:01.133  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:01.134   873  1933 D WifiService: setWifiEnabled: false pid=3978, uid=10000
09-12 13:52:01.134   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:52:01.138  2617  2645 D BluetoothAdapterState: Current state: ON, message: 23
09-12 13:52:01.138  2617  2645 D BluetoothAdapterProperties: Setting state to 13
09-12 13:52:01.138  2617  2645 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:52:01.139  2617  2645 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:52:01.139  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:01.139  2617  2645 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:01.142  2617  2649 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:52:01.142  2617  2645 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 13:52:01.144  2617  2617 D BluetoothMapService: onReceive
09-12 13:52:01.144  2617  2617 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:52:01.144  2617  2617 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:52:01.144  2617  2617 D BluetoothMapService: MAP Service closeService in
09-12 13:52:01.144  2617  2617 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 13:52:01.144  2617  2617 D ObexServerSockets0: shutdown(block = true)
09-12 13:52:01.145  2617  2617 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:52:01.145  2617  2617 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:52:01.145  2617  2729 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 13:52:01.145  2617  2746 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 13:52:01.146  2617  2747 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 13:52:01.147  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:01.147  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:01.147  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.147  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:01.147  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:52:01.148  2617  2617 I BtOppRfcommListener: stopping Accept Thread
09-12 13:52:01.148  2617  3405 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:52:01.149  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.149  2617  3405 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:52:01.151  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.152  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:52:01.153  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:01.153  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:01.153  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.153  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:01.154   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:52:01.154   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:52:01.154   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:52:01.154   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:52:01.155  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.158  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.160  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.166   873  1305 E native  : do suspend true
09-12 13:52:01.169   873   886 I ActivityManager: Start proc 4032:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 13:52:01.171  2617  2617 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:52:01.173   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:01.173   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:01.173   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:01.173  1352  1369 D BluetoothHeadset: Proxy object disconnected
,09-12 13:52:01.173  1352  1352 D HeadsetProfile: Bluetooth service disconnected
,09-12 13:52:01.173  1937  1951 D BluetoothHeadset: Proxy object disconnected
,09-12 13:52:01.175  2617  2617 D A2dpService: Received stop request...Stopping profile...
09-12 13:52:01.176  2617  2737 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:52:01.178   873   873 D BluetoothA2dp: Proxy object disconnected
,09-12 13:52:01.179  1352  1352 D BluetoothA2dp: Proxy object disconnected
09-12 13:52:01.179  2617  2617 D HidService: Received stop request...Stopping profile...
09-12 13:52:01.179  2617  2617 D HidService: Stopping Bluetooth HidService
,09-12 13:52:01.180  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-12 13:52:01.180  1352  1352 D HidProfile: Bluetooth service disconnected
,09-12 13:52:01.180  2617  2617 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:01.180  2617  2617 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:01.180  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:01.180  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:01.181  2617  2617 D HealthService: Received stop request...Stopping profile...
09-12 13:52:01.182   873  1888 D DhcpClient: Clearing IP address
09-12 13:52:01.182   374   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:52:01.184  2617  2617 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 13:52:01.184  2617  2617 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:52:01.184  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:01.185  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:01.185  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:01.185   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:01.185  2617  2617 D PanService: Received stop request...Stopping profile...
09-12 13:52:01.185  2617  2649 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:52:01.185  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:52:01.185  1352  1352 D PanProfile: Bluetooth service disconnected
09-12 13:52:01.185  2617  2649 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 13:52:01.186  2617  2617 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:52:01.186  2617  2617 D BluetoothMapService: stop()
09-12 13:52:01.187  2617  2617 D BluetoothMapAppObserver: deinitObservers()
09-12 13:52:01.187  2617  2617 D BluetoothMapAppObserver: removeReceiver()
09-12 13:52:01.188  1352  1352 D BluetoothMap: Proxy object disconnected
,09-12 13:52:01.188  1352  1352 D MapProfile: Bluetooth service disconnected
09-12 13:52:01.188  2617  2617 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:52:01.188  2617  2617 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:01.188  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:01.188  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:01.189   873  3936 D DhcpClient: Receive thread stopped
09-12 13:52:01.190  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:52:01.190  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:01.190  2617  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:52:01.190  2617  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:52:01.190  2617  2724 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:52:01.190  2617  2724 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:52:01.190  2617  2649 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 13:52:01.190  2617  2617 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 13:52:01.190  2617  2617 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:52:01.190  2617  2649 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:01.190  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:01.191  2617  2617 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 13:52:01.191  2617  2649 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 13:52:01.191  2617  2617 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:52:01.191  2617  2617 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:01.191  2617  2617 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:01.191  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:01.191  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:01.192  2617  2617 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:52:01.192  2617  2617 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 13:52:01.192  2617  2617 D BluetoothMapService: MAP Service closeService in
,09-12 13:52:01.192  2617  2617 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:52:01.192  2617  2617 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:01.193  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:01.193  2617  2617 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:01.193  2617  2645 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:52:01.193  2617  2645 D BluetoothAdapterProperties: Setting state to 15
09-12 13:52:01.193  2617  2645 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:52:01.193  2617  2645 I BluetoothAdapterState: Entering BleOnState
09-12 13:52:01.193  1352  1369 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:52:01.194  2617  2617 D BluetoothMapService: cleanup()
09-12 13:52:01.194  2617  2617 D BluetoothMapService: MAP Service closeService in
09-12 13:52:01.194  1352  2042 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:52:01.195   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:01.195  1352  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:01.195  1352  1369 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:52:01.196   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:52:01.196   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:01.196  1352  2042 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:52:01.197   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:52:01.197  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:52:01.198  1937  2106 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:01.198  2617  2645 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:52:01.199  2617  2645 D BluetoothAdapterProperties: Setting state to 16
09-12 13:52:01.199  2617  2645 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:52:01.199  2617  2645 D BluetoothAdapterProperties: onBleDisable
,09-12 13:52:01.199  2617  2646 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:52:01.199  2617  2645 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:01.200   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 13:52:01.200   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-12 13:52:01.200   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 13:52:01.201  2617  2724 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:52:01.201  2617  2724 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:01.201   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:52:01.201   873  1305 E native  : do suspend true
,09-12 13:52:01.201  2617  2649 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:52:01.203   400   400 E Parcel  : Reading a NULL string not supported here.
09-12 13:52:01.208  1522  3961 V NativeCrypto: Read error: ssl=0x9b285200: I/O error during system call, Connection timed out
09-12 13:52:01.211   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 13:52:01.212  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.212  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:01.212  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.212  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:01.213  1522  3961 V NativeCrypto: SSL shutdown failed: ssl=0x9b285200: I/O error during system call, Broken pipe
09-12 13:52:01.217  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.217  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:01.217  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.217  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:01.219  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.219  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:01.222  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.222  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:01.238   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:01.244  4032  4032 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 13:52:01.253  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:52:01.254   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:01.254   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 13:52:01.254   374   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:52:01.254   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:52:01.256   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 13:52:01.258   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:01.260  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:01.261  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:01.268  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:52:01.268   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37e9240:true
,09-12 13:52:01.281   873  1384 I ActivityManager: Start proc 4050:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 13:52:01.283   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:01.286  2154  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:52:01.287   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:52:01.287  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:01.287  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:01.287  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:01.290  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:01.290  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:01.291  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-12 13:52:01.291  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:01.294  4032  4032 D LocalBluetoothProfileManager: Adding local MAP profile
09-12 13:52:01.296  4032  4032 D BluetoothMap: Create BluetoothMap proxy object
,09-12 13:52:01.306  4032  4032 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 13:52:01.309   374   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:52:01.318  4050  4050 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 13:52:01.326  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:52:01.329   873  2003 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 13:52:01.401  2617  2649 I bt_hci  : shut_down
,09-12 13:52:01.405  2617  2655 D bt_hwcfg: hw_epilog_process
09-12 13:52:01.405  2617  2655 I bt_vendor: low_power_mode_cb
,09-12 13:52:01.432  2617  2655 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:52:01.432  2617  2655 I bt_vendor: epilog_cb
09-12 13:52:01.432  2617  2655 I bt_hci  : epilog_finished_callback
,09-12 13:52:01.436  2617  2649 I bt_hci_h4: hal_close
,09-12 13:52:01.437  2617  2649 I bt_userial_vendor: device fd = 51 close
,09-12 13:52:01.501  4050  4050 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:52:01.501  4050  4050 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:52:01.501  4050  4050 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:52:01.501  4050  4050 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:52:01.501  4050  4050 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.501  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:01.502  4050  4050 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:01.502  4050  4050 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.502  4050  4050 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:01.502  4050  4050 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:01.502  4050  4050 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:01.508  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:52:01.517  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:52:01.523  4032  4032 D DockEventReceiver: finishStartingService: stopping service
09-12 13:52:01.539   873   884 I ActivityManager: Killing 3708:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 13:52:01.602  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:52:01.610  1741  1741 D SystemUpdateService: onCreate
,09-12 13:52:01.610  3978  3978 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 13:52:01.611  2617  2646 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:52:01.611  2617  2645 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:52:01.613  2617  2645 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:52:01.614  2617  2617 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:52:01.614  2617  2617 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 13:52:01.614  2617  2617 D BtGatt.GattService: stop()
,09-12 13:52:01.615  2617  2617 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:52:01.616  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 13:52:01.616  2617  2617 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:01.616  2617  2617 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:01.616  2617  2617 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:01.616  2617  2617 V BluetoothAdapterState: isBleTurningOff()=true
09-12 13:52:01.617  2617  2645 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 13:52:01.617  2617  2645 D BluetoothAdapterProperties: Setting state to 10
09-12 13:52:01.617  2617  2645 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 13:52:01.618  2617  2645 I BluetoothAdapterState: Entering OffState
09-12 13:52:01.619   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 13:52:01.646  1741  4083 I SystemUpdateService: active receiver: enabled
,09-12 13:52:01.650  2617  2617 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 13:52:01.650  2617  2617 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:52:01.651  2617  2617 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:52:01.652  2617  2646 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:52:01.653  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:52:01.658  2617  2646 D bt_stack_manager: event_clean_up_stack finished.
09-12 13:52:01.659  1741  2458 I iu.UploadsManager: num queued entries: 0
,09-12 13:52:01.663  2617  2617 I art     : System.exit called, status: 0
,09-12 13:52:01.663  2617  2617 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:52:01.666  1741  4083 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:52:01.669  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:52:01.670  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-12 13:52:01.674  3838  3838 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:01.677  1741  2458 I iu.UploadsManager: num updated entries: 0
,09-12 13:52:01.682  1741  2458 I iu.SyncManager: NEXT; no task
,09-12 13:52:01.682  3838  3838 D SprintDMHelper: simOperator: 
,09-12 13:52:01.682  3838  3838 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 13:52:01.691  1741  4083 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:52:01.691  1741  4083 I SystemUpdateService: now status is 0 (complete)
,09-12 13:52:01.691  1741  4083 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 13:52:01.706  1741  4083 I SystemUpdateService: file has been verified
,09-12 13:52:01.706  1741  4083 I SystemUpdateService: OTA package size = 12249756
,09-12 13:52:01.732  2417  4086 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 13:52:01.738   873  1384 I ActivityManager: Start proc 4087:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 13:52:01.745  1741  4083 I SystemUpdateService: showing system update notification
,09-12 13:52:01.761   873   884 I ActivityManager: Process com.android.bluetooth (pid 2617) has died
,09-12 13:52:01.797  4087  4087 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 13:52:01.800  1741  1741 D SystemUpdateService: onDestroy
,09-12 13:52:01.856  4087  4087 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 13:52:01.989  4050  4076 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 13:52:02.000   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2632d15:true
,09-12 13:52:04.150   873  1980 D WifiService: setWifiEnabled: true pid=3978, uid=10000
,09-12 13:52:04.150   873  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:52:04.163   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:52:04.172  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:04.172  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:04.173  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:04.173  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:04.176  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:04.177  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:04.177  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:04.177  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:04.198   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:52:04.199   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 13:52:04.200   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 13:52:04.201   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:52:04.201   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:52:04.201   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:52:04.201   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:52:04.221   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:04.221   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:52:04.224   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:04.233   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-12 13:52:04.233   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:52:04.233   873  1305 E native  : do suspend true
,09-12 13:52:04.247   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:04.253   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:52:04.255   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:52:05.564   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:05.644   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.81 rxSuccessRate=11.50 delta 1000 -> 994
,09-12 13:52:05.645   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 13:52:05.645   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:52:05.662   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:52:05.717   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:52:05.723  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:52:06.160  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:52:06.203  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:52:06.204  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:52:06.207   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:06.216   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 13:52:06.217   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:52:06.217   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:52:06.240   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:52:06.254   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:06.255   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:52:06.273   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:52:06.294   873  4119 D DhcpClient: Receive thread started
,09-12 13:52:06.375   873  1305 E native  : do suspend false
,09-12 13:52:06.392   873  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:52:06.409   873  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172750, domain null
,09-12 13:52:06.411   873  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172750 seconds
,09-12 13:52:06.414   873  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:52:06.433   873  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:52:06.434   873  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:52:06.438   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:06.442   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:52:06.444   873  1305 E native  : do suspend true
,09-12 13:52:06.445   873  1888 D DhcpClient: Scheduling renewal in 86399s
,09-12 13:52:06.458   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:52:06.459   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:52:06.460   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 13:52:06.461   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:52:06.463   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 13:52:06.511   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:52:06.511   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 13:52:06.514   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 13:52:06.517   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 13:52:06.519   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 13:52:06.534   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:52:06.539   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 13:52:06.539   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 13:52:06.539   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 13:52:06.539   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 13:52:06.539   873  1308 D ConnectivityService:    accepting network in place of null
09-12 13:52:06.540   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:52:06.541   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:52:06.579   873  4118 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221202, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:52:06.603   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:06.656   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:06.656   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:52:06.663   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 13:52:06.663   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:06.667   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 13:52:06.668   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 13:52:06.677  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:06.677  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:06.677  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:06.677  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:52:06.682  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:52:06.682  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:52:06.682  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:06.682  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:52:06.694  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:52:06.697  1741  1741 D SystemUpdateService: onCreate
,09-12 13:52:06.701  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:52:06.703  1741  4128 I SystemUpdateService: active receiver: enabled
,09-12 13:52:06.707  1741  4128 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:52:06.710  1741  4128 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:52:06.711  1741  4128 I SystemUpdateService: now status is 0 (complete)
,09-12 13:52:06.711  1741  4128 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:52:06.711  1741  4128 I SystemUpdateService: file has been verified
09-12 13:52:06.711  1741  4128 I SystemUpdateService: OTA package size = 12249756
,09-12 13:52:06.719  1741  4128 I SystemUpdateService: showing system update notification
,09-12 13:52:06.724  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:52:06.725  1741  2458 I iu.UploadsManager: num queued entries: 0
,09-12 13:52:06.727  1741  2458 I iu.UploadsManager: num updated entries: 0
,09-12 13:52:06.728  1741  2458 I iu.SyncManager: NEXT; no task
,09-12 13:52:06.731  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 13:52:06.732  1741  4131 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 13:52:06.732  1741  4131 W BaseAppContext: Using Auth Proxy for data requests.
09-12 13:52:06.733  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:52:06.734  1741  4131 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:52:06.735  3838  3838 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:06.738  1741  1741 D SystemUpdateService: onDestroy
,09-12 13:52:06.742  3838  3838 D SprintDMHelper: simOperator: 
,09-12 13:52:06.742  3838  3838 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:52:06.744   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:52:06 GMT], X-Android-Received-Millis=[1473681126743], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473681126715]}
,09-12 13:52:06.744  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:52:06.744   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 13:52:06.745   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 13:52:06.745   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 13:52:06.746   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 13:52:06.747  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:52:06.777  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:52:06.777  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:52:06.777  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:52:06.777  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:52:06.789  1741  4131 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-12 13:52:06.858  2417  4134 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:52:07.015   873  3143 I ActivityManager: Killing 2244:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 13:52:07.156   873  1384 D WifiService: setWifiEnabled: false pid=3978, uid=10000
,09-12 13:52:07.156   873  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:52:07.167  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 13:52:07.170   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:52:07.170   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:52:07.171   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:52:07.171   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:52:07.193   873  1305 E native  : do suspend true
,09-12 13:52:07.203   873  1888 D DhcpClient: Clearing IP address,
09-12 13:52:07.204   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:52:07.208   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:07.210   873  4119 D DhcpClient: Receive thread stopped
,09-12 13:52:07.210  1522  4138 V NativeCrypto: Read error: ssl=0x9b285200: I/O error during system call, Connection timed out
09-12 13:52:07.213  1522  4138 V NativeCrypto: SSL shutdown failed: ssl=0x9b285200: I/O error during system call, Broken pipe
,09-12 13:52:07.222   873  1980 D ConnectivityService: reportNetworkConnectivity(102, false) by 10011
,09-12 13:52:07.224   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10011
,09-12 13:52:07.225   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:52:07.230   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 13:52:07.230   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
09-12 13:52:07.235   400   400 E Parcel  : Reading a NULL string not supported here.
09-12 13:52:07.237   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 3
09-12 13:52:07.237   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:52:07.238   873  1305 E native  : do suspend true
09-12 13:52:07.241   873  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-12 13:52:07.246   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:52:07.247   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
09-12 13:52:07.250   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:07.268   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:07.270  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:07.270  2154  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:07.270  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:07.270  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:07.270  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:07.271  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:07.271  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:07.271  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:07.271  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:07.272   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 13:52:07.282   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:07.317   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:07.318   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 13:52:07.318   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:07.322   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:52:07.330  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:07.331  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:07.339  1741  1741 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:52:07.343  1741  1741 D SystemUpdateService: onCreate
,09-12 13:52:07.348  1741  1741 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:52:07.361  1741  1741 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:52:07.363  1741  2458 I iu.UploadsManager: num queued entries: 0
09-12 13:52:07.364  1741  2458 I iu.UploadsManager: num updated entries: 0
09-12 13:52:07.364  1741  2458 I iu.SyncManager: NEXT; no task
,09-12 13:52:07.373  1741  1741 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:52:07.375  1741  1741 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:52:07.378  3838  3838 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:07.383  1741  4147 I SystemUpdateService: active receiver: enabled
09-12 13:52:07.383  3838  3838 D SprintDMHelper: simOperator: 
09-12 13:52:07.383  3838  3838 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:52:07.404  2417  4152 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 13:52:07.407   374   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:52:07.408   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:52:07.409   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:52:07.446  1741  4147 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:52:07.449  1741  4147 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:52:07.449  1741  4147 I SystemUpdateService: now status is 0 (complete)
09-12 13:52:07.449  1741  4147 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:52:07.449  1741  4147 I SystemUpdateService: file has been verified
09-12 13:52:07.449  1741  4147 I SystemUpdateService: OTA package size = 12249756
,09-12 13:52:07.453  1741  4147 I SystemUpdateService: showing system update notification
,09-12 13:52:07.462  1741  1741 D SystemUpdateService: onDestroy
,09-12 13:52:07.663   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 13:52:10.211   873   890 I ActivityManager: Start proc 4154:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:52:10.351  4154  4154 D AdapterServiceConfig: Adding HeadsetService
,09-12 13:52:10.351  4154  4154 D AdapterServiceConfig: Adding A2dpService
,09-12 13:52:10.351  4154  4154 D AdapterServiceConfig: Adding HidService
,09-12 13:52:10.351  4154  4154 D AdapterServiceConfig: Adding HealthService
,09-12 13:52:10.352  4154  4154 D AdapterServiceConfig: Adding PanService
,09-12 13:52:10.352  4154  4154 D AdapterServiceConfig: Adding GattService
,09-12 13:52:10.352  4154  4154 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:52:10.365  4154  4154 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 13:52:10.365   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b07e1:true
,09-12 13:52:10.372  4154  4166 I BluetoothAdapterState: Entering OffState
09-12 13:52:10.372  4154  4154 I bt_bluedroid: init
,09-12 13:52:10.374  4154  4167 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:52:10.374  4154  4167 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:52:10.374  4154  4167 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:52:10.375  4154  4167 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:52:10.375  4154  4154 I bt_bluedroid: get_profile_interface socket
,09-12 13:52:10.377  4154  4154 I bt_bluedroid: get_profile_interface sdp
,09-12 13:52:10.383  4154  4170 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:52:10.384  4154  4170 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:52:10.384  4154  4165 I bt_bluedroid: config_hci_snoop_log
,09-12 13:52:10.387   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:52:10.395  4154  4166 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:52:10.395  4154  4166 D BluetoothAdapterProperties: Setting state to 14
,09-12 13:52:10.395  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:52:10.396  4154  4166 D BluetoothBondStateMachine: make
,09-12 13:52:10.400  4154  4171 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:52:10.402  4154  4166 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:52:10.404  4154  4154 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:52:10.407  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
09-12 13:52:10.407  4154  4154 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:52:10.408  4154  4154 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:52:10.408  4154  4154 D BtGatt.GattService: start()
09-12 13:52:10.408  4154  4154 I bt_bluedroid: get_profile_interface gatt
09-12 13:52:10.409  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
09-12 13:52:10.410  4154  4154 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:52:10.416  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:10.416  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:10.416  4154  4154 V BluetoothAdapterState: isBleTurningOn()=true
09-12 13:52:10.417  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:10.417  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:52:10.418  4154  4166 I bt_bluedroid: enable
09-12 13:52:10.418  4154  4167 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 13:52:10.418  4154  4167 I bt_hci  : start_up
,09-12 13:52:10.429  4154  4167 I bt_vendor: alloc value 0xb3a7e189
,09-12 13:52:10.429  4154  4167 I bt_vendor: init
09-12 13:52:10.429  4154  4167 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 13:52:10.429  4154  4167 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:52:10.539  4154  4167 D bt_hci  : start_up starting async portion
,09-12 13:52:10.539  4154  4174 I bt_hci  : event_finish_startup
09-12 13:52:10.540  4154  4174 I bt_hci_h4: hal_open,
09-12 13:52:10.540  4154  4174 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:52:10.550  4154  4174 I bt_userial_vendor: device fd = 51 open
,09-12 13:52:10.580  4154  4174 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:52:10.612  4154  4174 D bt_hwcfg: Chipset BCM4354A2
09-12 13:52:10.612  4154  4174 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:52:10.613  4154  4174 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:52:11.273  4154  4174 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:52:11.275  4154  4174 D bt_hwcfg: Settlement delay -- 100 ms
09-12 13:52:11.275  4154  4174 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:52:11.392  4154  4174 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:52:11.393  4154  4174 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:52:11.423  4154  4174 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:52:11.423  4154  4174 I bt_vendor: firmware callback
09-12 13:52:11.423  4154  4174 I bt_hci  : firmware_config_callback
,09-12 13:52:11.434  4154  4176 I bt_btu  : btu_task pending for preload complete event
,09-12 13:52:11.434  4154  4176 I bt_btu_task: Bluetooth chip preload is complete
,09-12 13:52:11.435  4154  4176 I bt_btu  : btu_task received preload complete event
,09-12 13:52:11.447  4154  4176 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:52:11.447  4154  4176 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:52:11.447  4154  4176 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:52:11.448  4154  4176 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:52:11.448  4154  4176 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:52:11.448  4154  4176 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 13:52:11.449  4154  4176 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:52:11.449  4154  4176 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 13:52:11.449  4154  4176 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:52:11.450  4154  4176 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:52:11.450  4154  4176 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:52:11.450  4154  4176 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:52:11.451  4154  4176 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:52:11.451  4154  4176 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:52:11.451  4154  4176 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:52:11.598  4154  4176 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fbd9d
,09-12 13:52:11.598  4154  4176 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fbd9d 
,09-12 13:52:11.605  4154  4170 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:52:11.606  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:52:11.607  4154  4170 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:52:11.611  4154  4170 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:52:11.614  4154  4170 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:52:11.615  4154  4170 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:52:11.615  4154  4170 D bt_hci  : do_postload posting postload work item
,09-12 13:52:11.616  4154  4174 I bt_hci  : event_postload
,09-12 13:52:11.616  4154  4174 I bt_vendor: sco_config_cb
,09-12 13:52:11.616  4154  4174 I bt_hci  : sco_config_callback postload finished.
09-12 13:52:11.620  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:11.621  4154  4170 D bt_bte_conf: Device ID record 1 : primary
09-12 13:52:11.621  4154  4170 D bt_bte_conf:   vendorId            = 000f
09-12 13:52:11.621  4154  4170 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:52:11.621  4154  4170 D bt_bte_conf:   product             = 1200
09-12 13:52:11.622  4154  4170 D bt_bte_conf:   version             = 1436
,09-12 13:52:11.622  4154  4170 D bt_bte_conf:   clientExecutableURL = 
09-12 13:52:11.622  4154  4170 D bt_bte_conf:   serviceDescription  = 
09-12 13:52:11.622  4154  4170 D bt_bte_conf:   documentationURL    = 
,09-12 13:52:11.623  4154  4170 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:52:11.623  4154  4167 D bt_stack_manager: event_start_up_stack finished
09-12 13:52:11.624  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 13:52:11.625  4154  4166 D BluetoothAdapterProperties: Setting state to 15
09-12 13:52:11.625  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 13:52:11.630  4154  4166 I BluetoothAdapterState: Entering BleOnState
,09-12 13:52:11.631  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:11.632  4154  4166 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 13:52:11.632  4154  4166 D BluetoothAdapterProperties: Setting state to 11
09-12 13:52:11.633  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 13:52:11.638  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:11.639  4154  4154 D HeadsetService: Received start request. Starting profile...
,09-12 13:52:11.643  4154  4154 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 13:52:11.644  4154  4154 D HeadsetStateMachine: make
,09-12 13:52:11.647  4154  4174 I bt_vendor: low_power_mode_cb
,09-12 13:52:11.651  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:11.652  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:11.660  4154  4154 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:52:11.660  4154  4154 I bt_bluedroid: get_profile_interface handsfree
09-12 13:52:11.665  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
09-12 13:52:11.665  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:52:11.665  4154  4166 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:11.665  4154  4170 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-12 13:52:11.666  4154  4154 D A2dpService: Received start request. Starting profile...
09-12 13:52:11.667  4154  4154 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:52:11.667  4154  4154 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:52:11.674  4154  4154 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:52:11.674  4154  4154 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 13:52:11.674  4154  4154 D A2dpStateMachine: make
09-12 13:52:11.675  4154  4154 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:52:11.676  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:52:11.677  4154  4185 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:52:11.680  4154  4154 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:52:11.681  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
09-12 13:52:11.682  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:52:11.683  4032  4032 D BluetoothInputDevice: Proxy object connected
09-12 13:52:11.684  4154  4154 D HidService: Received start request. Starting profile...
09-12 13:52:11.684  4032  4032 D HidProfile: Bluetooth service connected
,09-12 13:52:11.684  4154  4154 I bt_bluedroid: get_profile_interface hidhost
09-12 13:52:11.684  4154  4154 D HidService: setHidService(): set to: null
09-12 13:52:11.684  4154  4170 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39dd3e5
09-12 13:52:11.684  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 13:52:11.685  4154  4154 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 13:52:11.686  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:11.687  4154  4154 D HealthService: Received start request. Starting profile...
,09-12 13:52:11.689  4154  4154 I bt_bluedroid: get_profile_interface health
,09-12 13:52:11.690  4154  4154 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:52:11.691  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:11.692  4154  4154 D PanService: Received start request. Starting profile...
,09-12 13:52:11.692  4032  4032 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:52:11.692  4154  4154 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:52:11.692  4154  4154 I bt_bluedroid: get_profile_interface pan
09-12 13:52:11.693  4154  4170 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:52:11.694  4032  4032 D PanProfile: Bluetooth service connected
,09-12 13:52:11.694  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:11.694  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:11.695  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:11.695  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:11.695  4154  4182 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 13:52:11.698  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:11.699  4154  4154 D BluetoothMapService: Received start request. Starting profile...
09-12 13:52:11.699  4154  4154 D BluetoothMapService: start()
,09-12 13:52:11.699  4032  4032 D BluetoothMap: Proxy object connected
09-12 13:52:11.700  4032  4032 D MapProfile: Bluetooth service connected
,09-12 13:52:11.701  4032  4032 D BluetoothMap: getConnectedDevices()
09-12 13:52:11.701  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 13:52:11.702  4032  4032 D BluetoothMap: Bluetooth is Not enabled
,09-12 13:52:11.702  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:52:11.702  4154  4154 D BluetoothMapAppObserver: createReceiver()
,09-12 13:52:11.703  4154  4154 D BluetoothMapAppObserver: initObservers()
09-12 13:52:11.703  4154  4154 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:52:11.710  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:11.710  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:11.710  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:11.710  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:11.711  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:11.712  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:11.712  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:52:11.713  4154  4166 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:52:11.713  4154  4166 D BluetoothAdapterProperties: State =  11
09-12 13:52:11.713  4154  4166 D BluetoothAdapterProperties: Setting state to 12
09-12 13:52:11.713  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:52:11.714  4154  4166 I BluetoothAdapterState: Entering OnState
09-12 13:52:11.714  1352  1363 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:52:11.716  4154  4170 D BluetoothAdapterProperties: Scan Mode:21
,09-12 13:52:11.716  4154  4170 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:52:11.717  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:52:11.717  1352  1352 D PanProfile: Bluetooth service connected
09-12 13:52:11.718  4032  4042 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:52:11.719  4032  4043 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:11.719  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:11.719  4032  4042 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:52:11.720  1352  1369 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:52:11.721  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:11.723  1352  1352 D BluetoothInputDevice: Proxy object connected
09-12 13:52:11.724  1352  1352 D HidProfile: Bluetooth service connected
09-12 13:52:11.724   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:11.724  1352  1363 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:11.725  1352  2042 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:11.727  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:11.729  1352  1352 D BluetoothMap: Proxy object connected
09-12 13:52:11.729  1352  1352 D MapProfile: Bluetooth service connected
,09-12 13:52:11.729  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 13:52:11.729  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:11.730   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:52:11.730   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:11.730  4032  4043 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:52:11.730  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:52:11.731  4154  4154 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 13:52:11.731  1352  1363 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:52:11.732  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:11.733   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:52:11.734  1352  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:52:11.734  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:52:11.735  4154  4154 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:52:11.735  4154  4154 D ObexServerSockets0: startAccept()
09-12 13:52:11.735  4154  4154 D ObexServerSockets0: prepareForNewConnect()
09-12 13:52:11.735  1937  2219 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:11.737   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:52:11.738  4154  4190 D ObexServerSockets0: Accepting socket connection...
09-12 13:52:11.738  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:11.739  4154  4154 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:52:11.739  4154  4154 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 13:52:11.740   873   873 D BluetoothA2dp: Proxy object connected
,09-12 13:52:11.740  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:11.740  4154  4154 D BluetoothMapService: onReceive
09-12 13:52:11.740  1352  1352 D BluetoothA2dp: Proxy object connected
09-12 13:52:11.740  4154  4154 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:52:11.740  4154  4154 D BluetoothMapService: STATE_ON
09-12 13:52:11.741  4154  4192 D ObexServerSockets0: Accepting socket connection...
09-12 13:52:11.743  4032  4032 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 13:52:11.747  4032  4032 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 13:52:11.753  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:52:11.755  4032  4032 D BluetoothA2dp: Proxy object connected
,09-12 13:52:11.758  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:52:11.762  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:52:11.766  1352  1352 D BluetoothPbap: Proxy object connected
,09-12 13:52:11.766  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-12 13:52:11.766  4032  4032 D BluetoothPbap: Proxy object connected
09-12 13:52:11.766  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:52:11.766  4154  4154 D ObexServerSockets0: prepareForNewConnect()
09-12 13:52:11.767  4032  4032 D PbapServerProfile: Bluetooth service connected
,09-12 13:52:11.774  4154  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:11.790  4154  4201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:11.792  4154  4201 I BtOppRfcommListener: Accept thread started.
,09-12 13:52:11.826   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.827   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:52:11.827   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.828  1352  1363 D BluetoothHeadset: Proxy object connected
09-12 13:52:11.828  1352  1352 D HeadsetProfile: Bluetooth service connected
,09-12 13:52:11.829  1937  1951 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.832   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.832   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.836  1937  2106 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.850  4032  4042 D BluetoothHeadset: Proxy object connected
,09-12 13:52:11.851  4032  4032 D HeadsetProfile: Bluetooth service connected
,09-12 13:52:13.173  4154  4166 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 13:52:13.173  4154  4166 D BluetoothAdapterProperties: Setting state to 13
09-12 13:52:13.173  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:52:13.175  4154  4166 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 13:52:13.180  4154  4166 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:13.189  4154  4154 D BluetoothMapService: onReceive
,09-12 13:52:13.189  4154  4154 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:52:13.190  4154  4154 D BluetoothMapService: STATE_TURNING_OFF
,09-12 13:52:13.190  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:13.190  4154  4154 D BluetoothMapService: MAP Service closeService in
09-12 13:52:13.191  4154  4154 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:13.191  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:13.191  4154  4154 D ObexServerSockets0: shutdown(block = true)
,09-12 13:52:13.192  4154  4190 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 13:52:13.193  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:52:13.194  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:13.198  4154  4170 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:52:13.198  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 13:52:13.202  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:13.203  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:13.204  4154  4154 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:52:13.204  4154  4192 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 13:52:13.205  3978  3978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:52:13.205  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:13.205  4154  4178 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 13:52:13.205  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:52:13.205  4154  4154 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:52:13.207  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:13.207  4154  4154 I BtOppRfcommListener: stopping Accept Thread
09-12 13:52:13.208  4154  4201 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:52:13.208  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:13.211  4154  4201 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:52:13.212  4154  4154 D HeadsetService: Received stop request...Stopping profile...
09-12 13:52:13.214  4032  4043 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:13.214   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:13.214   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:13.214  4154  4154 D A2dpService: Received stop request...Stopping profile...
09-12 13:52:13.214   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 13:52:13.215  1352  1369 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:13.215  4154  4185 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:52:13.215  1937  2220 D BluetoothHeadset: Proxy object disconnected
09-12 13:52:13.215  4032  4032 D DockEventReceiver: finishStartingService: stopping service
09-12 13:52:13.217   873   873 D BluetoothA2dp: Proxy object disconnected
,09-12 13:52:13.219  4032  4032 D HeadsetProfile: Bluetooth service disconnected
09-12 13:52:13.219  4154  4154 D HidService: Received stop request...Stopping profile...
09-12 13:52:13.219  1352  1352 D HeadsetProfile: Bluetooth service disconnected
09-12 13:52:13.220  4154  4154 D HidService: Stopping Bluetooth HidService
09-12 13:52:13.220  1352  1352 D BluetoothA2dp: Proxy object disconnected
,09-12 13:52:13.223  4032  4032 D BluetoothA2dp: Proxy object disconnected
,09-12 13:52:13.223  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-12 13:52:13.223  1352  1352 D HidProfile: Bluetooth service disconnected
09-12 13:52:13.223  4032  4032 D BluetoothInputDevice: Proxy object disconnected
09-12 13:52:13.223  4032  4032 D HidProfile: Bluetooth service disconnected
,09-12 13:52:13.224  4154  4154 D HealthService: Received stop request...Stopping profile...
,09-12 13:52:13.226  4154  4154 D PanService: Received stop request...Stopping profile...
,09-12 13:52:13.228  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:52:13.228  1352  1352 D PanProfile: Bluetooth service disconnected
,09-12 13:52:13.228  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:52:13.228  4154  4154 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 13:52:13.228  4154  4154 D BluetoothMapService: stop()
09-12 13:52:13.229  4154  4154 D BluetoothMapAppObserver: deinitObservers()
09-12 13:52:13.229  4154  4154 D BluetoothMapAppObserver: removeReceiver()
,09-12 13:52:13.229  4032  4032 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:52:13.229  4032  4032 D PanProfile: Bluetooth service disconnected
,09-12 13:52:13.231  1352  1352 D BluetoothMap: Proxy object disconnected
,09-12 13:52:13.231  1352  1352 D MapProfile: Bluetooth service disconnected
09-12 13:52:13.231  4032  4032 D BluetoothMap: Proxy object disconnected
09-12 13:52:13.231  4032  4032 D MapProfile: Bluetooth service disconnected
,09-12 13:52:13.233  4154  4154 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:52:13.233  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:13.233  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:13.233  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:13.234  4154  4154 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 13:52:13.234  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:52:13.234  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:13.235  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:52:13.235  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:52:13.236  4154  4154 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:52:13.236  4154  4170 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-12 13:52:13.237  4154  4154 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:13.237  4154  4154 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:13.237  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:13.237  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:13.239  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 13:52:13.239  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:52:13.239  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:13.239  4154  4176 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:52:13.239  4154  4176 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:52:13.239  4154  4176 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:52:13.239  4154  4176 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:52:13.242  4154  4154 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:52:13.243  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:13.243  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:13.243  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:13.243  4154  4154 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 13:52:13.244  4154  4154 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:52:13.244  4154  4170 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:52:13.245  4154  4154 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:13.245  4154  4154 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:13.245  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:13.245  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:13.245  4154  4154 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 13:52:13.245  4154  4170 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 13:52:13.245  4154  4154 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 13:52:13.247  1352  1352 D BluetoothPbap: Proxy object disconnected
09-12 13:52:13.247  1352  1352 D PbapServerProfile: Bluetooth service disconnected
09-12 13:52:13.248  4032  4032 D BluetoothPbap: Proxy object disconnected
09-12 13:52:13.248  4154  4154 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:13.248  4032  4032 D PbapServerProfile: Bluetooth service disconnected
09-12 13:52:13.248  4154  4154 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:13.248  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:13.248  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:13.249  4154  4154 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:52:13.249  4154  4154 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:52:13.250  4154  4154 D BluetoothMapService: MAP Service closeService in
,09-12 13:52:13.250  4154  4154 V BluetoothAdapterState: isTurningOff()=true
09-12 13:52:13.250  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:13.250  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:13.251  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:13.251  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:52:13.251  4154  4166 D BluetoothAdapterProperties: Setting state to 15
,09-12 13:52:13.251  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:52:13.252  4154  4166 I BluetoothAdapterState: Entering BleOnState
09-12 13:52:13.252  1352  1363 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:52:13.252  4154  4154 D BluetoothMapService: cleanup()
09-12 13:52:13.253  4154  4154 D BluetoothMapService: MAP Service closeService in
09-12 13:52:13.253  4032  4043 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:52:13.254  4032  4042 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:52:13.254  4032  4043 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:52:13.255  4032  4042 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:52:13.257  1352  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:52:13.258   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:13.258  1352  2042 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:13.258  4032  4043 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:13.258  1352  1363 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:52:13.259   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:13.259   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:52:13.259  4032  4042 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:52:13.260  1352  1369 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:52:13.262   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:52:13.262  1352  2042 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:52:13.263  1937  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:52:13.263  4154  4166 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-12 13:52:13.263  4154  4166 D BluetoothAdapterProperties: Setting state to 16
,09-12 13:52:13.264  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:52:13.264  4154  4166 D BluetoothAdapterProperties: onBleDisable
09-12 13:52:13.266  4154  4167 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:52:13.266  4154  4166 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:13.267  4154  4176 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 13:52:13.267  4154  4176 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:52:13.268  4154  4170 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:52:13.268  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:13.270  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:13.270  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:52:13.271  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:13.273  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:13.277  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:52:13.283  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:52:13.468  4154  4170 I bt_hci  : shut_down
,09-12 13:52:13.468  4154  4174 D bt_hwcfg: hw_epilog_process
,09-12 13:52:13.470  4154  4174 I bt_vendor: low_power_mode_cb
,09-12 13:52:13.491  4154  4174 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:52:13.491  4154  4174 I bt_vendor: epilog_cb
09-12 13:52:13.491  4154  4174 I bt_hci  : epilog_finished_callback
,09-12 13:52:13.512  4154  4170 I bt_hci_h4: hal_close
,09-12 13:52:13.514  4154  4170 I bt_userial_vendor: device fd = 51 close
,09-12 13:52:13.650  4154  4167 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:52:13.651  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:52:13.658  4154  4166 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:52:13.659  4154  4154 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:52:13.661  4154  4154 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:52:13.661  4154  4154 D BtGatt.GattService: stop()
09-12 13:52:13.661  4154  4154 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:52:13.667  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:13.668  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-12 13:52:13.668  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:52:13.668  4154  4154 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 13:52:13.670  4154  4166 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 13:52:13.670  4154  4166 D BluetoothAdapterProperties: Setting state to 10
,09-12 13:52:13.671  4154  4166 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 13:52:13.674  4154  4166 I BluetoothAdapterState: Entering OffState
09-12 13:52:13.675   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 13:52:13.696  4154  4154 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 13:52:13.696  4154  4154 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:52:13.696  4154  4167 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:52:13.697  4154  4154 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:52:13.700  4154  4167 D bt_stack_manager: event_clean_up_stack finished.
,09-12 13:52:13.702  4154  4154 I art     : System.exit called, status: 0
09-12 13:52:13.702  4154  4154 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:52:13.767   873  1981 I ActivityManager: Process com.android.bluetooth (pid 4154) has died
,09-12 13:52:14.546   873  1308 D ConnectivityService: handlePromptUnvalidated 102
,09-12 13:52:14.828  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:52:14.834  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:52:14.836  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:52:14.869  1522  2321 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 13:52:14.869  1522  2321 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:52:14.870  1522  2321 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:52:14.870  1522  2321 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:52:14.898  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 13:52:14.899  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:52:14.899  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 13:52:16.170  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:16.170  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:19.178  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:19.178  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f077d60 added. We now have 6 listener(s)
09-12 13:52:19.179  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:19.183  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:19.183  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a3d219 added. We now have 7 listener(s)
09-12 13:52:19.183  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:19.185  3978  4025 I System.out: IsBluetoothEnabled
,09-12 13:52:19.198  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:19.248   873   890 I ActivityManager: Start proc 4211:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:52:19.376  4211  4211 D AdapterServiceConfig: Adding HeadsetService
,09-12 13:52:19.376  4211  4211 D AdapterServiceConfig: Adding A2dpService
09-12 13:52:19.377  4211  4211 D AdapterServiceConfig: Adding HidService
09-12 13:52:19.377  4211  4211 D AdapterServiceConfig: Adding HealthService
,09-12 13:52:19.377  4211  4211 D AdapterServiceConfig: Adding PanService
09-12 13:52:19.378  4211  4211 D AdapterServiceConfig: Adding GattService
09-12 13:52:19.378  4211  4211 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:52:19.397   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ed284c:true
,09-12 13:52:19.398  4211  4211 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 13:52:19.403  4211  4211 I bt_bluedroid: init
,09-12 13:52:19.404  4211  4223 I BluetoothAdapterState: Entering OffState
,09-12 13:52:19.410  4211  4224 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:52:19.410  4211  4224 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 13:52:19.410  4211  4224 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:52:19.411  4211  4224 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:52:19.413  4211  4211 I bt_bluedroid: get_profile_interface socket
,09-12 13:52:19.416  4211  4211 I bt_bluedroid: get_profile_interface sdp
,09-12 13:52:19.418  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:52:19.432  4211  4222 I bt_bluedroid: config_hci_snoop_log
,09-12 13:52:19.433  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
09-12 13:52:19.436   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:52:19.447  4211  4223 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:52:19.448  4211  4223 D BluetoothAdapterProperties: Setting state to 14
09-12 13:52:19.448  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:52:19.453  4211  4223 D BluetoothBondStateMachine: make
,09-12 13:52:19.458  4211  4228 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:52:19.466  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:52:19.468  4211  4211 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:52:19.474  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:19.475  4211  4211 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:52:19.477  4211  4211 D BtGatt.GattService: Received start request. Starting profile...
,09-12 13:52:19.477  4211  4211 D BtGatt.GattService: start()
,09-12 13:52:19.477  4211  4211 I bt_bluedroid: get_profile_interface gatt
09-12 13:52:19.479  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:19.479  4211  4211 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:52:19.493  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:19.493  4211  4211 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:52:19.493  4211  4211 V BluetoothAdapterState: isBleTurningOn()=true
09-12 13:52:19.494  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:19.495  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:52:19.495  4211  4223 I bt_bluedroid: enable
09-12 13:52:19.496  4211  4224 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 13:52:19.496  4211  4224 I bt_hci  : start_up
,09-12 13:52:19.514  4211  4224 I bt_vendor: alloc value 0xb3a7e189
,09-12 13:52:19.514  4211  4224 I bt_vendor: init
,09-12 13:52:19.514  4211  4224 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 13:52:19.515  4211  4224 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:52:19.625  4211  4224 D bt_hci  : start_up starting async portion
,09-12 13:52:19.626  4211  4231 I bt_hci  : event_finish_startup
09-12 13:52:19.626  4211  4231 I bt_hci_h4: hal_open
09-12 13:52:19.626  4211  4231 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:52:19.635  4211  4231 I bt_userial_vendor: device fd = 51 open
,09-12 13:52:19.666  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:52:19.698  4211  4231 D bt_hwcfg: Chipset BCM4354A2
,09-12 13:52:19.699  4211  4231 D bt_hwcfg: Target name = [BCM4354A2]
09-12 13:52:19.700  4211  4231 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:52:20.355  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:52:20.357  4211  4231 D bt_hwcfg: Settlement delay -- 100 ms
09-12 13:52:20.358  4211  4231 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:52:20.475  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:52:20.476  4211  4231 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:52:20.505  4211  4231 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:52:20.505  4211  4231 I bt_vendor: firmware callback
09-12 13:52:20.505  4211  4231 I bt_hci  : firmware_config_callback
,09-12 13:52:20.517  4211  4233 I bt_btu  : btu_task pending for preload complete event
,09-12 13:52:20.517  4211  4233 I bt_btu_task: Bluetooth chip preload is complete
09-12 13:52:20.518  4211  4233 I bt_btu  : btu_task received preload complete event
,09-12 13:52:20.527  4211  4233 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:52:20.528  4211  4233 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:52:20.528  4211  4233 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:52:20.528  4211  4233 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:52:20.529  4211  4233 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:52:20.529  4211  4233 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 13:52:20.529  4211  4233 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 13:52:20.529  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:52:20.530  4211  4233 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:52:20.530  4211  4233 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:52:20.530  4211  4233 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:52:20.530  4211  4233 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:52:20.531  4211  4233 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:52:20.531  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:52:20.531  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:52:20.666  4211  4233 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fbd9d
,09-12 13:52:20.667  4211  4233 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fbd9d 
,09-12 13:52:20.697  4211  4227 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:52:20.698  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 13:52:20.699  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:52:20.703  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:52:20.705  4211  4227 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:52:20.705  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:52:20.706  4211  4227 D bt_hci  : do_postload posting postload work item
09-12 13:52:20.707  4211  4231 I bt_hci  : event_postload
09-12 13:52:20.707  4211  4231 I bt_vendor: sco_config_cb
,09-12 13:52:20.707  4211  4231 I bt_hci  : sco_config_callback postload finished.
,09-12 13:52:20.710  4211  4227 D bt_bte_conf: Device ID record 1 : primary
,09-12 13:52:20.710  4211  4227 D bt_bte_conf:   vendorId            = 000f
,09-12 13:52:20.710  4211  4227 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:52:20.710  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:20.711  4211  4227 D bt_bte_conf:   product             = 1200
09-12 13:52:20.711  4211  4227 D bt_bte_conf:   version             = 1436
09-12 13:52:20.711  4211  4227 D bt_bte_conf:   clientExecutableURL = 
09-12 13:52:20.711  4211  4227 D bt_bte_conf:   serviceDescription  = 
09-12 13:52:20.711  4211  4227 D bt_bte_conf:   documentationURL    = 
09-12 13:52:20.712  4211  4227 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 13:52:20.714  4211  4224 D bt_stack_manager: event_start_up_stack finished
,09-12 13:52:20.714  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 13:52:20.714  4211  4231 I bt_vendor: low_power_mode_cb
,09-12 13:52:20.715  4211  4223 D BluetoothAdapterProperties: Setting state to 15,
,09-12 13:52:20.715  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 13:52:20.717  4211  4223 I BluetoothAdapterState: Entering BleOnState
,09-12 13:52:20.719  4211  4223 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 13:52:20.719  4211  4223 D BluetoothAdapterProperties: Setting state to 11
,09-12 13:52:20.720  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 13:52:20.727  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:20.729  4211  4211 D HeadsetService: Received start request. Starting profile...
09-12 13:52:20.733  4211  4211 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:52:20.733  4211  4211 D HeadsetStateMachine: make
09-12 13:52:20.741  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:20.751  4211  4211 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:52:20.751  4211  4211 I bt_bluedroid: get_profile_interface handsfree
,09-12 13:52:20.751  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:52:20.751  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:52:20.752  4211  4227 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 13:52:20.756  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:20.756  4211  4211 D A2dpService: Received start request. Starting profile...
,09-12 13:52:20.757  4211  4211 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:52:20.757  4211  4211 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:52:20.763  4211  4211 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:52:20.763  4211  4211 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:52:20.763  4211  4211 D A2dpStateMachine: make
,09-12 13:52:20.764  4211  4211 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:52:20.765  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:52:20.767  4211  4242 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:52:20.768  4211  4211 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:52:20.768  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:20.769  4211  4211 D HidService: Received start request. Starting profile...
,09-12 13:52:20.769  4211  4211 I bt_bluedroid: get_profile_interface hidhost
09-12 13:52:20.769  4211  4211 D HidService: setHidService(): set to: null
09-12 13:52:20.769  4211  4227 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39dd3e5
09-12 13:52:20.769  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 13:52:20.770  4211  4211 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:52:20.770  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
09-12 13:52:20.771  4211  4211 D HealthService: Received start request. Starting profile...
,09-12 13:52:20.772  4211  4211 I bt_bluedroid: get_profile_interface health
,09-12 13:52:20.774  4211  4211 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:52:20.775  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:20.776  4211  4211 D PanService: Received start request. Starting profile...
,09-12 13:52:20.776  4211  4211 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:52:20.776  4211  4211 I bt_bluedroid: get_profile_interface pan
09-12 13:52:20.776  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:52:20.776  4211  4227 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:52:20.779  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:20.779  4211  4211 D BluetoothMapService: Received start request. Starting profile...
09-12 13:52:20.779  4211  4211 D BluetoothMapService: start()
,09-12 13:52:20.781  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:52:20.782  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:52:20.782  4211  4211 D BluetoothMapAppObserver: createReceiver()
,09-12 13:52:20.783  4211  4211 D BluetoothMapAppObserver: initObservers()
,09-12 13:52:20.783  4211  4211 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:52:20.789  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:20.789  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:52:20.789  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.789  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:20.791  4211  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.791  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.792  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:20.795  4211  4211 V BluetoothAdapterState: isTurningOff()=false
09-12 13:52:20.795  4211  4211 V BluetoothAdapterState: isTurningOn()=true
09-12 13:52:20.795  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:52:20.795  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:52:20.795  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:52:20.796  4211  4223 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:52:20.796  4211  4223 D BluetoothAdapterProperties: State =  11
09-12 13:52:20.796  4211  4223 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:52:20.796  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:52:20.797  1352  1369 D BluetoothPan: onBluetoothStateChange on: true
,09-12 13:52:20.798  4211  4223 I BluetoothAdapterState: Entering OnState
,09-12 13:52:20.799  4211  4227 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:52:20.799  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:52:20.800  4032  4042 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:52:20.801  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:52:20.801  1352  1352 D PanProfile: Bluetooth service connected
,09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:20.803  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:20.803  4032  4043 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:52:20.805  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:20.806  4032  4042 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:52:20.808  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 13:52:20.808  4032  4043 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:52:20.809  4211  4211 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 13:52:20.810  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:20.811  1352  2042 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:52:20.811  4032  4032 D BluetoothMap: Proxy object connected
,09-12 13:52:20.812  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:20.813  4032  4032 D MapProfile: Bluetooth service connected
,09-12 13:52:20.813   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:20.813  4032  4032 D BluetoothMap: getConnectedDevices()
09-12 13:52:20.813  1352  1369 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:20.813  4211  4211 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:52:20.813  4211  4211 D ObexServerSockets0: startAccept()
09-12 13:52:20.813  4211  4211 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:52:20.814  4032  4042 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:52:20.814  1352  1363 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:52:20.815  4211  4211 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:52:20.816  4211  4211 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:52:20.816  4032  4032 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:52:20.816  4032  4032 D PanProfile: Bluetooth service connected
,09-12 13:52:20.816  1352  1352 D BluetoothMap: Proxy object connected
09-12 13:52:20.816  1352  1352 D MapProfile: Bluetooth service connected
09-12 13:52:20.816  4211  4249 D ObexServerSockets0: Accepting socket connection...
09-12 13:52:20.816  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 13:52:20.817   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:20.817   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:52:20.817  4032  4247 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:52:20.817  4211  4248 D ObexServerSockets0: Accepting socket connection...
09-12 13:52:20.818  1352  1352 D BluetoothInputDevice: Proxy object connected
09-12 13:52:20.818  1352  1352 D HidProfile: Bluetooth service connected
09-12 13:52:20.819  4032  4032 D BluetoothA2dp: Proxy object connected
09-12 13:52:20.819  1352  2042 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:52:20.820  4032  4032 D BluetoothInputDevice: Proxy object connected
09-12 13:52:20.821  4032  4032 D HidProfile: Bluetooth service connected
09-12 13:52:20.821   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:52:20.821   873   873 D BluetoothA2dp: Proxy object connected
09-12 13:52:20.821  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:52:20.823  1937  1952 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:52:20.823  1352  1352 D BluetoothA2dp: Proxy object connected
09-12 13:52:20.825   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 13:52:20.826  4211  4211 D BluetoothMapService: onReceive
09-12 13:52:20.826  4211  4211 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:52:20.826  4211  4211 D BluetoothMapService: STATE_ON
09-12 13:52:20.827  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:20.833  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:52:20.839  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:52:20.839  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:52:20.848  4032  4032 D BluetoothPbap: Proxy object connected
,09-12 13:52:20.848  4032  4032 D PbapServerProfile: Bluetooth service connected
,09-12 13:52:20.850  1352  1352 D BluetoothPbap: Proxy object connected
,09-12 13:52:20.851  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-12 13:52:20.854  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 13:52:20.854  4211  4211 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:52:20.857  4211  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:20.873  4211  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:52:20.875  4211  4259 I BtOppRfcommListener: Accept thread started.
,09-12 13:52:20.915  4032  4043 D BluetoothHeadset: Proxy object connected
,09-12 13:52:20.915  4032  4032 D HeadsetProfile: Bluetooth service connected
09-12 13:52:20.915   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:52:20.915   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:52:20.916   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:52:20.916  1352  2042 D BluetoothHeadset: Proxy object connected
09-12 13:52:20.916  1352  1352 D HeadsetProfile: Bluetooth service connected
09-12 13:52:20.917  1937  2219 D BluetoothHeadset: Proxy object connected
09-12 13:52:20.917   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:52:20.918   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:52:20.923  1937  1951 D BluetoothHeadset: Proxy object connected
,09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:21.221  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:21.228  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:21.231  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:21.232  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61a42de added. We now have 8 listener(s)
09-12 13:52:21.232  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:21.238   873   883 D WifiService: setWifiEnabled: false pid=3978, uid=10000
,09-12 13:52:21.238   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:52:21.250  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:21.251   873  1980 D WifiService: setWifiEnabled: true pid=3978, uid=10000
09-12 13:52:21.251   873  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:52:21.267   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:21.287  3978  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:21.289  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:21.293  3978  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:21.295  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:21.299   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:52:21.300  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-12 13:52:21.300   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 13:52:21.301  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:52:21.301   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 13:52:21.302   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:52:21.302   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:52:21.303   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 13:52:21.303   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:52:21.303  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@22dfc07 Bundle[{}]
,09-12 13:52:21.303  3978  4025 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:52:21.304  3978  4025 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 13:52:21.304  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:52:21.305  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:52:21.305  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 13:52:21.306  3978  4025 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:52:21.310  3978  4025 I System.out: Running OutgoingSocketThread
,09-12 13:52:21.312  3978  4264 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 440)
,09-12 13:52:21.313  3978  4264 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42207
,09-12 13:52:21.314  3978  4264 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-12 13:52:21.314   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:52:21.315   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:21.315   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:21.316   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '182 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 182 Failed to set address (No such device)'
09-12 13:52:21.316   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:52:21.367   873  1305 E native  : do suspend true
,09-12 13:52:21.388   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:21.390   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:52:21.392   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:52:22.313  3978  4025 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 441)
09-12 13:52:22.314  3978  4025 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 441)
,09-12 13:52:22.323  3978  4025 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,09-12 13:52:22.325  3978  4025 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 13:52:22.326  3978  4025 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,09-12 13:52:22.331  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:52:22.331  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f424cbf added. We now have 2 listener(s)
,09-12 13:52:22.333  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.333  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:52:22.333  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:52:22.334  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.334  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d570f8c added. We now have 9 listener(s)
,09-12 13:52:22.334  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:22.334  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:52:22.337  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:22.347  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:22.350  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:22.351  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:22.351  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.352  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.352  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a83aeea added. We now have 3 listener(s)
09-12 13:52:22.353  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:22.357  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:52:22.358  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.358  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:52:22.359  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:22.359  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c58f5db added. We now have 10 listener(s)
09-12 13:52:22.359  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.360  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:22.360  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:22.360  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:22.360  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:52:22.361  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.361  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.361  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:52:22.361  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f424cbf removed from the list
,09-12 13:52:22.362  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:22.362  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d570f8c removed from the list
09-12 13:52:22.362  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:22.362  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:22.363  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.364  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.365  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:52:22.365  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.365  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.366  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d570f8c not in the list
,09-12 13:52:22.366  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.366  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:22.368  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.369  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.369  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:22.370  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c58f5db removed from the list
09-12 13:52:22.370  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.370  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.370  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.370  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:52:22.370  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a83aeea removed from the list
09-12 13:52:22.372  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.372  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2b9878 added. We now have 2 listener(s)
,09-12 13:52:22.376  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:52:22.377  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.377  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:52:22.377  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.377  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ab51 added. We now have 9 listener(s)
09-12 13:52:22.378  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:22.378  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:52:22.382  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:22.387  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:22.389  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:22.390  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:52:22.390  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.390  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76714b7 added. We now have 3 listener(s)
09-12 13:52:22.392  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.392  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.392  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.392  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.392  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbdc424 added. We now have 10 listener(s)
09-12 13:52:22.392  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.393  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:22.393  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.393  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:52:22.393  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:52:22.393  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:22.393  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:22.394  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.397  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:22.397  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:52:22.401  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:52:22.401  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:52:22.402  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:52:22.405  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:52:22.405  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:52:22.405  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:52:22.406  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:22.409  4211  4222 D BtGatt.GattService: registerClient() - UUID=43e5cd79-67f1-4f70-a403-832c17d828fa
09-12 13:52:22.410  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=43e5cd79-67f1-4f70-a403-832c17d828fa, clientIf=5
09-12 13:52:22.410  3978  3988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:52:22.412  4211  4251 D BtGatt.GattService: start scan with filters
09-12 13:52:22.416  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:52:22.416  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:52:22.416  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:52:22.416  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:52:22.417  4211  4230 D BtGatt.ScanManager: handling starting scan
09-12 13:52:22.419  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:22.419  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:52:22.419  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:22.420  4211  4230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@329082b
,09-12 13:52:22.421  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 13:52:22.423  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:22.423  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.424  3978  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:52:22.424  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:22.424  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:52:22.424  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.424  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:52:22.424  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:52:22.424  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:52:22.424  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:22.424  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:52:22.424  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:52:22.424  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:52:22.425  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:52:22.425  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:22.426  4211  4222 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:52:22.426  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:52:22.427  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.427  4211  4251 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:52:22.427  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:52:22.427  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:52:22.427  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:22.427  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:52:22.427  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:52:22.428  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:22.428  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:52:22.429  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.429  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:52:22.429  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:22.429  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:52:22.430  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.431  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.431  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.431  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.431  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:52:22.431  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.434  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:22.434  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:22.434  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:22.434  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.434  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.434  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:52:22.434  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.434  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.434  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.434  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2b9878 removed from the list
09-12 13:52:22.434  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.435  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ab51 removed from the list
09-12 13:52:22.435  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:22.435  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.435  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.435  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.436  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.436  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.436  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.436  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ab51 not in the list
09-12 13:52:22.437  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.437  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.438  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.438  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.438  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.438  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbdc424 removed from the list
09-12 13:52:22.438  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.438  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.438  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.439  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.439  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76714b7 removed from the list
09-12 13:52:22.439  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.439  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:22.440  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324fe90 added. We now have 2 listener(s)
09-12 13:52:22.440  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.440  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:52:22.441  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.441  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.442  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.442  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.442  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb07389 added. We now have 9 listener(s)
09-12 13:52:22.442  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.442  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:52:22.443  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:52:22.443  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.444  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:52:22.445  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:22.446  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:22.446  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:22.449  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:22.452  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:22.452  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:52:22.452  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.452  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76de3af added. We now have 3 listener(s)
09-12 13:52:22.454  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.454  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.455  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.455  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.455  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.455  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8373bc added. We now have 10 listener(s)
09-12 13:52:22.455  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.455  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.455  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:22.457  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:22.457  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:52:22.457  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:52:22.457  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:22.457  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:22.460  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:22.460  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:52:22.463  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:52:22.464  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:52:22.464  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:52:22.467  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:52:22.467  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:52:22.467  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:52:22.467  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:22.469  4211  4221 D BtGatt.GattService: registerClient() - UUID=5f172386-86c2-4f08-ad2a-ad2b4d5f81a7
09-12 13:52:22.470  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=5f172386-86c2-4f08-ad2a-ad2b4d5f81a7, clientIf=5
09-12 13:52:22.470  3978  3989 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:52:22.470  4211  4240 D BtGatt.GattService: start scan with filters
09-12 13:52:22.473  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:52:22.473  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:52:22.473  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:52:22.473  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:52:22.473  4211  4230 D BtGatt.ScanManager: handling starting scan
09-12 13:52:22.475  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:22.475  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:52:22.476  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:52:22.476  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:22.476  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.476  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:52:22.477  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 13:52:22.478  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:52:22.478  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.478  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:52:22.478  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:52:22.479  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:22.479  3978  4025 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:52:22.479  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:52:22.480  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:22.480  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:52:22.480  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.480  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.480  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:52:22.480  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.480  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324fe90 removed from the list
09-12 13:52:22.480  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.480  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb07389 removed from the list
09-12 13:52:22.480  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:52:22.480  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.481  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.481  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 13:52:22.481  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.481  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.482  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:52:22.482  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.482  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.482  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.482  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.482  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb07389 not in the list
09-12 13:52:22.482  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:52:22.482  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:52:22.482  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:52:22.483  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:52:22.483  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:52:22.483  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:22.484  4211  4240 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:52:22.484  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:52:22.484  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.484  4211  4222 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:52:22.484  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:52:22.484  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:52:22.484  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:22.485  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:52:22.485  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:22.485  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.486  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:52:22.486  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:22.486  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:52:22.486  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.487  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.487  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.487  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.487  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.487  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8373bc removed from the list
09-12 13:52:22.487  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.487  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.487  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.487  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.487  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.487  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.487  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76de3af removed from the list
09-12 13:52:22.488  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.488  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f20fa8 added. We now have 2 listener(s)
09-12 13:52:22.488  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:22.488  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.488  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:52:22.490  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.490  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.490  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.490  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.490  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc60ac1 added. We now have 9 listener(s)
09-12 13:52:22.490  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.491  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:52:22.492  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:52:22.492  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.492  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:52:22.493  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:22.494  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:22.494  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:22.497  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:52:22.499  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:52:22.499  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:52:22.499  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.499  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab099a7 added. We now have 3 listener(s)
09-12 13:52:22.500  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.501  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.501  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.501  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.501  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:52:22.501  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2c7e54 added. We now have 10 listener(s)
,09-12 13:52:22.501  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:52:22.501  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:52:22.501  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:52:22.501  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:52:22.502  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:52:22.502  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:52:22.502  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:22.504  3978  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:52:22.504  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:52:22.508  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:52:22.509  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:52:22.509  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:52:22.512  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:52:22.512  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:52:22.512  3978  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:52:22.513  3978  4025 D BluetoothAdapter: STATE_ON
,09-12 13:52:22.515  4211  4250 D BtGatt.GattService: registerClient() - UUID=2a36b18b-ec98-4fce-b5c3-6c9016eda7ae
,09-12 13:52:22.515  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=2a36b18b-ec98-4fce-b5c3-6c9016eda7ae, clientIf=5
,09-12 13:52:22.516  3978  3989 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:52:22.516  4211  4221 D BtGatt.GattService: start scan with filters
,09-12 13:52:22.518  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:52:22.519  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:52:22.519  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:52:22.519  4211  4230 D BtGatt.ScanManager: handling starting scan
09-12 13:52:22.519  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:52:22.521  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:52:22.521  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:52:22.521  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:52:22.523  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:52:22.527  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:22.527  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:22.527  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:22.527  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:52:22.527  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.527  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:52:22.527  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.527  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f20fa8 removed from the list,
09-12 13:52:22.528  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 13:52:22.528  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc60ac1 removed from the list
,09-12 13:52:22.528  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:22.528  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:52:22.528  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.528  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
09-12 13:52:22.528  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.528  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:52:22.529  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 13:52:22.529  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-12 13:52:22.529  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.530  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc60ac1 not in the list
,09-12 13:52:22.530  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:52:22.530  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:52:22.530  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:52:22.530  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-12 13:52:22.530  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:52:22.531  3978  4025 D BluetoothAdapter: STATE_ON
09-12 13:52:22.531  4211  4240 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:52:22.532  4211  4250 D BtGatt.GattService: unregisterClient() - clientIf=5,
09-12 13:52:22.532  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:52:22.532  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:52:22.532  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:52:22.532  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:52:22.532  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:52:22.532  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:52:22.532  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.533  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:52:22.536  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.537  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:52:22.537  3978  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:52:22.537  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:52:22.538  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.539  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.540  3978  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:52:22.540  3978  3978 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:52:22.540  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:52:22.540  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:52:22.540  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.540  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:52:22.540  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.540  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2c7e54 removed from the list
,09-12 13:52:22.540  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.541  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.541  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.541  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:52:22.541  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.541  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab099a7 removed from the list
,09-12 13:52:22.541  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:52:22.543  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:52:22.543  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd2bc0 added. We now have 2 listener(s)
,09-12 13:52:22.548  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:52:22.548  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:52:22.548  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:52:22.549  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:22.549  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca050f9 added. We now have 9 listener(s)
09-12 13:52:22.549  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:22.550  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:52:22.552  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 13:52:22.552  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:52:22.552  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:52:22.556  3978  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:52:22.558  3978  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:52:22.558  3978  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:52:22.558  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:52:22.559  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5169f added. We now have 3 listener(s)
09-12 13:52:22.559  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:52:22.560  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:52:22.560  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:52:22.560  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:52:22.560  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:52:22.561  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96943ec added. We now have 10 listener(s)
09-12 13:52:22.561  3978  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:52:22.561  3978  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:52:22.561  3978  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:52:22.561  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:52:22.562  3978  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:52:22.562  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:52:22.562  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.562  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:52:22.562  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:52:22.563  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd2bc0 removed from the list
09-12 13:52:22.563  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:22.563  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca050f9 removed from the list
09-12 13:52:22.563  3978  4025 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:52:22.563  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.563  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.563  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.564  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:52:22.564  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:22.564  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.564  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:22.564  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:22.564  3978  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca050f9 not in the list
,09-12 13:52:22.565  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:52:22.565  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:52:22.566  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:52:22.566  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:52:22.566  3978  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:52:22.566  3978  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96943ec removed from the list
09-12 13:52:22.566  3978  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:52:22.566  3978  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:52:22.566  3978  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:52:22.566  3978  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:52:22.566  3978  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5169f removed from the list
,09-12 13:52:22.567  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:52:22.567  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:52:22.567  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:52:22.567  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:52:22.567  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:52:22.568  3978  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:52:22.574  3978  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
09-12 13:52:22.575  3978  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: My test thread name)
,09-12 13:52:22.576  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:52:22.576  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:52:22.575  3978  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 13:52:22.577  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:52:22.581  3978  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,09-12 13:52:22.582  3978  4267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: My test thread name)
09-12 13:52:22.582  3978  4267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 13:52:22.585  3978  4025 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-12 13:52:22.585  3978  4025 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-12 13:52:22.585  3978  4025 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 13:52:22.585  3978  4025 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-12 13:52:22.585  3978  4025 D com.test.thalitest.ThaliTestRunner: Total duration: 21813 ms
09-12 13:52:22.586  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 13:52:22.586  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.586  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:52:22.588  3978  4025 I jxcore-log: *Native tests were executed*
09-12 13:52:22.588  3978  4025 I jxcore-log: 
09-12 13:52:22.588  3978  4025 I jxcore-log: Total number of executed tests:  80
09-12 13:52:22.588  3978  4025 I jxcore-log: 
,09-12 13:52:22.588  3978  4025 I jxcore-log: Number of passed tests:  80
09-12 13:52:22.588  3978  4025 I jxcore-log: 
09-12 13:52:22.588  3978  4025 I jxcore-log: Number of failed tests:  0
09-12 13:52:22.588  3978  4025 I jxcore-log: 
,09-12 13:52:22.589  3978  4025 I jxcore-log: Number of ignored tests:  0
09-12 13:52:22.589  3978  4025 I jxcore-log: 
09-12 13:52:22.589  3978  4025 I jxcore-log: Total duration:  21813
09-12 13:52:22.589  3978  4025 I jxcore-log: 
,09-12 13:52:22.589  3978  4025 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:52:22.589  3978  4025 I jxcore-log: 
,09-12 13:52:22.595  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.595  3978  4025 I jxcore-log: 
09-12 13:52:22.596  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:52:22.596  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:52:22.600  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.600  3978  4025 I jxcore-log: 
09-12 13:52:22.602  3978  3978 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:52:22.602  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.602  3978  4025 I jxcore-log: 
09-12 13:52:22.604  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.604  3978  4025 I jxcore-log: 
09-12 13:52:22.605  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.605  3978  4025 I jxcore-log: 
09-12 13:52:22.608  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.608  3978  4025 I jxcore-log: 
,09-12 13:52:22.611  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.611  3978  4025 I jxcore-log: 
,09-12 13:52:22.612  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.612  3978  4025 I jxcore-log: 
,09-12 13:52:22.613  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.613  3978  4025 I jxcore-log: 
,09-12 13:52:22.614  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.614  3978  4025 I jxcore-log: 
,09-12 13:52:22.615  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.615  3978  4025 I jxcore-log: 
,09-12 13:52:22.616  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:52:22.616  3978  4025 I jxcore-log: 
,09-12 13:52:22.617  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.617  3978  4025 I jxcore-log: 
,09-12 13:52:22.618  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.618  3978  4025 I jxcore-log: 
,09-12 13:52:22.619  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.619  3978  4025 I jxcore-log: 
,09-12 13:52:22.619  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:52:22.619  3978  4025 I jxcore-log: 
,09-12 13:52:22.620  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.620  3978  4025 I jxcore-log: 
,09-12 13:52:22.621  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.621  3978  4025 I jxcore-log: 
,09-12 13:52:22.622  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.622  3978  4025 I jxcore-log: 
,09-12 13:52:22.622  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.622  3978  4025 I jxcore-log: 
,09-12 13:52:22.623  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.623  3978  4025 I jxcore-log: 
,09-12 13:52:22.624  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.624  3978  4025 I jxcore-log: 
,09-12 13:52:22.625  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.625  3978  4025 I jxcore-log: 
,09-12 13:52:22.625  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:52:22.625  3978  4025 I jxcore-log: 
,09-12 13:52:22.626  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.626  3978  4025 I jxcore-log: 
,09-12 13:52:22.627  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.627  3978  4025 I jxcore-log: 
,09-12 13:52:22.627  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.627  3978  4025 I jxcore-log: 
,09-12 13:52:22.628  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.628  3978  4025 I jxcore-log: 
,09-12 13:52:22.629  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.629  3978  4025 I jxcore-log: 
,09-12 13:52:22.630  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.630  3978  4025 I jxcore-log: 
,09-12 13:52:22.630  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:52:22.630  3978  4025 I jxcore-log: 
,09-12 13:52:22.669   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:52:22.784   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.50 rxSuccessRate=12.94 delta 1000 -> 994
,09-12 13:52:22.785   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 13:52:22.785   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:52:22.807   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:52:22.858   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:52:22.860  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:52:22.932  3978  3978 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:52:22.934  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:52:22.934  3978  4025 I jxcore-log: 
,09-12 13:52:22.988  3978  3978 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:52:22.991  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:52:22.991  3978  4025 I jxcore-log: 
,09-12 13:52:23.041  3978  3978 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:52:23.044  3978  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:52:23.044  3978  4025 I jxcore-log: 
,09-12 13:52:23.256  4268  4268 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 13:52:23.261  4268  4268 D AndroidRuntime: CheckJNI is OFF
,09-12 13:52:23.274  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:52:23.312  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:52:23.312  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:52:23.317   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:52:23.321   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 13:52:23.321   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:52:23.321   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:52:23.335   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:52:23.336  4268  4268 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 13:52:23.342   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:23.342   873  1305 D WifiStateMachine: Start Dhcp Watchdog 4
,09-12 13:52:23.348   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:52:23.374   873  4277 D DhcpClient: Receive thread started
,09-12 13:52:23.390  4268  4268 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 13:52:23.414  4268  4268 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:52:23.422   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 13:52:23.422   873   886 I ActivityManager: Killing 3978:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 13:52:23.453   873  1305 E native  : do suspend false
,09-12 13:52:23.463   873  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:52:23.497   873  4277 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-12 13:52:23.525   873  1980 D GraphicsStats: Buffer count: 2
,09-12 13:52:23.525   873  1709 I WindowState: WIN DEATH: Window{625447 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:52:23.525   873  1307 D WifiService: Client connection lost with reason: 4
09-12 13:52:23.544   873   896 W PackageSettings: Skipping PackageSetting{f9176ec com.example.hello/10273} due to missing metadata
,09-12 13:52:23.575   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-12 13:52:23.575   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-12 13:52:23.577   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 13:52:23.577   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 13:52:23.577   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:23.577   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.577   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:52:23.577   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-12 13:52:23.577   873   886 I ActivityManager:   Force finishing activity ActivityRecord{1a76580 u0 com.test.thalitest/.MainActivity t4}
,09-12 13:52:23.577   873   896 I art     : Starting a blocking GC Explicit
,09-12 13:52:23.594   873  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-12 13:52:23.594   873  1981 W ActivityManager: Spurious death for ProcessRecord{4dbac79 0:com.test.thalitest/u0a0}, curProc for 3978: null
09-12 13:52:23.595   873  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:52:23.614   873  4277 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:52:23.615   873  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:52:23.616   374   871 D CommandListener: Setting iface cfg
,09-12 13:52:23.619   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:52:23.621   873  1888 D DhcpClient: Scheduling renewal in 86399s
,09-12 13:52:23.621   873  1305 E native  : do suspend true
,09-12 13:52:23.628   873   896 I art     : Explicit concurrent mark sweep GC freed 41170(2MB) AllocSpace objects, 8(204KB) LOS objects, 33% free, 29MB/43MB, paused 1.066ms total 48.147ms
,09-12 13:52:23.636   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:52:23.637   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:52:23.638   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:52:23.638   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 13:52:23.639   873  1308 D ConnectivityService: Adding iface wlan0 to network 103
,09-12 13:52:23.654   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 13:52:23.657  4268  4268 I art     : System.exit called, status: 0
,09-12 13:52:23.657  4268  4268 I AndroidRuntime: VM exiting with result code 0.
,09-12 13:52:23.660   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 13:52:23.673   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:52:23.673   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
09-12 13:52:23.674   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
09-12 13:52:23.675   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
09-12 13:52:23.675   873  1308 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,09-12 13:52:23.681   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 13:52:23.689  4211  4211 D BluetoothMapAppObserver: onReceive
,09-12 13:52:23.689  4211  4211 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 13:52:23.695  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 13:52:23.697  1870  4284 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 13:52:23.698   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:52:23.700  2154  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:52:23.701   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
09-12 13:52:23.707   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 103
09-12 13:52:23.707   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
09-12 13:52:23.707  3676  3676 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 13:52:23.707   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 13:52:23.708   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:52:23.708   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
09-12 13:52:23.708   873  1308 D ConnectivityService:    accepting network in place of null
09-12 13:52:23.709   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 13:52:23.709  1870  4284 I Decoder : createOrResetDecoder
,09-12 13:52:23.724   873  4271 D NetlinkSocketObserver: NeighborEvent{elapsedMs=238348, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:52:23.726   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:23.747  1937  1937 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 13:52:23.753   873   884 I ActivityManager: Start proc 4291:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 13:52:23.758  1522  1522 I ConfigService: onCreate
09-12 13:52:23.759   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:52:23.790   873  4270 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:52:23.792  4291  4291 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 13:52:23.805   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 13:52:23.812  1870  4284 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 13:52:23.830   873  3143 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3978 uid 10000
,09-12 13:52:23.831  1955  2067 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 13:52:23.831   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 13:52:23.832   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 13:52:23.832   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 13:52:23.832   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:52:23.832   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 13:52:23.832   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 13:52:23.832   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 13:52:23.832   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:23.832   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.832   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:52:23.833  1870  1870 I Keyboard.Facilitator: onFinishInput()
,09-12 13:52:23.836   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 13:52:23.836   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:52:23.836   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:23.836   873   886 E DropBoxManagerService: 	... 13 more
,09-12 13:52:23.844   873  1942 I ActivityManager: Start proc 4307:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 13:52:23.845  1955  2067 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 13:52:23.845  1955  2067 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1955
09-12 13:52:23.845  1955  2067 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.845  1955  2067 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:52:23.847   873  4314 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:52:23.847   873  4314 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:23.847   873  4314 E DropBoxManagerService: 	... 5 more
,09-12 13:52:23.849   873  1948 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:52:23.853  1955  2067 I Process : Sending signal. PID: 1955 SIG: 9
,09-12 13:52:23.859   873  4270 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:52:23 GMT], X-Android-Received-Millis=[1473681143859], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473681143834]}
,09-12 13:52:23.882  1870  4284 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 13:52:23.884  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 13:52:23.884  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 13:52:23.887  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 13:52:23.887  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 13:52:23.887  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-12 13:52:23.887  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 13:52:23.888  1870  4284 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 13:52:23.888  1870  4284 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 13:52:23.888  1870  4284 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 13:52:23.888  1870  4284 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 13:52:23.888  1870  4284 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 13:52:23.888  1870  4284 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 13:52:23.899  4291  4291 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 13:52:23.916   873  1970 I ActivityManager: Start proc 4325:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 13:52:23.918   873  1980 D GraphicsStats: Buffer count: 1
,09-12 13:52:23.918   873  1933 I WindowState: WIN DEATH: Window{8e19c15 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 13:52:23.929   873  1980 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1955) has died
,09-12 13:52:23.930   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-12 13:52:23.931  4291  4327 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 13:52:23.931   873  1980 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:52:23.947   873  1414 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:52:23.979  4325  4325 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 13:52:23.995  4338  4338 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:23.995  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:52:23.995  4338  4338 D AndroidRuntime: Shutting down VM
,09-12 13:52:23.998  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 13:52:23.999  1522  1522 D AndroidRuntime: Shutting down VM
,09-12 13:52:23.999  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:52:23.999  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
09-12 13:52:23.999  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 13:52:23.999  1522  1522 E AndroidRuntime: 	... 8 more
,09-12 13:52:24.002  4338  4338 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:52:24.002  4338  4338 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4338
09-12 13:52:24.002  4338  4338 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:52:24.002  4338  4338 E AndroidRuntime: 	... 10 more
,09-12 13:52:24.005   873  4352 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:52:24.005   873  4352 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:24.005   873  4352 E DropBoxManagerService: 	... 5 more
09-12 13:52:24.005  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
,09-12 13:52:24.006   873  1981 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:52:24.006  4338  4338 I Process : Sending signal. PID: 4338 SIG: 9
,09-12 13:52:24.008   873  4353 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:52:24.008   873  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:24.008   873  4353 E DropBoxManagerService: 	... 5 more
,09-12 13:52:24.012   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,09-12 13:52:24.012   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:52:24.014   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,09-12 13:52:24.014   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 13:52:24.014   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 13:52:24.014   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
09-12 13:52:24.015   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
09-12 13:52:24.015   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{bf03060 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{4028b5e 1522 com.google.process.gapps/10011/u0 remote:255ec99}: process crashing
09-12 13:52:24.017  2154  2230 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml.bak
09-12 13:52:24.019   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:52:24.029  4291  4306 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:24.029  4291  4306 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:24.029  4291  4306 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:52:24.035   873  2003 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4338) has died
,09-12 13:52:24.036   873  2003 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:52:24.054   873   886 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:52:24.061   873  1980 I ActivityManager: Killing 3729:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 13:52:24.066  1741  4356 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
09-12 13:52:24.066  1741  4356 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@e515d89
,09-12 13:52:24.067   873  1307 D WifiService: Client connection lost with reason: 4
,09-12 13:52:24.090  4291  4306 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-12 13:52:24.095  4291  4327 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:24.095  4291  4327 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:52:24.096  4291  4327 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 13:52:24.096  4291  4327 E AndroidRuntime: Process: android.process.acore, PID: 4291
09-12 13:52:24.096  4291  4327 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:52:24.096  4291  4327 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:52:24.097  4291  4306 I Process : Sending signal. PID: 4291 SIG: 9
,09-12 13:52:24.144   873  1996 I ActivityManager: Process com.google.process.gapps (pid 1522) has died
,09-12 13:52:24.144   873  1996 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-12 13:52:24.144   873  1996 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,09-12 13:52:24.145   873  1996 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
,09-12 13:52:24.147   873  1981 I ActivityManager: Process android.process.acore (pid 4291) has died
09-12 13:52:24.148   873  1981 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30996ms
,09-12 13:52:24.149  1741  1741 W RocketImpressions: ClearcutLogger connection suspended: 1
09-12 13:52:24.150   873  1414 W ActivityManager: Can't find mystery application for Crash from pid=4291 uid=10005: android.os.BinderProxy@b22c251
09-12 13:52:24.151   873  1414 E DropBoxManagerService: Can't write: system_server_crash
09-12 13:52:24.151   873  1414 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop62.tmp: open failed: EROFS (Read-only file system)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:52:24.151   873  1414 E DropBoxManagerService: 	... 11 more
,09-12 13:52:24.160   281   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
