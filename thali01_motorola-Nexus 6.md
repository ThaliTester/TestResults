#### Test 829140733a8c9ab_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 15:26:25.004  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:25.017  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 15:26:25.021  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 15:26:25.088  1506  2092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 15:26:25.088  1506  2092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:26:25.089  1506  2092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:25.089  1506  2092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 15:26:25.125  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 15:26:25.125  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:26:25.125  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-31 15:26:25.706  3468  3468 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 15:26:25.711  3468  3468 D AndroidRuntime: CheckJNI is OFF
08-31 15:26:25.754  3468  3468 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 15:26:25.804  3468  3468 I Radio-JNI: register_android_hardware_Radio DONE
08-31 15:26:25.826  3468  3468 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 15:26:25.831   873  1377 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 15:26:25.887   873  1377 I ActivityManager: Start proc 3477:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 15:26:25.891  3468  3468 D AndroidRuntime: Shutting down VM
08-31 15:26:25.987  3477  3477 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 15:26:26.023  3477  3477 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 15:26:26.067  3477  3477 I LibraryLoader: Time to load native libraries: 38 ms (timestamps 2847-2885)
08-31 15:26:26.068  3477  3477 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:26:26.099  3477  3477 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eea3583}
08-31 15:26:26.101  3477  3477 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:26:26.102  3477  3477 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:26:26.115  3477  3477 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 15:26:26.119  3477  3477 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 15:26:26.175  3477  3493 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-31 15:26:26.184  3477  3477 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 15:26:26.199  3477  3477 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 15:26:26.199  3477  3477 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 15:26:26.199  3477  3477 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 15:26:26.199  3477  3477 I Adreno  : Build Date                       : 10/20/15
08-31 15:26:26.199  3477  3477 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 15:26:26.199  3477  3477 I Adreno  : Local Branch                     : M14
08-31 15:26:26.199  3477  3477 I Adreno  : Remote Branch                    : 
08-31 15:26:26.199  3477  3477 I Adreno  : Remote Branch                    : 
08-31 15:26:26.199  3477  3477 I Adreno  : Reconstruct Branch               : 
,08-31 15:26:26.285   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efae4b2:true
,08-31 15:26:26.348  3477  3477 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 15:26:26.360  3477  3477 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 15:26:26.400  3477  3516 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 15:26:26.411  3477  3502 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 15:26:26.456  3477  3516 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 15:26:26.507   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +580ms (total +638ms)
,08-31 15:26:26.508  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-31 15:26:26.573  3477  3477 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3477
,08-31 15:26:26.724  3477  3477 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 15:26:26.870  3477  3519 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681454800
,08-31 15:26:26.878  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 15:26:26.878  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 15:26:26.878  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 15:26:26.878  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 15:26:26.878  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 15:26:26.879  3477  3519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160e516 added. We now have 1 listener(s)
,08-31 15:26:26.883  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 15:26:26.884  3477  3519 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:26:26.885  3477  3519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:26:26.885  3477  3519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 15:26:26.890  3477  3519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@480486d added. We now have 1 listener(s)
08-31 15:26:26.891  3477  3519 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:26:26.897   873  1309 D WifiService: New client listening to asynchronous messages
,08-31 15:26:26.898  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:26:26.898  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 15:26:26.899  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 15:26:26.899  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 15:26:26.899  3477  3519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 15:26:26.901  3477  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:26:26.902  3477  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 15:26:26.907  3477  3519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:26.907  3477  3519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:26.907  3477  3519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 15:26:26.907  3477  3519 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:26:26.908  3477  3519 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 15:26:26.908  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:26.933  3477  3477 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 15:26:27.787  3477  3524 W jxcore-log: Initializing JXcore engine
,08-31 15:26:27.787  3477  3524 W jxcore-log: JXcore engine is ready
,08-31 15:26:27.822  3524  3524 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 15:26:27.822  3524  3524 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12754]" dev="sockfs" ino=12754 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 15:26:27.822  3524  3524 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 15:26:27.836  3477  3524 W jxcore-log: Starting JXcore engine
,08-31 15:26:27.822  3524  3524 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25476]" dev="sockfs" ino=25476 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 15:26:27.914  3477  3524 W jxcore-log: Platform android
08-31 15:26:27.914  3477  3524 W jxcore-log: 
,08-31 15:26:27.914  3477  3524 W jxcore-log: Process ARCH arm
08-31 15:26:27.914  3477  3524 W jxcore-log: 
,08-31 15:26:28.142  3477  3524 I jxcore-log: JXcore Cordova bridge is ready!
08-31 15:26:28.142  3477  3524 I jxcore-log: 
,08-31 15:26:28.143  3477  3524 W jxcore-log: JXcore engine is started
,08-31 15:26:28.153  3477  3519 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 15:26:28.158  3477  3477 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 15:26:37.983  3477  3524 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 15:26:37.983  3477  3524 I jxcore-log: 
,08-31 15:26:37.987  3477  3524 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 15:26:37.987  3477  3524 I jxcore-log: 
,08-31 15:26:37.989  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:37.990  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:37.990  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:37.990  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:37.994  3477  3524 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 15:26:37.994  3477  3524 I jxcore-log: 
,08-31 15:26:37.996  3477  3524 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 15:26:37.996  3477  3524 I jxcore-log: 
,08-31 15:26:38.488  3477  3524 D executeNativeTests: Running unit tests
,08-31 15:26:38.549  3477  3524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:26:38.550  3477  3524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 added. We now have 2 listener(s)
,08-31 15:26:38.552  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:26:38.552  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:26:38.552  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:26:38.552  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:26:38.552  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 added. We now have 2 listener(s)
08-31 15:26:38.552  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:26:38.553  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:26:38.554  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.556  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.557  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.557  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.558  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:38.562  3477  3524 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:26:38.563  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:38.570  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 15:26:38.570  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:26:38.570  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:26:38.576  3477  3524 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 15:26:38.577  3477  3524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 15:26:38.577  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 15:26:38.578  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:26:38.579  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:26:38.579  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.580  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.580  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.581  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.581  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.581  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:26:38.581  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:26:38.581  3477  3524 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 removed from the list
08-31 15:26:38.581  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.581  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 removed from the list
08-31 15:26:38.581  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.582  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.582  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.583  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.583  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.583  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.583  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.583  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.585  3477  3524 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 15:26:38.585  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.585  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.586  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.586  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.586  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.586  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.586  3477  3524 E org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.586  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.586  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.586  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.586  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.586  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.586  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.586  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.587  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.587  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.588  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.588  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
,08-31 15:26:38.606  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:26:38.606  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:26:38.606  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 15:26:38.607  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:26:38.607  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:26:38.607  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-31 15:26:38.607  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:26:38.607  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:26:38.608  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:26:38.608  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:26:38.608  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:26:38.608  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:26:38.609  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:26:38.610  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-31 15:26:38.610  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.610  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.610  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.610  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.610  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.610  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.610  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.611  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.611  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.611  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.611  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.611  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.611  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.611  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.611  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.611  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.611  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.612  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.612  3477  3524 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:26:38.613  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.614  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.614  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.614  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.614  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:38.614  3477  3524 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:26:38.615  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:26:38.615  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:26:38.615  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:26:38.615  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.615  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:38.615  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:26:38.617  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 15:26:38.618  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:26:38.618  3477  3524 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:26:38.618  3477  3524 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:26:38.618  3477  3477 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:26:38.619  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.620  3477  3524 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-31 15:26:38.621  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.621  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.621  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:26:38.621  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.621  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:26:38.621  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:26:38.621  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:26:38.621  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:26:38.621  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:26:38.622  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:26:38.622  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:26:38.623  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.623  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.623  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.623  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.623  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.623  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:26:38.623  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.623  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.623  3477  3477 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.624  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.624  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.624  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.624  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.624  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.625  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.625  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.625  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.625  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.626  3477  3524 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:26:38.627  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.628  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.628  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.628  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.628  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:38.628  3477  3524 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:26:38.628  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:26:38.628  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:26:38.628  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:26:38.629  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.629  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:26:38.629  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:38.630  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 15:26:38.630  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:26:38.630  3477  3524 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:26:38.630  3477  3524 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:26:38.630  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.630  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.630  3477  3477 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:26:38.631  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:26:38.631  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.631  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:26:38.631  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:26:38.631  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:26:38.631  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:26:38.631  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:26:38.631  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:26:38.631  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:26:38.632  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.632  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.632  3477  3524 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 15:26:38.632  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.632  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.632  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.634  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.634  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.634  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:26:38.634  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.634  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.635  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.635  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.635  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.635  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.635  3477  3477 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.635  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.635  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.635  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.636  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.636  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.636  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.636  3477  3524 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 15:26:38.637  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.637  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.637  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.637  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.637  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.637  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.637  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.637  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.637  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.637  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.637  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.637  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.637  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.638  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.638  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.638  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.638  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.638  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.639  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:26:38.639  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.639  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.639  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.639  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.639  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.639  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.640  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.640  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.640  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.640  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.640  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.640  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.640  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.640  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.640  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.640  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.640  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.640  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.641  3477  3524 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 15:26:38.641  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.641  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.641  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.641  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.641  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.641  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.642  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.642  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.642  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.642  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.642  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.642  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.642  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.642  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.642  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.642  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.642  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.643  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.643  3477  3524 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 15:26:38.643  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.643  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.643  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.643  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.643  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.644  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.644  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.644  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.644  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.644  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.644  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.644  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.644  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.644  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.644  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.644  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.644  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.645  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.645  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:26:38.645  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:26:38.645  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:26:38.645  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:26:38.645  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:26:38.646  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:26:38.646  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.646  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.646  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.646  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.646  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.646  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.646  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.646  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.646  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.646  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.646  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.646  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.646  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.646  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.647  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.647  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.647  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.647  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.648  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:26:38.648  3477  3524 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:26:38.648  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:26:38.651  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:26:38.651  3477  3524 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 15:26:38.651  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:26:38.651  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:26:38.652  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:26:38.653  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:26:38.653  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 15:26:38.654  3477  3524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:26:38.654  3477  3524 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 15:26:38.654  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:26:38.654  3477  3524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:26:38.654  3477  3524 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 15:26:38.654  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:26:38.654  3477  3524 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:26:38.654  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 15:26:38.656  3477  3524 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-31 15:26:38.656  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 15:26:38.657  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 15:26:38.657  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 15:26:38.659  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 15:26:38.659  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 15:26:38.659  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 15:26:38.659  3477  3524 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:26:38.659  3477  3524 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 15:26:38.660  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.660  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.660  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.662  3477  3526 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-31 15:26:38.662  3477  3526 E BluetoothDevice: Bluetooth is not enabled
08-31 15:26:38.662  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.662  3477  3526 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 15:26:38.662  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.663  3477  3526 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-31 15:26:38.663  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.663  3477  3526 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 15:26:38.663  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 15:26:38.664  3477  3477 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-31 15:26:38.665  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.665  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.665  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.665  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.665  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.665  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.665  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.665  3477  3526 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-31 15:26:38.665  3477  3477 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-31 15:26:38.665  3477  3526 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-31 15:26:38.665  3477  3477 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:26:38.665  3477  3477 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:26:38.665  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.666  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.666  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.666  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.667  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.668  3477  3524 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 15:26:38.669  3477  3527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-31 15:26:38.669  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.670  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.670  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.670  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.670  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.670  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.671  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.671  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.671  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.671  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.672  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.672  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.672  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.672  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.673  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.673  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.673  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.673  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.673  3477  3524 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 15:26:38.673  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.674  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.674  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.674  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.674  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.674  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.674  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.674  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.674  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.674  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.674  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.674  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.674  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.674  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.674  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.674  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.675  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.675  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.675  3477  3524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 15:26:38.675  3477  3524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 15:26:38.675  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:26:38.675  3477  3524 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 15:26:38.675  3477  3524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:26:38.675  3477  3524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 15:26:38.675  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:26:38.676  3477  3524 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 15:26:38.676  3477  3524 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:26:38.676  3477  3524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-31 15:26:38.676  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:26:38.676  3477  3524 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 15:26:38.676  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.676  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.676  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.676  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.676  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.676  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.676  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.676  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.676  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.676  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.676  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.676  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.676  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.677  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:26:38.677  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.677  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.677  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.677  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.677  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.677  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.677  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.677  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
,08-31 15:26:38.678  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.678  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
,08-31 15:26:38.678  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.678  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.678  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.678  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.678  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.678  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:26:38.678  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.678  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.678  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.678  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.678  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.678  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:26:38.678  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.678  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.678  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.679  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.679  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.679  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.679  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.679  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:26:38.679  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.679  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.679  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.679  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.679  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.679  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.679  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.680  3477  3524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-31 15:26:38.680  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.680  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-31 15:26:38.680  3477  3524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 15:26:38.681  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:26:38.681  3477  3477 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 15:26:38.681  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.681  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 15:26:38.681  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:26:38.681  3477  3524 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-31 15:26:38.681  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.681  3477  3477 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 15:26:38.681  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.681  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:26:38.681  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:26:38.681  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:26:38.681  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.681  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.682  3477  3524 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.682  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.682  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.682  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.682  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.682  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:26:38.682  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.682  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.682  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.682  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.682  3477  3477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:26:38.682  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.682  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.683  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:26:38.682  3477  3477 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:26:38.683  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.683  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.683  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.683  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.683  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.683  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.683  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.683  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
,08-31 15:26:38.684  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:26:38.685  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:26:38.685  3477  3524 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 15:26:38.685  3477  3524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:26:38.685  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:26:38.685  3477  3524 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:26:38.686  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.686  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.686  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:26:38.686  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.686  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.686  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.686  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.686  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.686  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.686  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.686  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:26:38.687  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.687  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.687  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.687  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.687  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.687  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.687  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.689  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.689  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.689  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.689  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.689  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:26:38.689  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.689  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.690  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.690  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.691  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.691  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.691  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.691  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.691  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.691  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.691  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:26:38.691  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.692  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.692  3477  3524 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:26:38.692  3477  3524 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:26:38.692  3477  3524 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:26:38.693  3477  3524 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:26:38.693  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.693  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.693  3477  3524 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbd07a8 not in the list
08-31 15:26:38.693  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.693  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.693  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:26:38.693  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.693  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.694  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:26:38.694  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:26:38.694  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:26:38.694  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:26:38.694  3477  3524 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:26:38.694  3477  3524 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1a2c1 not in the list
08-31 15:26:38.695  3477  3524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 15:26:38.695  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:26:38.695  3477  3524 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 15:26:38.695  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:26:38.695  3477  3524 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 15:26:38.695  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:26:38.697  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:26:38.697  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> out,going]
08-31 15:26:38.697  3477  3524 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 15:26:38.698  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:26:38.698  3477  3524 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 15:26:38.698  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:26:38.698  3477  3524 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 15:26:38.698  3477  3524 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 15:26:38.698  3477  3524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 15:26:38.698  3477  3524 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 15:26:38.699  3477  3524 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 15:26:38.699  3477  3524 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 15:26:38.699  3477  3524 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 15:26:38.699  3477  3524 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 15:26:38.699  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:26:38.700  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a20143 added. We now have 2 listener(s)
08-31 15:26:38.700  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:26:38.703   873  1683 D WifiService: setWifiEnabled: true pid=3477, uid=10000
08-31 15:26:38.703   873  1683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:26:38.709  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:26:38.709  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2f23c0 added. We now have 3 listener(s)
08-31 15:26:38.709  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:26:38.713  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:38.713  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:38.715  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:26:38.716   873   890 I ActivityManager: Start proc 3529:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 15:26:38.716  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a76e8f9 added. We now have 4 listener(s)
,08-31 15:26:38.716  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:26:38.717   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:26:38.722  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.722  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.722  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.722  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:38.722  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:26:38.723  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@933403e added. We now have 5 listener(s)
08-31 15:26:38.723  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:26:38.725   873  1681 D WifiService: setWifiEnabled: false pid=3477, uid=10000
,08-31 15:26:38.725   873  1681 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:26:38.730   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-31 15:26:38.731   873   886 I ActivityManager: Start proc 3541:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-31 15:26:38.731   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 15:26:38.732   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 15:26:38.733   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:26:38.733  3477  3524 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:26:38.733  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.733  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.733  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.733  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:38.734  3477  3524 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:26:38.734   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 15:26:38.734   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 15:26:38.734   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-31 15:26:38.735  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:38.768  3541  3541 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 15:26:38.783   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 15:26:38.784   374   871 D CommandListener: Setting iface cfg
08-31 15:26:38.784   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 15:26:38.785   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
08-31 15:26:38.785   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:26:38.794   873  1308 E native  : do suspend true
,08-31 15:26:38.799   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 15:26:38.799   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 15:26:38.812  3541  3541 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 15:26:38.813  3529  3529 D AdapterServiceConfig: Adding HeadsetService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding A2dpService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding HidService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding HealthService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding PanService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding GattService
08-31 15:26:38.814  3529  3529 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 15:26:38.823  1464  1464 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
08-31 15:26:38.824  1464  1464 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-31 15:26:38.828   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:26:38.829  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:38.829  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:38.829  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:38.829  1860  2261 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:26:38.829  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:38.829  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:38.830  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:38.830  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:38.839   873   884 I ActivityManager: Killing 2805:com.google.android.calendar/u0a37 (adj 15): empty #17
08-31 15:26:38.841   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@826a209:true
,08-31 15:26:38.841  3529  3529 D BluetoothAdapterState: make() - Creating AdapterState
08-31 15:26:38.843  3529  3529 I bt_bluedroid: init
08-31 15:26:38.843  3529  3567 I BluetoothAdapterState: Entering OffState
,08-31 15:26:38.846  3529  3568 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 15:26:38.847  3529  3568 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:26:38.847  3529  3568 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 15:26:38.847  3529  3568 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 15:26:38.848  3529  3529 I bt_bluedroid: get_profile_interface socket
,08-31 15:26:38.849  3529  3529 I bt_bluedroid: get_profile_interface sdp
,08-31 15:26:38.849  3529  3571 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:26:38.888  3529  3571 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:26:38.891  3529  3551 I bt_bluedroid: config_hci_snoop_log
,08-31 15:26:38.892   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-31 15:26:38.897  3529  3567 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 15:26:38.897  3529  3567 D BluetoothAdapterProperties: Setting state to 14
08-31 15:26:38.897  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 15:26:38.898  3529  3567 D BluetoothBondStateMachine: make
,08-31 15:26:38.899  3529  3572 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:26:38.901  3529  3567 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:26:38.902  3529  3529 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 15:26:38.903  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:38.904  3529  3529 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:26:38.904  3529  3529 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:26:38.904  3529  3529 D BtGatt.GattService: start()
08-31 15:26:38.904  3529  3529 I bt_bluedroid: get_profile_interface gatt
,08-31 15:26:38.905  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
08-31 15:26:38.906  3529  3529 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:26:38.911  3529  3529 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:38.911  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:38.911  3529  3529 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 15:26:38.911  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:38.911  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 15:26:38.912  3529  3567 I bt_bluedroid: enable
,08-31 15:26:38.912  3529  3568 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 15:26:38.912  3529  3568 I bt_hci  : start_up
,08-31 15:26:38.927  3529  3568 I bt_vendor: alloc value 0xb39a9189
08-31 15:26:38.927  3529  3568 I bt_vendor: init
,08-31 15:26:38.927  3529  3568 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 15:26:38.928  3529  3568 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 15:26:39.038  3529  3568 D bt_hci  : start_up starting async portion
,08-31 15:26:39.039  3529  3575 I bt_hci  : event_finish_startup
,08-31 15:26:39.039  3529  3575 I bt_hci_h4: hal_open
,08-31 15:26:39.042  3529  3575 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 15:26:39.050  3529  3575 I bt_userial_vendor: device fd = 51 open
,08-31 15:26:39.081  3529  3575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:26:39.112  3529  3575 D bt_hwcfg: Chipset BCM4354A2
,08-31 15:26:39.112  3529  3575 D bt_hwcfg: Target name = [BCM4354A2]
08-31 15:26:39.113  3529  3575 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 15:26:39.184  3477  3477 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:26:39.992  3529  3575 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 15:26:39.993  3529  3575 D bt_hwcfg: Settlement delay -- 100 ms
08-31 15:26:39.993  3529  3575 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 15:26:40.111  3529  3575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:26:40.113  3529  3575 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 15:26:40.143  3529  3575 I bt_hwcfg: vendor lib fwcfg completed
,08-31 15:26:40.144  3529  3575 I bt_vendor: firmware callback
,08-31 15:26:40.144  3529  3575 I bt_hci  : firmware_config_callback
,08-31 15:26:40.156  3529  3577 I bt_btu  : btu_task pending for preload complete event
,08-31 15:26:40.156  3529  3577 I bt_btu_task: Bluetooth chip preload is complete
,08-31 15:26:40.156  3529  3577 I bt_btu  : btu_task received preload complete event
,08-31 15:26:40.167  3529  3577 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 15:26:40.168  3529  3577 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:26:40.168  3529  3577 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:26:40.168  3529  3577 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:26:40.168  3529  3577 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:26:40.169  3529  3577 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:26:40.169  3529  3577 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:26:40.169  3529  3577 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:26:40.169  3529  3577 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 15:26:40.170  3529  3577 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:26:40.170  3529  3577 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:26:40.170  3529  3577 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 15:26:40.170  3529  3577 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:26:40.170  3529  3577 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 15:26:40.171  3529  3577 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:26:40.319  3529  3577 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,08-31 15:26:40.320  3529  3577 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-31 15:26:40.333  3529  3571 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 15:26:40.334  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 15:26:40.335  3529  3571 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:26:40.339  3529  3571 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:26:40.342  3529  3571 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:26:40.343  3529  3571 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:26:40.343  3529  3571 D bt_hci  : do_postload posting postload work item
08-31 15:26:40.343  3529  3575 I bt_hci  : event_postload
08-31 15:26:40.344  3529  3575 I bt_vendor: sco_config_cb
08-31 15:26:40.344  3529  3575 I bt_hci  : sco_config_callback postload finished.
,08-31 15:26:40.349  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:40.354  3529  3575 I bt_vendor: low_power_mode_cb
08-31 15:26:40.354  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:40.357  3529  3571 D bt_bte_conf: Device ID record 1 : primary
,08-31 15:26:40.357  3529  3571 D bt_bte_conf:   vendorId            = 000f
08-31 15:26:40.357  3529  3571 D bt_bte_conf:   vendorIdSource      = 0001
08-31 15:26:40.357  3529  3571 D bt_bte_conf:   product             = 1200
08-31 15:26:40.357  3529  3571 D bt_bte_conf:   version             = 1436
,08-31 15:26:40.357  3529  3571 D bt_bte_conf:   clientExecutableURL = 
08-31 15:26:40.358  3529  3571 D bt_bte_conf:   serviceDescription  = 
08-31 15:26:40.358  3529  3571 D bt_bte_conf:   documentationURL    = 
08-31 15:26:40.358  3529  3571 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 15:26:40.358  3529  3568 D bt_stack_manager: event_start_up_stack finished
,08-31 15:26:40.359  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 15:26:40.360  3529  3567 D BluetoothAdapterProperties: Setting state to 15
08-31 15:26:40.360  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 15:26:40.361  3529  3567 I BluetoothAdapterState: Entering BleOnState
,08-31 15:26:40.369  3529  3567 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 15:26:40.370  3529  3567 D BluetoothAdapterProperties: Setting state to 11
,08-31 15:26:40.370  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 15:26:40.381  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:40.385  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:40.409   873   886 I ActivityManager: Start proc 3583:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 15:26:40.413  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
08-31 15:26:40.414  3529  3529 D HeadsetService: Received start request. Starting profile...
,08-31 15:26:40.417  3529  3529 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:26:40.417  3529  3529 D HeadsetStateMachine: make
,08-31 15:26:40.430  3529  3567 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:26:40.429  3529  3529 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:26:40.430  3529  3529 I bt_bluedroid: get_profile_interface handsfree
,08-31 15:26:40.432  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 15:26:40.432  3529  3571 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 15:26:40.439  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:40.440   873   873 D BluetoothA2dp: Proxy object connected
,08-31 15:26:40.441  3529  3529 D A2dpService: Received start request. Starting profile...
,08-31 15:26:40.441  3529  3529 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:26:40.442  3529  3529 I bt_bluedroid: get_profile_interface avrcp
,08-31 15:26:40.448  3529  3529 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:26:40.449  3529  3529 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:26:40.449  3529  3529 D A2dpStateMachine: make
,08-31 15:26:40.450  3529  3529 I bt_bluedroid: get_profile_interface a2dp
,08-31 15:26:40.451  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 15:26:40.456  3529  3598 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:26:40.456  3529  3529 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:26:40.457  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
08-31 15:26:40.458  1367  1367 D BluetoothInputDevice: Proxy object connected
08-31 15:26:40.459  3529  3529 D HidService: Received start request. Starting profile...
08-31 15:26:40.459  3529  3529 I bt_bluedroid: get_profile_interface hidhost
08-31 15:26:40.459  3529  3529 D HidService: setHidService(): set to: null
08-31 15:26:40.459  1367  1367 D HidProfile: Bluetooth service connected
08-31 15:26:40.459  3529  3571 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
08-31 15:26:40.459  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 15:26:40.460  3529  3529 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:26:40.461  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:40.464  3529  3529 D HealthService: Received start request. Starting profile...
,08-31 15:26:40.465  3529  3529 I bt_bluedroid: get_profile_interface health
,08-31 15:26:40.466  3529  3529 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:26:40.467  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:40.468  3529  3529 D PanService: Received start request. Starting profile...
,08-31 15:26:40.468  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected,
,08-31 15:26:40.468  3529  3529 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 15:26:40.469  3529  3529 I bt_bluedroid: get_profile_interface pan
08-31 15:26:40.469  3529  3571 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:26:40.469  1367  1367 D PanProfile: Bluetooth service connected
08-31 15:26:40.474  3529  3529 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:40.476  3529  3529 D BluetoothMapService: Received start request. Starting profile...
08-31 15:26:40.476  3529  3529 D BluetoothMapService: start()
08-31 15:26:40.476  1367  1367 D BluetoothMap: Proxy object connected
08-31 15:26:40.477  1367  1367 D MapProfile: Bluetooth service connected
08-31 15:26:40.477  1367  1367 D BluetoothMap: getConnectedDevices()
08-31 15:26:40.478  3529  3529 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 15:26:40.478  1367  1367 D BluetoothMap: Bluetooth is Not enabled
08-31 15:26:40.479  3529  3529 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 15:26:40.479  3529  3529 D BluetoothMapAppObserver: createReceiver()
08-31 15:26:40.480  3529  3529 D BluetoothMapAppObserver: initObservers()
08-31 15:26:40.480  3529  3529 D BluetoothMapAppObserver: getEnabledAccountItems()
08-31 15:26:40.483  3583  3583 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-31 15:26:40.487  3529  3529 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:40.487  3529  3529 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:40.487  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.488  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:40.489  3529  3529 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:40.489  3529  3529 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:26:40.489  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:40.490  3529  3589 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isTurningOn()=true,
,08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.490  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:40.491  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:40.491  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 15:26:40.492  3529  3567 D BluetoothAdapterProperties: ScanMode =  20
,08-31 15:26:40.492  3529  3567 D BluetoothAdapterProperties: State =  11
08-31 15:26:40.494  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:40.494  3529  3571 D BluetoothAdapterProperties: Scan Mode:21
,08-31 15:26:40.495  3529  3571 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:26:40.495  3529  3567 D BluetoothAdapterProperties: Setting state to 12
08-31 15:26:40.496  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:40.496  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 15:26:40.496   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:26:40.496  3529  3567 I BluetoothAdapterState: Entering OnState
08-31 15:26:40.497  1982  1994 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:26:40.499  3477  3477 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 15:26:40.499   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:26:40.500   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:40.500  1367  2081 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:26:40.501  1367  2079 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:26:40.502  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:26:40.502   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:26:40.503  1367  1389 D BluetoothPan: onBluetoothStateChange on: true
,08-31 15:26:40.503  3477  3477 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:40.503  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:40.506  3529  3529 D BluetoothMapService: onReceive
,08-31 15:26:40.506  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:40.506  3529  3529 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:26:40.506  3529  3529 D BluetoothMapService: STATE_ON
,08-31 15:26:40.507   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 15:26:40.508  3529  3529 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 15:26:40.508  3529  3529 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 15:26:40.510  3529  3529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:40.510  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:40.513  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:40.514  3529  3529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:26:40.516  3477  3477 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 15:26:40.516  3529  3529 D ObexServerSockets: Succeed to create listening sockets 
08-31 15:26:40.517  3529  3529 D ObexServerSockets0: startAccept()
,08-31 15:26:40.517  3529  3529 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:26:40.517  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:40.518  1367  1658 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 15:26:40.522  3529  3529 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 15:26:40.522  3529  3529 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 15:26:40.523  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:40.524  1367  1367 D BluetoothA2dp: Proxy object connected
,08-31 15:26:40.525  3529  3605 D ObexServerSockets0: Accepting socket connection...
08-31 15:26:40.525  3529  3604 D ObexServerSockets0: Accepting socket connection...
08-31 15:26:40.526  1367  1658 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:26:40.526   873  1681 I ActivityManager: Killing 2978:com.google.android.gm/u0a78 (adj 15): empty #17
08-31 15:26:40.528  3529  3529 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 15:26:40.528  3529  3529 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:26:40.564  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:40.584   873  2033 I ActivityManager: Start proc 3606:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 15:26:40.600  1982  2069 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.601   873   890 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.602   873   890 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.603   873   890 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.629  1367  2079 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.631  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-31 15:26:40.642  3606  3606 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616),
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2,
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229),
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177),
08-31 15:26:40.781  3606  3606 D StrictMode: 	,at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
,08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 ,D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  360,6  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.781  3606  3606 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:26:40.781  3606  3606 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:26:40.788  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 15:26:40.800   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b362a1e:true
08-31 15:26:40.805  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:26:40.818  3583  3583 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 15:26:40.822  3583  3583 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:26:40.829  1367  1367 D BluetoothPbap: Proxy object connected
08-31 15:26:40.829  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-31 15:26:40.839  3583  3583 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 15:26:40.840  3583  3583 D BluetoothMap: Create BluetoothMap proxy object
08-31 15:26:40.844  3583  3583 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 15:26:40.852  3529  3635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:26:40.859  3583  3583 D DockEventReceiver: finishStartingService: stopping service
08-31 15:26:40.860  3583  3583 D BluetoothA2dp: Proxy object connected
08-31 15:26:40.864  3583  3583 D BluetoothInputDevice: Proxy object connected
08-31 15:26:40.865  3583  3583 D HidProfile: Bluetooth service connected
08-31 15:26:40.867  3529  3640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:26:40.870  3529  3640 I BtOppRfcommListener: Accept thread started.
08-31 15:26:40.870  3583  3583 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:26:40.871  3583  3583 D PanProfile: Bluetooth service connected
08-31 15:26:40.871  3583  3583 D BluetoothMap: Proxy object connected
08-31 15:26:40.871  3583  3583 D MapProfile: Bluetooth service connected
08-31 15:26:40.871  3583  3583 D BluetoothMap: getConnectedDevices()
08-31 15:26:40.873  3583  3583 D BluetoothPbap: Proxy object connected
,08-31 15:26:40.874  3583  3583 D PbapServerProfile: Bluetooth service connected
08-31 15:26:40.875   873  2030 I ActivityManager: Killing 3179:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 15:26:40.928  3583  3595 D BluetoothHeadset: Proxy object connected
,08-31 15:26:40.929  3583  3583 D HeadsetProfile: Bluetooth service connected
,08-31 15:26:41.029  3606  3627 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 15:26:41.051   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@818b7fb:true
,08-31 15:26:41.738   873  1999 D WifiService: setWifiEnabled: true pid=3477, uid=10000
08-31 15:26:41.739   873  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:26:41.760   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:41.778  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:41.785  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:41.794  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:41.796  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:41.806   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-31 15:26:41.807   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 15:26:41.809   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 15:26:41.811   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 15:26:41.812   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 15:26:41.812   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 15:26:41.812   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 15:26:41.816  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 15:26:41.897   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 15:26:41.897   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 15:26:41.900   374   871 D CommandListener: Setting iface cfg
,08-31 15:26:41.901  1464  1464 E wpa_supplicant: PNO: In assoc process
,08-31 15:26:41.903   873  1308 E WifiStateMachine:  Fail to set up pno, want true now false
,08-31 15:26:41.904   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '111 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 111 Failed to set address (No such device)'
,08-31 15:26:41.904   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:26:41.911   873  1308 E native  : do suspend true
08-31 15:26:41.915   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 15:26:41.925   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 15:26:41.952   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:26:42.280  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:26:42.326  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 15:26:42.327  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 15:26:42.335   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:26:42.362   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 15:26:42.363   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:26:42.363   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,08-31 15:26:42.399   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:26:42.412   374   871 D CommandListener: Setting iface cfg
,08-31 15:26:42.421   873  1308 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 15:26:42.427   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 15:26:42.450   873  3650 D DhcpClient: Receive thread started
,08-31 15:26:42.539   873  1308 E native  : do suspend false
,08-31 15:26:42.565   873  3649 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 15:26:42.581   873  3650 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171036, domain null
,08-31 15:26:42.584   873  3649 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171036 seconds
,08-31 15:26:42.588   873  3649 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 15:26:42.616   873  3650 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 15:26:42.617   873  3649 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 15:26:42.622   374   871 D CommandListener: Setting iface cfg
,08-31 15:26:42.634   873  3649 D DhcpClient: Scheduling renewal in 86399s
,08-31 15:26:42.634   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 15:26:42.639   873  1308 E native  : do suspend true
,08-31 15:26:42.661   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 15:26:42.664   873  1308 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 15:26:42.666   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 15:26:42.670   873  1310 D ConnectivityService: Adding iface wlan0 to network 100
,08-31 15:26:42.680   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 15:26:42.731   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 15:26:42.732   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-31 15:26:42.734   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-31 15:26:42.737   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-31 15:26:42.739   873  1310 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-31 15:26:42.751   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 15:26:42.759   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-31 15:26:42.760   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-31 15:26:42.761   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 15:26:42.763   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-31 15:26:42.763   873  1310 D ConnectivityService:    accepting network in place of null
08-31 15:26:42.763   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-31 15:26:42.766   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 15:26:42.802   873  3648 D NetlinkSocketObserver: NeighborEvent{elapsedMs=199617, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 15:26:42.817   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:26:42.873   873  3647 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:811::200e
,08-31 15:26:42.896   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:26:42.901   873  1310 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-31 15:26:42.908   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 15:26:42.908   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:26:42.910   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-31 15:26:42.912   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:26:42.918   873  1683 V BackupManagerService: Scheduling immediate backup pass
,08-31 15:26:42.926   873   873 V BackupManagerService: Running a backup pass
,08-31 15:26:42.930   873  1333 V BackupManagerService: clearing pending backups
,08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:26:42.932  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:26:42.934  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:26:42.942  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 15:26:42.947   873  1333 V PerformBackupTask: Beginning backup of 16 targets
,08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:26:42.949  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:26:42.959   873  3647 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 13:26:42 GMT], X-Android-Received-Millis=[1472650002958], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472650002929]}
,08-31 15:26:42.968   873  1333 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-31 15:26:42.970  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:26:42.971  1698  1698 D SystemUpdateService: onCreate
08-31 15:26:42.972   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 15:26:42.972   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
,08-31 15:26:42.972   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 15:26:42.973   873  1333 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
08-31 15:26:42.973   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 15:26:42.977   873  1949 D AlarmManagerService: Setting time of day to sec=1472650002
,08-31 15:26:42.758   873  1949 W AlarmManagerService: Unable to set rtc to 1472650002: Invalid argument
,08-31 15:26:42.762  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 15:26:42.765  1698  3669 I SystemUpdateService: active receiver: enabled
08-31 15:26:42.773  1698  3669 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 15:26:42.776  1698  3669 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 15:26:42.776  1698  3669 I SystemUpdateService: now status is 0 (complete)
08-31 15:26:42.776  1698  3669 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 15:26:42.776  1698  3669 I SystemUpdateService: file has been verified
,08-31 15:26:42.776  1698  3669 I SystemUpdateService: OTA package size = 12249756
,08-31 15:26:42.779   873  3673 D GpsLocationProvider: NTP server returned: 1472650002758 (Wed Aug 31 15:26:42 GMT+02:00 2016) reference: 199794 certainty: 7 system time offset: -21,
08-31 15:26:42.779   873  3673 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-31 15:26:42.782  1698  3669 I SystemUpdateService: showing system update notification
,08-31 15:26:42.817  1698  1698 D SystemUpdateService: onDestroy
,08-31 15:26:42.822  1698  3672 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 15:26:42.832   873  1333 I BackupRestoreController: Getting widget state for user: 0
,08-31 15:26:42.844  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:42.848  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:42.850  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:42.870  1698  3684 I iu.SyncManager: SYNC; picasa accounts
,08-31 15:26:42.873  1698  1698 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 15:26:42.875  1860  1871 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-31 15:26:42.875  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 15:26:42.876  1860  1871 V GmsBackupTransport: starting performBackup for @pm@
,08-31 15:26:42.883  1860  1871 V GmsBackupTransport: performBackup done for @pm@
,08-31 15:26:42.889  1698  3684 I iu.UploadsManager: num queued entries: 0
,08-31 15:26:42.890  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 15:26:42.891  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 15:26:42.894  1698  3684 I iu.UploadsManager: num updated entries: 0
,08-31 15:26:42.895  1698  3684 I iu.SyncManager: NEXT; no task
,08-31 15:26:42.906   873  1683 I ActivityManager: Start proc 3688:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 15:26:42.919   873  1681 I ActivityManager: Start proc 3700:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-31 15:26:42.923  1698  3683 I MDM     : [146] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 15:26:42.923  1698  3683 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 15:26:42.932  1698  3683 V GoogleAuthProtoRequest: [146] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 15:26:42.934  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:42.949  3700  3700 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-31 15:26:42.958  1506  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-31 15:26:42.958  1506  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
,08-31 15:26:42.958  1506  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:26:42.958  1506  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:42.973  1506  2003 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:26:42.973  1506  2003 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:26:42.978  1860  2428 W GmsBackupTransport: Error sending final backup to server: 
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:26:42.978  1860  2428 W GmsBackupTransport: 	... 1 more
,08-31 15:26:42.991  3700  3713 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-31 15:26:42.987  1860  2242 I GmsBackupTransport: Next backup will happen in 43199989 millis.
,08-31 15:26:42.994   873  1333 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-31 15:26:43.010  1698  1698 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-31 15:26:43.022  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 15:26:43.022  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 15:26:43.022  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:26:43.022  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 15:26:43.026   873  1683 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1698 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:26:43.032  3541  3676 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 15:26:43.042  1698  3683 E MDM     : [146] SitrepService.a: Error sending sitrep.
,08-31 15:26:43.055  3688  3688 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 15:26:43.058  3688  3688 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:26:43.058  3700  3713 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-31 15:26:43.067  3688  3688 D SprintDMHelper: simOperator: 
08-31 15:26:43.067  3688  3688 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 15:26:43.095   873  1995 I ActivityManager: Start proc 3728:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 15:26:43.104   873  1333 I BackupManagerService: Backup pass finished.
,08-31 15:26:43.105  3700  3713 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 15:26:43.148  1506  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-31 15:26:43.148  1506  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-31 15:26:43.148  1506  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:43.148  1506  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 15:26:43.161  3700  3700 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-31 15:26:43.181  3541  3676 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-31 15:26:43.224  3743  3743 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-602522614.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-602522614.dex
,08-31 15:26:43.243  1698  3675 W DriveInitializer: Awaiting to be initialized
,08-31 15:26:43.243  1506  3712 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-31 15:26:43.243  1506  3712 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 15:26:43.243  1506  3712 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:43.243  1506  3712 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 15:26:43.244  1698  3761 W DriveInitializer: Background init thread started
08-31 15:26:43.260  3263  3680 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 15:26:43.260  3263  3680 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jdm.a(PG:82)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jcs.o(PG:406)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jcn.a(PG:1379)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jcs.i(PG:143)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at blb.a(PG:3937)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at czp.a(PG:18188)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at czp.a(PG:9081)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at czq.run(PG:1686)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:26:43.260  3263  3680 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jdj.a(PG:4091)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jdj.a(PG:1125)
,08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jdm.a(PG:77)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	... 12 more
08-31 15:26:43.260  3263  3680 E HttpOperation: Caused by: faj: BadAuthentication
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at fal.a(PG:38)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	at jdj.a(PG:4089)
08-31 15:26:43.260  3263  3680 E HttpOperation: 	... 14 more
,08-31 15:26:43.302  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 15:26:43.302  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 15:26:43.302  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:43.302  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:43.314  1698  3761 W DriveInitializer: Background init thread ended
,08-31 15:26:43.322  3263  3680 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 15:26:43.322  3263  3680 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jdm.a(PG:82)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jcs.o(PG:406)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jcn.a(PG:1379)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jcs.i(PG:143)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at hec.a(PG:42)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at hee.a(PG:102)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at czr.a(PG:65)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at kka.a(PG:108)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at czp.a(PG:19176)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at czp.a(PG:9081)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at czq.run(PG:1686)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:26:43.322  3263  3680 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jdj.a(PG:4091)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jdj.a(PG:1125)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jdm.a(PG:77)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	... 15 more
08-31 15:26:43.322  3263  3680 E HttpOperation: Caused by: faj: BadAuthentication
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at fal.a(PG:38)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	at jdj.a(PG:4089)
08-31 15:26:43.322  3263  3680 E HttpOperation: 	... 17 more
,08-31 15:26:43.322  3263  3680 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 15:26:43.322  3263  3680 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at hec.a(PG:42)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at hee.a(PG:102)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at czr.a(PG:65)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at kka.a(PG:108)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	... 15 more
08-31 15:26:43.322  3263  3680 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at fal.a(PG:38)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 15:26:43.322  3263  3680 E ExperimentLoader: 	... 17 more
,08-31 15:26:43.335  3700  3700 W InstanceID/Rpc: Found 10011
,08-31 15:26:43.358  3743  3743 I dex2oat : dex2oat took 133.945ms (threads: 4) arena alloc=443KB java alloc=29KB native alloc=1771KB free=1556KB
,08-31 15:26:43.439   873  2033 I ActivityManager: Start proc 3811:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 15:26:43.450  1506  3824 I VacuumService: Vacuum at: now=1472650003450 tag=VacuumService
,08-31 15:26:43.449   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 26065, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:26:43.470  3811  3811 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 15:26:43.491  3026  3767 V KeepSync: Connecting to GoogleApiClient
,08-31 15:26:43.492   873  1683 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 15:26:43.512   873   885 I ActivityManager: Start proc 3826:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-31 15:26:43.531  3826  3826 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-31 15:26:43.605  1506  2092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 15:26:43.605  1506  2092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 15:26:43.606  1506  2092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:43.606  1506  2092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-31 15:26:43.619  1698  3841 V BaseAuthAsyncOperation: access token request failed
,08-31 15:26:43.621  3026  3767 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 15:26:43.666  2864  3810 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-31 15:26:43.759  3826  3826 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 15:26:43.770  3826  3826 I BooksApp: Created application version: 3.6.9 (30609)
,08-31 15:26:43.801  3811  3811 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 15:26:43.801  3811  3811 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 15:26:43.801  3811  3811 I GAv4    :   adb logcat -s GAv4
,08-31 15:26:43.819  3811  3811 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:26:43.827  3811  3811 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:26:43.858  3826  3854 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 15:26:43.859  3811  3857 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:26:43.989  3811  3811 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 15:26:44.051  3811  3811 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 15:26:44.062  3811  3811 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1094-1100)
,08-31 15:26:44.062  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:26:44.092  3811  3811 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d126dd}
,08-31 15:26:44.093  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:26:44.093  3811  3811 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:26:44.107  3811  3811 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 15:26:44.110  3811  3811 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 15:26:44.156  3811  3811 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 15:26:44.172  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 15:26:44.172  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 15:26:44.172  3811  3811 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 15:26:44.172  3811  3811 I Adreno  : Build Date                       : 10/20/15
08-31 15:26:44.172  3811  3811 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 15:26:44.172  3811  3811 I Adreno  : Local Branch                     : M14
08-31 15:26:44.172  3811  3811 I Adreno  : Remote Branch                    : 
08-31 15:26:44.172  3811  3811 I Adreno  : Remote Branch                    : 
08-31 15:26:44.172  3811  3811 I Adreno  : Reconstruct Branch               : 
,08-31 15:26:44.279  3811  3811 I NSApplication: Starting up...
,08-31 15:26:44.294  3811  3888 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 15:26:44.297  1506  2003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-31 15:26:44.297  1506  2003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.,
08-31 15:26:44.297  1506  2003 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:26:44.298  1506  2003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:44.310   873  2034 I ActivityManager: Start proc 3893:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 15:26:44.311   873  2034 I ActivityManager: Killing 2615:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 15:26:44.397  3826  3907 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 15:26:44.437  3893  3893 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 15:26:44.443  3026  3767 E KeepSync: IOException
08-31 15:26:44.443  3026  3767 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 15:26:44.443  3026  3767 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 15:26:44.443  3026  3767 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 15:26:44.443  3026  3767 E KeepSync: 	... 10 more
,08-31 15:26:44.443  3026  3767 W KeepSync: Sync result 2
,08-31 15:26:44.458   873  1396 I ActivityManager: Killing 2959:android.process.acore/u0a5 (adj 15): empty #17
,08-31 15:26:44.459   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 26077, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:26:44.475  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 15:26:44.475  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 15:26:44.475  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:44.475  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:44.528   873  2027 D WifiService: setWifiEnabled: false pid=3477, uid=10000
,08-31 15:26:44.528   873  2027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:26:44.540  1506  2092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 15:26:44.541  1506  2092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 15:26:44.541  1506  2092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:26:44.541  1506  2092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:44.553  3826  3907 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-31 15:26:44.554  3826  3854 E BooksSync: Soft error
08-31 15:26:44.554  3826  3854 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 15:26:44.554  3826  3854 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-31 15:26:44.556  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 15:26:44.559   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 15:26:44.559   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 15:26:44.559   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 15:26:44.559   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:26:44.560  3826  3854 E BooksSync: Sync error
08-31 15:26:44.560  3826  3854 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 15:26:44.560  3826  3854 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-31 15:26:44.561  3826  3854 I BooksSync: Finished books sync
,08-31 15:26:44.590   873  1308 E native  : do suspend true
,08-31 15:26:44.599   374   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:26:44.599   873  3649 D DhcpClient: Clearing IP address
,08-31 15:26:44.600   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26078, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:26:44.601   374   871 D CommandListener: Setting iface cfg
,08-31 15:26:44.601   873   884 I ActivityManager: Killing 3351:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 15:26:44.602   873  3650 D DhcpClient: Receive thread stopped
08-31 15:26:44.603  1506  3720 V NativeCrypto: Read error: ssl=0x9a8c7000: I/O error during system call, Connection timed out
,08-31 15:26:44.606  1506  3720 V NativeCrypto: SSL shutdown failed: ssl=0x9a8c7000: I/O error during system call, Broken pipe
,08-31 15:26:44.607   873  2033 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-31 15:26:44.608   873  3647 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-31 15:26:44.608   873  3647 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:811::200e
,08-31 15:26:44.612   873  3647 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:811::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-31 15:26:44.614   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-31 15:26:44.614   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 15:26:44.615   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 15:26:44.650   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 15:26:44.650   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-31 15:26:44.652   397   397 E Parcel  : Reading a NULL string not supported here.
,08-31 15:26:44.655   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-31 15:26:44.660   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 15:26:44.660   873  1308 E native  : do suspend true
08-31 15:26:44.662   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-31 15:26:44.706   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:26:44.736   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:26:44.740   374   871 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:26:44.742   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 15:26:44.742   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 15:26:44.742   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:26:44.744   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:44.749  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:44.751  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:44.754  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:44.756  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:44.758   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:44.762  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:44.762   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 15:26:44.765  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:44.768  1860  2261 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:44.769  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:44.770  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:44.787  1506  3916 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-31 15:26:44.788  1506  3916 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 15:26:44.806   374   871 E Netd    : netlink response contains error (No such file or directory)
,08-31 15:26:44.806   873  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 15:26:44.806   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 15:26:44.831  1506  3916 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-31 15:26:45.006   873  1995 I ActivityManager: Killing 3368:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 15:26:45.115  1698  1698 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 15:26:45.129  1698  1698 D SystemUpdateService: onCreate
,08-31 15:26:45.149  1698  1698 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 15:26:45.155  1698  3931 I SystemUpdateService: active receiver: enabled
,08-31 15:26:45.159  1698  3931 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 15:26:45.161  1698  3931 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 15:26:45.161  1698  3931 I SystemUpdateService: now status is 0 (complete)
,08-31 15:26:45.161  1698  3931 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 15:26:45.161  1698  3931 I SystemUpdateService: file has been verified
,08-31 15:26:45.161  1698  3931 I SystemUpdateService: OTA package size = 12249756
,08-31 15:26:45.170  1698  3931 I SystemUpdateService: showing system update notification
,08-31 15:26:45.173  1698  1698 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-31 15:26:45.175  1698  3684 I iu.UploadsManager: num queued entries: 0
,08-31 15:26:45.176  1698  3684 I iu.UploadsManager: num updated entries: 0
,08-31 15:26:45.178  1698  3684 I iu.SyncManager: NEXT; no task
,08-31 15:26:45.189  1698  1698 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 15:26:45.194  1698  1698 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 15:26:45.194  1698  1698 D SystemUpdateService: onDestroy
,08-31 15:26:45.196  3688  3688 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:26:45.199  3688  3688 D SprintDMHelper: simOperator: 
,08-31 15:26:45.199  3688  3688 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 15:26:45.215  2864  3933 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 15:26:47.543  3529  3567 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 15:26:47.543  3529  3567 D BluetoothAdapterProperties: Setting state to 13
,08-31 15:26:47.544  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 15:26:47.546  3529  3567 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:26:47.548  3529  3567 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:26:47.555  3529  3529 D BluetoothMapService: onReceive
08-31 15:26:47.555  3529  3529 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:26:47.556  3529  3529 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:26:47.556  3529  3529 D BluetoothMapService: MAP Service closeService in
08-31 15:26:47.557  3529  3529 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 15:26:47.557  3529  3529 D ObexServerSockets0: shutdown(block = true)
,08-31 15:26:47.559  3529  3604 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 15:26:47.561  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:47.561  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:47.562  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:47.562  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:47.564  3529  3529 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:26:47.564  3529  3529 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 15:26:47.566  3529  3579 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 15:26:47.565  3529  3605 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 15:26:47.567  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:47.567  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:47.567  3529  3529 I BtOppRfcommListener: stopping Accept Thread
08-31 15:26:47.568  3529  3640 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:26:47.569  3529  3571 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:26:47.568  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:47.575  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:47.571  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 15:26:47.576  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 15:26:47.570  3529  3640 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 15:26:47.581  3529  3529 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:26:47.583  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:47.584  1367  1379 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:47.584   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:47.584   873   873 D BluetoothHeadset: Proxy object disconnected
,08-31 15:26:47.584  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:26:47.585  3583  3596 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:47.585   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:47.585  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:47.585  1982  1994 D BluetoothHeadset: Proxy object disconnected
,08-31 15:26:47.586  3529  3529 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:47.586  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:47.586  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:47.586  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:47.592  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:47.592  3529  3529 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:26:47.592  3529  3529 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:26:47.592  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-31 15:26:47.593  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:47.593  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:26:47.593  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:26:47.594  3529  3571 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 15:26:47.596  3529  3529 D A2dpService: Received stop request...Stopping profile...
,08-31 15:26:47.596  1367  1367 D BluetoothPbap: Proxy object disconnected
08-31 15:26:47.596  3529  3598 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:26:47.596  1367  1367 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:26:47.597  3583  3583 D DockEventReceiver: finishStartingService: stopping service
08-31 15:26:47.600   873   873 D BluetoothA2dp: Proxy object disconnected
08-31 15:26:47.600  3529  3529 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:47.600  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:47.600  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:47.600  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:47.601  3529  3529 D HidService: Received stop request...Stopping profile...
08-31 15:26:47.601  3529  3529 D HidService: Stopping Bluetooth HidService
08-31 15:26:47.602  1367  1367 D BluetoothA2dp: Proxy object disconnected
,08-31 15:26:47.604  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-31 15:26:47.604  1367  1367 D HidProfile: Bluetooth service disconnected
08-31 15:26:47.605  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 15:26:47.605  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:47.605  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:26:47.605  3529  3577 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:26:47.605  3529  3529 D HealthService: Received stop request...Stopping profile...
08-31 15:26:47.605  3529  3577 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 15:26:47.605  3529  3577 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 15:26:47.605  3529  3577 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:26:47.608  3529  3529 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:47.608  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:47.609  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:26:47.609  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:47.609  3529  3529 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:26:47.609  3529  3529 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:26:47.609  3529  3571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 15:26:47.609  3529  3529 D PanService: Received stop request...Stopping profile...
,08-31 15:26:47.610  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:26:47.610  3583  3583 D HeadsetProfile: Bluetooth service disconnected
08-31 15:26:47.610  1367  1367 D PanProfile: Bluetooth service disconnected
08-31 15:26:47.610  3583  3583 D BluetoothPbap: Proxy object disconnected
,08-31 15:26:47.610  3583  3583 D PbapServerProfile: Bluetooth service disconnected
08-31 15:26:47.611  3583  3583 D BluetoothA2dp: Proxy object disconnected
,08-31 15:26:47.611  3583  3583 D BluetoothInputDevice: Proxy object disconnected
08-31 15:26:47.611  3583  3583 D HidProfile: Bluetooth service disconnected
08-31 15:26:47.611  3583  3583 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:26:47.611  3583  3583 D PanProfile: Bluetooth service disconnected
,08-31 15:26:47.613  3529  3529 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:26:47.613  3529  3529 D BluetoothMapService: stop()
08-31 15:26:47.616  3529  3529 D BluetoothMapAppObserver: deinitObservers()
08-31 15:26:47.616  3529  3529 D BluetoothMapAppObserver: removeReceiver()
,08-31 15:26:47.617  1367  1367 D BluetoothMap: Proxy object disconnected
,08-31 15:26:47.617  1367  1367 D MapProfile: Bluetooth service disconnected
08-31 15:26:47.617  3529  3529 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:47.617  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:47.618  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:47.618  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:47.618  3529  3529 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:26:47.618  3529  3571 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 15:26:47.618  3529  3529 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:26:47.619  3529  3529 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:47.619  3529  3529 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:26:47.619  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:47.619  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:47.619  3529  3529 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:26:47.619  3529  3529 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 15:26:47.620  3583  3583 D BluetoothMap: Proxy object disconnected
08-31 15:26:47.620  3529  3529 D BluetoothMapService: MAP Service closeService in
08-31 15:26:47.620  3583  3583 D MapProfile: Bluetooth service disconnected
08-31 15:26:47.620  3529  3529 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:47.620  3529  3529 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:47.621  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:47.621  3529  3529 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:47.621  3529  3529 D BluetoothMapService: cleanup()
08-31 15:26:47.621  3529  3529 D BluetoothMapService: MAP Service closeService in
08-31 15:26:47.621  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 15:26:47.621  3529  3567 D BluetoothAdapterProperties: Setting state to 15
,08-31 15:26:47.621  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-31 15:26:47.622   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:26:47.622  3529  3567 I BluetoothAdapterState: Entering BleOnState
08-31 15:26:47.622  3583  3595 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:26:47.623  3583  3596 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:26:47.623  1982  2069 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:47.624  3583  3595 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:26:47.624   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:47.624  3583  3596 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:26:47.625  1367  2079 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:26:47.625  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:26:47.626   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:26:47.626  3583  3595 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:26:47.626  1367  2081 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:26:47.627  1367  1389 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:26:47.628  3583  3596 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:26:47.628  1367  2079 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 15:26:47.628   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:26:47.628  1367  1379 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:26:47.629  3529  3567 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-31 15:26:47.629  3529  3567 D BluetoothAdapterProperties: Setting state to 16
08-31 15:26:47.629  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 15:26:47.630  3529  3567 D BluetoothAdapterProperties: onBleDisable
,08-31 15:26:47.630  3529  3567 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:26:47.630  3529  3568 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 15:26:47.631  3529  3577 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 15:26:47.631  3529  3577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:47.631  3529  3571 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:26:47.634  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:47.635  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:47.636  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:47.637  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:26:47.637  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:47.641  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:47.650  3583  3583 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:26:47.837  3529  3571 I bt_hci  : shut_down
,08-31 15:26:47.837  3529  3575 D bt_hwcfg: hw_epilog_process
08-31 15:26:47.839  3529  3575 I bt_vendor: low_power_mode_cb
,08-31 15:26:47.865  3529  3575 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 15:26:47.865  3529  3575 I bt_vendor: epilog_cb
,08-31 15:26:47.865  3529  3575 I bt_hci  : epilog_finished_callback
,08-31 15:26:47.876  3529  3571 I bt_hci_h4: hal_close
,08-31 15:26:47.877  3529  3571 I bt_userial_vendor: device fd = 51 close
,08-31 15:26:48.004  3529  3568 D bt_stack_manager: event_shut_down_stack finished.
,08-31 15:26:48.005  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 15:26:48.010  3529  3567 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 15:26:48.010  3529  3529 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:26:48.011  3529  3529 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:26:48.011  3529  3529 D BtGatt.GattService: stop()
,08-31 15:26:48.012  3529  3529 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 15:26:48.016  3529  3529 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:48.016  3529  3529 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:26:48.016  3529  3529 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:26:48.017  3529  3529 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 15:26:48.017  3529  3567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 15:26:48.019  3529  3567 D BluetoothAdapterProperties: Setting state to 10
,08-31 15:26:48.019  3529  3567 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 15:26:48.020  3529  3567 I BluetoothAdapterState: Entering OffState
,08-31 15:26:48.021   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 15:26:48.038  3529  3529 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 15:26:48.038  3529  3529 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-31 15:26:48.038  3529  3568 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 15:26:48.040  3529  3568 D bt_stack_manager: event_clean_up_stack finished.
,08-31 15:26:48.040  3529  3529 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 15:26:48.049  3529  3529 I art     : System.exit called, status: 0
,08-31 15:26:48.049  3529  3529 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 15:26:48.109   873  2027 I ActivityManager: Process com.android.bluetooth (pid 3529) has died
,08-31 15:26:48.764  3826  3850 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 15:26:49.589  3700  3786 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,08-31 15:26:49.601   873  2034 I ActivityManager: Killing 3394:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 15:26:49.657   873  2034 I ActivityManager: Killing 1923:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,08-31 15:26:50.546   873  1310 D ConnectivityService: handlePromptUnvalidated 100
,08-31 15:26:50.591   873   890 I ActivityManager: Start proc 3947:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 15:26:50.718  3947  3947 D AdapterServiceConfig: Adding HeadsetService
,08-31 15:26:50.718  3947  3947 D AdapterServiceConfig: Adding A2dpService
,08-31 15:26:50.719  3947  3947 D AdapterServiceConfig: Adding HidService
,08-31 15:26:50.719  3947  3947 D AdapterServiceConfig: Adding HealthService
,08-31 15:26:50.719  3947  3947 D AdapterServiceConfig: Adding PanService
,08-31 15:26:50.719  3947  3947 D AdapterServiceConfig: Adding GattService
08-31 15:26:50.719  3947  3947 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 15:26:50.735   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ac2e243:true
,08-31 15:26:50.735  3947  3947 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 15:26:50.740  3947  3947 I bt_bluedroid: init
,08-31 15:26:50.741  3947  3959 I BluetoothAdapterState: Entering OffState
,08-31 15:26:50.746  3947  3960 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 15:26:50.746  3947  3960 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 15:26:50.746  3947  3960 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:26:50.746  3947  3960 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:26:50.747  3947  3947 I bt_bluedroid: get_profile_interface socket
08-31 15:26:50.750  3947  3947 I bt_bluedroid: get_profile_interface sdp
,08-31 15:26:50.752  3947  3963 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:26:50.755  3947  3963 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 15:26:50.755  3947  3958 I bt_bluedroid: config_hci_snoop_log
,08-31 15:26:50.759   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 15:26:50.768  3947  3959 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 15:26:50.768  3947  3959 D BluetoothAdapterProperties: Setting state to 14
08-31 15:26:50.769  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 15:26:50.773  3947  3959 D BluetoothBondStateMachine: make
,08-31 15:26:50.778  3947  3964 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:26:50.783  3947  3959 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:26:50.785  3947  3947 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 15:26:50.789  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:50.790  3947  3947 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:26:50.790  3947  3947 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:26:50.791  3947  3947 D BtGatt.GattService: start()
08-31 15:26:50.791  3947  3947 I bt_bluedroid: get_profile_interface gatt
08-31 15:26:50.792  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:50.793  3947  3947 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:26:50.807  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:50.807  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:50.807  3947  3947 V BluetoothAdapterState: isBleTurningOn()=true
08-31 15:26:50.808  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:50.809  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 15:26:50.809  3947  3959 I bt_bluedroid: enable
,08-31 15:26:50.810  3947  3960 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 15:26:50.810  3947  3960 I bt_hci  : start_up
,08-31 15:26:50.824  3947  3960 I bt_vendor: alloc value 0xb39ea189
,08-31 15:26:50.825  3947  3960 I bt_vendor: init
,08-31 15:26:50.825  3947  3960 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 15:26:50.826  3947  3960 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 15:26:50.932  3947  3960 D bt_hci  : start_up starting async portion
,08-31 15:26:50.933  3947  3967 I bt_hci  : event_finish_startup
,08-31 15:26:50.933  3947  3967 I bt_hci_h4: hal_open
,08-31 15:26:50.934  3947  3967 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 15:26:50.941  3947  3967 I bt_userial_vendor: device fd = 51 open
,08-31 15:26:50.975  3947  3967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:26:51.007  3947  3967 D bt_hwcfg: Chipset BCM4354A2
,08-31 15:26:51.008  3947  3967 D bt_hwcfg: Target name = [BCM4354A2]
08-31 15:26:51.008  3947  3967 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 15:26:51.672  3947  3967 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 15:26:51.674  3947  3967 D bt_hwcfg: Settlement delay -- 100 ms
08-31 15:26:51.674  3947  3967 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 15:26:51.791  3947  3967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:26:51.792  3947  3967 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 15:26:51.821  3947  3967 I bt_hwcfg: vendor lib fwcfg completed
08-31 15:26:51.821  3947  3967 I bt_vendor: firmware callback
,08-31 15:26:51.822  3947  3967 I bt_hci  : firmware_config_callback
,08-31 15:26:51.832  3947  3969 I bt_btu  : btu_task pending for preload complete event
,08-31 15:26:51.833  3947  3969 I bt_btu_task: Bluetooth chip preload is complete
08-31 15:26:51.833  3947  3969 I bt_btu  : btu_task received preload complete event
,08-31 15:26:51.843  3947  3969 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 15:26:51.843  3947  3969 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:26:51.843  3947  3969 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 15:26:51.844  3947  3969 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:26:51.844  3947  3969 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 15:26:51.844  3947  3969 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:26:51.844  3947  3969 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:26:51.844  3947  3969 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:26:51.845  3947  3969 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 15:26:51.845  3947  3969 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:26:51.845  3947  3969 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:26:51.846  3947  3969 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:26:51.846  3947  3969 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 15:26:51.846  3947  3969 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:26:51.846  3947  3969 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:26:51.979  3947  3969 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
,08-31 15:26:51.979  3947  3969 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,08-31 15:26:51.990  3947  3963 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 15:26:51.991  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 15:26:51.993  3947  3963 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:26:51.998  3947  3963 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:26:52.002  3947  3963 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:26:52.003  3947  3963 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:26:52.003  3947  3963 D bt_hci  : do_postload posting postload work item
,08-31 15:26:52.003  3947  3967 I bt_hci  : event_postload
,08-31 15:26:52.003  3947  3967 I bt_vendor: sco_config_cb
,08-31 15:26:52.003  3947  3967 I bt_hci  : sco_config_callback postload finished.
08-31 15:26:52.009  3947  3963 D bt_bte_conf: Device ID record 1 : primary
,08-31 15:26:52.009  3947  3963 D bt_bte_conf:   vendorId            = 000f
08-31 15:26:52.009  3947  3963 D bt_bte_conf:   vendorIdSource      = 0001
08-31 15:26:52.009  3947  3963 D bt_bte_conf:   product             = 1200
08-31 15:26:52.009  3947  3963 D bt_bte_conf:   version             = 1436
08-31 15:26:52.009  3947  3963 D bt_bte_conf:   clientExecutableURL = 
08-31 15:26:52.010  3947  3963 D bt_bte_conf:   serviceDescription  = 
08-31 15:26:52.010  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:52.010  3947  3963 D bt_bte_conf:   documentationURL    = 
08-31 15:26:52.010  3947  3963 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 15:26:52.010  3947  3960 D bt_stack_manager: event_start_up_stack finished
08-31 15:26:52.012  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-31 15:26:52.013  3947  3959 D BluetoothAdapterProperties: Setting state to 15
,08-31 15:26:52.013  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 15:26:52.014  3947  3967 I bt_vendor: low_power_mode_cb
08-31 15:26:52.014  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:52.015  3947  3959 I BluetoothAdapterState: Entering BleOnState
08-31 15:26:52.020  3947  3959 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 15:26:52.020  3947  3959 D BluetoothAdapterProperties: Setting state to 11
,08-31 15:26:52.020  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 15:26:52.027  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:52.030  3947  3947 D HeadsetService: Received start request. Starting profile...
,08-31 15:26:52.036  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:52.038  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:52.040  3947  3959 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:26:52.041  3947  3947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:26:52.042  3947  3947 D HeadsetStateMachine: make
,08-31 15:26:52.050  3947  3947 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:26:52.050  3947  3947 I bt_bluedroid: get_profile_interface handsfree
08-31 15:26:52.050  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 15:26:52.051  3947  3963 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 15:26:52.054  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:52.055  3947  3947 D A2dpService: Received start request. Starting profile...
08-31 15:26:52.056  3947  3947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:26:52.056  3947  3947 I bt_bluedroid: get_profile_interface avrcp
,08-31 15:26:52.063  3947  3947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:26:52.063  3947  3947 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:26:52.063  3947  3947 D A2dpStateMachine: make
,08-31 15:26:52.065  3947  3947 I bt_bluedroid: get_profile_interface a2dp
,08-31 15:26:52.065  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 15:26:52.067  3947  3977 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:26:52.068  3947  3947 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 15:26:52.069  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:52.069  3947  3947 D HidService: Received start request. Starting profile...
,08-31 15:26:52.069  3947  3947 I bt_bluedroid: get_profile_interface hidhost
08-31 15:26:52.070  3947  3947 D HidService: setHidService(): set to: null
08-31 15:26:52.070  3947  3963 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
08-31 15:26:52.070  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 15:26:52.070  3947  3947 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 15:26:52.071  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
08-31 15:26:52.072  3947  3947 D HealthService: Received start request. Starting profile...
,08-31 15:26:52.073  3947  3947 I bt_bluedroid: get_profile_interface health
,08-31 15:26:52.074  3947  3947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:26:52.075  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
08-31 15:26:52.075  3947  3947 D PanService: Received start request. Starting profile...
08-31 15:26:52.075  3947  3947 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 15:26:52.076  3947  3947 I bt_bluedroid: get_profile_interface pan
08-31 15:26:52.076  3947  3963 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 15:26:52.079  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b0adf5
,08-31 15:26:52.080  3947  3947 D BluetoothMapService: Received start request. Starting profile...
08-31 15:26:52.080  3947  3947 D BluetoothMapService: start()
,08-31 15:26:52.083  3947  3947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 15:26:52.084  3947  3947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 15:26:52.084  3947  3947 D BluetoothMapAppObserver: createReceiver()
,08-31 15:26:52.085  3947  3947 D BluetoothMapAppObserver: initObservers()
,08-31 15:26:52.085  3947  3947 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 15:26:52.095  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:52.097  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:52.097  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:52.097  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.097  3947  3975 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:26:52.097  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.099  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.100  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:52.101  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:52.101  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-31 15:26:52.101  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:52.101  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:52.101  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 15:26:52.101  3947  3959 D BluetoothAdapterProperties: ScanMode =  20
,08-31 15:26:52.101  3947  3959 D BluetoothAdapterProperties: State =  11
,08-31 15:26:52.107  3947  3963 D BluetoothAdapterProperties: Scan Mode:21
,08-31 15:26:52.107  3947  3959 D BluetoothAdapterProperties: Setting state to 12
,08-31 15:26:52.107  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 15:26:52.107  3947  3963 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:26:52.108   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:26:52.109  3947  3959 I BluetoothAdapterState: Entering OnState
08-31 15:26:52.110  3583  3595 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:26:52.110   873   873 D BluetoothA2dp: Proxy object connected
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:52.111  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:52.112  3947  3947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 15:26:52.113  3583  3596 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:26:52.113  3947  3947 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 15:26:52.113  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:26:52.115  1982  1993 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:52.116  3947  3947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:26:52.117  3583  3595 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:52.117  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:52.118  3947  3947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:26:52.120  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:52.120  3947  3947 D ObexServerSockets: Succeed to create listening sockets 
,08-31 15:26:52.120  3947  3947 D ObexServerSockets0: startAccept()
08-31 15:26:52.121   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:26:52.122  3583  3596 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:26:52.122  3947  3947 D ObexServerSockets0: prepareForNewConnect()
08-31 15:26:52.125  3947  3947 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 15:26:52.125  3947  3947 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 15:26:52.125  1367  1389 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:26:52.126  3947  3985 D ObexServerSockets0: Accepting socket connection...
,08-31 15:26:52.127  1367  1367 D BluetoothA2dp: Proxy object connected
08-31 15:26:52.127  1367  2081 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:52.126  3583  3583 D BluetoothA2dp: Proxy object connected
08-31 15:26:52.128   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:52.128  3583  3595 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:26:52.128  3947  3987 D ObexServerSockets0: Accepting socket connection...
,08-31 15:26:52.132  1367  2079 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:26:52.133  3583  3583 D BluetoothInputDevice: Proxy object connected
08-31 15:26:52.133  3583  3583 D HidProfile: Bluetooth service connected
,08-31 15:26:52.134  1367  1389 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:26:52.135  1367  1367 D BluetoothMap: Proxy object connected
,08-31 15:26:52.135  3583  3986 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:52.136  1367  1367 D MapProfile: Bluetooth service connected
08-31 15:26:52.136  1367  1367 D BluetoothMap: getConnectedDevices()
08-31 15:26:52.135  3583  3583 D BluetoothMap: Proxy object connected
08-31 15:26:52.136  3583  3583 D MapProfile: Bluetooth service connected
08-31 15:26:52.136  3583  3583 D BluetoothMap: getConnectedDevices()
,08-31 15:26:52.136  1367  2081 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:26:52.138  1367  1367 D BluetoothInputDevice: Proxy object connected
08-31 15:26:52.138  1367  1367 D HidProfile: Bluetooth service connected
08-31 15:26:52.138   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:26:52.138  1367  1389 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:26:52.138  3583  3583 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:26:52.139  3583  3583 D PanProfile: Bluetooth service connected
08-31 15:26:52.140  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:26:52.140  1367  1367 D PanProfile: Bluetooth service connected
08-31 15:26:52.141   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 15:26:52.142  3947  3947 D BluetoothMapService: onReceive
08-31 15:26:52.142  3947  3947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:26:52.142  3947  3947 D BluetoothMapService: STATE_ON
,08-31 15:26:52.143  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:52.145  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:52.152  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:26:52.157  3583  3583 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:26:52.159  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:52.169  1367  1367 D BluetoothPbap: Proxy object connected
,08-31 15:26:52.169  3947  3947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 15:26:52.169  1367  1367 D PbapServerProfile: Bluetooth service connected
08-31 15:26:52.169  3947  3947 D ObexServerSockets0: prepareForNewConnect()
08-31 15:26:52.170  3583  3583 D BluetoothPbap: Proxy object connected
08-31 15:26:52.170  3583  3583 D PbapServerProfile: Bluetooth service connected
,08-31 15:26:52.178  3947  3992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:26:52.198  3947  3996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:26:52.200  3947  3996 I BtOppRfcommListener: Accept thread started.
,08-31 15:26:52.218  1367  1389 D BluetoothHeadset: Proxy object connected
,08-31 15:26:52.218  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-31 15:26:52.218   873   873 D BluetoothHeadset: Proxy object connected
08-31 15:26:52.218   873   873 D BluetoothHeadset: Proxy object connected
08-31 15:26:52.219  3583  3596 D BluetoothHeadset: Proxy object connected
,08-31 15:26:52.220   873   873 D BluetoothHeadset: Proxy object connected
08-31 15:26:52.220  3583  3583 D HeadsetProfile: Bluetooth service connected
08-31 15:26:52.220  1982  1994 D BluetoothHeadset: Proxy object connected
,08-31 15:26:52.221   873   890 D BluetoothHeadset: Proxy object connected
,08-31 15:26:52.227  1367  2081 D BluetoothHeadset: Proxy object connected
,08-31 15:26:52.228   873   890 D BluetoothHeadset: Proxy object connected
08-31 15:26:52.228  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-31 15:26:52.237  3583  3986 D BluetoothHeadset: Proxy object connected
08-31 15:26:52.237  3583  3583 D HeadsetProfile: Bluetooth service connected
,08-31 15:26:52.238   873   890 D BluetoothHeadset: Proxy object connected
,08-31 15:26:53.545  3477  3524 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:26:53.545  3477  3524 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:26:53.809  2726  2737 D Finsky  : [173] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-31 15:26:53.827  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:53.839  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:53.842  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:53.884  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:26:53.884  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:26:53.884  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:26:53.884  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:53.911  2726  2737 D Finsky  : [173] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-31 15:26:53.986  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:26:54.027  1506  3712 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:26:54.028  1506  3712 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:26:54.028  1506  3712 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:26:54.028  1506  3712 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:26:54.068  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:26:54.069  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 15:26:54.069  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-31 15:26:56.552  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:26:56.553  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51f224a added. We now have 6 listener(s)
,08-31 15:26:56.553  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:26:56.560  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:26:56.561  3477  3524 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f055bb added. We now have 7 listener(s)
08-31 15:26:56.561  3477  3524 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:26:56.565  3477  3524 I System.out: IsBluetoothEnabled
,08-31 15:26:56.579  3947  3959 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 15:26:56.580  3947  3959 D BluetoothAdapterProperties: Setting state to 13
,08-31 15:26:56.580  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:26:56.582  3947  3959 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:26:56.586  3947  3959 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:26:56.597  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:56.598  3477  3524 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:26:56.600  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:26:56.600  3477  3477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:26:56.600  3947  3947 D BluetoothMapService: onReceive
08-31 15:26:56.601  3947  3947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:26:56.601  3947  3947 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:26:56.602  3477  3524 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:56.602  3477  3524 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:56.602  3947  3947 D BluetoothMapService: MAP Service closeService in
08-31 15:26:56.603  3947  3947 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 15:26:56.603  3947  3947 D ObexServerSockets0: shutdown(block = true)
08-31 15:26:56.603  3477  3477 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:26:56.604  3477  3477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:26:56.604  3947  3985 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 15:26:56.607  3947  3947 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:26:56.607  3947  3972 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-31 15:26:56.607  3947  3987 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 15:26:56.607  3947  3947 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:26:56.608  3947  3963 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:26:56.608  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 15:26:56.611  3947  3947 I BtOppRfcommListener: stopping Accept Thread
08-31 15:26:56.611  3947  3996 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:26:56.612  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:56.613  3947  3996 I BtOppRfcommListener: BluetoothSocket listen thread finished,
08-31 15:26:56.615  3947  3947 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:26:56.617  1367  1379 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:56.617   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:56.617   873   873 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:56.617  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:26:56.617  3583  3986 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:56.617  3947  3947 D A2dpService: Received stop request...Stopping profile...
08-31 15:26:56.618   873   873 D BluetoothHeadset: Proxy object disconnected
,08-31 15:26:56.618  1982  2278 D BluetoothHeadset: Proxy object disconnected
08-31 15:26:56.618  3947  3977 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:26:56.620   873   873 D BluetoothA2dp: Proxy object disconnected
,08-31 15:26:56.620  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-31 15:26:56.621  3947  3947 D HidService: Received stop request...Stopping profile...
08-31 15:26:56.621  3947  3947 D HidService: Stopping Bluetooth HidService
08-31 15:26:56.621  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-31 15:26:56.622  3947  3959 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-31 15:26:56.622  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-31 15:26:56.622  1367  1367 D HidProfile: Bluetooth service disconnected
,08-31 15:26:56.623  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:26:56.624  3947  3947 D HealthService: Received stop request...Stopping profile...
08-31 15:26:56.625  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:56.625  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:56.625  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:56.625  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:56.627  3583  3583 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:26:56.628  3583  3583 D BluetoothA2dp: Proxy object disconnected
,08-31 15:26:56.628  3947  3947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:26:56.628  3947  3947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 15:26:56.628  3583  3583 D BluetoothInputDevice: Proxy object disconnected
,08-31 15:26:56.628  3583  3583 D HidProfile: Bluetooth service disconnected
,08-31 15:26:56.628  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 15:26:56.628  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:56.628  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:56.628  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:56.629  3947  3947 D PanService: Received stop request...Stopping profile...
,08-31 15:26:56.629  3947  3963 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-31 15:26:56.630  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:26:56.630  1367  1367 D PanProfile: Bluetooth service disconnected
,08-31 15:26:56.630  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:56.630  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:56.630  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:26:56.630  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:56.631  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-31 15:26:56.632  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:56.632  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:26:56.632  3947  3969 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 15:26:56.632  3947  3969 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 15:26:56.632  3947  3969 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:26:56.632  3947  3969 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:26:56.632  3947  3947 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:26:56.633  3947  3947 D BluetoothMapService: stop()
08-31 15:26:56.633  3947  3947 D BluetoothMapAppObserver: deinitObservers()
,08-31 15:26:56.633  3947  3947 D BluetoothMapAppObserver: removeReceiver()
08-31 15:26:56.635  1367  1367 D BluetoothMap: Proxy object disconnected
08-31 15:26:56.635  1367  1367 D MapProfile: Bluetooth service disconnected
08-31 15:26:56.635  3947  3947 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:56.636  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:56.636  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:56.636  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:56.636  3947  3947 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:26:56.636  3947  3963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 15:26:56.636  3947  3947 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:26:56.637  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-31 15:26:56.637  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:56.637  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:56.637  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:26:56.637  3947  3947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:26:56.637  3947  3963 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 15:26:56.638  3947  3947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:26:56.640  3947  3947 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:56.640  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-31 15:26:56.640  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:56.640  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:56.640  3947  3947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:26:56.640  3947  3947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:26:56.641  3947  3947 D BluetoothMapService: MAP Service closeService in
08-31 15:26:56.641  3947  3947 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:26:56.642  3947  3947 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:26:56.642  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:26:56.642  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:26:56.642  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 15:26:56.642  3947  3947 D BluetoothMapService: cleanup()
08-31 15:26:56.642  3947  3959 D BluetoothAdapterProperties: Setting state to 15
08-31 15:26:56.642  3947  3947 D BluetoothMapService: MAP Service closeService in
08-31 15:26:56.642  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 15:26:56.643  3947  3959 I BluetoothAdapterState: Entering BleOnState
08-31 15:26:56.643   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:26:56.643  3947  3959 D BluetoothAdapterState: Current state: BLE ON, message: 0
,08-31 15:26:56.643  3583  3596 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:26:56.644  3583  3986 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:26:56.644  1367  1367 D BluetoothPbap: Proxy object disconnected
08-31 15:26:56.644  1367  1367 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:26:56.645  1982  1993 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:26:56.645  3583  3595 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:26:56.646   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:56.646  3583  3596 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:26:56.647  1367  1389 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:26:56.647  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:56.647  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:56.647   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:56.652  3583  3986 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:26:56.657  3583  3583 D DockEventReceiver: finishStartingService: stopping service
08-31 15:26:56.657  1367  2079 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:26:56.658  1367  2081 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:26:56.658  3583  3596 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:56.659  1367  1389 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:26:56.660   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:26:56.661  1367  1379 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:26:56.661  3947  3959 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 15:26:56.661  3947  3959 D BluetoothAdapterProperties: Setting state to 16
08-31 15:26:56.661  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 15:26:56.662  3947  3959 D BluetoothAdapterProperties: onBleDisable
,08-31 15:26:56.662  3947  3959 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:26:56.663  3947  3960 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 15:26:56.663  3947  3969 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 15:26:56.663  3947  3969 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:26:56.664  3947  3963 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:26:56.667  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:56.668  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:26:56.668  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:26:56.674  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:56.678  3583  3583 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:26:56.865  3947  3963 I bt_hci  : shut_down
,08-31 15:26:56.873  3947  3967 D bt_hwcfg: hw_epilog_process
,08-31 15:26:56.873  3947  3967 I bt_vendor: low_power_mode_cb
,08-31 15:26:56.890  3947  3967 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-31 15:26:56.890  3947  3967 I bt_vendor: epilog_cb
08-31 15:26:56.890  3947  3967 I bt_hci  : epilog_finished_callback
,08-31 15:26:56.896  3947  3963 I bt_hci_h4: hal_close
,08-31 15:26:56.898  3947  3963 I bt_userial_vendor: device fd = 51 close
,08-31 15:26:57.027  3947  3960 D bt_stack_manager: event_shut_down_stack finished.
,08-31 15:26:57.028  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 15:26:57.034  3947  3947 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:26:57.034  3947  3959 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 15:26:57.036  3947  3947 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 15:26:57.036  3947  3947 D BtGatt.GattService: stop()
08-31 15:26:57.036  3947  3947 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 15:26:57.041  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-31 15:26:57.041  3947  3947 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:26:57.041  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:26:57.042  3947  3947 V BluetoothAdapterState: isBleTurningOff()=true
,08-31 15:26:57.043  3947  3959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 15:26:57.044  3947  3959 D BluetoothAdapterProperties: Setting state to 10
08-31 15:26:57.044  3947  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 15:26:57.048  3947  3959 I BluetoothAdapterState: Entering OffState
,08-31 15:26:57.056  3477  3477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:26:57.068  3583  3583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:26:57.080  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:26:57.083  3583  3583 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:27:19.990  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:27:19.999  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:27:20.004  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:27:20.080  1506  2812 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:27:20.080  1506  2812 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:27:20.080  1506  2812 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:27:20.080  1506  2812 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:27:20.101  2726  2726 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 15:27:20.102  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 15:27:20.102  2726  2726 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-31 15:27:26.329  1894  1956 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-31 15:27:26.329  1894  1956 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-31 15:27:26.368  1506  1506 I ConfigService: onCreate
,08-31 15:27:31.441  1506  1506 I ConfigService: onDestroy
,08-31 15:27:44.799   873  1310 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 15:28:54.068  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:28:54.078  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:28:54.085  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:28:54.144  1506  3712 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:28:54.144  1506  3712 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:28:54.145  1506  3712 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:28:54.145  1506  3712 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:28:54.179  1506  3712 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:28:54.179  1506  3712 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:28:54.189  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:28:54.189  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:28:54.189  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:28:54.189  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:28:54.189  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:28:54.189  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:28:54.189  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:33:54.363  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:33:54.382  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:33:54.384  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:33:54.440  1506  2812 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-31 15:33:54.440  1506  2812 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-31 15:33:54.440  1506  2812 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:33:54.440  1506  2812 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:33:54.473  1506  2812 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:33:54.473  1506  2812 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:33:54.482  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:33:54.482  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:33:54.482  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:33:54.482  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:33:54.482  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:33:54.482  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:33:54.482  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:38:54.626  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:38:54.649  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:38:54.658  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:38:54.761  1506  2812 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:38:54.762  1506  2812 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:38:54.762  1506  2812 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:38:54.763  1506  2812 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:38:54.814  1506  2812 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:38:54.814  1506  2812 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:38:54.826  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:38:54.826  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:38:54.826  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:38:54.826  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:38:54.826  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:38:54.826  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:38:54.826  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:43:41.562   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-31 15:43:54.966  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:43:54.980  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:43:54.982  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:43:55.038  1506  2812 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:43:55.039  1506  2812 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:43:55.039  1506  2812 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:43:55.040  1506  2812 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:43:55.067  1506  2812 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:43:55.067  1506  2812 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:43:55.077  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:43:55.077  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:43:55.077  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:43:55.077  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:43:55.077  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:43:55.077  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:43:55.077  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:48:55.211  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:48:55.227  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:48:55.232  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:48:55.315  1506  3712 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:48:55.316  1506  3712 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 15:48:55.316  1506  3712 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:48:55.319  1506  3712 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:48:55.357  1506  3712 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:48:55.357  1506  3712 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:48:55.369  2726  2755 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 15:48:55.369  2726  2755 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:48:55.369  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:48:55.369  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:48:55.369  2726  2755 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:48:55.369  2726  2755 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:48:55.369  2726  2755 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-31 15:49:56.629  4097  4097 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 15:49:56.634  4097  4097 D AndroidRuntime: CheckJNI is OFF
08-31 15:49:56.670  4097  4097 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 15:49:56.711  4097  4097 I Radio-JNI: register_android_hardware_Radio DONE
08-31 15:49:56.731  4097  4097 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 15:49:56.744   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-31 15:49:56.745   873   886 I ActivityManager: Killing 3477:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-31 15:49:56.834   873  1377 D GraphicsStats: Buffer count: 2
08-31 15:49:56.835   873  1681 I WindowState: WIN DEATH: Window{991de62 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:49:56.835   873  1309 D WifiService: Client connection lost with reason: 4
08-31 15:49:56.875   873   896 W PackageSettings: Skipping PackageSetting{d3b3d4e com.example.hello/10273} due to missing metadata
08-31 15:49:56.911   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-31 15:49:56.911   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 15:49:56.913   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-31 15:49:56.913   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 15:49:56.913   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:56.913   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:56.913   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:56.913   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 15:49:56.914   873   896 I art     : Starting a blocking GC Explicit
08-31 15:49:56.916   873   886 I ActivityManager:   Force finishing activity ActivityRecord{7eac26f u0 com.test.thalitest/.MainActivity t2}
08-31 15:49:56.944   873   883 W ActivityManager: Spurious death for ProcessRecord{e9c01cd 0:com.test.thalitest/u0a0}, curProc for 3477: null
08-31 15:49:56.976   873   896 I art     : Explicit concurrent mark sweep GC freed 36632(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 800us total 61.121ms
08-31 15:49:57.027   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-31 15:49:57.030  4097  4097 I art     : System.exit called, status: 0
08-31 15:49:57.030  4097  4097 I AndroidRuntime: VM exiting with result code 0.
08-31 15:49:57.033   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-31 15:49:57.059   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-31 15:49:57.077  1860  2172 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 15:49:57.079  1894  1894 I Keyboard.Facilitator: resetDictionaries() : en_US
08-31 15:49:57.080   873  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 15:49:57.083  3337  3337 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-31 15:49:57.093  1894  4112 I Keyboard.Facilitator.DecoderInitializer: run()
08-31 15:49:57.097  1982  1982 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-31 15:49:57.101   873  1682 I ActivityManager: Start proc 4115:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-31 15:49:57.118  1894  4112 I Decoder : createOrResetDecoder
08-31 15:49:57.160  1506  1506 I ConfigService: onCreate
08-31 15:49:57.165   873  2030 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3477 uid 10000
08-31 15:49:57.166  1894  1894 I Keyboard.Facilitator: onFinishInput()
08-31 15:49:57.169  4115  4115 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-31 15:49:57.170   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 15:49:57.171  1506  4127 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 15:49:57.173  1506  4127 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:49:57.179  1506  4127 W SQLiteOpenHelper: Opened config.db in read-only mode
08-31 15:49:57.192  1894  4112 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-31 15:49:57.194   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-31 15:49:57.194   873   885 E PackageManager: Failed to write settings, restoring backup
08-31 15:49:57.194   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 15:49:57.194   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 15:49:57.194   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 15:49:57.194   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 15:49:57.194   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 15:49:57.194   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.194   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.194   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.201   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-31 15:49:57.201   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 15:49:57.201   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:49:57.201   873   886 E DropBoxManagerService: 	... 13 more
08-31 15:49:57.204  1996  2091 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-31 15:49:57.217   873  1377 I ActivityManager: Start proc 4128:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-31 15:49:57.217  1996  2091 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 15:49:57.217  1996  2091 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1996
08-31 15:49:57.217  1996  2091 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.217  1996  2091 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.220   873  1683 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 15:49:57.225  1996  2091 I Process : Sending signal. PID: 1996 SIG: 9
08-31 15:49:57.227   873  4136 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:49:57.227   873  4136 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:49:57.227   873  4136 E DropBoxManagerService: 	... 5 more
08-31 15:49:57.236  1894  4112 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-31 15:49:57.237  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 15:49:57.237  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-31 15:49:57.239  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 15:49:57.239  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 15:49:57.240  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-31 15:49:57.240  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 15:49:57.242  1894  4112 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 15:49:57.242  1894  4112 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 15:49:57.242  1894  4112 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 15:49:57.242  1894  4112 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-31 15:49:57.242  1894  4112 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 15:49:57.243  1894  4112 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-31 15:49:57.264  4115  4115 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-31 15:49:57.280  4115  4147 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 15:49:57.284   873  1683 I ActivityManager: Start proc 4148:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-31 15:49:57.312   873  2030 D GraphicsStats: Buffer count: 1
08-31 15:49:57.312   873  2027 I WindowState: WIN DEATH: Window{3610dde u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.320  4115  4144 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.321  4115  4144 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.323   873  2030 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1996) has died
08-31 15:49:57.323   873  2030 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-31 15:49:57.326   873  2030 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-31 15:49:57.346   873   884 I ActivityManager: Start proc 4162:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 15:49:57.366  1698  4161 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 15:49:57.367  1698  4161 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 15:49:57.372  4148  4148 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-31 15:49:57.396  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-31 15:49:57.398  1506  1506 D AndroidRuntime: Shutting down VM
08-31 15:49:57.399  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
08-31 15:49:57.399  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
08-31 15:49:57.399  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 15:49:57.399  1506  1506 E AndroidRuntime: 	... 8 more
08-31 15:49:57.402   873  4177 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:49:57.402   873  4177 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:49:57.402   873  4177 E DropBoxManagerService: 	... 5 more
08-31 15:49:57.404   873   883 I ActivityManager: Killing 2052:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:49:57.408  4162  4162 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:49:57.408  4162  4162 D AndroidRuntime: Shutting down VM
08-31 15:49:57.402  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
08-31 15:49:57.432  4115  4144 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.441  4115  4147 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 15:49:57.442  4115  4147 E AndroidRuntime: Process: android.process.acore, PID: 4115
08-31 15:49:57.442  4115  4147 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.442  4115  4147 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:49:57.444  4115  4144 I Process : Sending signal. PID: 4115 SIG: 9
08-31 15:49:57.470   873  1309 D WifiService: Client connection lost with reason: 4
08-31 15:49:57.470   873  1309 D WifiService: Client connection lost with reason: 4
08-31 15:49:57.477   873  1377 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
08-31 15:49:57.477   873  1377 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-31 15:49:57.477   873  1377 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-31 15:49:57.477   873  1377 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-31 15:49:57.485  1698  1698 W RocketImpressions: ClearcutLogger connection suspended: 1
08-31 15:49:57.491  4162  4162 E AndroidRuntime: FATAL EXCEPTION: main
08-31 15:49:57.491  4162  4162 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4162
08-31 15:49:57.491  4162  4162 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 15:49:57.491  4162  4162 E AndroidRuntime: 	... 10 more
08-31 15:49:57.492   873  4178 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:49:57.492   873  4178 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:49:57.492   873  4178 E DropBoxManagerService: 	... 5 more
08-31 15:49:57.520   873  2030 I ActivityManager: Start proc 4182:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-31 15:49:57.522   873  4187 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:49:57.522   873  4187 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:49:57.522   873  4187 E DropBoxManagerService: 	... 5 more
08-31 15:49:57.523   873  1683 I ActivityManager: Process android.process.acore (pid 4115) has died

```
