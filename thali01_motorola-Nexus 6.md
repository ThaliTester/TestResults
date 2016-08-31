#### Test 8344405013e13cf_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 14:56:59.642  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 14:56:59.655  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 14:56:59.661  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 14:56:59.736  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 14:56:59.736  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 14:56:59.737  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:56:59.737  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 14:56:59.791  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 14:56:59.793  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 14:56:59.796  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-31 14:57:01.424  3475  3475 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 14:57:01.429  3475  3475 D AndroidRuntime: CheckJNI is OFF
08-31 14:57:01.471  3475  3475 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 14:57:01.522  3475  3475 I Radio-JNI: register_android_hardware_Radio DONE
08-31 14:57:01.543  3475  3475 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 14:57:01.547   869  2046 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 14:57:01.589   869  2046 I ActivityManager: Start proc 3484:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 14:57:01.599  3475  3475 D AndroidRuntime: Shutting down VM
08-31 14:57:01.704  3484  3484 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 14:57:01.728  3484  3484 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 14:57:01.736  3484  3484 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3698-3701)
08-31 14:57:01.736  3484  3484 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 14:57:01.753  3484  3484 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33803c2}
08-31 14:57:01.754  3484  3484 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 14:57:01.754  3484  3484 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 14:57:01.761  3484  3484 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 14:57:01.762  3484  3484 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 14:57:01.786  3484  3499 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-31 14:57:01.793  3484  3484 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 14:57:01.804  3484  3484 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 14:57:01.804  3484  3484 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 14:57:01.804  3484  3484 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 14:57:01.804  3484  3484 I Adreno  : Build Date                       : 10/20/15
08-31 14:57:01.804  3484  3484 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 14:57:01.804  3484  3484 I Adreno  : Local Branch                     : M14
08-31 14:57:01.804  3484  3484 I Adreno  : Remote Branch                    : 
08-31 14:57:01.804  3484  3484 I Adreno  : Remote Branch                    : 
08-31 14:57:01.804  3484  3484 I Adreno  : Reconstruct Branch               : 
,08-31 14:57:01.887   869   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed61e45:true
,08-31 14:57:01.917  3484  3484 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 14:57:01.929  3484  3484 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 14:57:01.988  3484  3522 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 14:57:02.007  3484  3508 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 14:57:02.039  3484  3522 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 14:57:02.055  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-31 14:57:02.099   869   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms (total +532ms)
,08-31 14:57:02.118  3484  3484 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3484
,08-31 14:57:02.214  3484  3484 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 14:57:02.393  3484  3523 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1657685712
,08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 14:57:02.398  3484  3523 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e4501 added. We now have 1 listener(s)
,08-31 14:57:02.402  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 14:57:02.403  3484  3523 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 14:57:02.404  3484  3523 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 14:57:02.405  3484  3523 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 14:57:02.412  3484  3523 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@474ad94 added. We now have 1 listener(s)
08-31 14:57:02.412  3484  3523 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 14:57:02.416   869  1314 D WifiService: New client listening to asynchronous messages
,08-31 14:57:02.416  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 14:57:02.416  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 14:57:02.416  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 14:57:02.417  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 14:57:02.417  3484  3523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 14:57:02.420  3484  3523 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 14:57:02.420  3484  3523 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 14:57:02.427  3484  3523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:02.427  3484  3523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:02.428  3484  3523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 14:57:02.428  3484  3523 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 14:57:02.430  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:02.430  3484  3523 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 14:57:02.463  3484  3484 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 14:57:03.281  3484  3531 W jxcore-log: Initializing JXcore engine
08-31 14:57:03.281  3484  3531 W jxcore-log: JXcore engine is ready
,08-31 14:57:03.349  3531  3531 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 14:57:03.349  3531  3531 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11467]" dev="sockfs" ino=11467 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 14:57:03.349  3531  3531 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 14:57:03.352  3531  3531 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25824]" dev="sockfs" ino=25824 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 14:57:03.367  3484  3531 W jxcore-log: Starting JXcore engine
,08-31 14:57:03.449  3484  3531 W jxcore-log: Platform android
08-31 14:57:03.449  3484  3531 W jxcore-log: 
,08-31 14:57:03.449  3484  3531 W jxcore-log: Process ARCH arm
08-31 14:57:03.449  3484  3531 W jxcore-log: 
,08-31 14:57:03.639  3484  3531 I jxcore-log: JXcore Cordova bridge is ready!
08-31 14:57:03.639  3484  3531 I jxcore-log: 
,08-31 14:57:03.639  3484  3531 W jxcore-log: JXcore engine is started
,08-31 14:57:03.651  3484  3523 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 14:57:03.656  3484  3484 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 14:57:13.008  3484  3531 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 14:57:13.008  3484  3531 I jxcore-log: 
08-31 14:57:13.010  3484  3531 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 14:57:13.010  3484  3531 I jxcore-log: 
,08-31 14:57:13.014  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.014  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.014  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.014  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:13.017  3484  3531 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 14:57:13.017  3484  3531 I jxcore-log: 
,08-31 14:57:13.019  3484  3531 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 14:57:13.019  3484  3531 I jxcore-log: 
,08-31 14:57:13.514  3484  3531 D executeNativeTests: Running unit tests
,08-31 14:57:13.572  3484  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 14:57:13.572  3484  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b added. We now have 2 listener(s)
08-31 14:57:13.573  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 14:57:13.573  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 14:57:13.573  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 14:57:13.573  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 14:57:13.574  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 added. We now have 2 listener(s)
,08-31 14:57:13.574  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 14:57:13.575  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 14:57:13.579  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 14:57:13.580  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.580  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:13.581  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 14:57:13.581  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:13.581  3484  3531 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 14:57:13.583  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 14:57:13.583  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:13.587  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 14:57:13.587  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 14:57:13.592  3484  3531 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 14:57:13.593  3484  3531 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 14:57:13.593  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 14:57:13.593  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 14:57:13.593  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 14:57:13.593  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.594  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.594  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.594  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.594  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.594  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 14:57:13.595  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 14:57:13.595  3484  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b removed from the list
08-31 14:57:13.595  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.595  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 removed from the list
08-31 14:57:13.595  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.595  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.596  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.596  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.596  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.597  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 14:57:13.597  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.597  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.599  3484  3531 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 14:57:13.599  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.599  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.600  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.600  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.600  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.600  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.600  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.600  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.600  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.600  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.600  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.600  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.600  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.600  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.601  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.601  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.602  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.602  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
,08-31 14:57:13.622  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 14:57:13.622  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-31 14:57:13.623  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 14:57:13.623  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 14:57:13.623  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 14:57:13.623  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-31 14:57:13.624  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 14:57:13.624  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 14:57:13.624  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 14:57:13.625  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-31 14:57:13.625  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 14:57:13.625  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 14:57:13.625  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 14:57:13.626  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 14:57:13.626  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 14:57:13.626  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 14:57:13.626  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 14:57:13.627  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 14:57:13.627  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 14:57:13.627  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 14:57:13.627  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 14:57:13.628  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 14:57:13.628  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 14:57:13.628  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 14:57:13.628  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 14:57:13.629  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 14:57:13.629  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 14:57:13.629  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 14:57:13.629  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 14:57:13.630  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 14:57:13.630  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 14:57:13.630  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.631  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.631  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.632  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.632  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.632  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.632  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.632  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.632  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.632  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.632  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.632  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.632  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.633  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.633  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.633  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.633  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.633  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.634  3484  3531 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 14:57:13.635  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.636  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.636  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.636  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.637  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:13.637  3484  3531 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 14:57:13.637  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:13.638  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 14:57:13.638  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 14:57:13.638  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 14:57:13.638  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.638  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 14:57:13.641  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 14:57:13.642  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 14:57:13.642  3484  3484 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 14:57:13.643  3484  3531 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 14:57:13.643  3484  3531 I io.jxcore.node.ConnectionHelper: start: OK
08-31 14:57:13.644  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.644  3484  3531 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-31 14:57:13.645  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.645  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.646  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 14:57:13.646  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.646  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 14:57:13.646  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 14:57:13.646  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 14:57:13.646  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 14:57:13.646  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 14:57:13.647  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 14:57:13.647  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 14:57:13.648  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.648  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.648  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.648  3484  3484 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.648  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.648  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.649  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 14:57:13.649  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.649  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.649  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.649  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.649  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.649  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.649  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.650  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.650  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.650  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.650  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.651  3484  3531 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 14:57:13.653  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.654  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.654  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.655  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.655  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:13.655  3484  3531 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 14:57:13.655  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:13.656  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 14:57:13.656  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 14:57:13.656  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 14:57:13.656  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.656  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 14:57:13.658  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 14:57:13.658  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 14:57:13.658  3484  3484 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 14:57:13.658  3484  3531 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 14:57:13.659  3484  3531 I io.jxcore.node.ConnectionHelper: start: OK
08-31 14:57:13.659  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.659  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.659  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 14:57:13.659  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.659  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 14:57:13.659  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 14:57:13.659  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 14:57:13.659  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 14:57:13.659  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 14:57:13.660  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 14:57:13.660  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 14:57:13.660  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.660  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.660  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.661  3484  3484 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.661  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.661  3484  3531 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 14:57:13.661  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.661  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.661  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.661  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.662  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 14:57:13.662  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.662  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.662  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.662  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.662  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.662  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.662  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.663  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.663  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.663  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.663  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.663  3484  3531 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 14:57:13.664  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.664  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.664  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 14:57:13.664  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.664  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.664  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.665  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.665  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.665  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.665  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.665  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.665  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.665  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.665  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.665  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.665  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.666  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.666  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.666  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 14:57:13.667  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.667  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.667  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.667  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.667  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.667  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.667  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.667  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.667  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.667  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.668  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.668  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.668  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.668  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.668  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.668  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.668  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.668  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.669  3484  3531 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 14:57:13.669  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.669  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.669  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.669  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.669  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.670  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.670  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.670  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.670  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.670  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.670  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.670  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.670  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.670  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.670  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.670  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.671  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.671  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.672  3484  3531 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 14:57:13.672  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.672  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.672  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.672  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.672  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.672  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.672  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.672  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.672  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.673  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.673  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.673  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.673  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.673  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.673  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.673  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.673  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.673  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.674  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 14:57:13.674  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 14:57:13.674  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 14:57:13.674  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 14:57:13.674  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 14:57:13.674  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 14:57:13.674  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.675  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.675  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.675  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.675  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.675  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.675  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.675  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.675  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.675  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.675  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.675  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.675  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.675  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.676  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.676  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.676  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.676  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.677  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 14:57:13.677  3484  3531 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 14:57:13.677  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 14:57:13.680  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 14:57:13.680  3484  3531 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 14:57:13.680  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 14:57:13.680  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 14:57:13.681  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 14:57:13.682  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 14:57:13.683  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 14:57:13.683  3484  3531 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 14:57:13.683  3484  3531 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 14:57:13.683  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 14:57:13.683  3484  3531 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 14:57:13.683  3484  3531 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 14:57:13.683  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 14:57:13.683  3484  3531 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 14:57:13.684  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 14:57:13.685  3484  3531 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-31 14:57:13.685  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 14:57:13.686  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 14:57:13.686  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 14:57:13.687  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 14:57:13.687  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 14:57:13.687  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 14:57:13.687  3484  3531 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 14:57:13.687  3484  3531 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 14:57:13.688  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.688  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.688  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.689  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.689  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.689  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.689  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 14:57:13.691  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.691  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.691  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.691  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.691  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.692  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.692  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.692  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.691  3484  3533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-31 14:57:13.692  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.692  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.692  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.692  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.692  3484  3533 E BluetoothDevice: Bluetooth is not enabled
08-31 14:57:13.693  3484  3531 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 14:57:13.693  3484  3533 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 14:57:13.694  3484  3533 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-31 14:57:13.694  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.694  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.695  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.695  3484  3534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-31 14:57:13.695  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.698  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.698  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.698  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.698  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.698  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.698  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.695  3484  3533 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 14:57:13.698  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.698  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.698  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.698  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.699  3484  3533 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-31 14:57:13.699  3484  3484 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-31 14:57:13.700  3484  3484 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-31 14:57:13.700  3484  3484 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 14:57:13.700  3484  3533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-31 14:57:13.700  3484  3484 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 14:57:13.700  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.700  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.700  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.701  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.701  3484  3531 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 14:57:13.702  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.702  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.702  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.702  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.702  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.702  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.702  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.702  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.702  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.702  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.702  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.702  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.702  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.703  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.703  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.703  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.703  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.703  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 14:57:13.704  3484  3531 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 14:57:13.704  3484  3531 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 14:57:13.704  3484  3531 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 14:57:13.704  3484  3531 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 14:57:13.704  3484  3531 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 14:57:13.704  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 14:57:13.705  3484  3531 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 14:57:13.705  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.705  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.705  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 14:57:13.705  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.705  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.705  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.705  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.705  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.705  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.705  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.705  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.705  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.706  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.706  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.706  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.706  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.706  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.706  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.707  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.707  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.707  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.707  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.707  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.707  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.707  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.707  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.707  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.707  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.707  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.707  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.707  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.707  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.708  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.708  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.708  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.708  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.708  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.708  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.708  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.708  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.708  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.708  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.708  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.708  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.709  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.709  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.709  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.709  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.709  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.709  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.709  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.710  3484  3531 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 14:57:13.711  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.711  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-31 14:57:13.711  3484  3531 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 14:57:13.712  3484  3484 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 14:57:13.712  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 14:57:13.712  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.712  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 14:57:13.712  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.712  3484  3531 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-31 14:57:13.712  3484  3484 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 14:57:13.712  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.712  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.713  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 14:57:13.713  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 14:57:13.713  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 14:57:13.713  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.713  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.713  3484  3531 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.713  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.714  3484  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 14:57:13.714  3484  3484 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 14:57:13.714  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.714  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.714  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.714  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.714  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.714  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.714  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.714  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.714  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.715  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.715  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.715  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.715  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.715  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.715  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.715  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.715  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.715  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.715  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.716  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 14:57:13.716  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 14:57:13.716  3484  3531 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 14:57:13.716  3484  3531 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 14:57:13.716  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 14:57:13.716  3484  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 14:57:13.717  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.717  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.717  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.717  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.717  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.717  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.717  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.717  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.717  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.717  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.717  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.717  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.717  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.717  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.718  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.718  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.718  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.718  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.720  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.720  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.720  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.720  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.720  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.720  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.720  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.720  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.720  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.721  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.721  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.721  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.721  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.721  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.721  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.721  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.721  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.721  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.722  3484  3531 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 14:57:13.722  3484  3531 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 14:57:13.722  3484  3531 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 14:57:13.722  3484  3531 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 14:57:13.722  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.722  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.723  3484  3531 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b6ea1b not in the list
08-31 14:57:13.723  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.723  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.723  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:13.723  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.723  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.723  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 14:57:13.723  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 14:57:13.723  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 14:57:13.723  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 14:57:13.723  3484  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 14:57:13.724  3484  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61817b8 not in the list
08-31 14:57:13.724  3484  3531 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 14:57:13.725  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 14:57:13.725  3484  3531 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 14:57:13.725  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 14:57:13.725  3484  3531 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 14:57:13.725  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 14:57:13.727  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 14:57:13.727  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 14:57:13.727  3484  3531 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 14:57:13.727  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 14:57:13.728  3484  3531 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 14:57:13.728  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 14:57:13.728  3484  3531 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 14:57:13.728  3484  3531 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 14:57:13.728  3484  3531 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 14:57:13.728  3484  3531 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 14:57:13.729  3484  3531 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 14:57:13.729  3484  3531 D io.jxcore.node.ConnectionModel: hasConnect,ion: No connection with peer with ID outgoing
08-31 14:57:13.729  3484  3531 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 14:57:13.729  3484  3531 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 14:57:13.730  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 14:57:13.730  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9bdb682 added. We now have 2 listener(s)
08-31 14:57:13.730  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 14:57:13.731   869  1910 D WifiService: setWifiEnabled: true pid=3484, uid=10000
08-31 14:57:13.731   869  1910 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 14:57:13.734  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 14:57:13.734  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dee8193 added. We now have 3 listener(s)
08-31 14:57:13.735  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 14:57:13.735  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.735  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.736  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 14:57:13.736  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ba25d0 added. We now have 4 listener(s)
08-31 14:57:13.736  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 14:57:13.737  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 14:57:13.737  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a7a9c9 added. We now have 5 listener(s)
08-31 14:57:13.737  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 14:57:13.737   869  1387 D WifiService: setWifiEnabled: false pid=3484, uid=10000
08-31 14:57:13.737   869  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 14:57:13.746   869   887 I ActivityManager: Start proc 3537:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 14:57:13.747   869  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-31 14:57:13.749  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.749  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.749  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.749  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:13.760   869  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-31 14:57:13.761   869  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 14:57:13.762   869  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 14:57:13.763   869  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 14:57:13.763   869  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 14:57:13.763   869  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 14:57:13.763   869  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 14:57:13.763   869   883 I ActivityManager: Start proc 3549:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 14:57:13.765  3484  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 14:57:13.765  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.765  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.765  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.765  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:13.765  3484  3531 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 14:57:13.766  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:13.798  3549  3549 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 14:57:13.822   369   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 14:57:13.823   869  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 14:57:13.823   369   868 D CommandListener: Setting iface cfg
,08-31 14:57:13.824   869  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
08-31 14:57:13.824   869  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 14:57:13.829  3537  3537 D AdapterServiceConfig: Adding HeadsetService
,08-31 14:57:13.829  3537  3537 D AdapterServiceConfig: Adding A2dpService
08-31 14:57:13.829  3537  3537 D AdapterServiceConfig: Adding HidService
08-31 14:57:13.830  3537  3537 D AdapterServiceConfig: Adding HealthService
08-31 14:57:13.830  3537  3537 D AdapterServiceConfig: Adding PanService
08-31 14:57:13.830  3537  3537 D AdapterServiceConfig: Adding GattService
08-31 14:57:13.830  3537  3537 D AdapterServiceConfig: Adding BluetoothMapService
08-31 14:57:13.832   869  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 14:57:13.833   869  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 14:57:13.834   869  1312 E native  : do suspend true
,08-31 14:57:13.852  3549  3549 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 14:57:13.865  1464  1464 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-31 14:57:13.865  1464  1464 W wpa_supplicant: wlan0: Failed to initiate AP scan
08-31 14:57:13.866   869  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 14:57:13.866   869   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bde838:true
08-31 14:57:13.868  3537  3537 D BluetoothAdapterState: make() - Creating AdapterState
08-31 14:57:13.868  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.868  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:13.868  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.868  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:13.869  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:13.869  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:13.869  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:13.869  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:13.869  1911  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 14:57:13.872  3537  3537 I bt_bluedroid: init
,08-31 14:57:13.873  3537  3573 I BluetoothAdapterState: Entering OffState
,08-31 14:57:13.875  3537  3575 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 14:57:13.876  3537  3575 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 14:57:13.876  3537  3575 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 14:57:13.876  3537  3575 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 14:57:13.877  3537  3537 I bt_bluedroid: get_profile_interface socket
,08-31 14:57:13.880  3537  3537 I bt_bluedroid: get_profile_interface sdp
,08-31 14:57:13.880  3537  3578 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 14:57:13.881  3537  3578 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 14:57:13.882  3537  3548 I bt_bluedroid: config_hci_snoop_log
,08-31 14:57:13.883   869   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 14:57:13.883   869  1970 I ActivityManager: Killing 2812:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-31 14:57:13.886  3537  3573 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 14:57:13.886  3537  3573 D BluetoothAdapterProperties: Setting state to 14
08-31 14:57:13.886  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 14:57:13.887  3537  3573 D BluetoothBondStateMachine: make
,08-31 14:57:13.889  3537  3579 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 14:57:13.951  3537  3537 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 14:57:13.949  3537  3573 I BluetoothAdapterState: Entering PendingCommandState
,08-31 14:57:13.955  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:13.956  3537  3537 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 14:57:13.957  3537  3537 D BtGatt.GattService: Received start request. Starting profile...
,08-31 14:57:13.957  3537  3537 D BtGatt.GattService: start()
08-31 14:57:13.957  3537  3537 I bt_bluedroid: get_profile_interface gatt
,08-31 14:57:13.959  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:13.959  3537  3537 D BtGatt.AdvertiseManager: advertise manager created
,08-31 14:57:13.969  3537  3537 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:13.970  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:13.970  3537  3537 V BluetoothAdapterState: isBleTurningOn()=true
08-31 14:57:13.970  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:13.971  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 14:57:13.971  3537  3573 I bt_bluedroid: enable
08-31 14:57:13.971  3537  3575 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 14:57:13.972  3537  3575 I bt_hci  : start_up
,08-31 14:57:14.002  3537  3575 I bt_vendor: alloc value 0xb39e8189
,08-31 14:57:14.002  3537  3575 I bt_vendor: init
08-31 14:57:14.002  3537  3575 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 14:57:14.002  3537  3575 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 14:57:14.109  3537  3575 D bt_hci  : start_up starting async portion
,08-31 14:57:14.110  3537  3582 I bt_hci  : event_finish_startup
,08-31 14:57:14.111  3537  3582 I bt_hci_h4: hal_open
,08-31 14:57:14.111  3537  3582 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 14:57:14.119  3537  3582 I bt_userial_vendor: device fd = 51 open
,08-31 14:57:14.152  3537  3582 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 14:57:14.184  3537  3582 D bt_hwcfg: Chipset BCM4354A2
,08-31 14:57:14.184  3537  3582 D bt_hwcfg: Target name = [BCM4354A2]
08-31 14:57:14.185  3537  3582 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 14:57:14.215  3484  3484 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 14:57:14.851  3537  3582 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 14:57:14.852  3537  3582 D bt_hwcfg: Settlement delay -- 100 ms
08-31 14:57:14.853  3537  3582 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 14:57:14.969  3537  3582 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 14:57:14.970  3537  3582 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 14:57:15.001  3537  3582 I bt_hwcfg: vendor lib fwcfg completed
,08-31 14:57:15.001  3537  3582 I bt_vendor: firmware callback
,08-31 14:57:15.001  3537  3582 I bt_hci  : firmware_config_callback
,08-31 14:57:15.012  3537  3584 I bt_btu  : btu_task pending for preload complete event
,08-31 14:57:15.013  3537  3584 I bt_btu_task: Bluetooth chip preload is complete
,08-31 14:57:15.013  3537  3584 I bt_btu  : btu_task received preload complete event
,08-31 14:57:15.023  3537  3584 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 14:57:15.024  3537  3584 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 14:57:15.024  3537  3584 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 14:57:15.024  3537  3584 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 14:57:15.024  3537  3584 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 14:57:15.025  3537  3584 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 14:57:15.025  3537  3584 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 14:57:15.025  3537  3584 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 14:57:15.025  3537  3584 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 14:57:15.026  3537  3584 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 14:57:15.026  3537  3584 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 14:57:15.026  3537  3584 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 14:57:15.026  3537  3584 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 14:57:15.027  3537  3584 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 14:57:15.027  3537  3584 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 14:57:15.176  3537  3584 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3965d9d
,08-31 14:57:15.176  3537  3584 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3965d9d 
,08-31 14:57:15.186  3537  3578 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 14:57:15.187  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 14:57:15.188  3537  3578 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 14:57:15.195  3537  3578 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 14:57:15.199  3537  3578 D BluetoothAdapterProperties: Scan Mode:20
08-31 14:57:15.199  3537  3578 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 14:57:15.199  3537  3578 D bt_hci  : do_postload posting postload work item
08-31 14:57:15.199  3537  3582 I bt_hci  : event_postload
08-31 14:57:15.199  3537  3582 I bt_vendor: sco_config_cb
08-31 14:57:15.199  3537  3582 I bt_hci  : sco_config_callback postload finished.
,08-31 14:57:15.200  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:15.202  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:15.203  3537  3582 I bt_vendor: low_power_mode_cb
,08-31 14:57:15.209  3537  3578 D bt_bte_conf: Device ID record 1 : primary
,08-31 14:57:15.209  3537  3578 D bt_bte_conf:   vendorId            = 000f
,08-31 14:57:15.209  3537  3578 D bt_bte_conf:   vendorIdSource      = 0001
08-31 14:57:15.209  3537  3578 D bt_bte_conf:   product             = 1200
08-31 14:57:15.209  3537  3578 D bt_bte_conf:   version             = 1436
08-31 14:57:15.209  3537  3578 D bt_bte_conf:   clientExecutableURL = 
08-31 14:57:15.209  3537  3578 D bt_bte_conf:   serviceDescription  = 
08-31 14:57:15.210  3537  3578 D bt_bte_conf:   documentationURL    = 
,08-31 14:57:15.210  3537  3578 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 14:57:15.210  3537  3575 D bt_stack_manager: event_start_up_stack finished
08-31 14:57:15.211  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 14:57:15.211  3537  3573 D BluetoothAdapterProperties: Setting state to 15
08-31 14:57:15.211  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 14:57:15.211  3537  3573 I BluetoothAdapterState: Entering BleOnState
,08-31 14:57:15.215  3537  3573 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 14:57:15.215  3537  3573 D BluetoothAdapterProperties: Setting state to 11
,08-31 14:57:15.215  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 14:57:15.221  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:15.223  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:15.239   869   883 I ActivityManager: Start proc 3592:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 14:57:15.242  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:15.242  3537  3537 D HeadsetService: Received start request. Starting profile...
,08-31 14:57:15.245  3537  3537 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 14:57:15.246  3537  3537 D HeadsetStateMachine: make
,08-31 14:57:15.249  3537  3573 I BluetoothAdapterState: Entering PendingCommandState
,08-31 14:57:15.255  3537  3537 D HeadsetStateMachine: max_hf_connections = 1
08-31 14:57:15.256  3537  3537 I bt_bluedroid: get_profile_interface handsfree
,08-31 14:57:15.256  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 14:57:15.259  3537  3578 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 14:57:15.264  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:15.265   869   869 D BluetoothA2dp: Proxy object connected
08-31 14:57:15.265  3537  3537 D A2dpService: Received start request. Starting profile...
08-31 14:57:15.266  3537  3537 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 14:57:15.266  3537  3537 I bt_bluedroid: get_profile_interface avrcp
08-31 14:57:15.272  3537  3537 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 14:57:15.272  3537  3537 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 14:57:15.272  3537  3537 D A2dpStateMachine: make
08-31 14:57:15.274  3537  3537 I bt_bluedroid: get_profile_interface a2dp
08-31 14:57:15.274  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 14:57:15.278  3537  3606 D A2dpStateMachine: Enter Disconnected: -2
08-31 14:57:15.279  3537  3537 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 14:57:15.280  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:15.281  1354  1354 D BluetoothInputDevice: Proxy object connected
08-31 14:57:15.281  3537  3537 D HidService: Received start request. Starting profile...
08-31 14:57:15.281  3537  3537 I bt_bluedroid: get_profile_interface hidhost
08-31 14:57:15.281  1354  1354 D HidProfile: Bluetooth service connected
08-31 14:57:15.282  3537  3578 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39473e5
08-31 14:57:15.282  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 14:57:15.282  3537  3537 D HidService: setHidService(): set to: null
08-31 14:57:15.283  3537  3537 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 14:57:15.284  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:15.285  3537  3537 D HealthService: Received start request. Starting profile...
08-31 14:57:15.286  3537  3537 I bt_bluedroid: get_profile_interface health
,08-31 14:57:15.292  3537  3537 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 14:57:15.293  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:15.294  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 14:57:15.294  3537  3537 D PanService: Received start request. Starting profile...
,08-31 14:57:15.294  1354  1354 D PanProfile: Bluetooth service connected
08-31 14:57:15.294  3537  3537 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 14:57:15.294  3537  3537 I bt_bluedroid: get_profile_interface pan
08-31 14:57:15.295  3537  3578 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 14:57:15.298  3537  3537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:15.299  1354  1354 D BluetoothMap: Proxy object connected
08-31 14:57:15.299  1354  1354 D MapProfile: Bluetooth service connected
08-31 14:57:15.299  1354  1354 D BluetoothMap: getConnectedDevices()
08-31 14:57:15.300  1354  1354 D BluetoothMap: Bluetooth is Not enabled
08-31 14:57:15.300  3537  3537 D BluetoothMapService: Received start request. Starting profile...
,08-31 14:57:15.301  3537  3537 D BluetoothMapService: start()
08-31 14:57:15.302  3537  3537 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 14:57:15.303  3537  3537 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 14:57:15.303  3537  3537 D BluetoothMapAppObserver: createReceiver()
,08-31 14:57:15.304  3537  3537 D BluetoothMapAppObserver: initObservers()
08-31 14:57:15.304  3537  3537 D BluetoothMapAppObserver: getEnabledAccountItems()
08-31 14:57:15.304  3592  3592 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-31 14:57:15.311  3537  3537 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:15.311  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.311  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 14:57:15.311  3537  3597 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 14:57:15.311  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:15.312   869   879 I ActivityManager: Killing 2973:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 14:57:15.348  3537  3537 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:15.348  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.348  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:15.348  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:15.349  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:15.350  3537  3537 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:15.350  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.350  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:15.350  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:15.351  3537  3537 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:15.351  3537  3537 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:15.351  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:15.351  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:15.351  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 14:57:15.351  3537  3573 D BluetoothAdapterProperties: ScanMode =  20
08-31 14:57:15.352  3537  3573 D BluetoothAdapterProperties: State =  11
08-31 14:57:15.352  3537  3573 D BluetoothAdapterProperties: Setting state to 12
,08-31 14:57:15.352  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 14:57:15.352  3537  3573 I BluetoothAdapterState: Entering OnState
08-31 14:57:15.352  1354  1374 D BluetoothMap: onBluetoothStateChange: up=true
08-31 14:57:15.353  3537  3537 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 14:57:15.353  1999  2010 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:15.354  3537  3537 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 14:57:15.356  3537  3578 D BluetoothAdapterProperties: Scan Mode:21
,08-31 14:57:15.356  3537  3578 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 14:57:15.358  3537  3537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 14:57:15.365  1354  2093 D BluetoothPan: onBluetoothStateChange on: true
,08-31 14:57:15.365  3484  3484 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 14:57:15.365  1354  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 14:57:15.366   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:15.366  3537  3537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 14:57:15.366   869   887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 14:57:15.366   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:15.366  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 14:57:15.367  3537  3537 D ObexServerSockets: Succeed to create listening sockets 
08-31 14:57:15.367  3537  3537 D ObexServerSockets0: startAccept()
,08-31 14:57:15.367  3537  3537 D ObexServerSockets0: prepareForNewConnect()
,08-31 14:57:15.367   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:15.367  3484  3484 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 14:57:15.368  3537  3537 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 14:57:15.368  3537  3537 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 14:57:15.369   869   869 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 14:57:15.371  3484  3484 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:15.374  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:15.375  3537  3611 D ObexServerSockets0: Accepting socket connection...
08-31 14:57:15.376  3537  3537 D BluetoothMapService: onReceive
08-31 14:57:15.376  3537  3537 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
08-31 14:57:15.376  3537  3537 D BluetoothMapService: STATE_ON
08-31 14:57:15.377  3537  3612 D ObexServerSockets0: Accepting socket connection...
,08-31 14:57:15.377  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:15.377  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:15.380  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:15.382  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:15.384  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:15.385  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:15.396  3537  3537 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 14:57:15.396  3537  3537 D ObexServerSockets0: prepareForNewConnect()
,08-31 14:57:15.399   869  1910 I ActivityManager: Start proc 3615:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 14:57:15.400  1354  1652 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 14:57:15.403  1354  1652 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 14:57:15.403  1354  1354 D BluetoothA2dp: Proxy object connected
,08-31 14:57:15.431  3615  3615 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 14:57:15.458  1999  2012 D BluetoothHeadset: Proxy object connected
,08-31 14:57:15.466   869   887 D BluetoothHeadset: Proxy object connected
,08-31 14:57:15.466   869   887 D BluetoothHeadset: Proxy object connected
08-31 14:57:15.468   869   887 D BluetoothHeadset: Proxy object connected
,08-31 14:57:15.505  1354  2093 D BluetoothHeadset: Proxy object connected
,08-31 14:57:15.506  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 14:57:15.617  3615  3615 D StrictMode: ,	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.617  3615  3615 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 14:57:15.617  3615  3615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 14:57:15.627  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 14:57:15.641  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:57:15.650   869   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ec8261:true
,08-31 14:57:15.650  1354  1354 D BluetoothPbap: Proxy object connected
,08-31 14:57:15.651  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-31 14:57:15.656  3537  3642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 14:57:15.676  3592  3592 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 14:57:15.681  3592  3592 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 14:57:15.693  3592  3592 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 14:57:15.694  3592  3592 D BluetoothMap: Create BluetoothMap proxy object
,08-31 14:57:15.702  3592  3592 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 14:57:15.717  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:15.718  3592  3592 D BluetoothA2dp: Proxy object connected
,08-31 14:57:15.720  3592  3592 D BluetoothInputDevice: Proxy object connected
,08-31 14:57:15.721  3592  3592 D HidProfile: Bluetooth service connected
,08-31 14:57:15.723  3592  3592 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 14:57:15.725  3592  3592 D PanProfile: Bluetooth service connected
08-31 14:57:15.725  3592  3592 D BluetoothMap: Proxy object connected
08-31 14:57:15.725  3592  3592 D MapProfile: Bluetooth service connected
08-31 14:57:15.725  3592  3592 D BluetoothMap: getConnectedDevices()
,08-31 14:57:15.729  3592  3592 D BluetoothPbap: Proxy object connected
,08-31 14:57:15.729  3592  3592 D PbapServerProfile: Bluetooth service connected
,08-31 14:57:15.730   869  1909 I ActivityManager: Killing 3162:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 14:57:15.768  3537  3650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 14:57:15.773  3537  3650 I BtOppRfcommListener: Accept thread started.
,08-31 14:57:15.784  3592  3603 D BluetoothHeadset: Proxy object connected
,08-31 14:57:15.785  3592  3592 D HeadsetProfile: Bluetooth service connected
,08-31 14:57:15.861  3615  3632 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 14:57:15.879   869   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d2df72:true
,08-31 14:57:16.770   869  1909 D WifiService: setWifiEnabled: true pid=3484, uid=10000
,08-31 14:57:16.770   869  1909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 14:57:16.782   869  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:16.801  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:16.807  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:16.815   869  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-31 14:57:16.816   869  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:16.816  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:16.817   869  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 14:57:16.817   869  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 14:57:16.818   869  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 14:57:16.818   869  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 14:57:16.818   869  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 14:57:16.821  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:16.888   369   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 14:57:16.888   869  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 14:57:16.891   369   868 D CommandListener: Setting iface cfg
,08-31 14:57:16.902   869  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '111 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 111 Failed to set address (No such device)'
,08-31 14:57:16.903   869  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 14:57:16.905   869  1312 E native  : do suspend true
,08-31 14:57:16.919   869  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 14:57:16.920   869  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 14:57:16.938   869  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 14:57:16.956  1464  1464 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
08-31 14:57:16.956  1464  1464 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-31 14:57:17.957  1464  1464 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-31 14:57:17.958  1464  1464 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-31 14:57:18.226  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 14:57:18.279   869  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-31 14:57:18.285   869  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 14:57:18.285   869  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 14:57:18.300   869  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 14:57:18.346   869  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 14:57:18.669  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 14:57:18.743  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 14:57:18.744  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 14:57:18.751   869  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 14:57:18.777   869  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 14:57:18.777   869  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 14:57:18.778   869  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 14:57:18.810   869  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 14:57:18.833   369   868 D CommandListener: Setting iface cfg
,08-31 14:57:18.852   869  1312 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 14:57:18.861   869  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 14:57:18.888   869  3659 D DhcpClient: Receive thread started
,08-31 14:57:18.971   869  1312 E native  : do suspend false
,08-31 14:57:18.996   869  3658 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 14:57:19.013   869  3659 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 168668, domain null
,08-31 14:57:19.015   869  3658 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 168668 seconds
,08-31 14:57:19.019   869  3658 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 14:57:19.036   869  3659 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 14:57:19.038   869  3658 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 14:57:19.044   369   868 D CommandListener: Setting iface cfg
,08-31 14:57:19.054   869  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 14:57:19.055   869  3658 D DhcpClient: Scheduling renewal in 86399s
,08-31 14:57:19.057   869  1312 E native  : do suspend true
,08-31 14:57:19.084   869  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 14:57:19.088   869  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 14:57:19.089   869  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 14:57:19.095   869  1315 D ConnectivityService: Adding iface wlan0 to network 100
,08-31 14:57:19.109   869  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 14:57:19.170   869  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 14:57:19.172   869  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-31 14:57:19.178   869  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-31 14:57:19.180   869  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-31 14:57:19.188   869  1315 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-31 14:57:19.201   869  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 14:57:19.206   869  1315 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-31 14:57:19.207   869  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-31 14:57:19.208   869  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-31 14:57:19.209   869  1315 D ConnectivityService:    accepting network in place of null
,08-31 14:57:19.211   869  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 14:57:19.211   869  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 14:57:19.213   869  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 14:57:19.237   869  3657 D NetlinkSocketObserver: NeighborEvent{elapsedMs=201198, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 14:57:19.275   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 14:57:19.310   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 14:57:19.315   869  1315 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-31 14:57:19.320   869  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 14:57:19.321   869  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 14:57:19.328   869  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-31 14:57:19.331   869   887 D Tethering: MasterInitialState.processMessage what=3
,08-31 14:57:19.344   869  2046 V BackupManagerService: Scheduling immediate backup pass
,08-31 14:57:19.351   869   869 V BackupManagerService: Running a backup pass
,08-31 14:57:19.353   869  1331 V BackupManagerService: clearing pending backups
,08-31 14:57:19.356   869  1331 V PerformBackupTask: Beginning backup of 16 targets
,08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 14:57:19.358  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 14:57:19.360  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 14:57:19.363  2069  2069 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-31 14:57:19.376   869  1331 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 14:57:19.379  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 14:57:19.379  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 14:57:19.381  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 14:57:19.382  1729  1729 D SystemUpdateService: onCreate
,08-31 14:57:19.386  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 14:57:19.388  1729  3674 I SystemUpdateService: active receiver: enabled
,08-31 14:57:19.389   869  1331 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-31 14:57:19.391  1729  3674 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 14:57:19.394  1729  3674 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 14:57:19.394  1729  3674 I SystemUpdateService: now status is 0 (complete)
08-31 14:57:19.394  1729  3674 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 14:57:19.395  1729  3674 I SystemUpdateService: file has been verified
08-31 14:57:19.395  1729  3674 I SystemUpdateService: OTA package size = 12249756
,08-31 14:57:19.397  1729  3674 I SystemUpdateService: showing system update notification
,08-31 14:57:19.419   869  1331 I BackupRestoreController: Getting widget state for user: 0
,08-31 14:57:19.430  1729  1729 D SystemUpdateService: onDestroy
,08-31 14:57:19.461  1911  1921 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-31 14:57:19.463  1911  1921 V GmsBackupTransport: starting performBackup for @pm@
,08-31 14:57:19.469  1911  1921 V GmsBackupTransport: performBackup done for @pm@
,08-31 14:57:19.482  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:57:19.483  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:57:19.488  1517  1517 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 14:57:19.496  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:57:19.506  1729  3690 I iu.SyncManager: SYNC; picasa accounts
,08-31 14:57:19.514  1729  1729 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 14:57:19.519  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 14:57:19.524  1729  3690 I iu.UploadsManager: num queued entries: 0
,08-31 14:57:19.525  1729  3683 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
08-31 14:57:19.525  1729  3690 I iu.UploadsManager: num updated entries: 0
,08-31 14:57:19.525  1729  3690 I iu.SyncManager: NEXT; no task
,08-31 14:57:19.530  1517  2386 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-31 14:57:19.531  1517  2386 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-31 14:57:19.531  1517  2386 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:57:19.531  1517  2386 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:19.539  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 14:57:19.540  1729  3688 I MDM     : [150] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 14:57:19.540  1729  3688 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 14:57:19.541  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 14:57:19.545  1517  2386 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 14:57:19.545  1517  2386 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 14:57:19.555   869  1387 I ActivityManager: Start proc 3697:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 14:57:19.559  1911  1922 W GmsBackupTransport: Error sending final backup to server: 
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 14:57:19.559  1911  1922 W GmsBackupTransport: 	... 1 more
,08-31 14:57:19.565  1911  3185 I GmsBackupTransport: Next backup will happen in 43199993 millis.
,08-31 14:57:19.566   869  1331 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-31 14:57:19.575  1729  3688 V GoogleAuthProtoRequest: [150] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 14:57:19.586  3549  3685 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 14:57:19.612  3697  3697 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 14:57:19.614  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 14:57:19.614  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 14:57:19.616  3697  3697 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 14:57:19.614  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 14:57:19.619  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:19.626  3697  3697 D SprintDMHelper: simOperator: 
,08-31 14:57:19.626  3697  3697 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-31 14:57:19.631   869  1331 I BackupManagerService: Backup pass finished.
,08-31 14:57:19.637   869  2013 I ActivityManager: Start proc 3713:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 14:57:19.659   869  1910 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1729 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 14:57:19.668  1517  2386 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-31 14:57:19.668  1517  2386 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-31 14:57:19.668  1517  2386 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:57:19.668  1517  2386 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:19.668  1729  3688 E MDM     : [150] SitrepService.a: Error sending sitrep.
,08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-31 14:57:19.695  3549  3685 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-31 14:57:19.771  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:57:19.775   869   879 D WifiService: setWifiEnabled: false pid=3484, uid=10000
08-31 14:57:19.775   869   879 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 14:57:19.787  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 14:57:19.788   869  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 14:57:19.789   869  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 14:57:19.789   869  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 14:57:19.789   869  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 14:57:19.792  1729  3684 W DriveInitializer: Awaiting to be initialized
,08-31 14:57:19.792  1729  3728 W DriveInitializer: Background init thread started
,08-31 14:57:19.805   869  1312 E native  : do suspend true
,08-31 14:57:19.815   869  3658 D DhcpClient: Clearing IP address
,08-31 14:57:19.816   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-31 14:57:19.818   369   868 D CommandListener: Setting iface cfg
,08-31 14:57:19.822   869  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 14:57:19.822   869  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-31 14:57:19.823   869  3659 D DhcpClient: Receive thread stopped
,08-31 14:57:19.824   869  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-31 14:57:19.824   401   401 E Parcel  : Reading a NULL string not supported here.
08-31 14:57:19.824   869  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 14:57:19.824   869  1312 E native  : do suspend true
08-31 14:57:19.827   869  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-31 14:57:19.866   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 14:57:19.869  1729  3728 W DriveInitializer: Background init thread ended
,08-31 14:57:19.893   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 14:57:19.893   369   868 D CommandListener: Clearing all IP addresses on wlan0
08-31 14:57:19.894   869  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 14:57:19.894   869  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 14:57:19.897   869   887 D Tethering: MasterInitialState.processMessage what=3
,08-31 14:57:19.906  2069  2069 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:19.908  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:19.909  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:19.912  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:19.913  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:19.914  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-31 14:57:19.914  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 14:57:19.914  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:57:19.915  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-31 14:57:19.930  3274  3696 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 14:57:19.930  3274  3696 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jdm.a(PG:82)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jcs.o(PG:406)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jcn.a(PG:1379)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jcs.i(PG:143)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at blb.a(PG:3937)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at czp.a(PG:18188)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at czp.a(PG:9081)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at czq.run(PG:1686)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 14:57:19.930  3274  3696 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jdj.a(PG:4091)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jdj.a(PG:1125)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jdm.a(PG:77)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	... 12 more
08-31 14:57:19.930  3274  3696 E HttpOperation: Caused by: faj: BadAuthentication
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at fal.a(PG:38)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	at jdj.a(PG:4089)
08-31 14:57:19.930  3274  3696 E HttpOperation: 	... 14 more
,08-31 14:57:19.943   369   868 E Netd    : netlink response contains error (No such file or directory)
08-31 14:57:19.944   869  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 14:57:19.944   869  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 14:57:19.965   869  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:19.967  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:19.969  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:19.971  1911  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:19.972  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:19.973   869  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 14:57:19.974  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:19.978  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 14:57:19.978  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 14:57:19.978  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:57:19.978  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:19.996  3021  3737 V KeepSync: Connecting to GoogleApiClient
,08-31 14:57:19.997   869   880 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 14:57:20.004   869  2015 I ActivityManager: Start proc 3753:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 14:57:20.010  2228  3752 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 14:57:20.015  3274  3696 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 14:57:20.015  3274  3696 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jdm.a(PG:82)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jcs.o(PG:406)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jcn.a(PG:1379)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jcs.i(PG:143)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at hec.a(PG:42)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at hee.a(PG:102)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at czr.a(PG:65)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at kka.a(PG:108)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at czp.a(PG:19176)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at czp.a(PG:9081)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at czq.run(PG:1686)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 14:57:20.015  3274  3696 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jdj.a(PG:4091)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jdj.a(PG:1125)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jdm.a(PG:77)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	... 15 more
08-31 14:57:20.015  3274  3696 E HttpOperation: Caused by: faj: BadAuthentication
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at fal.a(PG:38)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	at jdj.a(PG:4089)
08-31 14:57:20.015  3274  3696 E HttpOperation: 	... 17 more
,08-31 14:57:20.016  3274  3696 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 14:57:20.016  3274  3696 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at hec.a(PG:42)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at hee.a(PG:102)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at czr.a(PG:65)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at kka.a(PG:108)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	... 15 more
08-31 14:57:20.016  3274  3696 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at fal.a(PG:38)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 14:57:20.016  3274  3696 E ExperimentLoader: 	... 17 more
,08-31 14:57:20.057  3753  3753 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 14:57:20.102  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 14:57:20.102  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 14:57:20.102  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:57:20.102  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:20.115  1729  3765 V BaseAuthAsyncOperation: access token request failed
,08-31 14:57:20.117  3021  3737 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 14:57:20.149   869   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 25319, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 14:57:20.258  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:57:20.278  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 14:57:20.278  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 14:57:20.278  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 14:57:20.278  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:20.293  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 14:57:20.293  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 14:57:20.294  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-31 14:57:20.312  3753  3753 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 14:57:20.312  3753  3753 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 14:57:20.312  3753  3753 I GAv4    :   adb logcat -s GAv4
,08-31 14:57:20.339  3753  3753 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 14:57:20.344  3753  3753 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 14:57:20.362  3753  3772 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 14:57:20.406  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-31 14:57:20.406  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 14:57:20.407  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 14:57:20.407  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:57:20.433  3021  3737 E KeepSync: IOException
08-31 14:57:20.433  3021  3737 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 14:57:20.433  3021  3737 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 14:57:20.433  3021  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 14:57:20.433  3021  3737 E KeepSync: 	... 10 more
08-31 14:57:20.433  3021  3737 W KeepSync: Sync result 2
,08-31 14:57:20.460   869   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 25331, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 14:57:20.461   869  2046 I ActivityManager: Killing 2621:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 14:57:20.555  3753  3753 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 14:57:20.601  3753  3753 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 14:57:20.608  3753  3753 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2571-2573)
,08-31 14:57:20.609  3753  3753 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 14:57:20.626  3753  3753 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {657e56}
08-31 14:57:20.627  3753  3753 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 14:57:20.627  3753  3753 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 14:57:20.639  3753  3753 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 14:57:20.641  3753  3753 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 14:57:20.654  3753  3753 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 14:57:20.670  3753  3753 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 14:57:20.670  3753  3753 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 14:57:20.670  3753  3753 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 14:57:20.670  3753  3753 I Adreno  : Build Date                       : 10/20/15
08-31 14:57:20.670  3753  3753 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 14:57:20.670  3753  3753 I Adreno  : Local Branch                     : M14
08-31 14:57:20.670  3753  3753 I Adreno  : Remote Branch                    : 
08-31 14:57:20.670  3753  3753 I Adreno  : Remote Branch                    : 
08-31 14:57:20.670  3753  3753 I Adreno  : Reconstruct Branch               : 
,08-31 14:57:20.730  3753  3801 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 14:57:20.731  3753  3753 I NSApplication: Starting up...
,08-31 14:57:20.758   869  1994 I ActivityManager: Start proc 3806:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 14:57:20.759   869  1994 I ActivityManager: Killing 2890:android.process.acore/u0a5 (adj 15): empty #17
,08-31 14:57:20.824  3806  3806 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 14:57:21.303   869   880 I ActivityManager: Killing 3345:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 14:57:21.392  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 14:57:21.398  1729  1729 D SystemUpdateService: onCreate
,08-31 14:57:21.410  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 14:57:21.426  1729  3820 I SystemUpdateService: active receiver: enabled
,08-31 14:57:21.439  1729  3820 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 14:57:21.441  1729  3820 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 14:57:21.441  1729  3820 I SystemUpdateService: now status is 0 (complete)
,08-31 14:57:21.441  1729  3820 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 14:57:21.441  1729  3820 I SystemUpdateService: file has been verified
,08-31 14:57:21.443  1729  3820 I SystemUpdateService: OTA package size = 12249756
08-31 14:57:21.445  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 14:57:21.448  1729  3690 I iu.UploadsManager: num queued entries: 0
,08-31 14:57:21.448  1729  3820 I SystemUpdateService: showing system update notification
,08-31 14:57:21.450  1729  3690 I iu.UploadsManager: num updated entries: 0
,08-31 14:57:21.450  1729  3690 I iu.SyncManager: NEXT; no task
,08-31 14:57:21.453  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 14:57:21.455  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 14:57:21.456  3697  3697 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 14:57:21.460  3697  3697 D SprintDMHelper: simOperator: 
,08-31 14:57:21.460  3697  3697 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-31 14:57:21.460  1729  1729 D SystemUpdateService: onDestroy
,08-31 14:57:22.787  3537  3573 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 14:57:22.787  3537  3573 D BluetoothAdapterProperties: Setting state to 13
,08-31 14:57:22.787  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 14:57:22.789  3537  3573 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 14:57:22.793  3537  3573 I BluetoothAdapterState: Entering PendingCommandState
,08-31 14:57:22.797  3537  3537 D BluetoothMapService: onReceive
08-31 14:57:22.798  3537  3537 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 14:57:22.798  3537  3537 D BluetoothMapService: STATE_TURNING_OFF
,08-31 14:57:22.799  3537  3537 D BluetoothMapService: MAP Service closeService in
08-31 14:57:22.799  3537  3537 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 14:57:22.800  3537  3537 D ObexServerSockets0: shutdown(block = true)
08-31 14:57:22.801  3537  3611 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 14:57:22.803  3537  3537 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 14:57:22.804  3537  3612 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 14:57:22.808  3537  3578 D BluetoothAdapterProperties: Scan Mode:20
08-31 14:57:22.808  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 14:57:22.815  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:22.815  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:22.815  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:22.815  3537  3586 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 14:57:22.816  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:22.816  3537  3537 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 14:57:22.818  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 14:57:22.818  3537  3537 I BtOppRfcommListener: stopping Accept Thread
08-31 14:57:22.818  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:22.818  3537  3650 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:22.818  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:22.820  3537  3650 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 14:57:22.821  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:22.821  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:22.824  3537  3537 D HeadsetService: Received stop request...Stopping profile...
08-31 14:57:22.824  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:22.826  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:22.827  3592  3604 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.828   869   869 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.828   869   869 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.828  3537  3537 D A2dpService: Received stop request...Stopping profile...
08-31 14:57:22.828  1354  1374 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.829  3537  3606 D A2dpStateMachine: Exit Disconnected: -1
08-31 14:57:22.829   869   869 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.829  1999  2169 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:22.832   869   869 D BluetoothA2dp: Proxy object disconnected
08-31 14:57:22.833  3537  3537 D HidService: Received stop request...Stopping profile...
,08-31 14:57:22.833  3537  3537 D HidService: Stopping Bluetooth HidService
08-31 14:57:22.835  3537  3537 D HealthService: Received stop request...Stopping profile...
08-31 14:57:22.836  3592  3592 D DockEventReceiver: finishStartingService: stopping service
08-31 14:57:22.836  3537  3537 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:22.837  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.837  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:22.837  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:22.838  3537  3537 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 14:57:22.839  3537  3537 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 14:57:22.839  3592  3592 D HeadsetProfile: Bluetooth service disconnected
08-31 14:57:22.839  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 14:57:22.839  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:22.839  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:22.839  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 14:57:22.839  3537  3578 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 14:57:22.839  3537  3537 D PanService: Received stop request...Stopping profile...
,08-31 14:57:22.840  3592  3592 D BluetoothA2dp: Proxy object disconnected
,08-31 14:57:22.841  3592  3592 D BluetoothInputDevice: Proxy object disconnected
,08-31 14:57:22.844  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 14:57:22.845  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,08-31 14:57:22.845  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-31 14:57:22.845  3537  3537 D BluetoothMapService: Received stop request...Stopping profile...
08-31 14:57:22.845  3537  3537 D BluetoothMapService: stop()
08-31 14:57:22.846  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-31 14:57:22.846  1354  1354 D HidProfile: Bluetooth service disconnected
08-31 14:57:22.846  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 14:57:22.846  1354  1354 D PanProfile: Bluetooth service disconnected
08-31 14:57:22.846  3537  3537 D BluetoothMapAppObserver: deinitObservers()
08-31 14:57:22.846  3592  3592 D HidProfile: Bluetooth service disconnected
08-31 14:57:22.846  3537  3537 D BluetoothMapAppObserver: removeReceiver()
08-31 14:57:22.847  3592  3592 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 14:57:22.847  3592  3592 D PanProfile: Bluetooth service disconnected
,08-31 14:57:22.849  3592  3592 D BluetoothMap: Proxy object disconnected
08-31 14:57:22.849  3592  3592 D MapProfile: Bluetooth service disconnected
08-31 14:57:22.850  1354  1354 D BluetoothMap: Proxy object disconnected
08-31 14:57:22.850  1354  1354 D MapProfile: Bluetooth service disconnected
08-31 14:57:22.851  3537  3537 V BluetoothAdapterState: isTurningOff()=true
,08-31 14:57:22.851  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.851  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:22.851  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:22.852  3537  3537 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:22.852  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.852  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:22.852  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:22.852  3537  3537 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 14:57:22.852  3537  3537 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 14:57:22.853  3537  3537 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:22.853  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.853  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 14:57:22.853  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:22.853  3537  3537 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 14:57:22.853  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:22.853  3537  3537 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 14:57:22.853  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:22.854  3537  3584 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 14:57:22.854  3537  3537 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:22.854  3537  3584 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 14:57:22.854  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.854  3537  3584 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 14:57:22.854  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:22.854  3537  3584 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 14:57:22.854  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:22.854  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 14:57:22.854  3537  3578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 14:57:22.854  3537  3537 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 14:57:22.854  3537  3537 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 14:57:22.854  3537  3578 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 14:57:22.857  1354  1354 D BluetoothPbap: Proxy object disconnected
08-31 14:57:22.857  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-31 14:57:22.857  3592  3592 D BluetoothPbap: Proxy object disconnected
08-31 14:57:22.857  3592  3592 D PbapServerProfile: Bluetooth service disconnected
,08-31 14:57:22.858  3537  3537 D BluetoothMapService: MAP Service closeService in
08-31 14:57:22.858  3537  3537 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:22.858  3537  3537 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:22.858  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:22.858  3537  3537 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:22.860  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 14:57:22.860  3537  3573 D BluetoothAdapterProperties: Setting state to 15
08-31 14:57:22.860  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 14:57:22.861  3537  3573 I BluetoothAdapterState: Entering BleOnState
08-31 14:57:22.861  3537  3537 D BluetoothMapService: cleanup()
,08-31 14:57:22.862  3537  3537 D BluetoothMapService: MAP Service closeService in
08-31 14:57:22.862  1354  1368 D BluetoothMap: onBluetoothStateChange: up=false
08-31 14:57:22.862  1999  2158 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:22.862  1354  1374 D BluetoothPan: onBluetoothStateChange on: false
,08-31 14:57:22.863  1354  2093 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 14:57:22.864  3592  3603 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 14:57:22.864  3592  3604 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 14:57:22.865   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 14:57:22.865   869   887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 14:57:22.865  1354  1368 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:22.865   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:22.865  3592  3603 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 14:57:22.866  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 14:57:22.866  3592  3604 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 14:57:22.867  1354  2093 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 14:57:22.870  3592  3603 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 14:57:22.870  3592  3604 D BluetoothPan: onBluetoothStateChange on: false
08-31 14:57:22.870   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:22.871  3537  3573 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 14:57:22.871  3537  3573 D BluetoothAdapterProperties: Setting state to 16
08-31 14:57:22.871  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 14:57:22.871  3537  3573 D BluetoothAdapterProperties: onBleDisable
,08-31 14:57:22.871  3537  3575 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 14:57:22.872  3537  3573 I BluetoothAdapterState: Entering PendingCommandState
08-31 14:57:22.872  3537  3584 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 14:57:22.872  3537  3584 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 14:57:22.876  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 14:57:22.878  3537  3578 D BluetoothAdapterProperties: Scan Mode:20
08-31 14:57:22.879  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:22.880  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:22.881  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:22.881  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:22.883  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:57:22.890  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:23.086  3537  3578 I bt_hci  : shut_down
,08-31 14:57:23.092  3537  3582 I bt_vendor: low_power_mode_cb
,08-31 14:57:23.096  3537  3582 D bt_hwcfg: hw_epilog_process
,08-31 14:57:23.119  3537  3582 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 14:57:23.119  3537  3582 I bt_vendor: epilog_cb
08-31 14:57:23.119  3537  3582 I bt_hci  : epilog_finished_callback
,08-31 14:57:23.126  3537  3578 I bt_hci_h4: hal_close
,08-31 14:57:23.127  3537  3578 I bt_userial_vendor: device fd = 51 close
,08-31 14:57:23.256  3537  3575 D bt_stack_manager: event_shut_down_stack finished.
,08-31 14:57:23.258  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 14:57:23.268  3537  3573 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 14:57:23.268  3537  3537 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 14:57:23.269  3537  3537 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 14:57:23.270  3537  3537 D BtGatt.GattService: stop(),
,08-31 14:57:23.270  3537  3537 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 14:57:23.275  3537  3537 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:23.275  3537  3537 V BluetoothAdapterState: isTurningOn()=false
,08-31 14:57:23.275  3537  3537 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 14:57:23.276  3537  3537 V BluetoothAdapterState: isBleTurningOff()=true
08-31 14:57:23.277  3537  3573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 14:57:23.277  3537  3573 D BluetoothAdapterProperties: Setting state to 10
08-31 14:57:23.278  3537  3573 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 14:57:23.279  3537  3573 I BluetoothAdapterState: Entering OffState
08-31 14:57:23.282   869   887 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 14:57:23.303  3537  3537 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 14:57:23.304  3537  3537 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 14:57:23.304  3537  3575 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-31 14:57:23.306  3537  3575 D bt_stack_manager: event_clean_up_stack finished.
08-31 14:57:23.307  3537  3537 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 14:57:23.310  3537  3537 I art     : System.exit called, status: 0
,08-31 14:57:23.310  3537  3537 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 14:57:23.371   869   879 I ActivityManager: Process com.android.bluetooth (pid 3537) has died
,08-31 14:57:24.228   869  3656 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-31 14:57:24.232   869  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 14:57:24.578  1517  3686 W PhenotypeConfigurator: IOException while sending for: 
,08-31 14:57:24.692  1517  3686 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-31 14:57:25.186  1517  3841 I VacuumService: Vacuum at: now=1472648245186 tag=VacuumService
,08-31 14:57:25.836   869   887 I ActivityManager: Start proc 3842:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 14:57:25.957  3842  3842 D AdapterServiceConfig: Adding HeadsetService
,08-31 14:57:25.957  3842  3842 D AdapterServiceConfig: Adding A2dpService
08-31 14:57:25.958  3842  3842 D AdapterServiceConfig: Adding HidService
,08-31 14:57:25.958  3842  3842 D AdapterServiceConfig: Adding HealthService
08-31 14:57:25.958  3842  3842 D AdapterServiceConfig: Adding PanService
,08-31 14:57:25.958  3842  3842 D AdapterServiceConfig: Adding GattService
08-31 14:57:25.958  3842  3842 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 14:57:25.974   869   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ae85e6:true
,08-31 14:57:25.975  3842  3842 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 14:57:25.981  3842  3842 I bt_bluedroid: init
,08-31 14:57:25.981  3842  3854 I BluetoothAdapterState: Entering OffState
,08-31 14:57:25.987  3842  3855 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 14:57:25.987  3842  3855 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 14:57:25.987  3842  3855 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 14:57:25.988  3842  3855 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 14:57:25.990  3842  3842 I bt_bluedroid: get_profile_interface socket
,08-31 14:57:25.992  3842  3858 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 14:57:25.995  3842  3858 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 14:57:25.996  3842  3842 I bt_bluedroid: get_profile_interface sdp
,08-31 14:57:26.002  3842  3852 I bt_bluedroid: config_hci_snoop_log
,08-31 14:57:26.005   869   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 14:57:26.021  3842  3854 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 14:57:26.022  3842  3854 D BluetoothAdapterProperties: Setting state to 14
08-31 14:57:26.022  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14,
,08-31 14:57:26.027  3842  3854 D BluetoothBondStateMachine: make
,08-31 14:57:26.032  3842  3859 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 14:57:26.039  3842  3854 I BluetoothAdapterState: Entering PendingCommandState
,08-31 14:57:26.042  3842  3842 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 14:57:26.051  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:26.054  3842  3842 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 14:57:26.055  3842  3842 D BtGatt.GattService: Received start request. Starting profile...,
08-31 14:57:26.056  3842  3842 D BtGatt.GattService: start()
08-31 14:57:26.056  3842  3842 I bt_bluedroid: get_profile_interface gatt
,08-31 14:57:26.059  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:26.059  3842  3842 D BtGatt.AdvertiseManager: advertise manager created
,08-31 14:57:26.072  3842  3842 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:26.073  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:26.073  3842  3842 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 14:57:26.073  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:26.075  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 14:57:26.076  3842  3854 I bt_bluedroid: enable
08-31 14:57:26.076  3842  3855 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 14:57:26.076  3842  3855 I bt_hci  : start_up
,08-31 14:57:26.084  3842  3855 I bt_vendor: alloc value 0xb39e8189
,08-31 14:57:26.084  3842  3855 I bt_vendor: init
08-31 14:57:26.084  3842  3855 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 14:57:26.084  3842  3855 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 14:57:26.193  3842  3855 D bt_hci  : start_up starting async portion
,08-31 14:57:26.194  3842  3862 I bt_hci  : event_finish_startup
08-31 14:57:26.194  3842  3862 I bt_hci_h4: hal_open
,08-31 14:57:26.195  3842  3862 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 14:57:26.206  3842  3862 I bt_userial_vendor: device fd = 51 open
,08-31 14:57:26.235  3842  3862 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 14:57:26.267  3842  3862 D bt_hwcfg: Chipset BCM4354A2
,08-31 14:57:26.267  3842  3862 D bt_hwcfg: Target name = [BCM4354A2]
08-31 14:57:26.268  3842  3862 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 14:57:26.917  3842  3862 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 14:57:26.919  3842  3862 D bt_hwcfg: Settlement delay -- 100 ms
08-31 14:57:26.919  3842  3862 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 14:57:27.035  3842  3862 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 14:57:27.037  3842  3862 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 14:57:27.066  3842  3862 I bt_hwcfg: vendor lib fwcfg completed
,08-31 14:57:27.066  3842  3862 I bt_vendor: firmware callback
08-31 14:57:27.067  3842  3862 I bt_hci  : firmware_config_callback
,08-31 14:57:27.078  3842  3864 I bt_btu  : btu_task pending for preload complete event
,08-31 14:57:27.078  3842  3864 I bt_btu_task: Bluetooth chip preload is complete
,08-31 14:57:27.078  3842  3864 I bt_btu  : btu_task received preload complete event
,08-31 14:57:27.090  3842  3864 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 14:57:27.091  3842  3864 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 14:57:27.091  3842  3864 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 14:57:27.091  3842  3864 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 14:57:27.092  3842  3864 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 14:57:27.092  3842  3864 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 14:57:27.092  3842  3864 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 14:57:27.092  3842  3864 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 14:57:27.093  3842  3864 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 14:57:27.093  3842  3864 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 14:57:27.093  3842  3864 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 14:57:27.093  3842  3864 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 14:57:27.094  3842  3864 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 14:57:27.094  3842  3864 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 14:57:27.094  3842  3864 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 14:57:27.211   869  1315 D ConnectivityService: handlePromptUnvalidated 100
,08-31 14:57:27.230  3842  3864 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3965d9d
,08-31 14:57:27.230  3842  3864 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3965d9d 
,08-31 14:57:27.254  3842  3858 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 14:57:27.256  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 14:57:27.256  3842  3858 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 14:57:27.260  3842  3858 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 14:57:27.264  3842  3858 D BluetoothAdapterProperties: Scan Mode:20
,08-31 14:57:27.265  3842  3858 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 14:57:27.266  3842  3858 D bt_hci  : do_postload posting postload work item
08-31 14:57:27.268  3842  3862 I bt_hci  : event_postload
08-31 14:57:27.268  3842  3862 I bt_vendor: sco_config_cb
08-31 14:57:27.269  3842  3862 I bt_hci  : sco_config_callback postload finished.
08-31 14:57:27.269  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:27.273  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:27.274  3842  3858 D bt_bte_conf: Device ID record 1 : primary
,08-31 14:57:27.274  3842  3858 D bt_bte_conf:   vendorId            = 000f
08-31 14:57:27.274  3842  3858 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 14:57:27.274  3842  3858 D bt_bte_conf:   product             = 1200
,08-31 14:57:27.274  3842  3858 D bt_bte_conf:   version             = 1436
08-31 14:57:27.274  3842  3858 D bt_bte_conf:   clientExecutableURL = 
,08-31 14:57:27.274  3842  3858 D bt_bte_conf:   serviceDescription  = 
,08-31 14:57:27.274  3842  3858 D bt_bte_conf:   documentationURL    = 
,08-31 14:57:27.274  3842  3862 I bt_vendor: low_power_mode_cb
,08-31 14:57:27.274  3842  3858 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 14:57:27.274  3842  3855 D bt_stack_manager: event_start_up_stack finished
,08-31 14:57:27.275  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-31 14:57:27.275  3842  3854 D BluetoothAdapterProperties: Setting state to 15
08-31 14:57:27.275  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 14:57:27.276  3842  3854 I BluetoothAdapterState: Entering BleOnState
08-31 14:57:27.281  3842  3854 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 14:57:27.281  3842  3854 D BluetoothAdapterProperties: Setting state to 11
08-31 14:57:27.281  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 14:57:27.285  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:27.286  3842  3842 D HeadsetService: Received start request. Starting profile...
,08-31 14:57:27.292  3842  3842 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 14:57:27.292  3842  3842 D HeadsetStateMachine: make
,08-31 14:57:27.299  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:27.302  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:27.304  3842  3854 I BluetoothAdapterState: Entering PendingCommandState
,08-31 14:57:27.307  3842  3842 D HeadsetStateMachine: max_hf_connections = 1
,08-31 14:57:27.307  3842  3842 I bt_bluedroid: get_profile_interface handsfree
,08-31 14:57:27.308  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 14:57:27.310  3842  3858 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 14:57:27.315  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:27.316  3842  3842 D A2dpService: Received start request. Starting profile...
,08-31 14:57:27.317  3842  3842 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 14:57:27.317  3842  3842 I bt_bluedroid: get_profile_interface avrcp
,08-31 14:57:27.324  3842  3842 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 14:57:27.325  3842  3842 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 14:57:27.325  3842  3842 D A2dpStateMachine: make
,08-31 14:57:27.326  3842  3842 I bt_bluedroid: get_profile_interface a2dp
,08-31 14:57:27.328  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 14:57:27.330  3842  3874 D A2dpStateMachine: Enter Disconnected: -2
,08-31 14:57:27.330  3842  3842 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 14:57:27.332  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:27.333  3842  3842 D HidService: Received start request. Starting profile...
,08-31 14:57:27.333  3842  3842 I bt_bluedroid: get_profile_interface hidhost
08-31 14:57:27.333  3842  3858 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39473e5
,08-31 14:57:27.333  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 14:57:27.333  3842  3842 D HidService: setHidService(): set to: null
08-31 14:57:27.335  3842  3842 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 14:57:27.336  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
08-31 14:57:27.337  3842  3842 D HealthService: Received start request. Starting profile...
08-31 14:57:27.338  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 14:57:27.339  3842  3842 I bt_bluedroid: get_profile_interface health
,08-31 14:57:27.340  3842  3842 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 14:57:27.341  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:27.341  3842  3842 D PanService: Received start request. Starting profile...
08-31 14:57:27.342  3842  3842 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 14:57:27.342  3842  3842 I bt_bluedroid: get_profile_interface pan
,08-31 14:57:27.343  3842  3858 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 14:57:27.347  3842  3842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d99b23c
,08-31 14:57:27.348  3842  3842 D BluetoothMapService: Received start request. Starting profile...
08-31 14:57:27.348  3842  3842 D BluetoothMapService: start()
,08-31 14:57:27.352  3842  3842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 14:57:27.353  3842  3842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 14:57:27.354  3842  3842 D BluetoothMapAppObserver: createReceiver()
,08-31 14:57:27.356  3842  3842 D BluetoothMapAppObserver: initObservers()
,08-31 14:57:27.356  3842  3842 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 14:57:27.368  3842  3842 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:27.368  3842  3842 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:27.368  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:27.368  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:27.369  3842  3871 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 14:57:27.372  3842  3842 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:27.372  3842  3842 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:27.372  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 14:57:27.373  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:27.373  3842  3842 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:27.373  3842  3842 V BluetoothAdapterState: isTurningOn()=true
,08-31 14:57:27.374  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:27.374  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:27.374  3842  3842 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:27.375  3842  3842 V BluetoothAdapterState: isTurningOn()=true
,08-31 14:57:27.375  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:27.375  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:27.377  3842  3842 V BluetoothAdapterState: isTurningOff()=false
08-31 14:57:27.377  3842  3842 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:27.377  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 14:57:27.377  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 14:57:27.378  3842  3842 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:27.378  3842  3842 V BluetoothAdapterState: isTurningOn()=true
08-31 14:57:27.379  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:27.379  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:27.379  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 14:57:27.379  3842  3854 D BluetoothAdapterProperties: ScanMode =  20
08-31 14:57:27.380  3842  3854 D BluetoothAdapterProperties: State =  11
08-31 14:57:27.381  3842  3858 D BluetoothAdapterProperties: Scan Mode:21
08-31 14:57:27.381  3842  3858 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 14:57:27.381  3842  3854 D BluetoothAdapterProperties: Setting state to 12
,08-31 14:57:27.381  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 14:57:27.381  3842  3854 I BluetoothAdapterState: Entering OnState
08-31 14:57:27.382  1354  2093 D BluetoothMap: onBluetoothStateChange: up=true
08-31 14:57:27.385  1999  2012 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:27.386  1354  1354 D BluetoothMap: Proxy object connected
,08-31 14:57:27.386  1354  1374 D BluetoothPan: onBluetoothStateChange on: true
08-31 14:57:27.386  1354  1354 D MapProfile: Bluetooth service connected
,08-31 14:57:27.386  1354  1354 D BluetoothMap: getConnectedDevices()
08-31 14:57:27.388  1354  2093 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:27.388  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:27.390  3592  3603 D BluetoothMap: onBluetoothStateChange: up=true
08-31 14:57:27.390  3842  3842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 14:57:27.390  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:27.391  3842  3842 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 14:57:27.392  3592  3604 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 14:57:27.393   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:27.393   869   887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:27.394  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:27.394  3842  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 14:57:27.394  3592  3592 D BluetoothMap: Proxy object connected
,08-31 14:57:27.395  1354  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 14:57:27.396   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 14:57:27.396  3592  3603 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 14:57:27.397  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:27.399  3842  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 14:57:27.399  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 14:57:27.402  3842  3842 D ObexServerSockets: Succeed to create listening sockets 
08-31 14:57:27.402  3592  3604 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 14:57:27.402  3842  3842 D ObexServerSockets0: startAccept()
08-31 14:57:27.402  3842  3842 D ObexServerSockets0: prepareForNewConnect()
,08-31 14:57:27.404  1354  2093 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 14:57:27.394  3592  3592 D MapProfile: Bluetooth service connected
,08-31 14:57:27.404  3592  3592 D BluetoothMap: getConnectedDevices()
,08-31 14:57:27.406  3592  3603 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 14:57:27.407  3592  3604 D BluetoothPan: onBluetoothStateChange on: true
,08-31 14:57:27.407  3842  3880 D ObexServerSockets0: Accepting socket connection...
,08-31 14:57:27.408  3842  3842 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 14:57:27.408  3842  3842 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 14:57:27.409  3842  3881 D ObexServerSockets0: Accepting socket connection...
08-31 14:57:27.409   869   887 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 14:57:27.410  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 14:57:27.410  1354  1354 D PanProfile: Bluetooth service connected
08-31 14:57:27.411  1354  1354 D BluetoothInputDevice: Proxy object connected
08-31 14:57:27.411  1354  1354 D HidProfile: Bluetooth service connected
,08-31 14:57:27.411  3592  3592 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 14:57:27.411  3592  3592 D PanProfile: Bluetooth service connected
08-31 14:57:27.411  3592  3592 D BluetoothInputDevice: Proxy object connected
08-31 14:57:27.411  3592  3592 D HidProfile: Bluetooth service connected
08-31 14:57:27.414   869   869 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 14:57:27.414   869   869 D BluetoothA2dp: Proxy object connected
08-31 14:57:27.415  3842  3842 D BluetoothMapService: onReceive
,08-31 14:57:27.415  3842  3842 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 14:57:27.415  3842  3842 D BluetoothMapService: STATE_ON
08-31 14:57:27.415  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:27.417  1354  1354 D BluetoothA2dp: Proxy object connected
08-31 14:57:27.418  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:27.423  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 14:57:27.427  3592  3592 D BluetoothA2dp: Proxy object connected
,08-31 14:57:27.431  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:57:27.435  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:27.439  3592  3592 D BluetoothPbap: Proxy object connected
,08-31 14:57:27.439  3592  3592 D PbapServerProfile: Bluetooth service connected
,08-31 14:57:27.442  1354  1354 D BluetoothPbap: Proxy object connected
,08-31 14:57:27.443  1354  1354 D PbapServerProfile: Bluetooth service connected
08-31 14:57:27.444  3842  3842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 14:57:27.444  3842  3842 D ObexServerSockets0: prepareForNewConnect()
,08-31 14:57:27.447  3842  3888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 14:57:27.463  3842  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 14:57:27.466  3842  3892 I BtOppRfcommListener: Accept thread started.
,08-31 14:57:27.488  3592  3604 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.488  3592  3592 D HeadsetProfile: Bluetooth service connected
08-31 14:57:27.488   869   869 D BluetoothHeadset: Proxy object connected
08-31 14:57:27.488   869   869 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.489  1354  1368 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.489  1354  1354 D HeadsetProfile: Bluetooth service connected
08-31 14:57:27.490   869   869 D BluetoothHeadset: Proxy object connected
08-31 14:57:27.490  1999  2169 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.494   869   887 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.495  1354  1374 D BluetoothHeadset: Proxy object connected
08-31 14:57:27.495  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-31 14:57:27.496   869   887 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.506  3592  3603 D BluetoothHeadset: Proxy object connected
,08-31 14:57:27.507  3592  3592 D HeadsetProfile: Bluetooth service connected
,08-31 14:57:27.510   869   887 D BluetoothHeadset: Proxy object connected
,08-31 14:57:28.787  3484  3531 D io.jxcore.node.ConnectivityMonitor: stop
08-31 14:57:28.788  3484  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 14:57:30.247   869  1910 I ActivityManager: Killing 3362:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 14:57:31.795  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 14:57:31.796  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@781985 added. We now have 6 listener(s)
08-31 14:57:31.796  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 14:57:31.802  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 14:57:31.803  3484  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc793da added. We now have 7 listener(s)
08-31 14:57:31.803  3484  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 14:57:31.806  3484  3531 I System.out: IsBluetoothEnabled
,08-31 14:57:31.819  3842  3854 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 14:57:31.820  3842  3854 D BluetoothAdapterProperties: Setting state to 13
,08-31 14:57:31.820  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 14:57:31.821  3842  3854 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 14:57:31.823  3842  3854 I BluetoothAdapterState: Entering PendingCommandState
08-31 14:57:31.836  3842  3858 D BluetoothAdapterProperties: Scan Mode:20
,08-31 14:57:31.836  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 14:57:31.838  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:31.838  3484  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 14:57:31.839  3842  3842 D BluetoothMapService: onReceive
08-31 14:57:31.839  3842  3842 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 14:57:31.839  3842  3842 D BluetoothMapService: STATE_TURNING_OFF
08-31 14:57:31.839  3842  3842 D BluetoothMapService: MAP Service closeService in
08-31 14:57:31.840  3842  3842 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 14:57:31.840  3842  3842 D ObexServerSockets0: shutdown(block = true)
,08-31 14:57:31.840  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 14:57:31.840  3484  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 14:57:31.840  3842  3842 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 14:57:31.841  3842  3880 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 14:57:31.841  3842  3842 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 14:57:31.841  3842  3881 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 14:57:31.842  3842  3867 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 14:57:31.842  3484  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 14:57:31.842  3484  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 14:57:31.842  3842  3842 I BtOppRfcommListener: stopping Accept Thread
08-31 14:57:31.842  3842  3892 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 14:57:31.843  3484  3484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 14:57:31.843  3484  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 14:57:31.843  3842  3892 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 14:57:31.846  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 14:57:31.846  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:31.847  3842  3842 D HeadsetService: Received stop request...Stopping profile...
08-31 14:57:31.853  3592  3603 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:31.853  3842  3842 D A2dpService: Received stop request...Stopping profile...
08-31 14:57:31.854   869   869 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:31.854  3842  3874 D A2dpStateMachine: Exit Disconnected: -1
08-31 14:57:31.854   869   869 D BluetoothHeadset: Proxy object disconnected
,08-31 14:57:31.854  1354  1368 D BluetoothHeadset: Proxy object disconnected
,08-31 14:57:31.854   869   869 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:31.855  1999  2158 D BluetoothHeadset: Proxy object disconnected
08-31 14:57:31.856   869   869 D BluetoothA2dp: Proxy object disconnected
08-31 14:57:31.856  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-31 14:57:31.857  3842  3854 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
,08-31 14:57:31.858  3842  3842 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:31.858  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.859  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.859  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.859  3842  3842 D HidService: Received stop request...Stopping profile...
08-31 14:57:31.859  3842  3842 D HidService: Stopping Bluetooth HidService
,08-31 14:57:31.859  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-31 14:57:31.861  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-31 14:57:31.861  1354  1354 D BluetoothInputDevice: Proxy object disconnected
,08-31 14:57:31.861  1354  1354 D HidProfile: Bluetooth service disconnected
,08-31 14:57:31.864  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 14:57:31.865  3842  3842 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 14:57:31.865  3842  3842 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 14:57:31.865  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 14:57:31.865  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:31.865  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 14:57:31.865  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:31.866  3842  3858 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 14:57:31.866  3842  3842 D HealthService: Received stop request...Stopping profile...
08-31 14:57:31.867  3842  3842 V BluetoothAdapterState: isTurningOff()=true
,08-31 14:57:31.867  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.867  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.868  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.868  3842  3842 D PanService: Received stop request...Stopping profile...
,08-31 14:57:31.870  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 14:57:31.870  1354  1354 D PanProfile: Bluetooth service disconnected
08-31 14:57:31.871  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:31.871  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:31.871  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:31.871  3842  3864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 14:57:31.871  3842  3864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 14:57:31.871  3842  3864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 14:57:31.872  3842  3864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 14:57:31.872  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 14:57:31.872  3842  3842 D BluetoothMapService: Received stop request...Stopping profile...
08-31 14:57:31.872  3842  3842 D BluetoothMapService: stop()
08-31 14:57:31.872  3842  3842 D BluetoothMapAppObserver: deinitObservers()
,08-31 14:57:31.873  3842  3842 D BluetoothMapAppObserver: removeReceiver()
08-31 14:57:31.873  3592  3592 D HeadsetProfile: Bluetooth service disconnected
,08-31 14:57:31.874  3592  3592 D BluetoothA2dp: Proxy object disconnected
,08-31 14:57:31.874  3592  3592 D BluetoothInputDevice: Proxy object disconnected
08-31 14:57:31.874  1354  1354 D BluetoothMap: Proxy object disconnected
08-31 14:57:31.874  1354  1354 D MapProfile: Bluetooth service disconnected
08-31 14:57:31.876  3842  3842 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:31.876  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.876  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.876  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.876  3842  3842 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 14:57:31.876  3842  3858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 14:57:31.877  3842  3842 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 14:57:31.878  1354  1354 D BluetoothPbap: Proxy object disconnected
,08-31 14:57:31.878  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-31 14:57:31.874  3592  3592 D HidProfile: Bluetooth service disconnected
08-31 14:57:31.879  3842  3842 V BluetoothAdapterState: isTurningOff()=true
,08-31 14:57:31.879  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.879  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.879  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.879  3842  3842 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 14:57:31.879  3842  3858 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-31 14:57:31.880  3842  3842 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 14:57:31.880  3842  3842 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:31.880  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.880  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.880  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.881  3842  3842 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 14:57:31.881  3842  3842 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 14:57:31.882  3842  3842 D BluetoothMapService: MAP Service closeService in
,08-31 14:57:31.882  3842  3842 V BluetoothAdapterState: isTurningOff()=true
08-31 14:57:31.882  3842  3842 V BluetoothAdapterState: isTurningOn()=false
08-31 14:57:31.882  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:31.882  3842  3842 V BluetoothAdapterState: isBleTurningOff()=false
08-31 14:57:31.882  3842  3842 D BluetoothMapService: cleanup()
08-31 14:57:31.882  3842  3842 D BluetoothMapService: MAP Service closeService in
08-31 14:57:31.883  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-31 14:57:31.883  3842  3854 D BluetoothAdapterProperties: Setting state to 15
08-31 14:57:31.883  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 14:57:31.883  3842  3854 I BluetoothAdapterState: Entering BleOnState
08-31 14:57:31.883  3842  3854 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-31 14:57:31.884  1354  2093 D BluetoothMap: onBluetoothStateChange: up=false
08-31 14:57:31.884  1999  2010 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:31.885  1354  1368 D BluetoothPan: onBluetoothStateChange on: false
08-31 14:57:31.885  3592  3592 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 14:57:31.885  1354  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 14:57:31.885  3592  3592 D PanProfile: Bluetooth service disconnected
08-31 14:57:31.886  3592  3604 D BluetoothMap: onBluetoothStateChange: up=false
08-31 14:57:31.887  3592  3882 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 14:57:31.887   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:31.888   869   887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 14:57:31.888  1354  2093 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:31.888   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 14:57:31.888  3592  3879 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 14:57:31.889  1354  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 14:57:31.889  3592  3604 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 14:57:31.890  1354  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 14:57:31.891  3592  3882 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 14:57:31.891  3592  3603 D BluetoothPan: onBluetoothStateChange on: false
08-31 14:57:31.892   869   887 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 14:57:31.888  3592  3592 D BluetoothPbap: Proxy object disconnected
,08-31 14:57:31.892  3592  3592 D PbapServerProfile: Bluetooth service disconnected
08-31 14:57:31.892  3842  3854 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 14:57:31.892  3842  3854 D BluetoothAdapterProperties: Setting state to 16
08-31 14:57:31.892  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 14:57:31.893  3842  3854 D BluetoothAdapterProperties: onBleDisable
08-31 14:57:31.894  3842  3855 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 14:57:31.895  3842  3864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 14:57:31.895  3842  3864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 14:57:31.895  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:31.896  3842  3858 D BluetoothAdapterProperties: Scan Mode:20
,08-31 14:57:31.898  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 14:57:31.898  3842  3854 I BluetoothAdapterState: Entering PendingCommandState
08-31 14:57:31.898  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 14:57:31.904  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:57:31.910  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:32.097  3842  3858 I bt_hci  : shut_down
,08-31 14:57:32.109  3842  3862 I bt_vendor: low_power_mode_cb
,08-31 14:57:32.110  3842  3862 D bt_hwcfg: hw_epilog_process
,08-31 14:57:32.135  3842  3862 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 14:57:32.135  3842  3862 I bt_vendor: epilog_cb
08-31 14:57:32.135  3842  3862 I bt_hci  : epilog_finished_callback
,08-31 14:57:32.143  3842  3858 I bt_hci_h4: hal_close
,08-31 14:57:32.144  3842  3858 I bt_userial_vendor: device fd = 51 close
,08-31 14:57:32.271  3842  3855 D bt_stack_manager: event_shut_down_stack finished.
,08-31 14:57:32.272  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 14:57:32.278  3842  3842 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 14:57:32.279  3842  3854 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 14:57:32.279  3842  3842 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 14:57:32.280  3842  3842 D BtGatt.GattService: stop()
08-31 14:57:32.280  3842  3842 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 14:57:32.285  3842  3842 V BluetoothAdapterState: isTurningOff()=false
,08-31 14:57:32.285  3842  3842 V BluetoothAdapterState: isTurningOn()=false
,08-31 14:57:32.285  3842  3842 V BluetoothAdapterState: isBleTurningOn()=false
08-31 14:57:32.286  3842  3842 V BluetoothAdapterState: isBleTurningOff()=true
08-31 14:57:32.286  3842  3854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 14:57:32.287  3842  3854 D BluetoothAdapterProperties: Setting state to 10
,08-31 14:57:32.287  3842  3854 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 14:57:32.289  3842  3854 I BluetoothAdapterState: Entering OffState
,08-31 14:57:32.302  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 14:57:32.311  3592  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 14:57:32.324  3592  3592 D DockEventReceiver: finishStartingService: stopping service
,08-31 14:57:32.328  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 14:58:02.098  1881  1947 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-31 14:58:02.098  1881  1947 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-31 14:58:02.143  1517  1517 I ConfigService: onCreate
,08-31 14:58:07.222  1517  1517 I ConfigService: onDestroy
,08-31 14:58:19.950   869  1315 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 14:59:29.153  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:59:29.166  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:59:29.168  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 14:59:29.218  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 14:59:29.218  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 14:59:29.218  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 14:59:29.218  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 14:59:29.252  1517  1530 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 14:59:29.252  1517  1530 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 14:59:29.255  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 14:59:29.255  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 14:59:29.255  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 14:59:29.255  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 14:59:29.255  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 14:59:29.255  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 14:59:29.255  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:04:29.406  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:04:29.430  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:04:29.439  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:04:29.538  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:04:29.538  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:04:29.538  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:04:29.538  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:04:29.575  1517  2719 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:04:29.575  1517  2719 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:04:29.586  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:04:29.586  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:04:29.586  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:04:29.586  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:04:29.586  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:04:29.586  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:04:29.586  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:04:29.589   869   878 I art     : Background partial concurrent mark sweep GC freed 21977(1257KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 29MB/43MB, paused 1.344ms total 103.455ms
,08-31 15:05:42.310  2726  2726 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-31 15:05:42.340  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:42.361  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:42.367  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:42.444  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:05:42.445  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:05:42.445  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:05:42.445  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:05:42.520  2726  2726 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-31 15:05:42.564  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:42.640  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-31 15:05:42.641  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:05:42.641  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:05:42.642  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:05:42.737  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:42.837  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:05:42.838  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-31 15:05:42.839  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:05:42.839  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:05:42.914  2726  2726 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-31 15:05:43.159  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:43.221  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:05:43.221  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:05:43.222  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:05:43.224  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:05:43.275  2726  2726 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-31 15:05:43.276  2726  2726 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-31 15:05:43.278  2726  2726 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-31 15:05:43.286  2726  3441 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-31 15:05:43.289  2726  2726 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,08-31 15:05:58.176  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:58.189  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:58.194  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:05:58.232  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:05:58.233  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:05:58.233  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:05:58.233  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:05:58.257  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 15:05:58.257  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:05:58.258  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-31 15:06:18.518  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:18.534  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:18.538  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:18.604  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:06:18.604  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:06:18.605  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:06:18.605  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:06:18.658  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 15:06:18.659  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:06:18.660  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-31 15:06:39.032  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:39.049  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:39.056  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:39.137  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:06:39.138  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 15:06:39.138  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:06:39.139  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:06:39.205  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:06:39.207  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 15:06:39.209  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-31 15:06:59.725  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:59.739  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:06:59.741  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-31 15:06:59.777  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:06:59.778  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 15:06:59.778  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:06:59.778  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-31 15:06:59.805  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:06:59.806  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:06:59.806  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 15:07:20.039  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:20.052  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:20.057  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:20.115  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 15:07:20.116  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 15:07:20.116  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:07:20.116  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:07:20.157  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:07:20.158  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:07:20.158  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-31 15:07:40.424  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:40.439  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:40.445  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:07:40.518  1517  2719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:07:40.519  1517  2719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:07:40.519  1517  2719 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:07:40.519  1517  2719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:07:40.571  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:07:40.572  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:07:40.572  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-31 15:09:29.721  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:09:29.739  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:09:29.743  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:09:29.776  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-31 15:09:29.776  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:09:29.776  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:09:29.776  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:09:29.798  1517  3446 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:09:29.798  1517  3446 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:09:29.802  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:09:29.802  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:09:29.802  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:09:29.802  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:09:29.802  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:09:29.802  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:09:29.802  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:14:16.129   869   882 I UsageStatsService: User[0] Flushing usage stats to disk
,08-31 15:14:29.950  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:14:29.966  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:14:29.973  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:14:30.046  1517  3446 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:14:30.047  1517  3446 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-31 15:14:30.047  1517  3446 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:14:30.047  1517  3446 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:14:30.080  1517  3446 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:14:30.080  1517  3446 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:14:30.089  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:14:30.089  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:14:30.089  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:14:30.089  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:14:30.089  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:14:30.089  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:14:30.089  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:19:30.232  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:19:30.253  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:19:30.260  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:19:30.347  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:19:30.347  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-31 15:19:30.348  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:19:30.348  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:19:30.379  1517  1530 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:19:30.379  1517  1530 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:19:30.389  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:19:30.389  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:19:30.389  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:19:30.389  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:19:30.389  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:19:30.389  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:19:30.389  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-31 15:20:32.566  4002  4002 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 15:20:32.571  4002  4002 D AndroidRuntime: CheckJNI is OFF
08-31 15:20:32.614  4002  4002 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 15:20:32.661  4002  4002 I Radio-JNI: register_android_hardware_Radio DONE
08-31 15:20:32.685  4002  4002 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 15:20:32.696   869   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-31 15:20:32.697   869   883 I ActivityManager: Killing 3484:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-31 15:20:32.789   869  1397 D GraphicsStats: Buffer count: 2
08-31 15:20:32.789   869  2046 I WindowState: WIN DEATH: Window{71422b5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:20:32.790   869  1314 D WifiService: Client connection lost with reason: 4
08-31 15:20:32.830   869   894 W PackageSettings: Skipping PackageSetting{9a1ed19 com.example.hello/10273} due to missing metadata
08-31 15:20:32.855   869   883 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-31 15:20:32.855   869   883 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 15:20:32.856   869   883 E ActivityManager: Failure starting process com.test.thalitest
08-31 15:20:32.856   869   883 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 15:20:32.856   869   883 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:20:32.856   869   883 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:32.856   869   883 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:32.856   869   883 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 15:20:32.856   869   883 I ActivityManager:   Force finishing activity ActivityRecord{55fb2b6 u0 com.test.thalitest/.MainActivity t2}
08-31 15:20:32.857   869   894 I art     : Starting a blocking GC Explicit
08-31 15:20:32.867   869  1397 W ActivityManager: Spurious death for ProcessRecord{fe860d4 0:com.test.thalitest/u0a0}, curProc for 3484: null
08-31 15:20:32.905   869   894 I art     : Explicit concurrent mark sweep GC freed 19353(1393KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 720us total 47.052ms
08-31 15:20:32.935   869   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-31 15:20:32.939  4002  4002 I art     : System.exit called, status: 0
08-31 15:20:32.939  4002  4002 I AndroidRuntime: VM exiting with result code 0.
08-31 15:20:32.943   869   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-31 15:20:32.963   869   883 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-31 15:20:32.969  1911  2247 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 15:20:32.974  3331  3331 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-31 15:20:32.976   869  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 15:20:32.978  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
08-31 15:20:33.001   869  1970 I ActivityManager: Start proc 4019:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-31 15:20:33.008  1881  4016 I Keyboard.Facilitator.DecoderInitializer: run()
08-31 15:20:33.014  1999  1999 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-31 15:20:33.016  1881  4016 I Decoder : createOrResetDecoder
08-31 15:20:33.043  1517  1517 I ConfigService: onCreate
08-31 15:20:33.053  4019  4019 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-31 15:20:33.065   869   869 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 15:20:33.073   869  1397 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3484 uid 10000
08-31 15:20:33.077  1881  4016 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-31 15:20:33.077  1881  1881 I Keyboard.Facilitator: onFinishInput()
08-31 15:20:33.105  1881  4016 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-31 15:20:33.107  2014  2087 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-31 15:20:33.108  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 15:20:33.108   869   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-31 15:20:33.108  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-31 15:20:33.109   869   882 E PackageManager: Failed to write settings, restoring backup
08-31 15:20:33.109   869   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 15:20:33.109   869   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 15:20:33.109   869   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 15:20:33.109   869   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 15:20:33.109   869   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 15:20:33.109   869   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:20:33.109   869   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.109   869   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:33.111  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 15:20:33.111  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 15:20:33.113   869   883 E DropBoxManagerService: Can't write: system_server_wtf
08-31 15:20:33.113   869   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 15:20:33.113   869   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:20:33.113   869   883 E DropBoxManagerService: 	... 13 more
08-31 15:20:33.114  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-31 15:20:33.114  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 15:20:33.116  1881  4016 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 15:20:33.116  1881  4016 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 15:20:33.116  1881  4016 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 15:20:33.120   869  2041 I ActivityManager: Start proc 4036:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-31 15:20:33.120  2014  2087 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 15:20:33.120  2014  2087 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2014
08-31 15:20:33.120  2014  2087 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.120  2014  2087 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:33.123   869  2046 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 15:20:33.124   869  4044 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:20:33.124   869  4044 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:20:33.124   869  4044 E DropBoxManagerService: 	... 5 more
08-31 15:20:33.127  2014  2087 I Process : Sending signal. PID: 2014 SIG: 9
08-31 15:20:33.131  1881  4016 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-31 15:20:33.131  1881  4016 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 15:20:33.131  1881  4016 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
08-31 15:20:33.131  1881  4016 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
08-31 15:20:33.134  1881  4016 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml to backup file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml.bak
08-31 15:20:33.147  4019  4019 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-31 15:20:33.169   869  2041 I ActivityManager: Start proc 4053:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-31 15:20:33.173  4019  4056 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:20:33.191  1517  4052 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:20:33.195  4053  4053 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:20:33.202  1517  4052 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:20:33.211  1517  4052 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-31 15:20:33.211  1517  4052 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.214  4019  4056 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:20:33.219  1517  4052 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 15:20:33.231  4019  4056 E AndroidRuntime: Process: android.process.acore, PID: 4019
08-31 15:20:33.231  4019  4056 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.231  4019  4056 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:20:33.233  4019  4056 I Process : Sending signal. PID: 4019 SIG: 9
08-31 15:20:33.233   869  4071 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:20:33.233   869  4071 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:20:33.233   869  4071 E DropBoxManagerService: 	... 5 more
08-31 15:20:33.239  1517  1517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-31 15:20:33.240  1517  1517 D AndroidRuntime: Shutting down VM
08-31 15:20:33.241  1517  1517 E AndroidRuntime: FATAL EXCEPTION: main
08-31 15:20:33.241  1517  1517 E AndroidRuntime: Process: com.google.process.gapps, PID: 1517
08-31 15:20:33.241  1517  1517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 15:20:33.241  1517  1517 E AndroidRuntime: 	... 8 more
08-31 15:20:33.245   869  4072 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:20:33.245   869  4072 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:20:33.245   869  4072 E DropBoxManagerService: 	... 5 more
08-31 15:20:33.245  1517  1517 I Process : Sending signal. PID: 1517 SIG: 9
08-31 15:20:33.284   869  1970 D GraphicsStats: Buffer count: 1
08-31 15:20:33.285   869  2015 I WindowState: WIN DEATH: Window{77ec837 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-31 15:20:33.288   869  2046 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2014) has died
08-31 15:20:33.289   869  2046 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-31 15:20:33.295   869  2046 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-31 15:20:33.305   279   279 E lowmemorykiller: Error writing /proc/4019/oom_score_adj; errno=22
08-31 15:20:33.322   869   883 I ActivityManager: Start proc 4075:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 15:20:33.323   869  1909 I ActivityManager: Killing 3209:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
08-31 15:20:33.383   869  1314 D WifiService: Client connection lost with reason: 4
08-31 15:20:33.409   869  2041 I ActivityManager: Process com.google.process.gapps (pid 1517) has died
08-31 15:20:33.409  1729  4074 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@dc40e35
08-31 15:20:33.410   869  2041 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-31 15:20:33.410   869  2041 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-31 15:20:33.410   869  2041 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 21000ms
08-31 15:20:33.410   869  2041 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-31 15:20:33.412   869  1387 I ActivityManager: Process android.process.acore (pid 4019) has died
08-31 15:20:33.412   869  1387 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30997ms

```
