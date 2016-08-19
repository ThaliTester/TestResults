#### Test 8180285644342f8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-19 17:56:03.737  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-19 17:56:03.747  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-19 17:56:03.750  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-19 17:56:03.789  1489  2849 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-19 17:56:03.789  1489  2849 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-19 17:56:03.789  1489  2849 I GLSUser : [GLSUser] Extracting token using key: Auth
08-19 17:56:03.790  1489  2849 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-19 17:56:03.831  2751  2751 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-19 17:56:03.831  2751  2751 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-19 17:56:03.832  2751  2751 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-19 17:56:04.399  3562  3562 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-19 17:56:04.404  3562  3562 D AndroidRuntime: CheckJNI is OFF
08-19 17:56:04.447  3562  3562 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-19 17:56:04.498  3562  3562 I Radio-JNI: register_android_hardware_Radio DONE
08-19 17:56:04.519  3562  3562 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-19 17:56:04.523   872  1888 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-19 17:56:04.587   872  1888 I ActivityManager: Start proc 3571:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-19 17:56:04.598  3562  3562 D AndroidRuntime: Shutting down VM
08-19 17:56:04.687  3571  3571 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-19 17:56:04.708  3571  3571 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-19 17:56:04.715  3571  3571 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6805-6808)
08-19 17:56:04.715  3571  3571 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-19 17:56:04.731  3571  3571 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d9fd068}
08-19 17:56:04.731  3571  3571 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-19 17:56:04.732  3571  3571 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-19 17:56:04.742  3571  3571 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-19 17:56:04.743  3571  3571 E SysUtils: ApplicationContext is null in ApplicationStatus
08-19 17:56:04.759  3571  3586 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-19 17:56:04.768  3571  3571 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-19 17:56:04.779  3571  3571 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-19 17:56:04.779  3571  3571 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-19 17:56:04.779  3571  3571 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-19 17:56:04.779  3571  3571 I Adreno  : Build Date                       : 10/20/15
08-19 17:56:04.779  3571  3571 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-19 17:56:04.779  3571  3571 I Adreno  : Local Branch                     : M14
08-19 17:56:04.779  3571  3571 I Adreno  : Remote Branch                    : 
08-19 17:56:04.779  3571  3571 I Adreno  : Remote Branch                    : 
08-19 17:56:04.779  3571  3571 I Adreno  : Reconstruct Branch               : 
,08-19 17:56:04.852   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9487a1c:true
,08-19 17:56:04.883  3571  3571 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-19 17:56:04.897  3571  3571 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-19 17:56:04.952  3571  3609 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-19 17:56:04.966  3571  3595 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-19 17:56:05.008  3571  3609 I OpenGLRenderer: Initialized EGL, version 1.4
,08-19 17:56:05.126   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +485ms (total +579ms)
,08-19 17:56:05.139  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-19 17:56:05.205  3571  3571 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3571
,08-19 17:56:05.342  3571  3571 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-19 17:56:05.526  3571  3611 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1702364880
,08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-19 17:56:05.531  3571  3611 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f73a1f added. We now have 1 listener(s)
,08-19 17:56:05.535  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-19 17:56:05.535  3571  3611 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:05.536  3571  3611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:05.536  3571  3611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-19 17:56:05.541  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-19 17:56:05.542  3571  3611 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa203ca added. We now have 1 listener(s)
,08-19 17:56:05.542  3571  3611 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:05.549   872  1304 D WifiService: New client listening to asynchronous messages
,08-19 17:56:05.550  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:56:05.551  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-19 17:56:05.551  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-19 17:56:05.552  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-19 17:56:05.552  3571  3611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-19 17:56:05.558  3571  3611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:05.559  3571  3611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-19 17:56:05.568  3571  3611 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:05.569  3571  3611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:05.569  3571  3611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-19 17:56:05.569  3571  3611 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:05.570  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:05.571  3571  3611 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-19 17:56:05.600  3571  3571 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-19 17:56:06.436  3571  3617 W jxcore-log: Initializing JXcore engine
,08-19 17:56:06.436  3571  3617 W jxcore-log: JXcore engine is ready
,08-19 17:56:06.473  3617  3617 W Thread-293: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-19 17:56:06.473  3617  3617 W Thread-293: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10567]" dev="sockfs" ino=10567 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-19 17:56:06.473  3617  3617 W Thread-293: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-19 17:56:06.473  3617  3617 W Thread-293: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22390]" dev="sockfs" ino=22390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-19 17:56:06.486  3571  3617 W jxcore-log: Starting JXcore engine
,08-19 17:56:06.564  3571  3617 W jxcore-log: Platform android
08-19 17:56:06.564  3571  3617 W jxcore-log: 
,08-19 17:56:06.564  3571  3617 W jxcore-log: Process ARCH arm
08-19 17:56:06.564  3571  3617 W jxcore-log: 
,08-19 17:56:06.750  3571  3617 I jxcore-log: JXcore Cordova bridge is ready!
08-19 17:56:06.750  3571  3617 I jxcore-log: 
,08-19 17:56:06.751  3571  3617 W jxcore-log: JXcore engine is started
,08-19 17:56:06.762  3571  3611 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-19 17:56:06.768  3571  3571 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-19 17:56:16.058  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-19 17:56:16.058  3571  3617 I jxcore-log: 
,08-19 17:56:16.061  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-19 17:56:16.061  3571  3617 I jxcore-log: 
,08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.069  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:16.073  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:16.075  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-19 17:56:16.075  3571  3617 I jxcore-log: 
,08-19 17:56:16.077  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-19 17:56:16.077  3571  3617 I jxcore-log: 
,08-19 17:56:16.560  3571  3617 D ExecuteNativeTests: Running unit tests
,08-19 17:56:16.618  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:56:16.618  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 added. We now have 2 listener(s)
,08-19 17:56:16.619  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:16.619  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:56:16.619  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:16.619  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:16.619  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e added. We now have 2 listener(s)
08-19 17:56:16.619  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:16.620  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:56:16.626  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.640  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:16.642  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:16.643  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:16.644  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.645  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-19 17:56:16.647  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:56:16.647  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:56:16.648  3571  3617 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-19 17:56:16.648  3571  3617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-19 17:56:16.648  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-19 17:56:16.649  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-19 17:56:16.649  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:56:16.649  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:56:16.649  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:56:16.649  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.650  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:56:16.650  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-19 17:56:16.650  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.650  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:56:16.650  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 removed from the list
,08-19 17:56:16.650  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.650  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e removed from the list
,08-19 17:56:16.650  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:56:16.650  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.651  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-19 17:56:16.652  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.652  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:56:16.652  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.653  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.653  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.654  3571  3617 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-19 17:56:16.655  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.655  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.655  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.655  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.655  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.655  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.655  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.655  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.655  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.655  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.655  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.655  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.655  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.655  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.656  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.656  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.656  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.656  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:56:16.661  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:56:16.662  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-19 17:56:16.662  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.662  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.662  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.663  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.663  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.663  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.663  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.663  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.663  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.663  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.663  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.663  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.663  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.663  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.664  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.664  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.664  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.664  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.664  3571  3617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:56:16.666  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.668  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:16.669  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.669  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:56:16.669  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:16.669  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:56:16.669  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:16.670  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.670  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:56:16.670  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.676  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-19 17:56:16.676  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:56:16.680  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:56:16.681  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-19 17:56:16.681  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:56:16.683  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-19 17:56:16.685  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-19 17:56:16.685  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:56:16.685  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:16.685  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:56:16.686  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:16.690  2553  2567 D BtGatt.GattService: registerClient() - UUID=8a3ebed5-8a44-4f01-be9a-c4095e9988bf
08-19 17:56:16.692  2553  2611 D BtGatt.GattService: onClientRegistered() - UUID=8a3ebed5-8a44-4f01-be9a-c4095e9988bf, clientIf=5
08-19 17:56:16.693  3571  3581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-19 17:56:16.695  2553  2742 D BtGatt.GattService: start scan with filters
08-19 17:56:16.697  2553  2615 D BtGatt.ScanManager: handling starting scan
08-19 17:56:16.698  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:56:16.698  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:16.698  2553  2615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:16.699  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:16.699  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-19 17:56:16.701  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:56:16.701  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:56:16.701  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:56:16.702  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-19 17:56:16.705  3571  3617 I io.jxcore.node.ConnectionHelper: start: OK
08-19 17:56:16.706  2553  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-19 17:56:16.706  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.706  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.706  3571  3617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:56:16.707  2553  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-19 17:56:16.707  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.707  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:56:16.707  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.707  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:56:16.707  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:56:16.708  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:16.708  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:56:16.708  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:16.708  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:56:16.708  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:16.709  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:16.709  2553  2567 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:56:16.710  2553  2742 D BtGatt.GattService: unregisterClient() - clientIf=5
08-19 17:56:16.710  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:56:16.710  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:16.710  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:16.710  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:16.710  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:56:16.711  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.712  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:56:16.712  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:56:16.712  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:56:16.713  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.713  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.713  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.713  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.713  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.713  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.713  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.713  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.714  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.713  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-19 17:56:16.714  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.714  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.714  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.714  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.714  3571  3617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:56:16.715  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.715  2553  2615 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:56:16.715  2553  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.719  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:16.721  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.721  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:56:16.721  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:16.721  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:56:16.722  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:16.722  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.722  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.722  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:56:16.725  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-19 17:56:16.725  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:56:16.728  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:56:16.728  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-19 17:56:16.728  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:56:16.730  2553  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-19 17:56:16.730  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.738  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:56:16.738  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:16.738  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:56:16.739  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:16.741  2553  2750 D BtGatt.GattService: registerClient() - UUID=efa79555-325f-4631-8415-7c8f11fe39c6
08-19 17:56:16.741  2553  2611 D BtGatt.GattService: onClientRegistered() - UUID=efa79555-325f-4631-8415-7c8f11fe39c6, clientIf=5
08-19 17:56:16.742  3571  3582 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-19 17:56:16.742  2553  2574 D BtGatt.GattService: start scan with filters
08-19 17:56:16.745  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-19 17:56:16.745  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.745  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:56:16.745  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:16.746  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:16.746  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-19 17:56:16.749  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:56:16.750  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:56:16.750  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:56:16.752  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-19 17:56:16.752  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.752  2553  2615 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:56:16.752  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-19 17:56:16.754  3571  3617 I io.jxcore.node.ConnectionHelper: start: OK
08-19 17:56:16.756  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.756  3571  3617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:56:16.756  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.756  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-19 17:56:16.756  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.756  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:56:16.756  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:56:16.756  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:16.756  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:56:16.756  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:16.757  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:56:16.757  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:16.757  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:16.757  2553  2750 D BtGatt.GattService: stopScan() - queue size =0
08-19 17:56:16.758  2553  2574 D BtGatt.GattService: unregisterClient() - clientIf=5
08-19 17:56:16.758  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:56:16.758  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:16.758  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:16.758  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:16.758  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:56:16.759  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.759  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:56:16.759  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:56:16.759  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:56:16.760  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-19 17:56:16.760  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.760  2553  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-19 17:56:16.761  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.763  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.763  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.763  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.763  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.763  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.763  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:56:16.763  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.764  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.764  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.764  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:56:16.764  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.765  2553  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-19 17:56:16.765  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.765  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.765  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.766  2553  2615 D BtGatt.ScanManager: handling starting scan
08-19 17:56:16.766  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.766  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.766  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.766  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.767  3571  3617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:56:16.768  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.771  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:16.773  2553  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-19 17:56:16.773  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.774  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:16.774  2553  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-19 17:56:16.775  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:16.776  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:56:16.776  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-19 17:56:16.776  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:16.776  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.776  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:56:16.778  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.778  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-19 17:56:16.779  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:56:16.784  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-19 17:56:16.784  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.784  2553  2615 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:56:16.785  2553  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:16.786  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:56:16.787  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-19 17:56:16.788  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:56:16.793  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:56:16.793  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:16.793  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:56:16.794  3571  3617 D BluetoothAdapter: STATE_ON
,08-19 17:56:16.801  2553  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-19 17:56:16.801  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:16.803  2553  2750 D BtGatt.GattService: registerClient() - UUID=1a53f735-5cd0-44e0-a876-6f7693319b4b
,08-19 17:56:16.803  2553  2611 D BtGatt.GattService: onClientRegistered() - UUID=1a53f735-5cd0-44e0-a876-6f7693319b4b, clientIf=5
,08-19 17:56:16.804  3571  3581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-19 17:56:16.804  2553  2567 D BtGatt.GattService: start scan with filters
08-19 17:56:16.805  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-19 17:56:16.806  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:16.811  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:56:16.811  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:16.812  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:16.812  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:56:16.813  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:16.813  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:56:16.813  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:16.814  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:56:16.816  3571  3617 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:56:16.816  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.816  3571  3617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:56:16.816  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.816  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:56:16.816  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.816  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:56:16.816  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:56:16.816  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:16.816  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-19 17:56:16.816  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:16.817  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:56:16.817  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:16.817  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:16.818  2553  2567 D BtGatt.GattService: stopScan() - queue size =0
08-19 17:56:16.818  2553  2574 D BtGatt.GattService: unregisterClient() - clientIf=5
08-19 17:56:16.818  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:56:16.819  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:16.819  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:16.819  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:16.819  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:56:16.819  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:56:16.819  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:56:16.820  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:56:16.820  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:56:16.820  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.822  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-19 17:56:16.822  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:16.822  2553  2615 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:56:16.822  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.823  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.823  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.823  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:56:16.823  3571  3617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:56:16.823  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.823  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.823  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.823  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.823  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:16.823  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.823  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.823  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.823  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.823  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.824  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.824  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.825  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.825  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:16.825  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.825  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.825  3571  3617 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-19 17:56:16.826  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.826  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.826  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.826  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.826  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.826  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.826  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.826  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.826  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.826  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.826  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.826  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.826  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.826  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.827  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.827  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.827  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.827  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.828  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:56:16.828  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.828  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.828  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.829  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.829  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.829  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.829  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.829  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.829  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.829  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.829  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.829  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.829  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.829  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.830  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-19 17:56:16.830  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.830  2553  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-19 17:56:16.830  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.830  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.830  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.830  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.831  3571  3617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-19 17:56:16.831  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:56:16.831  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:56:16.831  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.831  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:56:16.831  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.831  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.831  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
,08-19 17:56:16.831  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.832  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.832  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.832  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.832  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.832  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.832  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.832  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.832  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.832  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.832  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.833  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-19 17:56:16.833  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.833  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.833  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.834  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:56:16.834  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.834  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.834  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
,08-19 17:56:16.834  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.834  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.834  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.834  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.834  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.834  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.834  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.835  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:56:16.835  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:16.835  2553  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-19 17:56:16.835  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:16.835  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.835  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.836  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:56:16.836  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:56:16.836  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:56:16.836  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:56:16.836  2553  2615 D BtGatt.ScanManager: handling starting scan
08-19 17:56:16.836  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:56:16.836  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:56:16.836  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.836  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.837  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.837  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.837  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.837  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.837  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.837  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.837  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.837  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.837  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.837  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.837  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.837  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.838  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.838  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.838  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.838  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
,08-19 17:56:16.839  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:56:16.839  3571  3617 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:56:16.839  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-19 17:56:16.841  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:56:16.841  3571  3617 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-19 17:56:16.841  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:56:16.841  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-19 17:56:16.842  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-19 17:56:16.843  2553  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-19 17:56:16.843  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.843  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:56:16.843  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-19 17:56:16.843  2553  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-19 17:56:16.844  3571  3617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:56:16.844  3571  3617 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-19 17:56:16.844  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:56:16.844  3571  3617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-19 17:56:16.844  3571  3617 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-19 17:56:16.844  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-19 17:56:16.844  3571  3617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:56:16.844  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-19 17:56:16.847  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-19 17:56:16.848  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-19 17:56:16.848  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-19 17:56:16.848  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-19 17:56:16.848  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-19 17:56:16.848  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-19 17:56:16.849  3571  3617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-19 17:56:16.849  3571  3617 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-19 17:56:16.849  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:56:16.849  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.849  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:16.849  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.849  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.849  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.849  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-19 17:56:16.850  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-19 17:56:16.850  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-19 17:56:16.850  2553  2615 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:56:16.850  2553  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:16.852  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.852  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:16.852  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.852  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:56:16.852  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.852  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.852  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:16.853  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.854  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.854  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:16.854  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.854  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.855  3571  3617 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-19 17:56:16.855  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.855  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.855  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.855  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.856  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.856  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.856  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.856  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.856  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.856  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.856  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.856  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:16.856  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-19 17:56:16.856  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.857  3571  3619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 357)
08-19 17:56:16.858  2553  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-19 17:56:16.858  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.858  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.859  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.859  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.859  3571  3619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:56:16.859  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.861  3571  3617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-19 17:56:16.861  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.861  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.861  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.861  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.861  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.861  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.862  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.862  3571  3620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 357
08-19 17:56:16.862  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.862  3571  3620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 357)
08-19 17:56:16.862  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.862  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.862  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.862  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.862  3571  3619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 357)
08-19 17:56:16.862  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.862  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.863  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.863  2553  2739 E bt_btif_sock_rfcomm: btsock_r,fc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-19 17:56:16.863  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.863  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.863  3571  3620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 357)
08-19 17:56:16.863  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.863  3571  3617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-19 17:56:16.864  3571  3617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-19 17:56:16.864  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:56:16.864  3571  3617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-19 17:56:16.864  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-19 17:56:16.864  3571  3617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:56:16.864  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.864  3571  3617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-19 17:56:16.864  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:56:16.864  3571  3617 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-19 17:56:16.864  3571  3617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:56:16.864  3571  3617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:56:16.864  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:56:16.864  3571  3617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-19 17:56:16.865  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.865  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.865  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.865  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.865  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.866  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.866  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.866  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.866  3571  3617 E org.thaliproject,.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.866  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.866  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.866  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.866  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.866  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.867  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.867  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.867  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.867  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.868  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.868  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.868  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.868  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.868  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.868  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.868  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.868  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.868  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.868  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.868  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.868  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.869  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.869  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.869  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.869  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.869  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.869  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.869  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.869  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.869  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.869  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.869  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.869  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.869  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.870  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.870  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.870  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.870  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.871  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.871  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.871  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.871  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.872  3571  3617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-19 17:56:16.872  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.872  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-19 17:56:16.873  3571  3617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-19 17:56:16.873  3571  3617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-19 17:56:16.873  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-19 17:56:16.873  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:56:16.873  3571  3571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-19 17:56:16.873  2553  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-19 17:56:16.874  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.874  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.874  2553  2615 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:56:16.874  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-19 17:56:16.874  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-19 17:56:16.874  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-19 17:56:16.874  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.874  3571  3617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-19 17:56:16.875  3571  3571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-19 17:56:16.875  3571  3621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:56:16.875  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.875  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.875  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:16.877  3571  3621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-19 17:56:16.877  3571  3621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-19 17:56:16.875  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:56:16.877  3571  3621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-19 17:56:16.877  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:16.877  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.877  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.878  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.878  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.878  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.878  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.878  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.878  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.878  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.878  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:16.878  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.878  3571  3571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-19 17:56:16.878  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.879  2553  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-19 17:56:16.879  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:16.879  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.879  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.879  2553  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-19 17:56:16.879  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.879  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.879  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.879  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.879  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.879  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.879  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.880  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.880  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.880  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.880  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.881  3571  3617 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-19 17:56:16.881  3571  3617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:56:16.881  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:56:16.882  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:56:16.882  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.882  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.882  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.882  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.882  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.882  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.882  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.882  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.882  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.882  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.882  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.883  ,3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.883  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.883  2553  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-19 17:56:16.883  2553  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:16.883  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.884  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.884  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.884  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.884  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.886  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.887  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.887  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.887  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.887  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.887  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.887  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.887  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.887  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.887  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.887  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.887  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.887  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.887  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.888  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.888  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.888  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.888  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.889  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:16.889  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:16.889  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:16.889  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:16.889  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.889  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.889  3571  3617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1542f09 not in the list
08-19 17:56:16.889  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.889  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.889  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:16.889  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.889  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.890  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:16.890  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:16.890  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:16.890  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:16.890  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:16.891  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@122f50e not in the list
08-19 17:56:16.891  3571  3617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-19 17:56:16.891  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:56:16.891  3571  3617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-19 17:56:16.892  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:56:16.892  3571  3617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-19 17:56:16.892  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:56:16.893  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:56:16.893  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-19 17:56:16.894  3571  3617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-19 17:56:16.894  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:56:16.894  3571  3617 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-19 17:56:16.894  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:56:16.894  3571  3617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-19 17:56:16.894  3571  3617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-19 17:56:16.895  3571  3617 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-19 17:56:16.896  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:16.896  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc60540 added. We now have 2 listener(s)
08-19 17:56:16.896  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:16.898  3571  3617 D BluetoothAdapter: enable(): BT is already enabled..!
08-19 17:56:16.898   872   883 D WifiService: setWifiEnabled: true pid=3571, uid=10000
08-19 17:56:16.898   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-19 17:56:16.899  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:16.899  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@269ec79 added. We now have 3 listener(s)
08-19 17:56:16.899  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:16.902  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:16.902  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bbcbdbe added. We now have 4 listener(s)
08-19 17:56:16.902  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:16.903  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:16.904  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20de1f added. We now have 5 listener(s)
08-19 17:56:16.904  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:16.905   872  2007 D WifiService: setWifiEnabled: false pid=3571, uid=10000
08-19 17:56:16.905   872  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-19 17:56:16.913  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:16.913  2553  2606 D BluetoothAdapterState: Current state: ON, message: 23
,08-19 17:56:16.913  2553  2606 D BluetoothAdapterProperties: Setting state to 13
08-19 17:56:16.913  2553  2606 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:56:16.914  2553  2606 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:56:16.914  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.914  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:16.914   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-19 17:56:16.915  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.915  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.915  2553  2606 I BluetoothAdapterState: Entering PendingCommandState
08-19 17:56:16.915  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:56:16.917  2553  2553 D BluetoothMapService: onReceive
08-19 17:56:16.917  2553  2553 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:56:16.917  2553  2553 D BluetoothMapService: STATE_TURNING_OFF
08-19 17:56:16.918  2553  2553 D BluetoothMapService: MAP Service closeService in
08-19 17:56:16.918  2553  2553 D BluetoothMapMasInstance0: MAP Service shutdown
08-19 17:56:16.918  2553  2553 D ObexServerSockets0: shutdown(block = true)
08-19 17:56:16.918  2553  2553 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-19 17:56:16.918  2553  2553 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-19 17:56:16.918  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.918  2553  2761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.919  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:16.919  2553  2739 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-19 17:56:16.919  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.919  2553  2762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-19 17:56:16.919  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.921  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:16.921  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:16.921  2553  2553 I BtOppRfcommListener: stopping Accept Thread
08-19 17:56:16.921  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:16.921  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:16.922  2553  3254 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:56:16.922  2553  3254 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:56:16.922  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.924  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.925  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.925  1971  2278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:56:16.932   872   885 I ActivityManager: Start proc 3624:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-19 17:56:16.933  2553  2611 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:56:16.933  2553  2606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-19 17:56:16.936  2553  2553 D HeadsetService: Received stop request...Stopping profile...
08-19 17:56:16.936  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.938  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.941   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:16.941   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:16.941  1357  1378 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:16.941   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:16.941  1917  2041 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:16.943  2553  2553 D A2dpService: Received stop request...Stopping profile...
08-19 17:56:16.943  2553  2745 D A2dpStateMachine: Exit Disconnected: -1
08-19 17:56:16.944   872   872 D BluetoothA2dp: Proxy object disconnected
08-19 17:56:16.944  2553  2553 D HidService: Received stop request...Stopping profile...
08-19 17:56:16.944  2553  2553 D HidService: Stopping Bluetooth HidService
08-19 17:56:16.945  2553  2553 D HealthService: Received stop request...Stopping profile...
08-19 17:56:16.946  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:16.946  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:16.946  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:16.946  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:16.947  2553  2553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:56:16.947  2553  2553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:56:16.948  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:16.948  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:16.948  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:16.948  2553  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-19 17:56:16.948  2553  2611 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-19 17:56:16.948  2553  2553 D PanService: Received stop request...Stopping profile...
08-19 17:56:16.952  2553  2553 D BluetoothMapService: Received stop request...Stopping profile...
08-19 17:56:16.952  2553  2553 D BluetoothMapService: stop()
08-19 17:56:16.953  2553  2553 D BluetoothMapAppObserver: deinitObservers()
08-19 17:56:16.953  2553  2553 D BluetoothMapAppObserver: removeReceiver()
08-19 17:56:16.955  1357  1357 D HeadsetProfile: Bluetooth service disconnected
08-19 17:56:16.955  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:16.955  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:16.955  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:16.955  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:16.955  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-19 17:56:16.956  1357  1357 D BluetoothInputDevice: Proxy object disconnected,
08-19 17:56:16.956  1357  1357 D HidProfile: Bluetooth service disconnected
,08-19 17:56:16.956  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-19 17:56:16.956  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:56:16.956  1357  1357 D PanProfile: Bluetooth service disconnected
08-19 17:56:16.956  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-19 17:56:16.956  1357  1357 D BluetoothMap: Proxy object disconnected
08-19 17:56:16.956  2553  2733 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:56:16.956  1357  1357 D MapProfile: Bluetooth service disconnected
,08-19 17:56:16.956  2553  2733 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:56:16.957  2553  2733 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-19 17:56:16.957  2553  2733 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:56:16.957  2553  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-19 17:56:16.956  2553  2553 V BluetoothAdapterState: isTurningOff()=true
,08-19 17:56:16.957  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:16.957  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:16.957  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:16.957  2553  2553 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-19 17:56:16.958  2553  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-19 17:56:16.957  2553  2553 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-19 17:56:16.958  2553  2553 V BluetoothAdapterState: isTurningOff()=true
,08-19 17:56:16.958  2553  2553 V BluetoothAdapterState: isTurningOn()=false
,08-19 17:56:16.958  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:16.958  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:16.958  2553  2553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-19 17:56:16.958  2553  2611 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-19 17:56:16.959  2553  2553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:56:16.959  2553  2553 V BluetoothAdapterState: isTurningOff()=true
,08-19 17:56:16.959  2553  2553 V BluetoothAdapterState: isTurningOn()=false
,08-19 17:56:16.959  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:16.959  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:16.959  2553  2553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:56:16.959  2553  2553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-19 17:56:16.960  2553  2553 D BluetoothMapService: MAP Service closeService in
,08-19 17:56:16.960  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:16.960  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:16.960  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:16.960  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:16.961  2553  2553 D BluetoothMapService: cleanup()
08-19 17:56:16.961  2553  2553 D BluetoothMapService: MAP Service closeService in
08-19 17:56:16.961  2553  2606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-19 17:56:16.961  2553  2606 D BluetoothAdapterProperties: Setting state to 15
08-19 17:56:16.961  2553  2606 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-19 17:56:16.962  2553  2606 I BluetoothAdapterState: Entering BleOnState
,08-19 17:56:16.962   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:56:16.962  1357  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:16.962  1917  1929 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:16.963  1357  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:56:16.963  1357  1370 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:56:16.964  1357  2014 D BluetoothPan: onBluetoothStateChange on: false
08-19 17:56:16.964  1357  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:56:16.965   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:16.965   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:16.965   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-19 17:56:16.965  1357  1370 D BluetoothMap: onBluetoothStateChange: up=false
08-19 17:56:16.966  2553  2606 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-19 17:56:16.966  2553  2606 D BluetoothAdapterProperties: Setting state to 16
08-19 17:56:16.966  2553  2606 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-19 17:56:16.966  2553  2606 D BluetoothAdapterProperties: onBleDisable
08-19 17:56:16.966  2553  2606 I BluetoothAdapterState: Entering PendingCommandState
08-19 17:56:16.967  2553  2607 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-19 17:56:16.968  2553  2733 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-19 17:56:16.968  2553  2733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:16.968  2553  2611 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:56:16.969  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.970  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.974  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:16.975  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:17.007  3624  3624 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-19 17:56:17.046  3624  3624 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-19 17:56:17.071   872  1930 I ActivityManager: Start proc 3649:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-19 17:56:17.073   872  2011 I ActivityManager: Killing 2838:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-19 17:56:17.153  3649  3649 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-19 17:56:17.169  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:56:17.170  2553  2611 I bt_hci  : shut_down
,08-19 17:56:17.170  2553  2618 D bt_hwcfg: hw_epilog_process
,08-19 17:56:17.177   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8bfbdd6:true
,08-19 17:56:17.181  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:17.183  2553  2618 I bt_vendor: low_power_mode_cb
,08-19 17:56:17.205   872   882 I ActivityManager: Start proc 3661:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-19 17:56:17.210  3649  3649 D LocalBluetoothProfileManager: Adding local MAP profile
08-19 17:56:17.212  3649  3649 D BluetoothMap: Create BluetoothMap proxy object
,08-19 17:56:17.213  2553  2618 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-19 17:56:17.213  2553  2618 I bt_vendor: epilog_cb
08-19 17:56:17.213  2553  2618 I bt_hci  : epilog_finished_callback
,08-19 17:56:17.218  2553  2611 I bt_hci_h4: hal_close
08-19 17:56:17.220  2553  2611 I bt_userial_vendor: device fd = 51 close
,08-19 17:56:17.243  3649  3649 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-19 17:56:17.249  3661  3661 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-19 17:56:17.261  3649  3649 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:56:17.266   872   882 I ActivityManager: Killing 3032:com.google.android.gm/u0a78 (adj 15): empty #17
,08-19 17:56:17.349  2553  2607 D bt_stack_manager: event_shut_down_stack finished.
,08-19 17:56:17.350  2553  2606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-19 17:56:17.355  2553  2606 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-19 17:56:17.355  2553  2553 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:56:17.356  2553  2553 D BtGatt.GattService: Received stop request...Stopping profile...
,08-19 17:56:17.356  2553  2553 D BtGatt.GattService: stop()
,08-19 17:56:17.356  2553  2553 D BtGatt.AdvertiseManager: advertise clients cleared
,08-19 17:56:17.360  2553  2553 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:17.360  2553  2553 V BluetoothAdapterState: isTurningOn()=false
,08-19 17:56:17.360  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:17.361  2553  2553 V BluetoothAdapterState: isBleTurningOff()=true
,08-19 17:56:17.361  2553  2606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-19 17:56:17.362  2553  2606 D BluetoothAdapterProperties: Setting state to 10
08-19 17:56:17.362  2553  2606 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-19 17:56:17.363  2553  2606 I BluetoothAdapterState: Entering OffState
,08-19 17:56:17.364   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-19 17:56:17.379  3571  3571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:56:17.381  2553  2553 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-19 17:56:17.381  2553  2553 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-19 17:56:17.381  2553  2553 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-19 17:56:17.382  2553  2607 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-19 17:56:17.385  2553  2607 D bt_stack_manager: event_clean_up_stack finished.
,08-19 17:56:17.391  2553  2553 I art     : System.exit called, status: 0
,08-19 17:56:17.391  2553  2553 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-19 17:56:17.468   872  1377 I ActivityManager: Process com.android.bluetooth (pid 2553) has died
,08-19 17:56:17.496  3661  3661 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at java.io.File.exists(File.java:361)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.496  3661  3661 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.496  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.497  3661  3661 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.497  3661  3661 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.e.b(PG:170)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.497  3661  3661 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.k.d(PG:583)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.e.b(PG:170)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.497  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.500  3661  3661 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.io.File.exists(File.java:361)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.500  3661  3661 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.io.File.exists(File.java:361)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.500  3661  3661 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:17.500  3661  3661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-19 17:56:17.505  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:56:17.548   872  2011 I ActivityManager: Start proc 3693:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-19 17:56:17.551  3649  3649 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:56:17.555   872  1377 I ActivityManager: Killing 3244:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-19 17:56:17.759  3693  3693 D AdapterServiceConfig: Adding HeadsetService
,08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding A2dpService
08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding HidService
08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding HealthService
08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding PanService
08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding GattService
08-19 17:56:17.760  3693  3693 D AdapterServiceConfig: Adding BluetoothMapService
,08-19 17:56:17.768  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:17.773  3661  3678 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-19 17:56:17.801   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@462f75b:true
,08-19 17:56:19.918   872   882 D WifiService: setWifiEnabled: true pid=3571, uid=10000
,08-19 17:56:19.918   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:56:19.933   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-19 17:56:19.939  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:19.940  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:19.940  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:56:19.940  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:19.944  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:19.945  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:19.945  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:19.945  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:19.977   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-19 17:56:19.978   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-19 17:56:19.979   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-19 17:56:19.980   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-19 17:56:19.980   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-19 17:56:19.980   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-19 17:56:19.980   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-19 17:56:19.981  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-REENABLED id=1 ssid="NG700"
,08-19 17:56:20.045   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-19 17:56:20.046   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-19 17:56:20.049   370   870 D CommandListener: Setting iface cfg
,08-19 17:56:20.056   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '104 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 104 Failed to set address (No such device)'
,08-19 17:56:20.056   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-19 17:56:20.060   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-19 17:56:20.060   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-19 17:56:20.065   872  1303 E native  : do suspend true
,08-19 17:56:20.098   872  1303 D WifiStateMachine: ConnectModeState SSID state=re-enabled nid=1 [id=1 ssid="NG700"]
,08-19 17:56:20.098   872  1303 E WifiConfigStore: Ignoring SSID re-enabled from supplicant:  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
08-19 17:56:20.099   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-19 17:56:20.102  1449  1449 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-19 17:56:20.103  1449  1449 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-19 17:56:21.105  1449  1449 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-19 17:56:21.105  1449  1449 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-19 17:56:21.386  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-19 17:56:21.470   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-19 17:56:21.471   872  1303 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,08-19 17:56:21.487   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-19 17:56:21.488   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-19 17:56:21.517   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-19 17:56:21.572   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-19 17:56:22.034  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
08-19 17:56:22.035  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,08-19 17:56:22.041   872  1303 D WifiStateMachine: ConnectModeState SSID state=temp-disabled nid=1 [id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED]
08-19 17:56:22.041   872  1303 E WifiConfigStore: SSID temp disabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
08-19 17:56:22.042   872  1303 E WifiConfigStore:  message=id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,08-19 17:56:22.895   872  2007 I ActivityManager: Killing 2632:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-19 17:56:22.925   872  1918 D WifiService: setWifiEnabled: false pid=3571, uid=10000
,08-19 17:56:22.925   872  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:56:22.993   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-19 17:56:23.009  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:23.009  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:23.009  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:56:23.010  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:23.011  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:23.011  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:23.011  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:23.011  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:23.014  1971  2278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:56:24.172  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-19 17:56:24.187  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-19 17:56:24.192  1489  1489 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-19 17:56:24.256  1489  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-19 17:56:24.257  1489  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-19 17:56:24.257  1489  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
08-19 17:56:24.258  1489  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-19 17:56:24.312  2751  2751 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-19 17:56:24.313  2751  2751 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-19 17:56:24.316  2751  2751 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-19 17:56:25.973  3693  3693 D BluetoothAdapterState: make() - Creating AdapterState
08-19 17:56:25.973   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed67e79:true
,08-19 17:56:25.978  3693  3693 I bt_bluedroid: init
,08-19 17:56:25.979  3693  3716 I BluetoothAdapterState: Entering OffState
,08-19 17:56:25.986  3693  3717 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-19 17:56:25.987  3693  3717 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-19 17:56:25.988  3693  3717 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-19 17:56:25.991  3693  3717 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-19 17:56:25.995  3693  3693 I bt_bluedroid: get_profile_interface socket
,08-19 17:56:25.997  3693  3693 I bt_bluedroid: get_profile_interface sdp
08-19 17:56:25.999  3693  3720 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-19 17:56:26.001  3693  3703 I bt_bluedroid: config_hci_snoop_log
,08-19 17:56:26.002  3693  3720 D BluetoothAdapterProperties: Name is: Nexus 6,
08-19 17:56:26.002   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-19 17:56:26.008  3693  3716 D BluetoothAdapterState: Current state: OFF, message: 0
,08-19 17:56:26.008  3693  3716 D BluetoothAdapterProperties: Setting state to 14
,08-19 17:56:26.009  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-19 17:56:26.011  3693  3716 D BluetoothBondStateMachine: make
,08-19 17:56:26.013  3693  3721 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-19 17:56:26.017  3693  3716 I BluetoothAdapterState: Entering PendingCommandState
,08-19 17:56:26.018  3693  3693 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-19 17:56:26.021  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:26.022  3693  3693 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:56:26.022  3693  3693 D BtGatt.GattService: Received start request. Starting profile...
08-19 17:56:26.023  3693  3693 D BtGatt.GattService: start()
08-19 17:56:26.023  3693  3693 I bt_bluedroid: get_profile_interface gatt
,08-19 17:56:26.024  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:26.024  3693  3693 D BtGatt.AdvertiseManager: advertise manager created
,08-19 17:56:26.030  3693  3693 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:26.031  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:26.031  3693  3693 V BluetoothAdapterState: isBleTurningOn()=true
08-19 17:56:26.031  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:26.031  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-19 17:56:26.031  3693  3716 I bt_bluedroid: enable
,08-19 17:56:26.032  3693  3717 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-19 17:56:26.032  3693  3717 I bt_hci  : start_up
,08-19 17:56:26.041  3693  3717 I bt_vendor: alloc value 0xb3969189
,08-19 17:56:26.041  3693  3717 I bt_vendor: init
08-19 17:56:26.041  3693  3717 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-19 17:56:26.041  3693  3717 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-19 17:56:26.148  3693  3717 D bt_hci  : start_up starting async portion
,08-19 17:56:26.149  3693  3724 I bt_hci  : event_finish_startup
,08-19 17:56:26.149  3693  3724 I bt_hci_h4: hal_open
08-19 17:56:26.149  3693  3724 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-19 17:56:26.157  3693  3724 I bt_userial_vendor: device fd = 51 open
,08-19 17:56:26.191  3693  3724 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-19 17:56:26.223  3693  3724 D bt_hwcfg: Chipset BCM4354A2
,08-19 17:56:26.223  3693  3724 D bt_hwcfg: Target name = [BCM4354A2]
08-19 17:56:26.223  3693  3724 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-19 17:56:26.876  3693  3724 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-19 17:56:26.878  3693  3724 D bt_hwcfg: Settlement delay -- 100 ms
08-19 17:56:26.878  3693  3724 I bt_hwcfg: Setting fw settlement delay to 100 
,08-19 17:56:26.995  3693  3724 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-19 17:56:26.996  3693  3724 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-19 17:56:27.026  3693  3724 I bt_hwcfg: vendor lib fwcfg completed
,08-19 17:56:27.026  3693  3724 I bt_vendor: firmware callback
,08-19 17:56:27.026  3693  3724 I bt_hci  : firmware_config_callback
,08-19 17:56:27.037  3693  3726 I bt_btu  : btu_task pending for preload complete event
,08-19 17:56:27.038  3693  3726 I bt_btu_task: Bluetooth chip preload is complete
,08-19 17:56:27.038  3693  3726 I bt_btu  : btu_task received preload complete event
,08-19 17:56:27.048  3693  3726 I         : BTE_InitTraceLevels -- TRC_HCI
08-19 17:56:27.048  3693  3726 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-19 17:56:27.049  3693  3726 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-19 17:56:27.049  3693  3726 I         : BTE_InitTraceLevels -- TRC_AVDT
08-19 17:56:27.049  3693  3726 I         : BTE_InitTraceLevels -- TRC_AVRC
08-19 17:56:27.050  3693  3726 I         : BTE_InitTraceLevels -- TRC_A2D
,08-19 17:56:27.050  3693  3726 I         : BTE_InitTraceLevels -- TRC_BNEP
08-19 17:56:27.051  3693  3726 I         : BTE_InitTraceLevels -- TRC_BTM
,08-19 17:56:27.051  3693  3726 I         : BTE_InitTraceLevels -- TRC_GAP
08-19 17:56:27.051  3693  3726 I         : BTE_InitTraceLevels -- TRC_PAN
,08-19 17:56:27.051  3693  3726 I         : BTE_InitTraceLevels -- TRC_SDP
08-19 17:56:27.052  3693  3726 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:56:27.052  3693  3726 I         : BTE_InitTraceLevels -- TRC_SMP
,08-19 17:56:27.052  3693  3726 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-19 17:56:27.052  3693  3726 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-19 17:56:27.190  3693  3726 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-19 17:56:27.190  3693  3726 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-19 17:56:27.202  3693  3720 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-19 17:56:27.204  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-19 17:56:27.205  3693  3720 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-19 17:56:27.208  3693  3720 D BluetoothAdapterProperties: Name is: Nexus 6
08-19 17:56:27.212  3693  3720 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:56:27.212  3693  3720 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:56:27.212  3693  3720 D bt_hci  : do_postload posting postload work item
,08-19 17:56:27.213  3693  3724 I bt_hci  : event_postload
08-19 17:56:27.213  3693  3724 I bt_vendor: sco_config_cb
,08-19 17:56:27.213  3693  3724 I bt_hci  : sco_config_callback postload finished.
08-19 17:56:27.215  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:27.215  3693  3720 D bt_bte_conf: Device ID record 1 : primary
08-19 17:56:27.216  3693  3720 D bt_bte_conf:   vendorId            = 000f
08-19 17:56:27.216  3693  3720 D bt_bte_conf:   vendorIdSource      = 0001
,08-19 17:56:27.216  3693  3720 D bt_bte_conf:   product             = 1200
08-19 17:56:27.217  3693  3720 D bt_bte_conf:   version             = 1436
08-19 17:56:27.217  3693  3720 D bt_bte_conf:   clientExecutableURL = 
,08-19 17:56:27.217  3693  3720 D bt_bte_conf:   serviceDescription  = 
,08-19 17:56:27.218  3693  3720 D bt_bte_conf:   documentationURL    = 
,08-19 17:56:27.218  3693  3724 I bt_vendor: low_power_mode_cb
08-19 17:56:27.218  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:27.218  3693  3720 D bt_bte_conf: bte_load_did_conf no section named DID2.,
08-19 17:56:27.218  3693  3717 D bt_stack_manager: event_start_up_stack finished
08-19 17:56:27.219  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-19 17:56:27.220  3693  3716 D BluetoothAdapterProperties: Setting state to 15
08-19 17:56:27.220  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-19 17:56:27.222  3693  3716 I BluetoothAdapterState: Entering BleOnState
,08-19 17:56:27.226  3693  3716 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-19 17:56:27.226  3693  3716 D BluetoothAdapterProperties: Setting state to 11
08-19 17:56:27.226  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11,
,08-19 17:56:27.236  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:27.239  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:27.244  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:27.245  3693  3693 D HeadsetService: Received start request. Starting profile...
,08-19 17:56:27.248  3693  3693 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-19 17:56:27.248  3693  3693 D HeadsetStateMachine: make
,08-19 17:56:27.256  3693  3716 I BluetoothAdapterState: Entering PendingCommandState
,08-19 17:56:27.258  3693  3693 D HeadsetStateMachine: max_hf_connections = 1
,08-19 17:56:27.258  3693  3693 I bt_bluedroid: get_profile_interface handsfree
,08-19 17:56:27.259  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-19 17:56:27.260  3693  3720 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-19 17:56:27.264  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:27.265  3693  3693 D A2dpService: Received start request. Starting profile...
08-19 17:56:27.265  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:56:27.265  3693  3693 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-19 17:56:27.266  3693  3693 I bt_bluedroid: get_profile_interface avrcp
,08-19 17:56:27.272  3693  3693 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-19 17:56:27.272  3693  3693 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:56:27.272  3693  3693 D A2dpStateMachine: make
,08-19 17:56:27.273  3693  3693 I bt_bluedroid: get_profile_interface a2dp
,08-19 17:56:27.274  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-19 17:56:27.275  3693  3735 D A2dpStateMachine: Enter Disconnected: -2
,08-19 17:56:27.275  3693  3693 I BluetoothHidServiceJni: classInitNative: succeeds
,08-19 17:56:27.276  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:27.278  3693  3693 D HidService: Received start request. Starting profile...
,08-19 17:56:27.278  3649  3649 D BluetoothInputDevice: Proxy object connected
08-19 17:56:27.278  3693  3693 I bt_bluedroid: get_profile_interface hidhost
08-19 17:56:27.278  3693  3693 D HidService: setHidService(): set to: null
08-19 17:56:27.278  3693  3720 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
08-19 17:56:27.278  3649  3649 D HidProfile: Bluetooth service connected
08-19 17:56:27.279  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-19 17:56:27.279  3693  3693 I BluetoothHealthServiceJni: classInitNative: succeeds
08-19 17:56:27.279  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:27.280  3693  3693 D HealthService: Received start request. Starting profile...
,08-19 17:56:27.282  3693  3693 I bt_bluedroid: get_profile_interface health
,08-19 17:56:27.282  3693  3693 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-19 17:56:27.283  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:27.284  3693  3693 D PanService: Received start request. Starting profile...
08-19 17:56:27.284  3649  3649 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:56:27.284  3693  3693 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:56:27.285  3693  3693 I bt_bluedroid: get_profile_interface pan
08-19 17:56:27.285  3649  3649 D PanProfile: Bluetooth service connected
08-19 17:56:27.286  3693  3720 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-19 17:56:27.287  3693  3693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:27.288  3649  3649 D BluetoothMap: Proxy object connected
08-19 17:56:27.289  3649  3649 D MapProfile: Bluetooth service connected
08-19 17:56:27.289  3649  3649 D BluetoothMap: getConnectedDevices()
08-19 17:56:27.289  3693  3693 D BluetoothMapService: Received start request. Starting profile...
,08-19 17:56:27.290  3693  3693 D BluetoothMapService: start()
08-19 17:56:27.290  3649  3649 D BluetoothMap: Bluetooth is Not enabled
,08-19 17:56:27.292  3693  3693 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-19 17:56:27.292  3693  3693 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-19 17:56:27.292  3693  3693 D BluetoothMapAppObserver: createReceiver()
,08-19 17:56:27.293  3693  3693 D BluetoothMapAppObserver: initObservers()
08-19 17:56:27.293  3693  3693 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-19 17:56:27.299  3693  3693 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:27.299  3693  3693 V BluetoothAdapterState: isTurningOn()=true
,08-19 17:56:27.299  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:27.300  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:27.302  3693  3733 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:27.303  3693  3693 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:27.304  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:27.305  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-19 17:56:27.305  3693  3716 D BluetoothAdapterProperties: ScanMode =  20
08-19 17:56:27.305  3693  3716 D BluetoothAdapterProperties: State =  11
08-19 17:56:27.306  3693  3716 D BluetoothAdapterProperties: Setting state to 12
08-19 17:56:27.307  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-19 17:56:27.307  3693  3716 I BluetoothAdapterState: Entering OnState
08-19 17:56:27.307  3649  3659 D BluetoothMap: onBluetoothStateChange: up=true
08-19 17:56:27.308  3693  3720 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:56:27.308  3649  3660 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-19 17:56:27.308  3693  3720 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:56:27.309   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:56:27.310  1357  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:27.311  1917  1929 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:27.312   872   872 D BluetoothA2dp: Proxy object connected
08-19 17:56:27.312  1357  2014 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:27.313  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:27.314  1357  1357 D BluetoothA2dp: Proxy object connected
08-19 17:56:27.314  1357  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:56:27.316  1357  1370 D BluetoothPan: onBluetoothStateChange on: true
08-19 17:56:27.316  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:27.316  1357  1357 D BluetoothInputDevice: Proxy object connected
08-19 17:56:27.316  1357  1357 D HidProfile: Bluetooth service connected
,08-19 17:56:27.318  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:56:27.318  1357  1357 D PanProfile: Bluetooth service connected
08-19 17:56:27.320  1357  2014 D BluetoothPbap: onBluetoothStateChange: up=true
,08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:27.321  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:27.322  3693  3693 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-19 17:56:27.322   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:27.322  3649  3659 D BluetoothPbap: onBluetoothStateChange: up=true
08-19 17:56:27.323  3693  3693 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-19 17:56:27.324  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:27.324   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:56:27.324   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:27.324  1357  1378 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:56:27.327  3649  3660 D BluetoothPan: onBluetoothStateChange on: true
,08-19 17:56:27.327  1357  1357 D BluetoothMap: Proxy object connected
08-19 17:56:27.327  1357  1357 D MapProfile: Bluetooth service connected
08-19 17:56:27.327  1357  1357 D BluetoothMap: getConnectedDevices()
,08-19 17:56:27.328  3693  3693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:56:27.329   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-19 17:56:27.331  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:27.333  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:27.334  3693  3693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:56:27.335  3649  3649 D LocalBluetoothProfileManager: Adding local A2DP profile
08-19 17:56:27.335  3693  3693 D ObexServerSockets: Succeed to create listening sockets 
08-19 17:56:27.335  3693  3693 D ObexServerSockets0: startAccept()
08-19 17:56:27.335  3693  3693 D ObexServerSockets0: prepareForNewConnect()
08-19 17:56:27.337  3693  3693 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-19 17:56:27.338  3693  3693 D BluetoothSdpJni: SDP Create record success - handle: 0
08-19 17:56:27.338  3693  3693 D BluetoothMapService: onReceive
,08-19 17:56:27.338  3693  3742 D ObexServerSockets0: Accepting socket connection...
08-19 17:56:27.338  3693  3693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:56:27.338  3693  3743 D ObexServerSockets0: Accepting socket connection...
08-19 17:56:27.338  3693  3693 D BluetoothMapService: STATE_ON
,08-19 17:56:27.343  3649  3649 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-19 17:56:27.350  3649  3649 D BluetoothA2dp: Proxy object connected
,08-19 17:56:27.353  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:56:27.357  3649  3649 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:56:27.359  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:27.368  3649  3649 D BluetoothPbap: Proxy object connected
,08-19 17:56:27.368  1357  1357 D BluetoothPbap: Proxy object connected
08-19 17:56:27.369  3649  3649 D PbapServerProfile: Bluetooth service connected
08-19 17:56:27.369  1357  1357 D PbapServerProfile: Bluetooth service connected
08-19 17:56:27.369  3693  3693 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-19 17:56:27.369  3693  3693 D ObexServerSockets0: prepareForNewConnect()
,08-19 17:56:27.377  3693  3747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,08-19 17:56:27.406  3693  3751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:56:27.407  3693  3751 I BtOppRfcommListener: Accept thread started.
,08-19 17:56:27.412   872   872 D BluetoothHeadset: Proxy object connected
08-19 17:56:27.412  1917  2066 D BluetoothHeadset: Proxy object connected
,08-19 17:56:27.412   872   872 D BluetoothHeadset: Proxy object connected
08-19 17:56:27.413  1357  2014 D BluetoothHeadset: Proxy object connected
08-19 17:56:27.414   872   872 D BluetoothHeadset: Proxy object connected
08-19 17:56:27.414  1357  1357 D HeadsetProfile: Bluetooth service connected
08-19 17:56:27.414  1917  1928 D BluetoothHeadset: Proxy object connected
,08-19 17:56:27.423   872   889 D BluetoothHeadset: Proxy object connected
,08-19 17:56:27.425   872   889 D BluetoothHeadset: Proxy object connected
,08-19 17:56:27.425   872   889 D BluetoothHeadset: Proxy object connected
,08-19 17:56:27.448  3649  3659 D BluetoothHeadset: Proxy object connected
08-19 17:56:27.449  3649  3649 D HeadsetProfile: Bluetooth service connected
,08-19 17:56:28.941  3693  3716 D BluetoothAdapterState: Current state: ON, message: 23
,08-19 17:56:28.942  3693  3716 D BluetoothAdapterProperties: Setting state to 13
08-19 17:56:28.942  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:56:28.944  3693  3716 D BluetoothAdapterProperties: onBluetoothDisable()
,08-19 17:56:28.949  3693  3716 I BluetoothAdapterState: Entering PendingCommandState
,08-19 17:56:28.952  3693  3720 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:56:28.953  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-19 17:56:28.959  3693  3693 D BluetoothMapService: onReceive
,08-19 17:56:28.960  3693  3693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:56:28.961  3693  3693 D BluetoothMapService: STATE_TURNING_OFF
,08-19 17:56:28.962  3693  3693 D BluetoothMapService: MAP Service closeService in
08-19 17:56:28.962  3693  3693 D BluetoothMapMasInstance0: MAP Service shutdown
08-19 17:56:28.963  3693  3693 D ObexServerSockets0: shutdown(block = true)
08-19 17:56:28.964  3693  3742 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-19 17:56:28.965  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:28.965  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:28.968  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:28.969  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:28.971  3693  3693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-19 17:56:28.972  3693  3743 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-19 17:56:28.973  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-19 17:56:28.973  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:28.974  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:28.975  3571  3571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:56:28.975  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:28.976  3693  3693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-19 17:56:28.975  3693  3729 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-19 17:56:28.976  3693  3693 D HeadsetService: Received stop request...Stopping profile...
08-19 17:56:28.977  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:28.979   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:28.979   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:28.980  3649  3660 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:28.980  1357  1370 D BluetoothHeadset:, Proxy object disconnected
08-19 17:56:28.980   872   872 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:28.981  1917  2041 D BluetoothHeadset: Proxy object disconnected
08-19 17:56:28.981  1357  1357 D HeadsetProfile: Bluetooth service disconnected
08-19 17:56:28.981  3693  3693 D A2dpService: Received stop request...Stopping profile...
08-19 17:56:28.982  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:28.983  3693  3735 D A2dpStateMachine: Exit Disconnected: -1
08-19 17:56:28.985  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-19 17:56:28.985   872   872 D BluetoothA2dp: Proxy object disconnected
,08-19 17:56:28.986  3693  3693 D HidService: Received stop request...Stopping profile...
08-19 17:56:28.986  3693  3693 D HidService: Stopping Bluetooth HidService
08-19 17:56:28.986  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-19 17:56:28.987  1357  1357 D HidProfile: Bluetooth service disconnected
,08-19 17:56:28.987  3693  3693 I BtOppRfcommListener: stopping Accept Thread
08-19 17:56:28.987  3693  3751 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:56:28.987  3693  3751 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:56:28.988  3649  3649 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:56:28.989  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:28.989  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:28.989  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:28.989  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:28.989  3649  3649 D HeadsetProfile: Bluetooth service disconnected
,08-19 17:56:28.990  3693  3693 D HealthService: Received stop request...Stopping profile...
08-19 17:56:28.990  3649  3649 D BluetoothA2dp: Proxy object disconnected
08-19 17:56:28.990  3649  3649 D BluetoothInputDevice: Proxy object disconnected
08-19 17:56:28.991  3649  3649 D HidProfile: Bluetooth service disconnected
,08-19 17:56:28.994  3693  3693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-19 17:56:28.994  3693  3693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:56:28.994  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:28.994  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:28.994  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-19 17:56:28.995  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-19 17:56:28.995  3693  3720 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-19 17:56:28.997  3693  3693 D PanService: Received stop request...Stopping profile...
,08-19 17:56:28.998  3649  3649 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:56:28.998  3649  3649 D PanProfile: Bluetooth service disconnected
08-19 17:56:28.998  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:56:28.999  1357  1357 D PanProfile: Bluetooth service disconnected
08-19 17:56:28.999  3693  3693 D BluetoothMapService: Received stop request...Stopping profile...,
,08-19 17:56:28.999  3693  3693 D BluetoothMapService: stop()
08-19 17:56:29.000  3693  3693 D BluetoothMapAppObserver: deinitObservers()
08-19 17:56:29.000  3693  3693 D BluetoothMapAppObserver: removeReceiver()
08-19 17:56:29.001  1357  1357 D BluetoothMap: Proxy object disconnected
,08-19 17:56:29.001  1357  1357 D MapProfile: Bluetooth service disconnected
08-19 17:56:29.001  3649  3649 D BluetoothMap: Proxy object disconnected
08-19 17:56:29.002  3649  3649 D MapProfile: Bluetooth service disconnected
,08-19 17:56:29.003  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:29.003  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:29.003  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:29.004  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:29.004  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:56:29.005  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:29.005  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:29.005  3693  3726 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:56:29.005  3693  3726 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-19 17:56:29.005  3693  3726 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:56:29.005  3693  3726 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:56:29.005  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-19 17:56:29.006  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:29.006  3693  3693 V BluetoothAdapterState: isTurningOn()=false
,08-19 17:56:29.006  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:29.006  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:29.006  3693  3693 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:56:29.006  3693  3720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-19 17:56:29.006  3693  3693 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-19 17:56:29.009  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:29.010  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:29.010  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:29.010  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:29.010  3693  3693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-19 17:56:29.010  3693  3720 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-19 17:56:29.010  3693  3693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:56:29.011  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:29.011  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:29.011  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:29.011  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:29.011  3693  3693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:56:29.011  3693  3693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-19 17:56:29.012  3693  3693 D BluetoothMapService: MAP Service closeService in
08-19 17:56:29.012  3693  3693 V BluetoothAdapterState: isTurningOff()=true
08-19 17:56:29.012  3693  3693 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:29.012  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:29.013  3693  3693 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:29.013  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-19 17:56:29.013  3693  3716 D BluetoothAdapterProperties: Setting state to 15
08-19 17:56:29.013  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-19 17:56:29.014  3693  3716 I BluetoothAdapterState: Entering BleOnState
08-19 17:56:29.014  3649  3659 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:56:29.014  3693  3693 D BluetoothMapService: cleanup()
,08-19 17:56:29.014  3693  3693 D BluetoothMapService: MAP Service closeService in
,08-19 17:56:29.015  3649  3660 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-19 17:56:29.015  3649  3659 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:56:29.016  1357  1357 D BluetoothPbap: Proxy object disconnected
08-19 17:56:29.016  1357  1357 D PbapServerProfile: Bluetooth service disconnected
08-19 17:56:29.016   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:56:29.017  1357  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-19 17:56:29.017  1917  1929 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:29.017  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-19 17:56:29.019  1357  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:56:29.019  3649  3649 D BluetoothPbap: Proxy object disconnected
,08-19 17:56:29.019  3649  3649 D PbapServerProfile: Bluetooth service disconnected
08-19 17:56:29.021  1357  2014 D BluetoothPan: onBluetoothStateChange on: false
08-19 17:56:29.021  3649  3659 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:29.022  1357  1370 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:56:29.022   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:29.022  3649  3660 D BluetoothPbap: onBluetoothStateChange: up=false
08-19 17:56:29.023   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-19 17:56:29.023   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-19 17:56:29.023  1357  1378 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:56:29.024  3649  3755 D BluetoothPan: onBluetoothStateChange on: false
08-19 17:56:29.025  3693  3716 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-19 17:56:29.025  3693  3716 D BluetoothAdapterProperties: Setting state to 16
08-19 17:56:29.025  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-19 17:56:29.025  3693  3716 D BluetoothAdapterProperties: onBleDisable
08-19 17:56:29.026  3693  3716 I BluetoothAdapterState: Entering PendingCommandState
08-19 17:56:29.026  3693  3717 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-19 17:56:29.027  3693  3726 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-19 17:56:29.027  3693  3726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-19 17:56:29.029  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:29.030  3693  3720 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:56:29.030  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:29.031  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-19 17:56:29.031  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:29.032  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:29.036  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:29.043  3649  3649 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:56:29.230  3693  3720 I bt_hci  : shut_down
,08-19 17:56:29.243  3693  3724 D bt_hwcfg: hw_epilog_process
,08-19 17:56:29.243  3693  3724 I bt_vendor: low_power_mode_cb
,08-19 17:56:29.269  3693  3724 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-19 17:56:29.269  3693  3724 I bt_vendor: epilog_cb
,08-19 17:56:29.270  3693  3724 I bt_hci  : epilog_finished_callback
,08-19 17:56:29.300  3693  3720 I bt_hci_h4: hal_close
,08-19 17:56:29.303  3693  3720 I bt_userial_vendor: device fd = 51 close
,08-19 17:56:29.413  3693  3717 D bt_stack_manager: event_shut_down_stack finished.
,08-19 17:56:29.414  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-19 17:56:29.418  3693  3693 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:56:29.419  3693  3716 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-19 17:56:29.419  3693  3693 D BtGatt.GattService: Received stop request...Stopping profile...
,08-19 17:56:29.420  3693  3693 D BtGatt.GattService: stop()
08-19 17:56:29.420  3693  3693 D BtGatt.AdvertiseManager: advertise clients cleared
,08-19 17:56:29.423  3693  3693 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:29.423  3693  3693 V BluetoothAdapterState: isTurningOn()=false
,08-19 17:56:29.423  3693  3693 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:29.424  3693  3693 V BluetoothAdapterState: isBleTurningOff()=true
08-19 17:56:29.424  3693  3716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-19 17:56:29.425  3693  3716 D BluetoothAdapterProperties: Setting state to 10
08-19 17:56:29.425  3693  3716 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-19 17:56:29.426  3693  3716 I BluetoothAdapterState: Entering OffState
,08-19 17:56:29.426   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-19 17:56:29.437  3693  3693 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-19 17:56:29.438  3693  3693 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-19 17:56:29.438  3693  3717 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-19 17:56:29.439  3693  3717 D bt_stack_manager: event_clean_up_stack finished.
08-19 17:56:29.440  3693  3693 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-19 17:56:29.441  3693  3693 I art     : System.exit called, status: 0
,08-19 17:56:29.442  3693  3693 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-19 17:56:29.487   872  1918 I ActivityManager: Process com.android.bluetooth (pid 3693) has died
,08-19 17:56:31.939  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:31.939  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:34.947  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:34.948  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7f3d3b added. We now have 6 listener(s)
08-19 17:56:34.948  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:34.952  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:34.953  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a773c58 added. We now have 7 listener(s)
08-19 17:56:34.953  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:34.955  3571  3617 I System.out: IsBluetoothEnabled
,08-19 17:56:34.968  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:35.016   872   889 I ActivityManager: Start proc 3760:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-19 17:56:35.120  3760  3760 D AdapterServiceConfig: Adding HeadsetService
,08-19 17:56:35.121  3760  3760 D AdapterServiceConfig: Adding A2dpService
08-19 17:56:35.121  3760  3760 D AdapterServiceConfig: Adding HidService
08-19 17:56:35.121  3760  3760 D AdapterServiceConfig: Adding HealthService
,08-19 17:56:35.121  3760  3760 D AdapterServiceConfig: Adding PanService
08-19 17:56:35.122  3760  3760 D AdapterServiceConfig: Adding GattService
08-19 17:56:35.122  3760  3760 D AdapterServiceConfig: Adding BluetoothMapService
,08-19 17:56:35.139   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0c4532:true
,08-19 17:56:35.139  3760  3760 D BluetoothAdapterState: make() - Creating AdapterState
,08-19 17:56:35.145  3760  3760 I bt_bluedroid: init
,08-19 17:56:35.146  3760  3772 I BluetoothAdapterState: Entering OffState
,08-19 17:56:35.152  3760  3773 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-19 17:56:35.152  3760  3773 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-19 17:56:35.152  3760  3773 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-19 17:56:35.153  3760  3773 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-19 17:56:35.155  3760  3760 I bt_bluedroid: get_profile_interface socket
,08-19 17:56:35.158  3760  3776 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-19 17:56:35.158  3760  3760 I bt_bluedroid: get_profile_interface sdp
08-19 17:56:35.159  3760  3776 D BluetoothAdapterProperties: Name is: Nexus 6
,08-19 17:56:35.168  3760  3771 I bt_bluedroid: config_hci_snoop_log
,08-19 17:56:35.170   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-19 17:56:35.176  3760  3772 D BluetoothAdapterState: Current state: OFF, message: 0
,08-19 17:56:35.177  3760  3772 D BluetoothAdapterProperties: Setting state to 14
08-19 17:56:35.178  3760  3772 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-19 17:56:35.182  3760  3772 D BluetoothBondStateMachine: make
,08-19 17:56:35.188  3760  3777 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-19 17:56:35.198  3760  3772 I BluetoothAdapterState: Entering PendingCommandState
,08-19 17:56:35.199  3760  3760 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-19 17:56:35.207  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:35.209  3760  3760 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-19 17:56:35.211  3760  3760 D BtGatt.GattService: Received start request. Starting profile...
,08-19 17:56:35.211  3760  3760 D BtGatt.GattService: start()
08-19 17:56:35.212  3760  3760 I bt_bluedroid: get_profile_interface gatt
,08-19 17:56:35.214  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:35.214  3760  3760 D BtGatt.AdvertiseManager: advertise manager created
,08-19 17:56:35.228  3760  3760 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:35.229  3760  3760 V BluetoothAdapterState: isTurningOn()=false
08-19 17:56:35.229  3760  3760 V BluetoothAdapterState: isBleTurningOn()=true
08-19 17:56:35.229  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:35.230  3760  3772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-19 17:56:35.232  3760  3772 I bt_bluedroid: enable
,08-19 17:56:35.233  3760  3773 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-19 17:56:35.234  3760  3773 I bt_hci  : start_up
,08-19 17:56:35.257  3760  3773 I bt_vendor: alloc value 0xb39c5189
08-19 17:56:35.257  3760  3773 I bt_vendor: init
08-19 17:56:35.258  3760  3773 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-19 17:56:35.258  3760  3773 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-19 17:56:35.364  3760  3773 D bt_hci  : start_up starting async portion
,08-19 17:56:35.365  3760  3780 I bt_hci  : event_finish_startup
,08-19 17:56:35.366  3760  3780 I bt_hci_h4: hal_open
,08-19 17:56:35.366  3760  3780 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-19 17:56:35.375  3760  3780 I bt_userial_vendor: device fd = 51 open
,08-19 17:56:35.408  3760  3780 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-19 17:56:35.440  3760  3780 D bt_hwcfg: Chipset BCM4354A2
,08-19 17:56:35.440  3760  3780 D bt_hwcfg: Target name = [BCM4354A2]
08-19 17:56:35.441  3760  3780 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-19 17:56:36.095  3760  3780 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-19 17:56:36.097  3760  3780 D bt_hwcfg: Settlement delay -- 100 ms
08-19 17:56:36.097  3760  3780 I bt_hwcfg: Setting fw settlement delay to 100 
,08-19 17:56:36.214  3760  3780 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-19 17:56:36.215  3760  3780 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-19 17:56:36.244  3760  3780 I bt_hwcfg: vendor lib fwcfg completed
08-19 17:56:36.245  3760  3780 I bt_vendor: firmware callback
08-19 17:56:36.245  3760  3780 I bt_hci  : firmware_config_callback
,08-19 17:56:36.255  3760  3782 I bt_btu  : btu_task pending for preload complete event,
08-19 17:56:36.256  3760  3782 I bt_btu_task: Bluetooth chip preload is complete
08-19 17:56:36.256  3760  3782 I bt_btu  : btu_task received preload complete event
,08-19 17:56:36.266  3760  3782 I         : BTE_InitTraceLevels -- TRC_HCI,
08-19 17:56:36.266  3760  3782 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-19 17:56:36.266  3760  3782 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-19 17:56:36.267  3760  3782 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-19 17:56:36.267  3760  3782 I         : BTE_InitTraceLevels -- TRC_AVRC
08-19 17:56:36.267  3760  3782 I         : BTE_InitTraceLevels -- TRC_A2D
,08-19 17:56:36.268  3760  3782 I         : BTE_InitTraceLevels -- TRC_BNEP
08-19 17:56:36.268  3760  3782 I         : BTE_InitTraceLevels -- TRC_BTM
08-19 17:56:36.268  3760  3782 I         : BTE_InitTraceLevels -- TRC_GAP
,08-19 17:56:36.268  3760  3782 I         : BTE_InitTraceLevels -- TRC_PAN
08-19 17:56:36.269  3760  3782 I         : BTE_InitTraceLevels -- TRC_SDP
08-19 17:56:36.269  3760  3782 I         : BTE_InitTraceLevels -- TRC_GATT
08-19 17:56:36.269  3760  3782 I         : BTE_InitTraceLevels -- TRC_SMP
08-19 17:56:36.269  3760  3782 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-19 17:56:36.269  3760  3782 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-19 17:56:36.406  3760  3782 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3942d9d
,08-19 17:56:36.406  3760  3782 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3942d9d 
,08-19 17:56:36.419  3760  3776 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-19 17:56:36.420  3760  3776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-19 17:56:36.421  3760  3776 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-19 17:56:36.425  3760  3776 D BluetoothAdapterProperties: Name is: Nexus 6
,08-19 17:56:36.429  3760  3776 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:56:36.431  3760  3776 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:56:36.431  3760  3776 D bt_hci  : do_postload posting postload work item
,08-19 17:56:36.431  3760  3780 I bt_hci  : event_postload
,08-19 17:56:36.431  3760  3780 I bt_vendor: sco_config_cb
,08-19 17:56:36.431  3760  3780 I bt_hci  : sco_config_callback postload finished.
08-19 17:56:36.433  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:36.435  3760  3776 D bt_bte_conf: Device ID record 1 : primary
,08-19 17:56:36.435  3760  3776 D bt_bte_conf:   vendorId            = 000f
08-19 17:56:36.435  3760  3776 D bt_bte_conf:   vendorIdSource      = 0001
08-19 17:56:36.435  3760  3776 D bt_bte_conf:   product             = 1200
,08-19 17:56:36.436  3760  3776 D bt_bte_conf:   version             = 1436
08-19 17:56:36.436  3760  3776 D bt_bte_conf:   clientExecutableURL = 
08-19 17:56:36.436  3760  3776 D bt_bte_conf:   serviceDescription  = 
08-19 17:56:36.436  3760  3776 D bt_bte_conf:   documentationURL    = 
08-19 17:56:36.436  3760  3776 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-19 17:56:36.437  3760  3780 I bt_vendor: low_power_mode_cb
08-19 17:56:36.437  3760  3773 D bt_stack_manager: event_start_up_stack finished
08-19 17:56:36.439  3760  3772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-19 17:56:36.440  3760  3772 D BluetoothAdapterProperties: Setting state to 15
08-19 17:56:36.441  3760  3772 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-19 17:56:36.442  3760  3772 I BluetoothAdapterState: Entering BleOnState
,08-19 17:56:36.448  3760  3772 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-19 17:56:36.449  3760  3772 D BluetoothAdapterProperties: Setting state to 11
08-19 17:56:36.449  3760  3772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-19 17:56:36.461  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:36.462  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:36.463  3760  3760 D HeadsetService: Received start request. Starting profile...
08-19 17:56:36.466  3760  3760 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-19 17:56:36.466  3760  3760 D HeadsetStateMachine: make
,08-19 17:56:36.477  3760  3760 D HeadsetStateMachine: max_hf_connections = 1
,08-19 17:56:36.477  3760  3760 I bt_bluedroid: get_profile_interface handsfree
,08-19 17:56:36.478  3760  3776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-19 17:56:36.478  3760  3776 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-19 17:56:36.482  3760  3772 I BluetoothAdapterState: Entering PendingCommandState
,08-19 17:56:36.484  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:36.485  3760  3760 D A2dpService: Received start request. Starting profile...
08-19 17:56:36.486  3760  3760 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-19 17:56:36.486  3760  3760 I bt_bluedroid: get_profile_interface avrcp
,08-19 17:56:36.493  3760  3760 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:56:36.493  3760  3760 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-19 17:56:36.493  3760  3760 D A2dpStateMachine: make
,08-19 17:56:36.494  3760  3760 I bt_bluedroid: get_profile_interface a2dp
,08-19 17:56:36.495  3760  3776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-19 17:56:36.498  3760  3790 D A2dpStateMachine: Enter Disconnected: -2
,08-19 17:56:36.499  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:36.501  3760  3760 I BluetoothHidServiceJni: classInitNative: succeeds
,08-19 17:56:36.502  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:36.502  3760  3760 D HidService: Received start request. Starting profile...
08-19 17:56:36.503  3760  3760 I bt_bluedroid: get_profile_interface hidhost
,08-19 17:56:36.503  3760  3760 D HidService: setHidService(): set to: null
08-19 17:56:36.503  3760  3776 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39243e5
08-19 17:56:36.503  3760  3776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-19 17:56:36.504  3760  3760 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-19 17:56:36.505  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:36.506  3760  3760 D HealthService: Received start request. Starting profile...
,08-19 17:56:36.508  3760  3760 I bt_bluedroid: get_profile_interface health
,08-19 17:56:36.509  3760  3760 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-19 17:56:36.509  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:36.510  3760  3760 D PanService: Received start request. Starting profile...
,08-19 17:56:36.510  3760  3760 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-19 17:56:36.510  3760  3760 I bt_bluedroid: get_profile_interface pan
08-19 17:56:36.512  3760  3776 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
08-19 17:56:36.513  3760  3760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
08-19 17:56:36.513  3760  3760 D BluetoothMapService: Received start request. Starting profile...
08-19 17:56:36.513  3760  3760 D BluetoothMapService: start()
08-19 17:56:36.515  3760  3760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-19 17:56:36.516  3760  3760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-19 17:56:36.516  3760  3760 D BluetoothMapAppObserver: createReceiver()
,08-19 17:56:36.517  3760  3760 D BluetoothMapAppObserver: initObservers()
08-19 17:56:36.517  3760  3760 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-19 17:56:36.523  3760  3760 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:36.523  3760  3760 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:36.523  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:36.523  3760  3788 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:56:36.523  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:36.525  3760  3760 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:36.525  3760  3760 V BluetoothAdapterState: isTurningOn()=true
,08-19 17:56:36.525  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
,08-19 17:56:36.525  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:36.528  3760  3760 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:36.529  3760  3760 V BluetoothAdapterState: isTurningOn()=true
,08-19 17:56:36.529  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:36.529  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:36.529  3760  3760 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isTurningOff()=false
,08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isTurningOn()=true
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isTurningOff()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isTurningOn()=true
,08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOn()=false
08-19 17:56:36.530  3760  3760 V BluetoothAdapterState: isBleTurningOff()=false
,08-19 17:56:36.531  3760  3772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-19 17:56:36.531  3760  3772 D BluetoothAdapterProperties: ScanMode =  20
08-19 17:56:36.531  3760  3772 D BluetoothAdapterProperties: State =  11
08-19 17:56:36.531  3760  3772 D BluetoothAdapterProperties: Setting state to 12
08-19 17:56:36.531  3760  3772 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-19 17:56:36.532  3760  3772 I BluetoothAdapterState: Entering OnState
08-19 17:56:36.532  3649  3659 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:56:36.532  3760  3776 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:56:36.533  3760  3776 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:36.535  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:56:36.535  3649  3660 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:56:36.536  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:56:36.540  3649  3755 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:56:36.542   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:56:36.543  1357  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:56:36.543  3760  3760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-19 17:56:36.543  1917  2066 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:36.543  3649  3649 D BluetoothMap: Proxy object connected
,08-19 17:56:36.543  3649  3649 D MapProfile: Bluetooth service connected,
08-19 17:56:36.543  3760  3760 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-19 17:56:36.543  3649  3649 D BluetoothMap: getConnectedDevices()
,08-19 17:56:36.544  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:56:36.544  3760  3760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:56:36.545  1357  2014 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-19 17:56:36.546  1357  1370 D BluetoothPan: onBluetoothStateChange on: true
,08-19 17:56:36.546  1357  1357 D BluetoothInputDevice: Proxy object connected
,08-19 17:56:36.546  1357  1357 D HidProfile: Bluetooth service connected
,08-19 17:56:36.546  3760  3760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:56:36.547  3649  3660 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:36.547  3760  3760 D ObexServerSockets: Succeed to create listening sockets 
08-19 17:56:36.547  3760  3760 D ObexServerSockets0: startAccept()
08-19 17:56:36.547  3760  3760 D ObexServerSockets0: prepareForNewConnect(),
08-19 17:56:36.548  1357  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-19 17:56:36.549  3760  3760 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-19 17:56:36.549  3760  3760 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-19 17:56:36.550  3760  3797 D ObexServerSockets0: Accepting socket connection...
,08-19 17:56:36.550   872   872 D BluetoothA2dp: Proxy object connected
,08-19 17:56:36.550  1357  1357 D BluetoothA2dp: Proxy object connected
08-19 17:56:36.551   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:36.549  3760  3796 D ObexServerSockets0: Accepting socket connection...
08-19 17:56:36.551  3649  3755 D BluetoothPbap: onBluetoothStateChange: up=true
08-19 17:56:36.552  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
,08-19 17:56:36.552  1357  1357 D PanProfile: Bluetooth service connected
08-19 17:56:36.552   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-19 17:56:36.552   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-19 17:56:36.552  3649  3649 D BluetoothInputDevice: Proxy object connected
08-19 17:56:36.552  1357  2014 D BluetoothMap: onBluetoothStateChange: up=true
08-19 17:56:36.552  3649  3649 D HidProfile: Bluetooth service connected
08-19 17:56:36.553  1357  1357 D BluetoothMap: Proxy object connected
08-19 17:56:36.553  1357  1357 D MapProfile: Bluetooth service connected
,08-19 17:56:36.553  1357  1357 D BluetoothMap: getConnectedDevices()
08-19 17:56:36.554  3649  3660 D BluetoothPan: onBluetoothStateChange on: true
08-19 17:56:36.555  3649  3649 D BluetoothA2dp: Proxy object connected
,08-19 17:56:36.557  3760  3760 D BluetoothMapService: onReceive
08-19 17:56:36.557  3760  3760 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:56:36.557  3760  3760 D BluetoothMapService: STATE_ON
,08-19 17:56:36.558   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-19 17:56:36.558  3649  3649 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:56:36.558  3649  3649 D PanProfile: Bluetooth service connected
08-19 17:56:36.558  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:36.561  3649  3649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:56:36.570  1489  1489 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:56:36.576  3760  3800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:56:36.581  3760  3760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-19 17:56:36.581  1357  1357 D BluetoothPbap: Proxy object connected
08-19 17:56:36.581  3760  3760 D ObexServerSockets0: prepareForNewConnect()
,08-19 17:56:36.581  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-19 17:56:36.584  3649  3649 D DockEventReceiver: finishStartingService: stopping service
08-19 17:56:36.585  3649  3649 D BluetoothPbap: Proxy object connected
08-19 17:56:36.585  3649  3649 D PbapServerProfile: Bluetooth service connected
,08-19 17:56:36.598  3760  3806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:56:36.598  3760  3806 I BtOppRfcommListener: Accept thread started.
,08-19 17:56:36.645   872   872 D BluetoothHeadset: Proxy object connected
,08-19 17:56:36.645   872   872 D BluetoothHeadset: Proxy object connected
,08-19 17:56:36.646  3649  3659 D BluetoothHeadset: Proxy object connected
08-19 17:56:36.646  3649  3649 D HeadsetProfile: Bluetooth service connected
08-19 17:56:36.647  1357  2014 D BluetoothHeadset: Proxy object connected
,08-19 17:56:36.648  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-19 17:56:36.649  3649  3660 D BluetoothHeadset: Proxy object connected
08-19 17:56:36.650   872   872 D BluetoothHeadset: Proxy object connected
08-19 17:56:36.651  1917  1928 D BluetoothHeadset: Proxy object connected
08-19 17:56:36.652   872   889 D BluetoothHeadset: Proxy object connected
08-19 17:56:36.653   872   889 D BluetoothHeadset: Proxy object connected
,08-19 17:56:36.653   872   889 D BluetoothHeadset: Proxy object connected
,08-19 17:56:36.655  3649  3649 D HeadsetProfile: Bluetooth service connected
,08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:36.991  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:36.998  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:37.002  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:37.002  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d37b1b1 added. We now have 8 listener(s)
,08-19 17:56:37.002  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:37.008   872   883 D WifiService: setWifiEnabled: false pid=3571, uid=10000
,08-19 17:56:37.008   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:56:37.020  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:37.021   872  2007 D WifiService: setWifiEnabled: true pid=3571, uid=10000
08-19 17:56:37.021   872  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-19 17:56:37.034   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:37.048  3571  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:37.053  3571  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:37.066   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-19 17:56:37.067   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-19 17:56:37.067   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-19 17:56:37.068   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-19 17:56:37.068   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-19 17:56:37.068   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-19 17:56:37.069   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-19 17:56:37.069  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-REENABLED id=1 ssid="NG700"
,08-19 17:56:37.137   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-19 17:56:37.137   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-19 17:56:37.139   370   870 D CommandListener: Setting iface cfg
,08-19 17:56:37.141   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '106 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 106 Failed to set address (No such device)'
,08-19 17:56:37.141   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-19 17:56:37.153   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-19 17:56:37.154   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-19 17:56:37.155   872  1303 E native  : do suspend true
,08-19 17:56:37.187   872  1303 D WifiStateMachine: ConnectModeState SSID state=re-enabled nid=1 [id=1 ssid="NG700"]
,08-19 17:56:37.187   872  1303 E WifiConfigStore: Ignoring SSID re-enabled from supplicant:  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
,08-19 17:56:37.193   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-19 17:56:37.197  1449  1449 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
08-19 17:56:37.197  1449  1449 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:38.043  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:38.050  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:38.063  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-19 17:56:38.065  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-19 17:56:38.071  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d472efe Bundle[{}]
,08-19 17:56:38.073  3571  3617 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-19 17:56:38.074  3571  3617 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-19 17:56:38.077  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-19 17:56:38.080  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-19 17:56:38.081  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-19 17:56:38.082  3571  3617 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-19 17:56:38.087  3571  3617 I System.out: Running OutgoingSocketThread
,08-19 17:56:38.090  3571  3812 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 388)
,08-19 17:56:38.092  3571  3812 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49560
,08-19 17:56:38.093  3571  3812 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-19 17:56:38.199  1449  1449 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-19 17:56:38.199  1449  1449 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-19 17:56:38.458  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-19 17:56:38.545   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-19 17:56:38.557   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-19 17:56:38.558   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-19 17:56:38.576   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-19 17:56:38.629   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-19 17:56:39.044  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,08-19 17:56:39.045  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,08-19 17:56:39.051   872  1303 D WifiStateMachine: ConnectModeState SSID state=temp-disabled nid=1 [id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED]
,08-19 17:56:39.052   872  1303 E WifiConfigStore: SSID temp disabled for  "NG700"WPA_PSK had autoJoinStatus=0 self added false ephemeral false
,08-19 17:56:39.052   872  1303 E WifiConfigStore:  message=id=1 ssid="NG700" auth_failures=1 duration=10 reason=CONN_FAILED
,08-19 17:56:39.090  3571  3617 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 389)
,08-19 17:56:39.091  3571  3617 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 389)
,08-19 17:56:39.102  3571  3617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 394)
,08-19 17:56:39.105  3571  3617 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-19 17:56:39.106  3571  3617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 395)
,08-19 17:56:39.112  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.112  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c0c696 added. We now have 2 listener(s)
,08-19 17:56:39.114  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:39.114  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:56:39.114  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:56:39.115  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.115  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49a7217 added. We now have 9 listener(s)
,08-19 17:56:39.115  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:39.115  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:56:39.119  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:39.127  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:39.132  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:39.132  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:56:39.133  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:56:39.133  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64b7ed added. We now have 3 listener(s)
,08-19 17:56:39.135  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:39.138  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:39.139  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.139  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.140  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.140  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93ab622 added. We now have 10 listener(s)
,08-19 17:56:39.140  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.141  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:39.141  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.141  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:39.142  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:56:39.142  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.142  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.142  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.143  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c0c696 removed from the list
08-19 17:56:39.143  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.143  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49a7217 removed from the list
,08-19 17:56:39.144  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:39.144  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.145  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.145  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.147  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.148  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.148  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:39.148  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49a7217 not in the list
08-19 17:56:39.148  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.149  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.151  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:39.151  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.152  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.152  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93ab622 removed from the list
08-19 17:56:39.152  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.152  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:39.152  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.153  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.153  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64b7ed removed from the list
08-19 17:56:39.155  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.155  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca18b3 added. We now have 2 listener(s)
,08-19 17:56:39.159  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:39.160  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.160  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.160  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.161  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4053e70 added. We now have 9 listener(s)
08-19 17:56:39.161  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:39.162  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:56:39.167  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:39.174  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:39.177  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:39.178  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:39.178  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.178  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@472126e added. We now have 3 listener(s)
,08-19 17:56:39.181  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:39.181  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:39.181  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.182  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-19 17:56:39.182  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.182  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5438d0f added. We now have 10 listener(s)
,08-19 17:56:39.182  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.182  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:39.183  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-19 17:56:39.183  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:39.183  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:39.183  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:56:39.189  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-19 17:56:39.189  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:56:39.200  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:56:39.201  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-19 17:56:39.202  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:56:39.208  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:56:39.209  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:39.209  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:56:39.211  3571  3617 D BluetoothAdapter: STATE_ON
,08-19 17:56:39.217  3760  3771 D BtGatt.GattService: registerClient() - UUID=0882e373-1667-4af0-8c85-aa4ea4a95e3b
,08-19 17:56:39.218  3760  3776 D BtGatt.GattService: onClientRegistered() - UUID=0882e373-1667-4af0-8c85-aa4ea4a95e3b, clientIf=5
,08-19 17:56:39.220  3571  3581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-19 17:56:39.222  3760  3795 D BtGatt.GattService: start scan with filters
,08-19 17:56:39.229  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:56:39.229  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:39.230  3760  3779 D BtGatt.ScanManager: handling starting scan
08-19 17:56:39.230  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:39.231  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:56:39.234  3760  3779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c429b2
,08-19 17:56:39.240  3760  3776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-19 17:56:39.240  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.241  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:39.241  3760  3779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-19 17:56:39.241  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:56:39.241  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:39.248  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:56:39.253  3571  3617 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:56:39.253  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.254  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-19 17:56:39.254  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.254  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-19 17:56:39.254  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-19 17:56:39.254  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:39.254  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-19 17:56:39.254  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:39.255  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:56:39.255  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:39.256  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-19 17:56:39.256  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.257  3760  3779 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:56:39.257  3760  3779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:39.257  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:39.261  3760  3795 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:56:39.263  3760  3770 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-19 17:56:39.264  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:56:39.264  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:39.265  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:39.265  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:39.265  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:56:39.268  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:39.269  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:56:39.269  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:56:39.270  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:56:39.271  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:56:39.273  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:56:39.273  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:56:39.273  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:56:39.279  3760  3776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-19 17:56:39.279  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.279  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:39.279  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.279  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:39.280  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.280  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.281  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.281  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.281  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca18b3 removed from the list
,08-19 17:56:39.281  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.282  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4053e70 removed from the list
08-19 17:56:39.282  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:39.282  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.283  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.284  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.285  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-19 17:56:39.286  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.286  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.286  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.286  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.287  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4053e70 not in the list
,08-19 17:56:39.287  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.287  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.290  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:39.291  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:56:39.291  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:56:39.291  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5438d0f removed from the list
08-19 17:56:39.291  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.291  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.291  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.291  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.291  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@472126e removed from the list
08-19 17:56:39.293  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:56:39.293  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@335eb2b added. We now have 2 listener(s)
,08-19 17:56:39.295  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-19 17:56:39.295  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.296  3760  3779 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:56:39.296  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:39.297  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.297  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:56:39.297  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:39.297  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de6b88 added. We now have 9 listener(s)
08-19 17:56:39.297  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.298  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:56:39.302  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:39.303  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-19 17:56:39.303  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.303  3760  3779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:39.307  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:39.310  3760  3776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-19 17:56:39.310  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.311  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:39.311  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:39.312  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.312  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d60146 added. We now have 3 listener(s)
08-19 17:56:39.313  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:39.314  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:39.315  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.315  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:56:39.315  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.315  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a60f07 added. We now have 10 listener(s)
08-19 17:56:39.315  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.315  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:39.316  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:39.317  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-19 17:56:39.317  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:39.317  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:39.317  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:56:39.321  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-19 17:56:39.321  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:56:39.327  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:56:39.328  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-19 17:56:39.328  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:56:39.332  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:56:39.333  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:39.333  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:56:39.334  3571  3617 D BluetoothAdapter: STATE_ON
,08-19 17:56:39.337  3760  3798 D BtGatt.GattService: registerClient() - UUID=fa4b304d-3966-4612-a7ff-e913121468d4
08-19 17:56:39.338  3760  3776 D BtGatt.GattService: onClientRegistered() - UUID=fa4b304d-3966-4612-a7ff-e913121468d4, clientIf=5
,08-19 17:56:39.338  3571  3581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-19 17:56:39.338  3760  3770 D BtGatt.GattService: start scan with filters
,08-19 17:56:39.342  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:56:39.342  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:39.342  3760  3779 D BtGatt.ScanManager: handling starting scan
08-19 17:56:39.342  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:39.343  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:56:39.347  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:39.347  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:56:39.348  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:56:39.350  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:56:39.352  3760  3776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-19 17:56:39.352  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.352  3760  3779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-19 17:56:39.354  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:56:39.354  3571  3617 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-19 17:56:39.355  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:39.355  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:56:39.355  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:39.356  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.356  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:56:39.356  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:56:39.356  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-19 17:56:39.356  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@335eb2b removed from the list
08-19 17:56:39.356  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.356  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de6b88 removed from the list
08-19 17:56:39.356  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:39.356  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:56:39.358  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.358  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-19 17:56:39.358  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.358  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.359  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.359  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.359  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.359  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de6b88 not in the list
,08-19 17:56:39.359  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:39.359  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:56:39.360  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:39.360  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:56:39.360  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:39.361  3571  3617 D BluetoothAdapter: STATE_ON
08-19 17:56:39.362  3760  3771 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:56:39.363  3760  3795 D BtGatt.GattService: unregisterClient() - clientIf=5
08-19 17:56:39.363  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:56:39.363  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:39.363  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:39.364  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:39.364  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:56:39.365  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:39.365  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:56:39.365  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:56:39.365  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:56:39.367  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.368  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-19 17:56:39.368  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.368  3760  3779 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:56:39.368  3760  3779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:39.368  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.368  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.369  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.369  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:56:39.369  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a60f07 removed from the list
08-19 17:56:39.369  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.369  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:56:39.369  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.369  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:56:39.369  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.369  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.369  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d60146 removed from the list
08-19 17:56:39.370  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.370  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80a94a3 added. We now have 2 listener(s)
08-19 17:56:39.373  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:39.373  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.373  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.373  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.373  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edd23a0 added. We now have 9 listener(s)
08-19 17:56:39.373  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.374  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:56:39.376  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:39.381  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:39.384  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:39.384  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:39.384  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.384  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3df31e added. We now have 3 listener(s)
08-19 17:56:39.386  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:56:39.387  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:39.387  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.387  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.387  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.387  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a7d7ff added. We now have 10 listener(s)
08-19 17:56:39.388  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:56:39.388  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:56:39.388  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:56:39.388  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:56:39.388  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:56:39.388  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:56:39.392  3571  3617 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-19 17:56:39.392  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:56:39.395  3760  3776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-19 17:56:39.395  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.396  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:56:39.397  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-19 17:56:39.397  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:56:39.401  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-19 17:56:39.401  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.402  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:56:39.402  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:56:39.402  3571  3617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:56:39.403  3571  3617 D BluetoothAdapter: STATE_ON
,08-19 17:56:39.405  3760  3770 D BtGatt.GattService: registerClient() - UUID=e35a03e5-1b7f-46a2-8c59-6bde164a1e7d
,08-19 17:56:39.406  3760  3776 D BtGatt.GattService: onClientRegistered() - UUID=e35a03e5-1b7f-46a2-8c59-6bde164a1e7d, clientIf=5
08-19 17:56:39.406  3571  3581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-19 17:56:39.406  3760  3771 D BtGatt.GattService: start scan with filters
,08-19 17:56:39.408  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-19 17:56:39.408  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.408  3760  3779 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:56:39.410  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:56:39.410  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:56:39.410  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:56:39.410  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:56:39.413  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:39.413  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:56:39.413  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:56:39.415  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-19 17:56:39.416  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-19 17:56:39.416  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.416  3760  3779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-19 17:56:39.420  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:56:39.421  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.421  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:56:39.421  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.421  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.422  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:56:39.422  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.422  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80a94a3 removed from the list
08-19 17:56:39.422  3760  3776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-19 17:56:39.422  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.422  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.423  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edd23a0 removed from the list
08-19 17:56:39.423  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:39.423  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.423  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.423  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-19 17:56:39.423  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.423  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.424  3760  3779 D BtGatt.ScanManager: handling starting scan
08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.425  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edd23a0 not in the list
,08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:56:39.425  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:56:39.425  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:56:39.425  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-19 17:56:39.426  3571  3617 D BluetoothAdapter: STATE_ON
,08-19 17:56:39.427  3760  3771 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:56:39.427  3760  3795 D BtGatt.GattService: unregisterClient() - clientIf=5
08-19 17:56:39.428  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:56:39.428  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:56:39.428  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:56:39.428  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:56:39.428  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:56:39.429  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:56:39.430  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:56:39.430  3571  3617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:56:39.430  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:56:39.430  3760  3776 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-19 17:56:39.430  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.430  3760  3779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-19 17:56:39.431  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.432  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:39.433  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.433  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.433  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:56:39.433  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a7d7ff removed from the list
08-19 17:56:39.433  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.433  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.433  3571  3571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:56:39.433  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.433  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.433  3571  3571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:56:39.433  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3df31e removed from the list
08-19 17:56:39.434  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:56:39.434  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@babf51b added. We now have 2 listener(s)
,08-19 17:56:39.436  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-19 17:56:39.436  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:56:39.436  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.436  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:56:39.436  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac7c6b8 added. We now have 9 listener(s)
08-19 17:56:39.436  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.437  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:56:39.437  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-19 17:56:39.437  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.437  3760  3779 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:56:39.438  3760  3779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-19 17:56:39.442  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:56:39.445  3571  3617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:56:39.448  3571  3617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:56:39.448  3571  3617 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:56:39.449  3760  3776 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-19 17:56:39.449  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-19 17:56:39.449  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:56:39.449  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc747f6 added. We now have 3 listener(s)
08-19 17:56:39.450  3571  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:56:39.453  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-19 17:56:39.453  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:56:39.453  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:56:39.454  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:56:39.454  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ac7f7 added. We now have 10 listener(s)
08-19 17:56:39.454  3571  3617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:56:39.454  3571  3617 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:56:39.454  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.454  3571  3617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:56:39.455  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.455  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.455  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:56:39.455  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.455  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-19 17:56:39.456  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.456  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@babf51b removed from the list
08-19 17:56:39.456  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.456  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac7c6b8 removed from the list
08-19 17:56:39.456  3571  3617 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:56:39.456  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.457  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.457  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.458  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.458  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:56:39.458  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.458  3571  3617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac7c6b8 not in the list
,08-19 17:56:39.458  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.458  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:56:39.459  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:56:39.459  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:56:39.459  3571  3617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:56:39.459  3571  3617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ac7f7 removed from the list
,08-19 17:56:39.459  3571  3617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:56:39.460  3571  3617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:56:39.460  3571  3617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:56:39.460  3571  3617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:56:39.460  3571  3617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc747f6 removed from the list
,08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-19 17:56:39.461  3571  3617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:56:39.463  3760  3776 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-19 17:56:39.463  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.463  3760  3779 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:56:39.468  3571  3813 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 402, name: My test thread name)
,08-19 17:56:39.468  3571  3813 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 402, thread name: My test thread name)
08-19 17:56:39.468  3571  3813 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 402, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-19 17:56:39.470  3571  3814 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 404, name: My test thread name)
08-19 17:56:39.470  3571  3814 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 404, thread name: My test thread name)
08-19 17:56:39.470  3760  3776 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-19 17:56:39.470  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.471  3760  3779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-19 17:56:39.471  3571  3814 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 404, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
08-19 17:56:39.473  3571  3617 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-19 17:56:39.473  3571  3617 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-19 17:56:39.473  3571  3617 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-19 17:56:39.473  3571  3617 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-19 17:56:39.473  3571  3617 D com.test.thalitest.ThaliTestRunner: Total duration: 22856 ms
08-19 17:56:39.475  3571  3617 I jxcore-log: Total number of executed tests:  80
08-19 17:56:39.475  3571  3617 I jxcore-log: 
,08-19 17:56:39.475  3571  3617 I jxcore-log: Number of passed tests:  80
08-19 17:56:39.475  3571  3617 I jxcore-log: 
08-19 17:56:39.475  3571  3617 I jxcore-log: Number of failed tests:  0
08-19 17:56:39.475  3571  3617 I jxcore-log: 
,08-19 17:56:39.476  3571  3617 I jxcore-log: Number of ignored tests:  0
08-19 17:56:39.476  3571  3617 I jxcore-log: 
,08-19 17:56:39.476  3571  3617 I jxcore-log: Total duration:  22856
08-19 17:56:39.476  3571  3617 I jxcore-log: 
08-19 17:56:39.476  3571  3617 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-19 17:56:39.476  3571  3617 I jxcore-log: 
08-19 17:56:39.477  3760  3776 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-19 17:56:39.477  3760  3776 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-19 17:56:39.481  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.481  3571  3617 I jxcore-log: 
08-19 17:56:39.483  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.483  3571  3617 I jxcore-log: 
08-19 17:56:39.484  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.484  3571  3617 I jxcore-log: 
08-19 17:56:39.485  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.485  3571  3617 I jxcore-log: 
08-19 17:56:39.486  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.486  3571  3617 I jxcore-log: 
08-19 17:56:39.487  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.487  3571  3617 I jxcore-log: 
08-19 17:56:39.489  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.489  3571  3617 I jxcore-log: 
08-19 17:56:39.491  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.491  3571  3617 I jxcore-log: 
08-19 17:56:39.492  3571  3571 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-19 17:56:39.492  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:56:39.492  3571  3617 I jxcore-log: 
08-19 17:56:39.493  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.493  3571  3617 I jxcore-log: 
08-19 17:56:39.494  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.494  3571  3617 I jxcore-log: 
08-19 17:56:39.495  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.495  3571  3617 I jxcore-log: 
08-19 17:56:39.495  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.495  3571  3617 I jxcore-log: 
08-19 17:56:39.496  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.496  3571  3617 I jxcore-log: 
08-19 17:56:39.496  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.496  3571  3617 I jxcore-log: 
08-19 17:56:39.497  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.497  3571  3617 I jxcore-log: 
08-19 17:56:39.498  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.498  3571  3617 I jxcore-log: 
08-19 17:56:39.498  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.498  3571  3617 I jxcore-log: 
08-19 17:56:39.499  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:56:39.499  3571  3617 I jxcore-log: 
08-19 17:56:39.499  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.499  3571  3617 I jxcore-log: 
08-19 17:56:39.500  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.500  3571  3617 I jxcore-log: 
,08-19 17:56:39.501  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.501  3571  3617 I jxcore-log: 
08-19 17:56:39.501  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.501  3571  3617 I jxcore-log: 
,08-19 17:56:39.502  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.502  3571  3617 I jxcore-log: 
08-19 17:56:39.502  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.502  3571  3617 I jxcore-log: 
,08-19 17:56:39.503  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:56:39.503  3571  3617 I jxcore-log: 
,08-19 17:56:39.774  3571  3571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:56:39.776  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:56:39.776  3571  3617 I jxcore-log: 
,08-19 17:56:39.870  3571  3571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:56:39.873  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:56:39.873  3571  3617 I jxcore-log: 
,08-19 17:56:39.934  3571  3571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-19 17:56:39.938  3571  3617 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:56:39.938  3571  3617 I jxcore-log: 
,08-19 17:56:40.119  3815  3815 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-19 17:56:40.123  3815  3815 D AndroidRuntime: CheckJNI is OFF
,08-19 17:56:40.166  3815  3815 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-19 17:56:40.213  3815  3815 I Radio-JNI: register_android_hardware_Radio DONE
,08-19 17:56:40.235  3815  3815 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-19 17:56:40.248   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-19 17:56:40.249   872   885 I ActivityManager: Killing 3571:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-19 17:56:40.346   872  1894 D GraphicsStats: Buffer count: 2
,08-19 17:56:40.346   872  1894 I WindowState: WIN DEATH: Window{72ca24c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-19 17:56:40.349   872  1304 D WifiService: Client connection lost with reason: 4
,08-19 17:56:40.390   872   895 W PackageSettings: Skipping PackageSetting{77646f7 com.example.hello/10273} due to missing metadata
,08-19 17:56:40.417   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-19 17:56:40.417   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-19 17:56:40.418   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-19 17:56:40.418   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-19 17:56:40.418   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.418   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.418   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:56:40.418   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-19 17:56:40.418   872   885 I ActivityManager:   Force finishing activity ActivityRecord{3c53831 u0 com.test.thalitest/.MainActivity t2}
,08-19 17:56:40.420   872   895 I art     : Starting a blocking GC Explicit
,08-19 17:56:40.425   872   882 W ActivityManager: Spurious death for ProcessRecord{82d11ee 0:com.test.thalitest/u0a0}, curProc for 3571: null
,08-19 17:56:40.461   872   895 I art     : Explicit concurrent mark sweep GC freed 30447(1853KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 656us total 39.283ms
,08-19 17:56:40.491   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-19 17:56:40.495  3815  3815 I art     : System.exit called, status: 0
,08-19 17:56:40.495  3815  3815 I AndroidRuntime: VM exiting with result code 0.
,08-19 17:56:40.510   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-19 17:56:40.539   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-19 17:56:40.543  3760  3760 D BluetoothMapAppObserver: onReceive
08-19 17:56:40.543  3760  3760 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-19 17:56:40.544  1858  1858 I Keyboard.Facilitator: resetDictionaries() : en_US
08-19 17:56:40.545  1971  2256 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-19 17:56:40.549   872  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-19 17:56:40.552  3420  3420 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-19 17:56:40.553  1858  3826 I Keyboard.Facilitator.DecoderInitializer: run()
,08-19 17:56:40.559  1858  3826 I Decoder : createOrResetDecoder
,08-19 17:56:40.602  1917  1917 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-19 17:56:40.617  1489  1489 I ConfigService: onCreate
,08-19 17:56:40.624  2940  3829 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-19 17:56:40.637  1489  3831 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-19 17:56:40.637  1489  3831 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-19 17:56:40.637  1489  3831 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-19 17:56:40.645  2940  3829 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-19 17:56:40.645  2940  3829 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-19 17:56:40.645  2940  3829 E AndroidRuntime: Process: android.process.acore, PID: 2940
08-19 17:56:40.645  2940  3829 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.645  2940  3829 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:56:40.649  1489  3831 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-19 17:56:40.652   872  3832 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:40.652   872  3832 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.652   872  3832 E DropBoxManagerService: 	... 5 more
,08-19 17:56:40.653  2940  3829 I Process : Sending signal. PID: 2940 SIG: 9
08-19 17:56:40.653   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-19 17:56:40.665  1858  3826 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-19 17:56:40.684  1932  2022 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-19 17:56:40.684   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-19 17:56:40.685   872   884 E PackageManager: Failed to write settings, restoring backup
08-19 17:56:40.685   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-19 17:56:40.685   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-19 17:56:40.685   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-19 17:56:40.685   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-19 17:56:40.685   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-19 17:56:40.685   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.685   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.685   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:56:40.687   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-19 17:56:40.687   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-19 17:56:40.687   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.687   872   885 E DropBoxManagerService: 	... 13 more
,08-19 17:56:40.696   872  1931 I ActivityManager: Start proc 3834:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-19 17:56:40.697  1932  2022 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-19 17:56:40.697  1932  2022 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1932
08-19 17:56:40.697  1932  2022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.697  1932  2022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-19 17:56:40.699   872  2011 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-19 17:56:40.700   872  3842 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:40.700   872  3842 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.700   872  3842 E DropBoxManagerService: 	... 5 more
08-19 17:56:40.702  1932  2022 I Process : Sending signal. PID: 1932 SIG: 9
,08-19 17:56:40.708  1489  1489 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-19 17:56:40.710  1489  1489 D AndroidRuntime: Shutting down VM
,08-19 17:56:40.712  1489  1489 E AndroidRuntime: FATAL EXCEPTION: main
08-19 17:56:40.712  1489  1489 E AndroidRuntime: Process: com.google.process.gapps, PID: 1489
08-19 17:56:40.712  1489  1489 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-19 17:56:40.712  1489  1489 E AndroidRuntime: 	... 8 more
,08-19 17:56:40.716   872  3847 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:40.716   872  3847 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.716   872  3847 E DropBoxManagerService: 	... 5 more
,08-19 17:56:40.717  1489  1489 I Process : Sending signal. PID: 1489 SIG: 9
,08-19 17:56:40.731   872  1918 I ActivityManager: Process android.process.acore (pid 2940) has died
,08-19 17:56:40.732   872  1918 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-19 17:56:40.747  1858  3826 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-19 17:56:40.748  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-19 17:56:40.748  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-19 17:56:40.750  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-19 17:56:40.750  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-19 17:56:40.752  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-19 17:56:40.752  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-19 17:56:40.757  1858  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-19 17:56:40.757  1858  3826 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-19 17:56:40.757  1858  3826 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-19 17:56:40.758  1858  3826 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-19 17:56:40.758  1858  3826 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-19 17:56:40.759  1858  3826 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-19 17:56:40.790  1680  3851 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-19 17:56:40.790  1680  3851 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@3d6acdf
08-19 17:56:40.791   872  1930 I ActivityManager: Process com.google.process.gapps (pid 1489) early provider death
,08-19 17:56:40.794   872  1304 D WifiService: Client connection lost with reason: 4
,08-19 17:56:40.796   872  1379 D GraphicsStats: Buffer count: 1
08-19 17:56:40.796   872  2007 I WindowState: WIN DEATH: Window{2e6828b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-19 17:56:40.802   872  1930 I ActivityManager: Process com.google.process.gapps (pid 1489) has died
,08-19 17:56:40.802   872  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-19 17:56:40.802   872  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,08-19 17:56:40.802   872  1930 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-19 17:56:40.803   872  2011 W ActivityManager: Spurious death for ProcessRecord{33123c6 0:com.google.process.gapps/u0a11}, curProc for 1489: null
08-19 17:56:40.804   872   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1932) has died
08-19 17:56:40.804   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30998ms
,08-19 17:56:40.808  3472  3472 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-19 17:56:40.820   872  1918 I ActivityManager: Start proc 3852:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-19 17:56:40.856  3852  3852 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-19 17:56:40.864  1680  1680 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-19 17:56:40.864  1680  1680 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-19 17:56:40.869  1680  1680 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-19 17:56:40.869  1680  1680 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-19 17:56:40.877  3852  3852 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-19 17:56:40.879  3852  3852 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: ,	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:40.879  3852  3852 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-19 17:56:40.879  3852  3852 D AndroidRuntime: Shutting down VM
08-19 17:56:40.880  3852  3852 E AndroidRuntime: FATAL EXCEPTION: main
08-19 17:56:40.880  3852  3852 E AndroidRuntime: Process: com.google.process.gapps, PID: 3852
08-19 17:56:40.880  3852  3852 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	,at android.app.ActivityThread.main(ActivityThread.java:5417)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-19 17:56:40.880  3852  3852 E AndroidRuntime: 	... 10 more
,08-19 17:56:40.886  1680  3867 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-19 17:56:40.901   872  1894 I ActivityManager: Start proc 3869:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-19 17:56:40.905  1992  3866 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-19 17:56:40.912  3852  3852 I Process : Sending signal. PID: 3852 SIG: 9
08-19 17:56:40.912  1680  3867 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-19 17:56:40.912  1680  3867 E AndroidRuntime: Process: com.google.android.gms, PID: 1680
08-19 17:56:40.912  1680  3867 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-19 17:56:40.912  1680  3867 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:40.907   872  3874 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	,at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.907   872  3874 E DropBoxManagerService: 	... 5 more
,08-19 17:56:40.941  1680  3867 I Process : Sending signal. PID: 1680 SIG: 9
,08-19 17:56:40.942   872  3882 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:40.942   872  3882 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:40.942   872  3882 E DropBoxManagerService: 	... 5 more
,08-19 17:56:40.963  1992  3866 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-19 17:56:40.967   872  1910 I ActivityManager: Process com.google.process.gapps (pid 3852) has died
,08-19 17:56:40.967   872  1910 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{f9708ec u0 com.google.android.gms/.gcm.GcmService}
,08-19 17:56:40.967   872  1910 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{e323e5d u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-19 17:56:40.968   872  1910 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8f9d667 u0 com.google.android.gms/.config.ConfigService}
08-19 17:56:40.980   872  1910 I ActivityManager: Start proc 3883:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-19 17:56:40.983   278   278 E lowmemorykiller: Error writing /proc/1680/oom_score_adj; errno=22
,08-19 17:56:41.002  1992  3866 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-19 17:56:41.002  1992  3866 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-19 17:56:41.002  1992  3866 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1992
08-19 17:56:41.002  1992  3866 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:148)
08-19 17:56:41.002  1992  3866 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-19 17:56:41.004   872  1894 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-19 17:56:41.004   872  1894 I ActivityManager: Killing 1992:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-19 17:56:41.006   872  3890 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:56:41.006   872  3890 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-19 17:56:41.006   872  3890 E DropBoxManagerService: 	... 5 more
,08-19 17:56:41.029   280   335 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
