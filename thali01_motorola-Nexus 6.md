#### Test 822030605965752_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-24 14:19:45.301  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:19:45.324  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:19:45.331  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:19:45.414  1508  2179 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 14:19:45.414  1508  2179 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 14:19:45.415  1508  2179 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:19:45.415  1508  2179 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 14:19:45.476  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 14:19:45.476  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 14:19:45.476  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-24 14:19:45.976  3819  3819 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 14:19:45.980  3819  3819 D AndroidRuntime: CheckJNI is OFF
08-24 14:19:46.015  3819  3819 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 14:19:46.059  3819  3819 I Radio-JNI: register_android_hardware_Radio DONE
08-24 14:19:46.078  3819  3819 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:19:46.082   871  1969 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:19:46.120   871  1969 I ActivityManager: Start proc 3829:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 14:19:46.132  3819  3819 D AndroidRuntime: Shutting down VM
08-24 14:19:46.273  3829  3829 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 14:19:46.294  3829  3829 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 14:19:46.301  3829  3829 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2669-2672)
08-24 14:19:46.302  3829  3829 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:19:46.316  3829  3829 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e745390}
08-24 14:19:46.316  3829  3829 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:19:46.317  3829  3829 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:19:46.324  3829  3829 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 14:19:46.325  3829  3829 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 14:19:46.345  3829  3829 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 14:19:46.360  3829  3829 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:19:46.360  3829  3829 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:19:46.360  3829  3829 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:19:46.360  3829  3829 I Adreno  : Build Date                       : 10/20/15
08-24 14:19:46.360  3829  3829 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:19:46.360  3829  3829 I Adreno  : Local Branch                     : M14
08-24 14:19:46.360  3829  3829 I Adreno  : Remote Branch                    : 
08-24 14:19:46.360  3829  3829 I Adreno  : Remote Branch                    : 
08-24 14:19:46.360  3829  3829 I Adreno  : Reconstruct Branch               : 
,08-24 14:19:46.409   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44facc8:true
,08-24 14:19:46.453  3829  3829 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:19:46.469  3829  3829 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 14:19:46.557  3829  3869 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 14:19:46.572  3829  3855 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 14:19:46.618  3829  3869 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 14:19:46.646  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-24 14:19:46.717   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +490ms (total +609ms)
,08-24 14:19:46.809  3829  3829 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3829
,08-24 14:19:47.010  3829  3829 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:19:47.186  3829  3871 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681983184
,08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 14:19:47.195  3829  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9fe67 added. We now have 1 listener(s)
,08-24 14:19:47.199  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-24 14:19:47.200  3829  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:19:47.201  3829  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:19:47.202  3829  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 14:19:47.207  3829  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3aab2 added. We now have 1 listener(s)
08-24 14:19:47.208  3829  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:47.217   871  1305 D WifiService: New client listening to asynchronous messages
08-24 14:19:47.221  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:19:47.221  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 14:19:47.223  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-24 14:19:47.226  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:19:47.228  3829  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 14:19:47.237  3829  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:19:47.237  3829  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 14:19:47.252  3829  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:47.253  3829  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:19:47.254  3829  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 14:19:47.254  3829  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:19:47.257  3829  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:19:47.260  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:19:47.262  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:19:47.288  3829  3829 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:19:48.040  3829  3877 W jxcore-log: Initializing JXcore engine
,08-24 14:19:48.040  3829  3877 W jxcore-log: JXcore engine is ready
,08-24 14:19:48.078  3877  3877 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-24 14:19:48.078  3877  3877 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11550]" dev="sockfs" ino=11550 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 14:19:48.078  3877  3877 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 14:19:48.078  3877  3877 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25096]" dev="sockfs" ino=25096 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 14:19:48.091  3829  3877 W jxcore-log: Starting JXcore engine
,08-24 14:19:48.172  3829  3877 W jxcore-log: Platform android
08-24 14:19:48.172  3829  3877 W jxcore-log: 
08-24 14:19:48.172  3829  3877 W jxcore-log: Process ARCH arm
08-24 14:19:48.172  3829  3877 W jxcore-log: 
,08-24 14:19:48.366  3829  3877 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:19:48.366  3829  3877 I jxcore-log: 
08-24 14:19:48.366  3829  3877 W jxcore-log: JXcore engine is started
,08-24 14:19:48.378  3829  3871 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:19:48.394  3829  3829 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:19:58.016  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 14:19:58.016  3829  3877 I jxcore-log: 
,08-24 14:19:58.018  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 14:19:58.018  3829  3877 I jxcore-log: 
,08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.030  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:19:58.037  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:19:58.039  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 14:19:58.039  3829  3877 I jxcore-log: 
,08-24 14:19:58.041  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 14:19:58.041  3829  3877 I jxcore-log: 
,08-24 14:19:58.529  3829  3877 D ExecuteNativeTests: Running unit tests
,08-24 14:19:58.587  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:19:58.587  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 added. We now have 2 listener(s)
,08-24 14:19:58.588  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:19:58.589  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:19:58.589  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:19:58.589  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:19:58.589  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 added. We now have 2 listener(s)
,08-24 14:19:58.589  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:58.590  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:19:58.596  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.605  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:19:58.608  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:19:58.609  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:19:58.611  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 14:19:58.611  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 14:19:58.611  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 14:19:58.612  3829  3877 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 14:19:58.613  3829  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:19:58.613  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 14:19:58.613  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:19:58.613  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 14:19:58.613  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.614  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.614  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.614  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.614  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.614  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.614  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:19:58.614  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 removed from the list
08-24 14:19:58.614  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.614  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 removed from the list
,08-24 14:19:58.615  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.619  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:19:58.619  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:19:58.619  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:19:58.622  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.623  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.624  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:19:58.624  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.624  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.624  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.626  3829  3877 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-24 14:19:58.627  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.627  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.627  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:19:58.628  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.628  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:19:58.628  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:19:58.628  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
,08-24 14:19:58.628  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.628  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.628  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:19:58.628  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.628  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.628  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:19:58.628  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.629  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:19:58.629  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.629  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.629  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
,08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 14:19:58.635  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:19:58.636  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:19:58.637  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.637  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.637  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.637  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.637  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.637  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:19:58.637  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.637  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.637  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.637  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.637  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.637  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.637  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.637  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:19:58.638  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.638  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.638  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.639  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.639  3829  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:19:58.640  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.645  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:19:58.647  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.648  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:19:58.648  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:19:58.648  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:19:58.648  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:19:58.648  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.649  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:19:58.650  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.652  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:19:58.652  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:19:58.652  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.657  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:19:58.660  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:19:58.660  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:19:58.663  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-24 14:19:58.667  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-24 14:19:58.667  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:19:58.668  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:19:58.668  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:19:58.669  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.673  2690  2881 D BtGatt.GattService: registerClient() - UUID=95950c52-e6cd-4bf9-80fc-fd30158633e9
08-24 14:19:58.674  2690  2746 D BtGatt.GattService: onClientRegistered() - UUID=95950c52-e6cd-4bf9-80fc-fd30158633e9, clientIf=5
08-24 14:19:58.674  3829  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:19:58.675  2690  2702 D BtGatt.GattService: start scan with filters
08-24 14:19:58.678  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:19:58.678  2690  2751 D BtGatt.ScanManager: handling starting scan
08-24 14:19:58.679  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:19:58.679  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:19:58.679  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 14:19:58.681  2690  2751 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:19:58.682  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.682  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-24 14:19:58.682  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.683  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 14:19:58.687  3829  3877 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:19:58.688  2690  2746 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:19:58.688  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.689  2690  2751 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:19:58.692  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.693  3829  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:19:58.693  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.693  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:19:58.693  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.693  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:19:58.693  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:19:58.693  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:19:58.693  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:19:58.693  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:19:58.694  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:19:58.694  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:19:58.694  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:19:58.694  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.694  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.695  2690  2751 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:19:58.695  2690  2701 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:19:58.695  2690  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:19:58.696  2690  2889 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:19:58.696  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:19:58.696  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:19:58.696  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:19:58.696  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:19:58.696  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:19:58.697  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.698  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:19:58.698  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:19:58.698  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:19:58.699  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.700  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.700  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.700  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.700  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.700  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.700  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.700  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.700  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.700  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.700  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.700  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.701  3829  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:19:58.702  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.705  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:19:58.706  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.706  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:19:58.706  2690  2746 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:19:58.706  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.708  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.708  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:19:58.708  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:19:58.708  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:19:58.708  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.708  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:19:58.711  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:19:58.711  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:19:58.712  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.712  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:19:58.712  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.714  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:19:58.716  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:19:58.716  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:19:58.719  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:19:58.719  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.719  2690  2751 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:19:58.720  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:19:58.720  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:19:58.720  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:19:58.720  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.722  2690  2701 D BtGatt.GattService: registerClient() - UUID=1e0eeac4-a48b-4a7a-9f72-cccc061ad428,
08-24 14:19:58.722  2690  2746 D BtGatt.GattService: onClientRegistered() - UUID=1e0eeac4-a48b-4a7a-9f72-cccc061ad428, clientIf=5
08-24 14:19:58.722  3829  3839 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:19:58.723  2690  2889 D BtGatt.GattService: start scan with filters
08-24 14:19:58.725  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:19:58.725  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.725  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:19:58.725  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:19:58.725  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:19:58.725  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 14:19:58.726  2690  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:19:58.727  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.727  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:19:58.727  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.728  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 14:19:58.730  3829  3877 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:19:58.731  2690  2746 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:19:58.731  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.731  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.731  3829  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:19:58.732  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.732  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:19:58.732  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.732  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:19:58.732  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:19:58.732  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:19:58.732  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:19:58.732  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:19:58.732  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:19:58.732  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:19:58.733  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.733  2690  2751 D BtGatt.ScanManager: handling starting scan
08-24 14:19:58.733  2690  2701 D BtGatt.GattService: stopScan() - queue size =0
08-24 14:19:58.734  2690  2889 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:19:58.734  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:19:58.734  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:19:58.734  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:19:58.734  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:19:58.734  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:19:58.735  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.735  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:19:58.735  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:19:58.735  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:19:58.735  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.736  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.736  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.736  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.736  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.736  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.736  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.736  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.736  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.736  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.736  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.736  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.737  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.737  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.737  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.737  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.737  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.737  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.738  3829  3877 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:19:58.739  2690  2746 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:19:58.739  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.739  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.739  2690  2751 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.743  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:19:58.744  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:19:58.744  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.744  2690  2751 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:19:58.744  2690  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:19:58.745  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.746  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:19:58.748  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.748  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:19:58.748  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:19:58.748  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:19:58.749  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.749  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:19:58.750  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.752  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:19:58.752  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:19:58.754  2690  2746 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:19:58.754  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.757  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:19:58.758  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:19:58.758  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:19:58.760  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 14:19:58.760  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.761  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:19:58.761  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:19:58.761  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:19:58.762  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.764  2690  2701 D BtGatt.GattService: registerClient() - UUID=4455a42d-516e-4836-b1be-b5fd628610de
08-24 14:19:58.764  2690  2746 D BtGatt.GattService: onClientRegistered() - UUID=4455a42d-516e-4836-b1be-b5fd628610de, clientIf=5
08-24 14:19:58.764  3829  3841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:19:58.764  2690  2881 D BtGatt.GattService: start scan with filters
08-24 14:19:58.765  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:19:58.765  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.765  2690  2751 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:19:58.768  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:19:58.768  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:19:58.768  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:19:58.768  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 14:19:58.770  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.770  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:19:58.770  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:19:58.771  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:19:58.771  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.771  2690  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:19:58.772  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 14:19:58.774  3829  3877 I io.jxcore.node.ConnectionHelper: start: OK
08-24 14:19:58.774  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.774  3829  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:19:58.775  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.775  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:19:58.775  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.775  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:19:58.775  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:19:58.775  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:19:58.775  2690  2746 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:19:58.775  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.775  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:19:58.775  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:19:58.775  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:19:58.776  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:19:58.776  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:19:58.776  2690  2751 D BtGatt.ScanManager: handling starting scan
08-24 14:19:58.776  2690  2881 D BtGatt.GattService: stopScan() - queue size =0
08-24 14:19:58.777  2690  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:19:58.777  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:19:58.777  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:19:58.777  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:19:58.778  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:19:58.778  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:19:58.778  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.779  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:19:58.779  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:19:58.779  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:19:58.779  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.780  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.780  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.780  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.780  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.781  3829  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:19:58.781  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.781  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.781  2690  2746 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:19:58.781  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.781  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.781  2690  2751 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 14:19:58.781  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.781  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:19:58.781  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.781  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.781  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.782  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.782  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.782  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.782  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.783  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.783  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.783  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.783  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.784  3829  3877 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 14:19:58.784  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.784  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.784  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.784  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.784  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.784  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.785  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.785  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.785  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.785  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.785  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.785  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:19:58.785  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.785  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.785  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.785  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.786  2690  2751 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:19:58.786  2690  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:19:58.786  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.786  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.786  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.787  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.787  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:19:58.788  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.788  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.788  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.788  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.788  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.788  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.788  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.788  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.788  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.788  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.788  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.789  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.789  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:19:58.789  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.789  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.789  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.790  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.790  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.790  3829  3877 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 14:19:58.790  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.790  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.791  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.791  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.791  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.791  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.791  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.791  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.791  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.791  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.791  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.791  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.791  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.791  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.792  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.792  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.792  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.792  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.793  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 14:19:58.793  2690  2746 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:19:58.793  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.793  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.793  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.793  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.793  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.793  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.793  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.794  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.794  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.794  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.794  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.794  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.794  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.794  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.794  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.795  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.795  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.795  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.795  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.795  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:19:58.796  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:19:58.796  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:19:58.796  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:19:58.796  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:19:58.796  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:19:58.796  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.796  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.796  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.796  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.796  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.797  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.797  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.797  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.797  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.797  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.797  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.797  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.797  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.797  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.798  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.798  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.798  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.798  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.798  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:19:58.798  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.799  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:19:58.799  3829  3877 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:19:58.799  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:19:58.803  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:19:58.803  3829  3877 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:19:58.803  2690  2746 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:19:58.803  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:19:58.803  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:19:58.804  2690  2751 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:19:58.804  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:19:58.805  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:19:58.805  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:19:58.805  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:19:58.805  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:19:58.805  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 14:19:58.805  3829  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:19:58.805  3829  3877 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 14:19:58.805  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:19:58.806  3829  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:19:58.806  3829  3877 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 14:19:58.806  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:19:58.806  3829  3877 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:19:58.806  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 14:19:58.808  2690  2746 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:19:58.808  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.808  2690  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:19:58.809  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 14:19:58.810  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 14:19:58.810  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 14:19:58.810  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 14:19:58.810  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 14:19:58.811  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 14:19:58.811  3829  3877 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:19:58.811  3829  3877 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 14:19:58.811  3829  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-24 14:19:58.811  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.811  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.811  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.812  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.812  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.812  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.813  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 14:19:58.813  3829  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:19:58.813  2690  2746 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:19:58.813  2690  2746 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:19:58.815  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.815  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.815  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.815  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.815  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.815  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.815  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.815  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.815  3829  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-24 14:19:58.815  3829  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-24 14:19:58.816  3829  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-24 14:19:58.816  3829  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-24 14:19:58.816  2690  2878 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-24 14:19:58.817  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.817  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.817  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.817  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.817  3829  3877 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 14:19:58.818  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.818  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.818  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.818  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.818  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.819  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.819  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.819  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.819  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.819  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.819  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.819  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:19:58.819  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.819  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.820  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.820  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.820  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.820  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.820  3829  3877 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 14:19:58.820  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.820  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.820  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.821  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.821  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.821  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.821  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.821  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.821  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.821  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.821  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.821  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.821  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.821  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.822  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.822  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.822  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.822  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.822  3829  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 14:19:58.823  3829  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 14:19:58.823  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:19:58.823  3829  3877 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 14:19:58.823  3829  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:19:58.823  3829  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 14:19:58.823  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:19:58.823  3829  3877 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 14:19:58.823  3829  3877 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:19:58.823  3829  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:19:58.823  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:19:58.823  3829  3877 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 14:19:58.823  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.823  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.823  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.824  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.824  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.824  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.824  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.824  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.824  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.824  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.824  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.824  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.824  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.824  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.825  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.825  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.825  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.825  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.825  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.826  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.826  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.826  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.826  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.826  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.826  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.826  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.826  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.826  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.826  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.826  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.826  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.826  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.826  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.826  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.826  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.826  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.827  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.827  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.827  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.827  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.827  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.827  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.827  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.827  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.827  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.827  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.827  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.828  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.828  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.828  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.828  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.829  3829  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 14:19:58.829  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.830  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 14:19:58.830  3829  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 14:19:58.830  3829  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 14:19:58.831  3829  3829 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 14:19:58.831  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 14:19:58.831  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:19:58.831  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.831  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 14:19:58.831  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 14:19:58.831  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 14:19:58.831  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.831  3829  3877 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 14:19:58.831  3829  3829 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 14:19:58.832  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.832  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.832  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:19:58.832  3829  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:19:58.832  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:19:58.832  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:19:58.832  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.832  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.833  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.833  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.833  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:19:58.833  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:19:58.833  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.833  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.833  3829  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 14:19:58.833  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.834  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.834  3829  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 14:19:58.834  3829  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 14:19:58.834  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.834  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.834  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.834  3829  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 14:19:58.834  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.834  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.834  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.834  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.834  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.834  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.834  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.834  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.835  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.835  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.835  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.835  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.836  3829  3877 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 14:19:58.836  3829  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:19:58.836  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:19:58.836  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:19:58.836  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.837  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.837  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.837  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.837  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.837  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.837  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.837  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.837  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.837  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.837  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.837  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.837  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.837  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.839  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.839  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.839  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.839  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.842  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.842  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.842  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.842  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.842  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.842  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.842  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.842  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.842  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.842  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.842  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.842  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.842  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.842  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.843  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.843  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.843  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.843  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.844  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:19:58.844  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:19:58.844  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:19:58.844  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:19:58.844  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.844  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.844  3829  3877 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fded77 not in the list
08-24 14:19:58.844  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.844  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.844  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:19:58.844  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.845  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.845  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:19:58.845  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:19:58.845  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:19:58.845  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:19:58.845  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:19:58.845  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828de4 not in the list
08-24 14:19:58.846  3829  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 14:19:58.846  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:19:58.846  3829  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 14:19:58.846  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:19:58.846  3829  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 14:19:58.846  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:19:58.848  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:19:58.848  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 14:19:58.848  3829  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 14:19:58.848  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:19:58.848  3829  3877 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 14:19:58.848  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:19:58.848  3829  3877 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 14:19:58.848  3829  3877 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 14:19:58.849  3829  3877 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 14:19:58.850  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:19:58.850  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f73c626 added. We now have 2 listener(s)
08-24 14:19:58.850  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:58.852  3829  3877 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 14:19:58.852   871  2244 D WifiService: setWifiEnabled: true pid=3829, uid=10000
08-24 14:19:58.852   871  2244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:19:58.853  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:19:58.853  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20f2267 added. We now have 3 listener(s)
08-24 14:19:58.853  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:58.858  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:19:58.858  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f973814 added. We now have 4 listener(s)
08-24 14:19:58.858  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:58.860  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:19:58.860  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f128bd added. We now have 5 listener(s)
08-24 14:19:58.860  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:19:58.861   871  1689 D WifiService: setWifiEnabled: false pid=3829, uid=10000
08-24 14:19:58.861   871  1689 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 14:19:58.865  2690  2736 D BluetoothAdapterState: Current state: ON, message: 23
08-24 14:19:58.865  2690  2736 D BluetoothAdapterProperties: Setting state to 13
08-24 14:19:58.865  2690  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:19:58.866  2690  2736 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:19:58.867  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:19:58.868  2690  2736 I BluetoothAdapterState: Entering PendingCommandState
08-24 14:19:58.869  2690  2746 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:19:58.869  2690  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-24 14:19:58.870  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.870  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:19:58.871  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.871  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.871  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:19:58.872  2690  2690 D HeadsetService: Received stop request...Stopping profile...
08-24 14:19:58.874   871   871 D BluetoothHeadset: Proxy object disconnected
08-24 14:19:58.874   871   871 D BluetoothHeadset: Proxy object disconnected
,08-24 14:19:58.874  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.874  1952  2073 D BluetoothHeadset: Proxy object disconnected
08-24 14:19:58.874  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-24 14:19:58.874  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-24 14:19:58.874  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:58.874  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:19:58.875  1349  1368 D BluetoothHeadset: Proxy object disconnected
08-24 14:19:58.875  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-24 14:19:58.876   871   871 D BluetoothHeadset: Proxy object disconnected
08-24 14:19:58.877  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.877  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 14:19:58.877  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:19:58.877  2690  2746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 14:19:58.877  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:19:58.877  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:19:58.877  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:19:58.878  2690  2690 D A2dpService: Received stop request...Stopping profile...
08-24 14:19:58.878  2690  2746 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 14:19:58.879  2690  2884 D A2dpStateMachine: Exit Disconnected: -1
08-24 14:19:58.880  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:19:58.880  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:19:58.881  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.881  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:19:58.881  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-24 14:19:58.881   871   871 D BluetoothA2dp: Proxy object disconnected
08-24 14:19:58.882  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 14:19:58.882  2690  2690 D HidService: Received stop request...Stopping profile...
,08-24 14:19:58.882  2690  2690 D HidService: Stopping Bluetooth HidService
,08-24 14:19:58.883   871  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 14:19:58.884   871  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 14:19:58.884  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-24 14:19:58.884   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-24 14:19:58.884  1349  1349 D HidProfile: Bluetooth service disconnected
08-24 14:19:58.884   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:19:58.885  2690  2690 V BluetoothAdapterState: isTurningOff()=true
,08-24 14:19:58.885  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-24 14:19:58.886  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:58.886  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:19:58.887  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.887  2690  2746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 14:19:58.887  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:19:58.887  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:19:58.887  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:19:58.887  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 14:19:58.887  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:19:58.887  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:19:58.887  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-24 14:19:58.887  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-24 14:19:58.887  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:19:58.888  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:19:58.888  2690  2690 D HealthService: Received stop request...Stopping profile...
08-24 14:19:58.890  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:19:58.890  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:19:58.890  2690  2746 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 14:19:58.891  2690  2690 D PanService: Received stop request...Stopping profile...
08-24 14:19:58.892  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 14:19:58.892  1349  1349 D PanProfile: Bluetooth service disconnected
08-24 14:19:58.892  2690  2690 D BluetoothMapService: Received stop request...Stopping profile...
08-24 14:19:58.892  2690  2690 D BluetoothMapService: stop()
08-24 14:19:58.893   871  1304 E native  : do suspend true
,08-24 14:19:58.893  2690  2690 D BluetoothMapAppObserver: deinitObservers()
08-24 14:19:58.893  2690  2690 D BluetoothMapAppObserver: removeReceiver()
08-24 14:19:58.894  1349  1349 D BluetoothMap: Proxy object disconnected
08-24 14:19:58.894  1349  1349 D MapProfile: Bluetooth service disconnected
08-24 14:19:58.894  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-24 14:19:58.894  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:19:58.894  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:58.894  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:19:58.894  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:19:58.895  2690  2746 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-24 14:19:58.895  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 14:19:58.895  2690  2690 V BluetoothAdapterState: isTurningOff()=true
,08-24 14:19:58.895  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:19:58.895  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:58.895  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:19:58.895  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-24 14:19:58.895  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 14:19:58.896  2690  2690 D BluetoothMapService: MAP Service closeService in
08-24 14:19:58.896  2690  2690 D BluetoothMapMasInstance0: MAP Service shutdown
,08-24 14:19:58.896  2690  2690 D ObexServerSockets0: shutdown(block = true)
08-24 14:19:58.896  2690  2890 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 14:19:58.897  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:19:58.897  2690  2891 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 14:19:58.897  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:19:58.897  2690  2878 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 14:19:58.897  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-24 14:19:58.898  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-24 14:19:58.898  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:58.898  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:19:58.898  2690  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 14:19:58.898  2690  2736 D BluetoothAdapterProperties: Setting state to 15
08-24 14:19:58.898  2690  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 14:19:58.898  2690  2736 I BluetoothAdapterState: Entering BleOnState
08-24 14:19:58.899  2690  2690 D BluetoothMapService: cleanup()
08-24 14:19:58.899  2690  2690 D BluetoothMapService: MAP Service closeService in
08-24 14:19:58.904   871  1900 D DhcpClient: Clearing IP address
08-24 14:19:58.904   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:19:58.907   372   870 D CommandListener: Setting iface cfg
08-24 14:19:58.909   871  1901 D DhcpClient: Receive thread stopped
08-24 14:19:58.910  1508  2468 V NativeCrypto: Read error: ssl=0xaec02800: I/O error during system call, Connection timed out
08-24 14:19:58.911  1508  2468 V NativeCrypto: SSL shutdown failed: ssl=0xaec02800: I/O error during system call, Broken pipe
08-24 14:19:58.913   871  2244 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-24 14:19:58.914   871  1876 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-24 14:19:58.915   871  1876 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-24 14:19:58.917   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 14:19:58.917  1349  2072 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:19:58.917   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-24 14:19:58.917  1952  1963 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:19:58.917   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-24 14:19:58.917   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:19:58.917   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:19:58.918  1349  3828 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 14:19:58.918   395   395 E Parcel  : Reading a NULL string not supported here.
08-24 14:19:58.919  2690  2690 I BtOppRfcommListener: stopping Accept Thread
08-24 14:19:58.919  2690  3424 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:19:58.920  2690  3424 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 14:19:58.920   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 14:19:58.922  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:58.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:19:58.923  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.923  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:19:58.924  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:58.924  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:19:58.925  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.925  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:19:58.932   871   884 I ActivityManager: Start proc 3886:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-24 14:19:58.935  1349  1368 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 14:19:58.935   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-24 14:19:58.936   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:19:58.936  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:19:58.937   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:19:58.937  1349  3828 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 14:19:58.937   871  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
08-24 14:19:58.937  1349  2072 D BluetoothPan: onBluetoothStateChange on: false
08-24 14:19:58.938  2690  2736 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 14:19:58.938  2690  2736 D BluetoothAdapterProperties: Setting state to 16
08-24 14:19:58.938  2690  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-24 14:19:58.938   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:19:58.939  2690  2736 D BluetoothAdapterProperties: onBleDisable
08-24 14:19:58.939  2690  2736 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:19:58.939  2690  2738 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-24 14:19:58.940  2690  2871 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 14:19:58.940  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:19:58.939   871  1304 E native  : do suspend true
08-24 14:19:58.943   871  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 14:19:58.944  2690  2746 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:19:58.947  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:58.947  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:19:58.950  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:58.950  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:19:58.951  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.953  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:19:58.973   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:19:58.981  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-24 14:19:58.990  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:19:58.992   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:19:58.993   871  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-24 14:19:58.993   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:19:58.993   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:19:58.995   871   888 D Tethering: MasterInitialState.processMessage what=3
08-24 14:19:58.997  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.998  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:19:58.999  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:19:59.008  3368  3368 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@79ee414 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-24 14:19:59.012   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fd5ed:true
,08-24 14:19:59.021   871  2245 I ActivityManager: Start proc 3904:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-24 14:19:59.044  3886  3886 D LocalBluetoothProfileManager: Adding local MAP profile
,08-24 14:19:59.051  3886  3886 D BluetoothMap: Create BluetoothMap proxy object
,08-24 14:19:59.052   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-24 14:19:59.053   871  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 14:19:59.053   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 14:19:59.054   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:19:59.057  3886  3886 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-24 14:19:59.063  3904  3904 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-24 14:19:59.064   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:19:59.066  1882  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:19:59.067  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:59.067  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:19:59.067  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:59.068  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:19:59.068   871  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 14:19:59.069  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:19:59.069  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:19:59.069  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:19:59.070  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:19:59.077  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:19:59.086   871  1976 I ActivityManager: Killing 3368:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 14:19:59.145  2690  2746 I bt_hci  : shut_down
,08-24 14:19:59.145  2690  2752 D bt_hwcfg: hw_epilog_process
08-24 14:19:59.146  2690  2752 I bt_vendor: low_power_mode_cb
,08-24 14:19:59.165  2690  2752 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-24 14:19:59.165  2690  2752 I bt_vendor: epilog_cb
08-24 14:19:59.165  2690  2752 I bt_hci  : epilog_finished_callback
,08-24 14:19:59.175  2690  2746 I bt_hci_h4: hal_close
,08-24 14:19:59.175  2690  2746 I bt_userial_vendor: device fd = 51 close
,08-24 14:19:59.236  3904  3904 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.236  3904  3904 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.236  3904  3904 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.236  3904  3904 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726),
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.236  3904  3904 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.236  3904  3904 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.236  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.237  3904  3904 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.237  3904  3904 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
,08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.237  3904  3904 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:19:59.237  3904  3904 D StrictMode: 	,at java.lang.reflect.Method.invoke(Native Method)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:19:59.237  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 14:19:59.246  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:19:59.250  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:19:59.265  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:19:59.272  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:19:59.294  1709  1709 D SystemUpdateService: onCreate
,08-24 14:19:59.298  2690  2738 D bt_stack_manager: event_shut_down_stack finished.
,08-24 14:19:59.298  2690  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 14:19:59.300  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:19:59.300  2690  2736 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 14:19:59.300  2690  2690 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 14:19:59.300  2690  2690 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:19:59.300  2690  2690 D BtGatt.GattService: stop()
,08-24 14:19:59.301  2690  2690 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 14:19:59.304  2690  2690 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:19:59.304  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-24 14:19:59.304  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:19:59.304  2690  2690 V BluetoothAdapterState: isBleTurningOff()=true
,08-24 14:19:59.304  2690  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 14:19:59.304  2690  2736 D BluetoothAdapterProperties: Setting state to 10
,08-24 14:19:59.304  2690  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 14:19:59.305  2690  2736 I BluetoothAdapterState: Entering OffState
,08-24 14:19:59.306   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 14:19:59.316  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 14:19:59.316  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 14:19:59.316  2690  2738 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 14:19:59.317  2690  2690 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 14:19:59.319  2690  2738 D bt_stack_manager: event_clean_up_stack finished.
,08-24 14:19:59.319  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 14:19:59.327  2690  2690 I art     : System.exit called, status: 0
,08-24 14:19:59.327  2690  2690 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 14:19:59.333  3829  3829 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:19:59.335  1709  2444 I iu.UploadsManager: num queued entries: 0
,08-24 14:19:59.336  1709  2444 I iu.UploadsManager: num updated entries: 0
,08-24 14:19:59.340  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:19:59.350  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:19:59.339  1709  3937 I SystemUpdateService: active receiver: enabled
,08-24 14:19:59.354  1709  3937 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:19:59.355  1709  2444 I iu.SyncManager: NEXT; no task
,08-24 14:19:59.365  1709  3937 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 14:19:59.368  1709  3937 I SystemUpdateService: now status is 0 (complete)
08-24 14:19:59.368  1709  3937 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 14:19:59.368  1709  3937 I SystemUpdateService: file has been verified
08-24 14:19:59.368  1709  3937 I SystemUpdateService: OTA package size = 12249756
,08-24 14:19:59.372  1709  3937 I SystemUpdateService: showing system update notification
,08-24 14:19:59.404   871  2245 I ActivityManager: Start proc 3941:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-24 14:19:59.407   871  1688 I ActivityManager: Process com.android.bluetooth (pid 2690) has died
,08-24 14:19:59.449  1709  1709 D SystemUpdateService: onDestroy
,08-24 14:19:59.478  3941  3941 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 14:19:59.487  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:19:59.498  3941  3941 D SprintDMHelper: simOperator: 
08-24 14:19:59.498  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:19:59.522  3904  3929 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 14:19:59.524   871  2246 I ActivityManager: Start proc 3955:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 14:19:59.525   871  2246 I ActivityManager: Killing 3553:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 14:19:59.544   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c43a93:true
,08-24 14:19:59.673  2265  3969 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 14:19:59.675   871  1976 I ActivityManager: Start proc 3970:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 14:19:59.678   871  1976 I ActivityManager: Killing 3437:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 14:19:59.753  3970  3970 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 14:19:59.810  3970  3970 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 14:19:59.810  3970  3970 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:19:59.810  3970  3970 I GAv4    :   adb logcat -s GAv4
,08-24 14:19:59.827  3970  3970 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:19:59.834  3970  3970 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:19:59.863  3970  3987 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:19:59.980  3970  3970 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 14:20:00.020  3970  3970 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 14:20:00.033  3970  3970 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 6397-6404)
,08-24 14:20:00.033  3970  3970 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 14:20:00.047  3970  3970 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {94d7a44}
,08-24 14:20:00.047  3970  3970 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 14:20:00.048  3970  3970 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:20:00.059  3970  3970 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 14:20:00.060  3970  3970 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 14:20:00.081  3970  3970 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 14:20:00.098  3970  3970 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:20:00.098  3970  3970 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:20:00.098  3970  3970 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:20:00.098  3970  3970 I Adreno  : Build Date                       : 10/20/15,
08-24 14:20:00.098  3970  3970 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:20:00.098  3970  3970 I Adreno  : Local Branch                     : M14
08-24 14:20:00.098  3970  3970 I Adreno  : Remote Branch                    : 
08-24 14:20:00.098  3970  3970 I Adreno  : Remote Branch                    : 
08-24 14:20:00.098  3970  3970 I Adreno  : Reconstruct Branch               : 
,08-24 14:20:00.172  3970  3970 I NSApplication: Starting up...
,08-24 14:20:00.182  3970  4016 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 14:20:00.217   871  1976 I ActivityManager: Start proc 4021:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 14:20:00.222   871  1976 I ActivityManager: Killing 3481:android.process.acore/u0a5 (adj 15): empty #17
,08-24 14:20:00.308  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 14:20:00.489   871  2245 I ActivityManager: Killing 3667:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 14:20:00.587   871  1381 I ActivityManager: Start proc 4035:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-24 14:20:00.671  4035  4035 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-24 14:20:00.729  4035  4035 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 14:20:00.788   871   882 I ActivityManager: Killing 3683:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 14:20:01.875   871  1983 D WifiService: setWifiEnabled: true pid=3829, uid=10000
,08-24 14:20:01.875   871  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:20:01.892   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-24 14:20:01.899  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:01.899  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:01.899  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:01.900  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:01.903  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:01.903  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:01.904  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:01.904  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:01.927   871  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-24 14:20:01.928   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 14:20:01.929   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 14:20:01.930   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 14:20:01.930   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 14:20:01.930   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-24 14:20:01.930   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 14:20:01.944   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 14:20:01.945   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:20:01.947   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:01.957   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-24 14:20:01.957   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 14:20:01.957   871  1304 E native  : do suspend true
,08-24 14:20:01.970   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:20:01.981   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 14:20:01.990   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 14:20:03.346   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:20:03.421   871  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.31 rxSuccessRate=7.75 delta 1000 -> 994
,08-24 14:20:03.423   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 14:20:03.424   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:20:03.442   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 14:20:03.499   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 14:20:03.502  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 14:20:03.937  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 14:20:03.969  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 14:20:03.970  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 14:20:03.975   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:20:03.989   871  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:20:03.990   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:20:03.990   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 14:20:04.011   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:20:04.027   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:04.028   871  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 14:20:04.044   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 14:20:04.080   871  4070 D DhcpClient: Receive thread started
,08-24 14:20:04.165   871  1304 E native  : do suspend false
,08-24 14:20:04.177   871  1900 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 14:20:04.189   871  4070 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172621, domain null
,08-24 14:20:04.189   871  1900 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172621 seconds
08-24 14:20:04.190   871  1900 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 14:20:04.203   871  4070 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-24 14:20:04.203   871  1900 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 14:20:04.204   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:04.208   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 14:20:04.210   871  1900 D DhcpClient: Scheduling renewal in 86399s
,08-24 14:20:04.211   871  1304 E native  : do suspend true
,08-24 14:20:04.233   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 14:20:04.235   871  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 14:20:04.236   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 14:20:04.239   871  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 14:20:04.247   871  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:20:04.311   871  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 14:20:04.311   871  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 14:20:04.313   871  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-24 14:20:04.314   871  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 14:20:04.316   871  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 14:20:04.326   871  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 14:20:04.333   871  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 14:20:04.333   871  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-24 14:20:04.333   871  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-24 14:20:04.333   871  1306 D ConnectivityService:    accepting network in place of null
08-24 14:20:04.334   871  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 14:20:04.335   871  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 14:20:04.335   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 14:20:04.347   871  4069 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200718, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 14:20:04.370   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:04.404   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:04.415   871  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 14:20:04.416   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:20:04.423   871  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-24 14:20:04.426   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:20:04.441  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:04.441   871  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:818::200e
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:20:04.442  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:20:04.442  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:04.443  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:20:04.452  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:20:04.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:20:04.453  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:04.453  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:20:04.460  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:20:04.463  1709  1709 D SystemUpdateService: onCreate
,08-24 14:20:04.466  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:20:04.468  1709  4081 I SystemUpdateService: active receiver: enabled
,08-24 14:20:04.474  1709  4081 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:20:04.476  1709  4081 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 14:20:04.477  1709  4081 I SystemUpdateService: now status is 0 (complete)
08-24 14:20:04.477  1709  4081 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 14:20:04.477  1709  4081 I SystemUpdateService: file has been verified
08-24 14:20:04.477  1709  4081 I SystemUpdateService: OTA package size = 12249756
,08-24 14:20:04.485  1709  4081 I SystemUpdateService: showing system update notification
,08-24 14:20:04.487  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 14:20:04.490  1709  2444 I iu.UploadsManager: num queued entries: 0
,08-24 14:20:04.490  1709  2444 I iu.UploadsManager: num updated entries: 0
,08-24 14:20:04.492  1709  4085 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-24 14:20:04.492  1709  4085 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:20:04.493  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-24 14:20:04.494  1709  4085 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 14:20:04.495  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:20:04.494  1709  2444 I iu.SyncManager: NEXT; no task
,08-24 14:20:04.499  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:20:04.499  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:20:04.500  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:20:04.503  1709  1709 D SystemUpdateService: onDestroy
,08-24 14:20:04.505  3941  3941 D SprintDMHelper: simOperator: 
,08-24 14:20:04.505  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:20:04.528   871  4068 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:20:04 GMT], X-Android-Received-Millis=[1472041204528], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472041204498]}
,08-24 14:20:04.529   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 14:20:04.529   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 14:20:04.530   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 14:20:04.531   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 14:20:04.535  1508  2002 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 14:20:04.535  1508  2002 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 14:20:04.535  1508  2002 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:20:04.535  1508  2002 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:20:04.548  1709  4085 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-24 14:20:04.647  2265  4088 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 14:20:04.675   871  1976 I ActivityManager: Killing 2054:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-24 14:20:04.884   871  1688 D WifiService: setWifiEnabled: false pid=3829, uid=10000
08-24 14:20:04.884   871  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:20:04.911  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 14:20:04.919   871  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 14:20:04.919   871  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-24 14:20:04.920   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 14:20:04.920   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:20:04.943   871  1304 E native  : do suspend true
,08-24 14:20:04.950   871  1900 D DhcpClient: Clearing IP address
,08-24 14:20:04.951   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:20:04.953   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:04.955  1508  4093 V NativeCrypto: Read error: ssl=0x99410800: I/O error during system call, Connection timed out
,08-24 14:20:04.959   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 14:20:04.959   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-24 14:20:04.961   871  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-24 14:20:04.962   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 14:20:04.963   871  1304 E native  : do suspend true
,08-24 14:20:04.965   395   395 E Parcel  : Reading a NULL string not supported here.
08-24 14:20:04.969   871  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-24 14:20:04.957  1508  4093 V NativeCrypto: SSL shutdown failed: ssl=0x99410800: I/O error during system call, Broken pipe
,08-24 14:20:04.979   871  4070 D DhcpClient: Receive thread stopped
,08-24 14:20:05.006   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:05.060   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:05.060   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:20:05.061   871  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 14:20:05.062   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:20:05.069   871   888 D Tethering: MasterInitialState.processMessage what=3
08-24 14:20:05.082  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:05.082  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:05.082  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:05.082  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:05.084  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:05.084  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:05.084  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.084  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:05.088   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:20:05.100  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 14:20:05.104  1709  1709 D SystemUpdateService: onCreate
,08-24 14:20:05.107   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:20:05.110  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:05.110  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:05.110  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.110  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:05.111  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:05.112  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:05.112  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:05.112  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:05.112  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-24 14:20:05.112   871  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 14:20:05.113  1882  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:20:05.132  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 14:20:05.139  1709  4103 I SystemUpdateService: active receiver: enabled
,08-24 14:20:05.140  1709  2444 I iu.UploadsManager: num queued entries: 0
,08-24 14:20:05.140  1709  2444 I iu.UploadsManager: num updated entries: 0
08-24 14:20:05.141  1709  2444 I iu.SyncManager: NEXT; no task
,08-24 14:20:05.142  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:20:05.144  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 14:20:05.147  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:20:05.153  3941  3941 D SprintDMHelper: simOperator: 
,08-24 14:20:05.153  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:20:05.157  1709  4103 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:20:05.165  1709  4103 I SystemUpdateService: network: null; metered: false; mobile allowed: false,
,08-24 14:20:05.167  1709  4103 I SystemUpdateService: now status is 0 (complete)
,08-24 14:20:05.170   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-24 14:20:05.171   871  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-24 14:20:05.176  2265  4107 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 14:20:05.177  1709  4103 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 14:20:05.177  1709  4103 I SystemUpdateService: file has been verified
08-24 14:20:05.177  1709  4103 I SystemUpdateService: OTA package size = 12249756
,08-24 14:20:05.185  1709  4103 I SystemUpdateService: showing system update notification
,08-24 14:20:05.206  1709  1709 D SystemUpdateService: onDestroy
,08-24 14:20:05.412   871  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 14:20:07.941   871   888 I ActivityManager: Start proc 4110:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 14:20:08.083  4110  4110 D AdapterServiceConfig: Adding HeadsetService
,08-24 14:20:08.083  4110  4110 D AdapterServiceConfig: Adding A2dpService
08-24 14:20:08.083  4110  4110 D AdapterServiceConfig: Adding HidService
,08-24 14:20:08.083  4110  4110 D AdapterServiceConfig: Adding HealthService
08-24 14:20:08.083  4110  4110 D AdapterServiceConfig: Adding PanService
,08-24 14:20:08.084  4110  4110 D AdapterServiceConfig: Adding GattService
08-24 14:20:08.084  4110  4110 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 14:20:08.099  4110  4110 D BluetoothAdapterState: make() - Creating AdapterState
08-24 14:20:08.099   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d1fd84:true
,08-24 14:20:08.104  4110  4110 I bt_bluedroid: init
,08-24 14:20:08.104  4110  4122 I BluetoothAdapterState: Entering OffState
,08-24 14:20:08.109  4110  4123 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 14:20:08.109  4110  4123 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 14:20:08.110  4110  4123 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-24 14:20:08.110  4110  4123 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 14:20:08.112  4110  4110 I bt_bluedroid: get_profile_interface socket
,08-24 14:20:08.114  4110  4110 I bt_bluedroid: get_profile_interface sdp
,08-24 14:20:08.118  4110  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:20:08.118  4110  4121 I bt_bluedroid: config_hci_snoop_log
,08-24 14:20:08.119   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 14:20:08.121  4110  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:20:08.125  4110  4122 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 14:20:08.125  4110  4122 D BluetoothAdapterProperties: Setting state to 14
08-24 14:20:08.126  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 14:20:08.129  4110  4122 D BluetoothBondStateMachine: make
,08-24 14:20:08.134  4110  4127 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 14:20:08.143  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:20:08.144  4110  4110 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 14:20:08.148  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:08.149  4110  4110 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:20:08.151  4110  4110 D BtGatt.GattService: Received start request. Starting profile...
,08-24 14:20:08.151  4110  4110 D BtGatt.GattService: start()
,08-24 14:20:08.151  4110  4110 I bt_bluedroid: get_profile_interface gatt
,08-24 14:20:08.153  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:08.153  4110  4110 D BtGatt.AdvertiseManager: advertise manager created
,08-24 14:20:08.163  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:08.163  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:08.163  4110  4110 V BluetoothAdapterState: isBleTurningOn()=true
08-24 14:20:08.163  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:08.164  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 14:20:08.164  4110  4122 I bt_bluedroid: enable
,08-24 14:20:08.165  4110  4123 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-24 14:20:08.166  4110  4123 I bt_hci  : start_up
,08-24 14:20:08.184  4110  4123 I bt_vendor: alloc value 0xb39cd189
08-24 14:20:08.185  4110  4123 I bt_vendor: init
08-24 14:20:08.185  4110  4123 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-24 14:20:08.185  4110  4123 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 14:20:08.294  4110  4123 D bt_hci  : start_up starting async portion
,08-24 14:20:08.295  4110  4130 I bt_hci  : event_finish_startup
08-24 14:20:08.295  4110  4130 I bt_hci_h4: hal_open
,08-24 14:20:08.297  4110  4130 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 14:20:08.307  4110  4130 I bt_userial_vendor: device fd = 51 open
,08-24 14:20:08.336  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:20:08.368  4110  4130 D bt_hwcfg: Chipset BCM4354A2
,08-24 14:20:08.368  4110  4130 D bt_hwcfg: Target name = [BCM4354A2]
08-24 14:20:08.369  4110  4130 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 14:20:09.000  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-24 14:20:09.001  4110  4130 D bt_hwcfg: Settlement delay -- 100 ms
08-24 14:20:09.001  4110  4130 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 14:20:09.118  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-24 14:20:09.119  4110  4130 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 14:20:09.148  4110  4130 I bt_hwcfg: vendor lib fwcfg completed
,08-24 14:20:09.148  4110  4130 I bt_vendor: firmware callback
,08-24 14:20:09.149  4110  4130 I bt_hci  : firmware_config_callback
,08-24 14:20:09.160  4110  4134 I bt_btu  : btu_task pending for preload complete event
08-24 14:20:09.160  4110  4134 I bt_btu_task: Bluetooth chip preload is complete
,08-24 14:20:09.160  4110  4134 I bt_btu  : btu_task received preload complete event
,08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:20:09.169  4110  4134 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:20:09.170  4110  4134 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:20:09.170  4110  4134 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 14:20:09.170  4110  4134 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 14:20:09.170  4110  4134 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:20:09.170  4110  4134 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 14:20:09.300  4110  4134 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb394ad9d
08-24 14:20:09.300  4110  4134 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb394ad9d 
,08-24 14:20:09.311  4110  4126 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 14:20:09.313  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 14:20:09.313  4110  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:20:09.317  4110  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:20:09.322  4110  4126 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:20:09.323  4110  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:20:09.323  4110  4126 D bt_hci  : do_postload posting postload work item
08-24 14:20:09.324  4110  4130 I bt_hci  : event_postload
,08-24 14:20:09.324  4110  4130 I bt_vendor: sco_config_cb
08-24 14:20:09.324  4110  4130 I bt_hci  : sco_config_callback postload finished.
08-24 14:20:09.327  4110  4126 D bt_bte_conf: Device ID record 1 : primary
,08-24 14:20:09.327  4110  4126 D bt_bte_conf:   vendorId            = 000f
,08-24 14:20:09.327  4110  4126 D bt_bte_conf:   vendorIdSource      = 0001
08-24 14:20:09.328  4110  4126 D bt_bte_conf:   product             = 1200
08-24 14:20:09.328  4110  4126 D bt_bte_conf:   version             = 1436
08-24 14:20:09.328  4110  4126 D bt_bte_conf:   clientExecutableURL = 
,08-24 14:20:09.328  4110  4126 D bt_bte_conf:   serviceDescription  = 
,08-24 14:20:09.328  4110  4126 D bt_bte_conf:   documentationURL    = 
08-24 14:20:09.329  4110  4126 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 14:20:09.329  4110  4123 D bt_stack_manager: event_start_up_stack finished
08-24 14:20:09.330  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 14:20:09.331  4110  4122 D BluetoothAdapterProperties: Setting state to 15
08-24 14:20:09.331  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-24 14:20:09.331  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:09.332  4110  4130 I bt_vendor: low_power_mode_cb
,08-24 14:20:09.332  4110  4122 I BluetoothAdapterState: Entering BleOnState
08-24 14:20:09.335  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:09.340  4110  4122 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-24 14:20:09.340  4110  4122 D BluetoothAdapterProperties: Setting state to 11
08-24 14:20:09.340  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-24 14:20:09.344  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.345  4110  4110 D HeadsetService: Received start request. Starting profile...
08-24 14:20:09.348  4110  4110 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 14:20:09.348  4110  4110 D HeadsetStateMachine: make
,08-24 14:20:09.357  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:09.359  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:09.362  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:20:09.370  4110  4110 D HeadsetStateMachine: max_hf_connections = 1
,08-24 14:20:09.370  4110  4110 I bt_bluedroid: get_profile_interface handsfree
,08-24 14:20:09.370  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 14:20:09.371  4110  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
08-24 14:20:09.373  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.374  4110  4110 D A2dpService: Received start request. Starting profile...
08-24 14:20:09.375  4110  4110 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 14:20:09.375  4110  4110 I bt_bluedroid: get_profile_interface avrcp
,08-24 14:20:09.381  4110  4110 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 14:20:09.381  4110  4110 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-24 14:20:09.381  4110  4110 D A2dpStateMachine: make
,08-24 14:20:09.382  4110  4110 I bt_bluedroid: get_profile_interface a2dp
,08-24 14:20:09.383  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 14:20:09.384  4110  4110 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 14:20:09.385  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.385  4110  4144 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:20:09.386  4110  4110 D HidService: Received start request. Starting profile...
,08-24 14:20:09.386  4110  4110 I bt_bluedroid: get_profile_interface hidhost
,08-24 14:20:09.386  4110  4110 D HidService: setHidService(): set to: null
08-24 14:20:09.386  3886  3886 D BluetoothInputDevice: Proxy object connected
08-24 14:20:09.386  4110  4126 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392c3e5
,08-24 14:20:09.387  4110  4110 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 14:20:09.387  3886  3886 D HidProfile: Bluetooth service connected
08-24 14:20:09.387  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 14:20:09.388  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.388  4110  4110 D HealthService: Received start request. Starting profile...
08-24 14:20:09.389  4110  4110 I bt_bluedroid: get_profile_interface health
08-24 14:20:09.391  4110  4110 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 14:20:09.392  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.393  4110  4110 D PanService: Received start request. Starting profile...
08-24 14:20:09.393  4110  4110 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:20:09.393  4110  4110 I bt_bluedroid: get_profile_interface pan
08-24 14:20:09.394  4110  4126 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 14:20:09.395  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:20:09.396  3886  3886 D PanProfile: Bluetooth service connected
08-24 14:20:09.396  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:09.396  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:20:09.399  4110  4110 D BluetoothMapService: Received start request. Starting profile...
08-24 14:20:09.399  4110  4110 D BluetoothMapService: start()
,08-24 14:20:09.400  3886  3886 D BluetoothMap: Proxy object connected
08-24 14:20:09.400  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 14:20:09.401  3886  3886 D MapProfile: Bluetooth service connected
08-24 14:20:09.401  3886  3886 D BluetoothMap: getConnectedDevices()
08-24 14:20:09.401  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-24 14:20:09.401  4110  4110 D BluetoothMapAppObserver: createReceiver()
,08-24 14:20:09.402  3886  3886 D BluetoothMap: Bluetooth is Not enabled
08-24 14:20:09.402  4110  4110 D BluetoothMapAppObserver: initObservers()
08-24 14:20:09.402  4110  4110 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 14:20:09.407  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:09.408  4110  4110 V BluetoothAdapterState: isTurningOn()=true
,08-24 14:20:09.408  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.408  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:09.408  4110  4141 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:09.409  4110  4110 V BluetoothAdapterState: isTurningOn()=true
,08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isTurningOn()=true
,08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.410  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:09.412  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:09.412  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:09.412  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:09.413  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:09.413  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-24 14:20:09.413  4110  4122 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:20:09.414  4110  4122 D BluetoothAdapterProperties: State =  11
08-24 14:20:09.414  4110  4122 D BluetoothAdapterProperties: Setting state to 12
08-24 14:20:09.414  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:20:09.414  1349  3828 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:09.415  4110  4122 I BluetoothAdapterState: Entering OnState
,08-24 14:20:09.415  1952  3464 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:09.416   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:20:09.416  4110  4126 D BluetoothAdapterProperties: Scan Mode:21
,08-24 14:20:09.416  3886  3898 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 14:20:09.416   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:20:09.417  4110  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:20:09.417  3886  3897 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:20:09.418  1349  2072 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:20:09.419  1349  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:09.419  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:09.420   871   871 D BluetoothA2dp: Proxy object connected,
08-24 14:20:09.422  1349  1349 D BluetoothInputDevice: Proxy object connected
08-24 14:20:09.422  1349  1349 D HidProfile: Bluetooth service connected
08-24 14:20:09.422  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:09.422   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:09.423  1349  3828 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:09.425  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:09.426  1349  1349 D BluetoothA2dp: Proxy object connected
08-24 14:20:09.426   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:20:09.427  3886  3898 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:20:09.427  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 14:20:09.427  1349  1360 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:20:09.427  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:09.428  4110  4110 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-24 14:20:09.429  1349  1349 D BluetoothMap: Proxy object connected
08-24 14:20:09.429  1349  1349 D MapProfile: Bluetooth service connected
,08-24 14:20:09.429  1349  1349 D BluetoothMap: getConnectedDevices()
,08-24 14:20:09.429  1349  3828 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:20:09.430  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:09.431  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:20:09.431  1349  1349 D PanProfile: Bluetooth service connected
,08-24 14:20:09.431  3886  3897 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:20:09.431  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:20:09.432  4110  4110 D ObexServerSockets: Succeed to create listening sockets 
,08-24 14:20:09.432  4110  4110 D ObexServerSockets0: startAccept()
08-24 14:20:09.432  4110  4110 D ObexServerSockets0: prepareForNewConnect()
08-24 14:20:09.434   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 14:20:09.434  4110  4110 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 14:20:09.434  4110  4110 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 14:20:09.436  4110  4110 D BluetoothMapService: onReceive
,08-24 14:20:09.436  4110  4110 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:20:09.436  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:09.436  4110  4110 D BluetoothMapService: STATE_ON
08-24 14:20:09.437  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:09.437  4110  4149 D ObexServerSockets0: Accepting socket connection...
08-24 14:20:09.438  4110  4150 D ObexServerSockets0: Accepting socket connection...
08-24 14:20:09.438  3886  3886 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 14:20:09.442  3886  3886 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 14:20:09.447  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:20:09.450  3886  3886 D BluetoothA2dp: Proxy object connected
,08-24 14:20:09.454  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:20:09.459  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 14:20:09.459  4110  4110 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:20:09.460  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:20:09.461  3886  3886 D BluetoothPbap: Proxy object connected
,08-24 14:20:09.461  3886  3886 D PbapServerProfile: Bluetooth service connected
,08-24 14:20:09.462  1349  1349 D BluetoothPbap: Proxy object connected
08-24 14:20:09.462  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-24 14:20:09.467  4110  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:09.482  4110  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:09.483  4110  4159 I BtOppRfcommListener: Accept thread started.
,08-24 14:20:09.516   871   871 D BluetoothHeadset: Proxy object connected
08-24 14:20:09.516   871   871 D BluetoothHeadset: Proxy object connected
,08-24 14:20:09.517  1952  2073 D BluetoothHeadset: Proxy object connected
,08-24 14:20:09.517  1349  2072 D BluetoothHeadset: Proxy object connected
,08-24 14:20:09.517  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-24 14:20:09.517   871   871 D BluetoothHeadset: Proxy object connected,
,08-24 14:20:09.522   871   888 D BluetoothHeadset: Proxy object connected
,08-24 14:20:09.526   871   888 D BluetoothHeadset: Proxy object connected
,08-24 14:20:09.546  3886  3897 D BluetoothHeadset: Proxy object connected
08-24 14:20:09.548  3886  3886 D HeadsetProfile: Bluetooth service connected
,08-24 14:20:10.903  4110  4122 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 14:20:10.903  4110  4122 D BluetoothAdapterProperties: Setting state to 13
,08-24 14:20:10.903  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-24 14:20:10.908  4110  4122 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 14:20:10.912  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:20:10.916  4110  4110 D BluetoothMapService: onReceive
,08-24 14:20:10.917  4110  4110 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:20:10.917  4110  4110 D BluetoothMapService: STATE_TURNING_OFF
08-24 14:20:10.918  4110  4110 D BluetoothMapService: MAP Service closeService in
,08-24 14:20:10.918  4110  4110 D BluetoothMapMasInstance0: MAP Service shutdown
,08-24 14:20:10.918  4110  4110 D ObexServerSockets0: shutdown(block = true)
,08-24 14:20:10.919  4110  4149 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-24 14:20:10.920  4110  4110 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 14:20:10.921  4110  4150 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-24 14:20:10.921  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:10.922  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:10.923  4110  4137 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-24 14:20:10.923  4110  4126 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:20:10.924  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-24 14:20:10.925  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:10.925  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:20:10.925  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:10.925  4110  4110 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 14:20:10.926  4110  4110 I BtOppRfcommListener: stopping Accept Thread
,08-24 14:20:10.926  4110  4159 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 14:20:10.927  4110  4159 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 14:20:10.934  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:10.934  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:10.936  3829  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:20:10.936  4110  4110 D HeadsetService: Received stop request...Stopping profile...
08-24 14:20:10.936  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:10.938  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:10.939   871   871 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.939   871   871 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.939  1952  3464 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.939  4110  4110 D A2dpService: Received stop request...Stopping profile...
08-24 14:20:10.940  4110  4144 D A2dpStateMachine: Exit Disconnected: -1
08-24 14:20:10.940  1349  1368 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.941  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-24 14:20:10.941  3886  3898 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.941   871   871 D BluetoothHeadset: Proxy object disconnected
08-24 14:20:10.942  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:10.942   871   871 D BluetoothA2dp: Proxy object disconnected
08-24 14:20:10.943  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-24 14:20:10.945  4110  4110 D HidService: Received stop request...Stopping profile...
08-24 14:20:10.946  4110  4110 D HidService: Stopping Bluetooth HidService
08-24 14:20:10.947  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-24 14:20:10.948  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:20:10.948  1349  1349 D HidProfile: Bluetooth service disconnected
,08-24 14:20:10.948  4110  4110 D HealthService: Received stop request...Stopping profile...
,08-24 14:20:10.951  4110  4110 D PanService: Received stop request...Stopping profile...
08-24 14:20:10.951  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:20:10.951  1349  1349 D PanProfile: Bluetooth service disconnected
08-24 14:20:10.952  4110  4110 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 14:20:10.952  4110  4110 D BluetoothMapService: stop()
,08-24 14:20:10.955  4110  4110 D BluetoothMapAppObserver: deinitObservers()
08-24 14:20:10.956  4110  4110 D BluetoothMapAppObserver: removeReceiver()
,08-24 14:20:10.956  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:20:10.957  1349  1349 D BluetoothMap: Proxy object disconnected
08-24 14:20:10.957  3886  3886 D HeadsetProfile: Bluetooth service disconnected
08-24 14:20:10.957  1349  1349 D MapProfile: Bluetooth service disconnected
,08-24 14:20:10.957  3886  3886 D BluetoothA2dp: Proxy object disconnected
08-24 14:20:10.957  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-24 14:20:10.957  3886  3886 D BluetoothInputDevice: Proxy object disconnected
,08-24 14:20:10.957  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.957  3886  3886 D HidProfile: Bluetooth service disconnected
,08-24 14:20:10.958  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:20:10.958  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:10.958  3886  3886 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:20:10.958  3886  3886 D PanProfile: Bluetooth service disconnected
,08-24 14:20:10.958  3886  3886 D BluetoothMap: Proxy object disconnected
08-24 14:20:10.959  4110  4110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 14:20:10.959  4110  4110 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 14:20:10.959  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 14:20:10.958  3886  3886 D MapProfile: Bluetooth service disconnected
08-24 14:20:10.959  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:20:10.959  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:20:10.959  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:20:10.959  4110  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-24 14:20:10.961  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-24 14:20:10.961  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.961  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:20:10.961  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:10.962  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 14:20:10.962  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:20:10.962  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 14:20:10.962  4110  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:20:10.962  4110  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 14:20:10.962  4110  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 14:20:10.962  4110  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:20:10.967  1349  1349 D BluetoothPbap: Proxy object disconnected
,08-24 14:20:10.967  1349  1349 D PbapServerProfile: Bluetooth service disconnected
08-24 14:20:10.967  4110  4110 V BluetoothAdapterState: isTurningOff()=true
,08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:20:10.968  4110  4110 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:20:10.968  4110  4110 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:20:10.968  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isTurningOff()=true
,08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:10.968  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:10.970  4110  4110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:20:10.970  4110  4126 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 14:20:10.970  4110  4110 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 14:20:10.971  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-24 14:20:10.971  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.971  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:10.971  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:20:10.971  4110  4110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:20:10.971  4110  4110 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 14:20:10.972  4110  4110 D BluetoothMapService: MAP Service closeService in
,08-24 14:20:10.972  3886  3886 D BluetoothPbap: Proxy object disconnected
08-24 14:20:10.972  3886  3886 D PbapServerProfile: Bluetooth service disconnected
08-24 14:20:10.972  4110  4110 V BluetoothAdapterState: isTurningOff()=true
08-24 14:20:10.972  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:10.972  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:20:10.972  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:10.973  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 14:20:10.973  4110  4122 D BluetoothAdapterProperties: Setting state to 15
08-24 14:20:10.973  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 14:20:10.974  4110  4122 I BluetoothAdapterState: Entering BleOnState
08-24 14:20:10.974  4110  4110 D BluetoothMapService: cleanup()
,08-24 14:20:10.974  4110  4110 D BluetoothMapService: MAP Service closeService in
,08-24 14:20:10.978  1349  2072 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:20:10.978  3886  3898 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:20:10.978  1952  2073 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:20:10.979   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:20:10.979  3886  3897 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 14:20:10.979   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:20:10.980  3886  3898 D BluetoothPan: onBluetoothStateChange on: false
,08-24 14:20:10.980  3886  3897 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:20:10.981  1349  1368 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 14:20:10.981  1349  3828 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 14:20:10.981   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 14:20:10.982  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 14:20:10.982   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 14:20:10.982  3886  3898 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 14:20:10.983  1349  2072 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:20:10.983  1349  1368 D BluetoothPan: onBluetoothStateChange on: false
,08-24 14:20:10.984  3886  3897 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 14:20:10.984  4110  4122 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 14:20:10.984  4110  4122 D BluetoothAdapterProperties: Setting state to 16
08-24 14:20:10.984  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-24 14:20:10.985  4110  4122 D BluetoothAdapterProperties: onBleDisable
08-24 14:20:10.985  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
08-24 14:20:10.986  4110  4123 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-24 14:20:10.986  4110  4134 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 14:20:10.986  4110  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 14:20:10.988  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:10.989  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:10.990  4110  4126 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:20:10.992  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:10.992  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:20:10.993  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:10.996  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:20:10.997  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:20:11.187  4110  4126 I bt_hci  : shut_down
,08-24 14:20:11.195  4110  4130 D bt_hwcfg: hw_epilog_process
,08-24 14:20:11.195  4110  4130 I bt_vendor: low_power_mode_cb
,08-24 14:20:11.216  4110  4130 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-24 14:20:11.217  4110  4130 I bt_vendor: epilog_cb
,08-24 14:20:11.217  4110  4130 I bt_hci  : epilog_finished_callback
,08-24 14:20:11.226  4110  4126 I bt_hci_h4: hal_close
,08-24 14:20:11.228  4110  4126 I bt_userial_vendor: device fd = 51 close
,08-24 14:20:11.353  4110  4123 D bt_stack_manager: event_shut_down_stack finished.
,08-24 14:20:11.355  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 14:20:11.360  4110  4110 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:20:11.361  4110  4122 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 14:20:11.362  4110  4110 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 14:20:11.362  4110  4110 D BtGatt.GattService: stop()
08-24 14:20:11.363  4110  4110 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 14:20:11.368  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:11.369  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-24 14:20:11.369  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:20:11.369  4110  4110 V BluetoothAdapterState: isBleTurningOff()=true
08-24 14:20:11.371  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-24 14:20:11.373  4110  4122 D BluetoothAdapterProperties: Setting state to 10
,08-24 14:20:11.373  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-24 14:20:11.376  4110  4122 I BluetoothAdapterState: Entering OffState
,08-24 14:20:11.377   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 14:20:11.400  4110  4110 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 14:20:11.400  4110  4110 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-24 14:20:11.401  4110  4123 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 14:20:11.407  4110  4123 D bt_stack_manager: event_clean_up_stack finished.
,08-24 14:20:11.407  4110  4110 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 14:20:11.411  4110  4110 I art     : System.exit called, status: 0
,08-24 14:20:11.411  4110  4110 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 14:20:11.469   871  2177 I ActivityManager: Process com.android.bluetooth (pid 4110) has died
,08-24 14:20:12.340   871  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-24 14:20:13.900  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:20:13.901  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:16.909  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:16.909  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be17e03 added. We now have 6 listener(s)
,08-24 14:20:16.910  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:20:16.914  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:16.915  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb9c180 added. We now have 7 listener(s)
,08-24 14:20:16.915  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:16.917  3829  3877 I System.out: IsBluetoothEnabled
,08-24 14:20:16.929  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:16.953   871   888 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 14:20:17.056  4169  4169 D AdapterServiceConfig: Adding HeadsetService
,08-24 14:20:17.057  4169  4169 D AdapterServiceConfig: Adding A2dpService
08-24 14:20:17.057  4169  4169 D AdapterServiceConfig: Adding HidService
,08-24 14:20:17.057  4169  4169 D AdapterServiceConfig: Adding HealthService
,08-24 14:20:17.057  4169  4169 D AdapterServiceConfig: Adding PanService
,08-24 14:20:17.058  4169  4169 D AdapterServiceConfig: Adding GattService
08-24 14:20:17.058  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 14:20:17.073   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e2000f1:true
,08-24 14:20:17.074  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 14:20:17.078  4169  4169 I bt_bluedroid: init
,08-24 14:20:17.079  4169  4181 I BluetoothAdapterState: Entering OffState
,08-24 14:20:17.084  4169  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 14:20:17.085  4169  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 14:20:17.085  4169  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-24 14:20:17.085  4169  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 14:20:17.087  4169  4169 I bt_bluedroid: get_profile_interface socket
,08-24 14:20:17.091  4169  4169 I bt_bluedroid: get_profile_interface sdp
,08-24 14:20:17.093  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:20:17.102  4169  4180 I bt_bluedroid: config_hci_snoop_log
,08-24 14:20:17.102  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
08-24 14:20:17.104   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 14:20:17.109  4169  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 14:20:17.109  4169  4181 D BluetoothAdapterProperties: Setting state to 14
08-24 14:20:17.110  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 14:20:17.113  4169  4181 D BluetoothBondStateMachine: make
,08-24 14:20:17.116  4169  4187 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 14:20:17.123  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:20:17.125  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 14:20:17.128  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:17.129  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 14:20:17.129  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
,08-24 14:20:17.129  4169  4169 D BtGatt.GattService: start()
08-24 14:20:17.129  4169  4169 I bt_bluedroid: get_profile_interface gatt
08-24 14:20:17.130  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:17.130  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
,08-24 14:20:17.137  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:17.137  4169  4169 V BluetoothAdapterState: isTurningOn()=false
,08-24 14:20:17.137  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
08-24 14:20:17.137  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:17.138  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 14:20:17.138  4169  4181 I bt_bluedroid: enable,
08-24 14:20:17.138  4169  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 14:20:17.139  4169  4182 I bt_hci  : start_up
,08-24 14:20:17.146  4169  4182 I bt_vendor: alloc value 0xb39cd189
08-24 14:20:17.146  4169  4182 I bt_vendor: init
08-24 14:20:17.146  4169  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 14:20:17.146  4169  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 14:20:17.254  4169  4182 D bt_hci  : start_up starting async portion
08-24 14:20:17.255  4169  4190 I bt_hci  : event_finish_startup
08-24 14:20:17.255  4169  4190 I bt_hci_h4: hal_open
08-24 14:20:17.255  4169  4190 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 14:20:17.265  4169  4190 I bt_userial_vendor: device fd = 51 open
,08-24 14:20:17.296  4169  4190 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 14:20:17.328  4169  4190 D bt_hwcfg: Chipset BCM4354A2
08-24 14:20:17.328  4169  4190 D bt_hwcfg: Target name = [BCM4354A2]
08-24 14:20:17.329  4169  4190 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 14:20:17.987  4169  4190 I bt_hwcfg: bt vendor lib: set UART baud 115200,
08-24 14:20:17.988  4169  4190 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 14:20:17.989  4169  4190 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 14:20:18.105  4169  4190 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
08-24 14:20:18.106  4169  4190 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 14:20:18.136  4169  4190 I bt_hwcfg: vendor lib fwcfg completed,
08-24 14:20:18.137  4169  4190 I bt_vendor: firmware callback
08-24 14:20:18.137  4169  4190 I bt_hci  : firmware_config_callback
,08-24 14:20:18.148  4169  4192 I bt_btu  : btu_task pending for preload complete event,
08-24 14:20:18.148  4169  4192 I bt_btu_task: Bluetooth chip preload is complete
08-24 14:20:18.149  4169  4192 I bt_btu  : btu_task received preload complete event,
,08-24 14:20:18.161  4169  4192 I         : BTE_InitTraceLevels -- TRC_HCI,
08-24 14:20:18.162  4169  4192 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 14:20:18.162  4169  4192 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 14:20:18.162  4169  4192 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 14:20:18.163  4169  4192 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 14:20:18.163  4169  4192 I         : BTE_InitTraceLevels -- TRC_A2D
,08-24 14:20:18.164  4169  4192 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-24 14:20:18.165  4169  4192 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 14:20:18.165  4169  4192 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 14:20:18.165  4169  4192 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 14:20:18.166  4169  4192 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 14:20:18.166  4169  4192 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 14:20:18.166  4169  4192 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 14:20:18.166  4169  4192 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 14:20:18.167  4169  4192 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 14:20:18.299  4169  4192 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb394ad9d,
08-24 14:20:18.300  4169  4192 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb394ad9d 
,08-24 14:20:18.310  4169  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 14:20:18.312  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 14:20:18.313  4169  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 14:20:18.319  4169  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 14:20:18.324  4169  4185 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:20:18.324  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:20:18.325  4169  4185 D bt_hci  : do_postload posting postload work item
,08-24 14:20:18.325  4169  4190 I bt_hci  : event_postload
,08-24 14:20:18.325  4169  4190 I bt_vendor: sco_config_cb
08-24 14:20:18.325  4169  4190 I bt_hci  : sco_config_callback postload finished.
08-24 14:20:18.326  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:18.329  4169  4185 D bt_bte_conf: Device ID record 1 : primary
08-24 14:20:18.329  4169  4185 D bt_bte_conf:   vendorId            = 000f
08-24 14:20:18.330  4169  4185 D bt_bte_conf:   vendorIdSource      = 0001
,08-24 14:20:18.330  4169  4185 D bt_bte_conf:   product             = 1200
08-24 14:20:18.330  4169  4185 D bt_bte_conf:   version             = 1436
,08-24 14:20:18.330  4169  4185 D bt_bte_conf:   clientExecutableURL = 
08-24 14:20:18.330  4169  4185 D bt_bte_conf:   serviceDescription  = 
08-24 14:20:18.331  4169  4185 D bt_bte_conf:   documentationURL    = 
08-24 14:20:18.331  4169  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 14:20:18.331  4169  4182 D bt_stack_manager: event_start_up_stack finished
,08-24 14:20:18.332  4169  4190 I bt_vendor: low_power_mode_cb
08-24 14:20:18.332  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 14:20:18.333  4169  4181 D BluetoothAdapterProperties: Setting state to 15
08-24 14:20:18.333  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 14:20:18.334  4169  4181 I BluetoothAdapterState: Entering BleOnState
08-24 14:20:18.339  4169  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-24 14:20:18.339  4169  4181 D BluetoothAdapterProperties: Setting state to 11
08-24 14:20:18.339  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-24 14:20:18.346  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:18.353  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:18.354  4169  4169 D HeadsetService: Received start request. Starting profile...
,08-24 14:20:18.358  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 14:20:18.358  4169  4169 D HeadsetStateMachine: make
,08-24 14:20:18.364  4169  4181 I BluetoothAdapterState: Entering PendingCommandState
,08-24 14:20:18.374  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
,08-24 14:20:18.374  4169  4169 I bt_bluedroid: get_profile_interface handsfree
08-24 14:20:18.375  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-24 14:20:18.375  4169  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 14:20:18.382  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:20:18.381  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
08-24 14:20:18.383  4169  4169 D A2dpService: Received start request. Starting profile...
08-24 14:20:18.384  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 14:20:18.384  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,08-24 14:20:18.391  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 14:20:18.392  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 14:20:18.392  4169  4169 D A2dpStateMachine: make
,08-24 14:20:18.394  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,08-24 14:20:18.395  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 14:20:18.398  4169  4200 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:20:18.399  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 14:20:18.401  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:18.401  4169  4169 D HidService: Received start request. Starting profile...
08-24 14:20:18.402  4169  4169 I bt_bluedroid: get_profile_interface hidhost
,08-24 14:20:18.402  4169  4169 D HidService: setHidService(): set to: null
08-24 14:20:18.402  4169  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392c3e5
08-24 14:20:18.402  4169  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-24 14:20:18.403  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 14:20:18.405  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:18.406  4169  4169 D HealthService: Received start request. Starting profile...
,08-24 14:20:18.408  4169  4169 I bt_bluedroid: get_profile_interface health
,08-24 14:20:18.409  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 14:20:18.410  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:18.411  4169  4169 D PanService: Received start request. Starting profile...
,08-24 14:20:18.411  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:20:18.411  4169  4169 I bt_bluedroid: get_profile_interface pan
,08-24 14:20:18.413  4169  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 14:20:18.417  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:18.419  4169  4169 D BluetoothMapService: Received start request. Starting profile...
,08-24 14:20:18.419  4169  4169 D BluetoothMapService: start()
,08-24 14:20:18.422  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 14:20:18.423  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 14:20:18.423  4169  4169 D BluetoothMapAppObserver: createReceiver()
,08-24 14:20:18.424  4169  4169 D BluetoothMapAppObserver: initObservers()
,08-24 14:20:18.425  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 14:20:18.432  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:18.432  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.432  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 14:20:18.432  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 14:20:18.435  4169  4198 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-24 14:20:18.437  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:18.438  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.438  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:18.438  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:18.438  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:18.438  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.439  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:18.439  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:18.439  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-24 14:20:18.439  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.440  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:18.440  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:18.441  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:18.441  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.441  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:18.441  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:18.442  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-24 14:20:18.442  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-24 14:20:18.442  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-24 14:20:18.442  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-24 14:20:18.443  4169  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-24 14:20:18.443  4169  4181 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:20:18.443  4169  4181 D BluetoothAdapterProperties: State =  11
08-24 14:20:18.444  4169  4181 D BluetoothAdapterProperties: Setting state to 12
08-24 14:20:18.444  4169  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 14:20:18.446  1349  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:18.446  4169  4185 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:20:18.446  4169  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:20:18.447  4169  4181 I BluetoothAdapterState: Entering OnState
08-24 14:20:18.447  3886  3897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:18.448  1952  2073 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:20:18.448   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 14:20:18.449  3886  3898 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:20:18.451   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:20:18.451  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 14:20:18.452  3886  3897 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:20:18.452  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:18.453  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:18.454  3886  3898 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:20:18.454  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:18.455  1349  3828 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 14:20:18.456  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 14:20:18.458  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:18.458   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:18.458  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:18.458  1349  2072 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:20:18.460   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 14:20:18.460  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
08-24 14:20:18.460  3886  3897 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:20:18.460  4169  4169 D ObexServerSockets0: startAccept()
,08-24 14:20:18.460  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:20:18.462  1349  1368 D BluetoothMap: onBluetoothStateChange: up=true
08-24 14:20:18.463  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 14:20:18.463  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 14:20:18.464  1349  1360 D BluetoothPan: onBluetoothStateChange on: true
08-24 14:20:18.465  4169  4205 D ObexServerSockets0: Accepting socket connection...
08-24 14:20:18.465  1349  1349 D BluetoothInputDevice: Proxy object connected
,08-24 14:20:18.465  1349  1349 D HidProfile: Bluetooth service connected
08-24 14:20:18.465  3886  3886 D BluetoothInputDevice: Proxy object connected
08-24 14:20:18.465  3886  3886 D HidProfile: Bluetooth service connected
08-24 14:20:18.466   871   871 D BluetoothA2dp: Proxy object connected
08-24 14:20:18.466  4169  4206 D ObexServerSockets0: Accepting socket connection...
08-24 14:20:18.468  3886  3897 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:20:18.469  1349  1349 D BluetoothA2dp: Proxy object connected
,08-24 14:20:18.471  3886  3886 D BluetoothA2dp: Proxy object connected
08-24 14:20:18.471   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 14:20:18.474  4169  4169 D BluetoothMapService: onReceive
,08-24 14:20:18.474  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:20:18.475  4169  4169 D BluetoothMapService: STATE_ON
,08-24 14:20:18.475  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:18.477  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:20:18.478  1349  1349 D PanProfile: Bluetooth service connected
,08-24 14:20:18.478  1349  1349 D BluetoothMap: Proxy object connected
08-24 14:20:18.478  1349  1349 D MapProfile: Bluetooth service connected
08-24 14:20:18.478  1349  1349 D BluetoothMap: getConnectedDevices()
08-24 14:20:18.479  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 14:20:18.479  3886  3886 D PanProfile: Bluetooth service connected
08-24 14:20:18.480  3886  3886 D BluetoothMap: Proxy object connected
,08-24 14:20:18.480  3886  3886 D MapProfile: Bluetooth service connected
08-24 14:20:18.480  3886  3886 D BluetoothMap: getConnectedDevices()
,08-24 14:20:18.485  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:20:18.490  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:20:18.491  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:20:18.500  3886  3886 D BluetoothPbap: Proxy object connected
,08-24 14:20:18.500  3886  3886 D PbapServerProfile: Bluetooth service connected
08-24 14:20:18.500  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 14:20:18.501  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,08-24 14:20:18.504  1349  1349 D BluetoothPbap: Proxy object connected
,08-24 14:20:18.505  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-24 14:20:18.517  4169  4213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:18.534  4169  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:20:18.536  4169  4217 I BtOppRfcommListener: Accept thread started.
,08-24 14:20:18.548   871   871 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.548  1952  1964 D BluetoothHeadset: Proxy object connected
08-24 14:20:18.548   871   871 D BluetoothHeadset: Proxy object connected
08-24 14:20:18.548   871   888 D BluetoothHeadset: Proxy object connected
08-24 14:20:18.549  1952  1963 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.550  1349  2072 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.550  1349  1349 D HeadsetProfile: Bluetooth service connected
08-24 14:20:18.550  3886  3897 D BluetoothHeadset: Proxy object connected
08-24 14:20:18.551  3886  3886 D HeadsetProfile: Bluetooth service connected
08-24 14:20:18.551   871   871 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.558   871   888 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.560   871   888 D BluetoothHeadset: Proxy object connected
,08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:18.951  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:18.959  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:18.962  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:18.962  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d0c93b9 added. We now have 8 listener(s)
08-24 14:20:18.963  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:20:18.968   871  2245 D WifiService: setWifiEnabled: false pid=3829, uid=10000
,08-24 14:20:18.969   871  2245 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:20:18.982  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:18.983   871  2145 D WifiService: setWifiEnabled: true pid=3829, uid=10000
,08-24 14:20:18.983   871  2145 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 14:20:18.998   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:19.010  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:19.018  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:19.024   871  1304 D WifiConfigStore: loaded 0 passpoint configs
08-24 14:20:19.025   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 14:20:19.026   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 14:20:19.027   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 14:20:19.027   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 14:20:19.027   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 14:20:19.027   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 14:20:19.044   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 14:20:19.044   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-24 14:20:19.045   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:19.046   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-24 14:20:19.046   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 14:20:19.103   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 14:20:19.104   871  1304 E native  : do suspend true
,08-24 14:20:19.104   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 14:20:19.142   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:20.009  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:20.016  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:20.028  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 14:20:20.030  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 14:20:20.034  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78a0f66 Bundle[{}]
,08-24 14:20:20.035  3829  3877 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:20:20.035  3829  3877 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 14:20:20.036  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 14:20:20.036  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 14:20:20.037  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 14:20:20.038  3829  3877 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:20:20.042  3829  3877 I System.out: Running OutgoingSocketThread
,08-24 14:20:20.046  3829  4224 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-24 14:20:20.050  3829  4224 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42688
,08-24 14:20:20.050  3829  4224 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 14:20:20.518   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 14:20:20.640   871  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.94 rxSuccessRate=9.19 delta 1000 -> 994
,08-24 14:20:20.641   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 14:20:20.641   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:20:20.656   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 14:20:20.740   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 14:20:20.743  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 14:20:21.045  3829  3877 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-24 14:20:21.046  3829  3877 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-24 14:20:21.055  3829  3877 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-24 14:20:21.057  3829  3877 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-24 14:20:21.058  3829  3877 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-24 14:20:21.064  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.064  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7373fe added. We now have 2 listener(s)
,08-24 14:20:21.066  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.066  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.066  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.066  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.066  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3f75f added. We now have 9 listener(s)
08-24 14:20:21.066  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.067  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:20:21.070  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:21.076  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:21.079  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:21.079  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:20:21.080  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.080  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9b275 added. We now have 3 listener(s)
,08-24 14:20:21.082  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:21.083  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:21.084  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.085  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.085  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:20:21.085  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:21.086  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8ed20a added. We now have 10 listener(s)
08-24 14:20:21.086  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.086  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:20:21.087  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:20:21.087  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:20:21.087  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.087  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.088  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.088  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:20:21.088  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7373fe removed from the list
08-24 14:20:21.089  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.089  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3f75f removed from the list
08-24 14:20:21.089  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:20:21.089  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.090  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.090  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.091  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:20:21.091  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.092  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.092  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3f75f not in the list
08-24 14:20:21.092  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.092  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.093  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.093  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.093  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.093  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8ed20a removed from the list
08-24 14:20:21.093  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:20:21.093  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.093  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.093  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.093  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9b275 removed from the list
,08-24 14:20:21.094  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.094  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78aaa7b added. We now have 2 listener(s)
08-24 14:20:21.096  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.096  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.096  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:20:21.096  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.097  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e4098 added. We now have 9 listener(s)
,08-24 14:20:21.097  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.097  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:20:21.100  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:21.106  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:21.110  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:21.110  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:20:21.111  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.111  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5004d6 added. We now have 3 listener(s)
,08-24 14:20:21.112  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:21.113  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:21.117  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:20:21.117  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.117  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.118  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:21.118  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f7357 added. We now have 10 listener(s)
08-24 14:20:21.119  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.119  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.119  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-24 14:20:21.119  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:20:21.119  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:20:21.119  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:20:21.123  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:20:21.123  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:20:21.127  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:20:21.128  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:20:21.128  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:20:21.132  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:20:21.132  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:20:21.132  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:20:21.133  3829  3877 D BluetoothAdapter: STATE_ON
,08-24 14:20:21.137  4169  4180 D BtGatt.GattService: registerClient() - UUID=7d7acd47-d4cf-405f-b37c-75aa865551f0
,08-24 14:20:21.138  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=7d7acd47-d4cf-405f-b37c-75aa865551f0, clientIf=5
08-24 14:20:21.139  3829  3841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 14:20:21.140  4169  4179 D BtGatt.GattService: start scan with filters
,08-24 14:20:21.144  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:20:21.144  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:20:21.144  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:20:21.144  4169  4189 D BtGatt.ScanManager: handling starting scan
08-24 14:20:21.144  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:20:21.147  4169  4189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96a539a
,08-24 14:20:21.150  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:20:21.150  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:20:21.150  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:20:21.152  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 14:20:21.152  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.153  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:20:21.153  4169  4189 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:20:21.157  3829  3877 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 14:20:21.158  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:20:21.158  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:20:21.158  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:20:21.158  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:20:21.158  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 14:20:21.158  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:20:21.158  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:20:21.158  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:20:21.159  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:20:21.159  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:20:21.160  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:20:21.161  4169  4208 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:20:21.162  4169  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 14:20:21.162  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:20:21.162  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:20:21.162  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 14:20:21.162  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:20:21.163  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:20:21.163  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:20:21.163  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.164  4169  4189 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:20:21.164  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:20:21.164  4169  4189 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:20:21.164  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:20:21.164  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:20:21.164  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:20:21.165  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.166  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 14:20:21.166  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:20:21.167  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:20:21.168  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:20:21.169  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:20:21.169  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:20:21.169  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.169  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.169  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.169  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.169  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78aaa7b removed from the list
,08-24 14:20:21.169  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.169  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e4098 removed from the list
08-24 14:20:21.169  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:20:21.170  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.170  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.170  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.171  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-24 14:20:21.182  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:20:21.182  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.182  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.183  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e4098 not in the list
08-24 14:20:21.183  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.183  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.184  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.184  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.184  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:20:21.184  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f7357 removed from the list
08-24 14:20:21.184  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.184  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.184  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.184  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.185  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5004d6 removed from the list
,08-24 14:20:21.186  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.186  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1adedf3 added. We now have 2 listener(s)
08-24 14:20:21.188  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 14:20:21.188  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.188  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.188  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.188  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.188  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.188  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2808ab0 added. We now have 9 listener(s)
08-24 14:20:21.189  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.190  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:20:21.192  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:20:21.193  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 14:20:21.193  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:21.196  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:20:21.198  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:21.198  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:20:21.198  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.198  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162d8ae added. We now have 3 listener(s)
,08-24 14:20:21.199  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:21.200  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.200  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.200  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:20:21.200  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:21.200  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.201  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9af764f added. We now have 10 listener(s)
,08-24 14:20:21.201  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:20:21.201  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.201  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:20:21.201  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.201  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.201  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:20:21.201  4169  4189 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:20:21.201  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:20:21.202  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:20:21.202  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:20:21.203  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 14:20:21.204  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 14:20:21.204  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 14:20:21.205  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:20:21.208  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:20:21.208  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.208  4169  4189 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:20:21.208  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:20:21.209   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 14:20:21.209  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 14:20:21.209  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:20:21.213  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:20:21.213  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:20:21.213  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:20:21.214  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:20:21.214  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 14:20:21.214  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.214   871  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 14:20:21.215   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 14:20:21.215   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:20:21.216  4169  4186 D BtGatt.GattService: registerClient() - UUID=c287dd02-5295-4a13-84b6-ea12743170ce
,08-24 14:20:21.216  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=c287dd02-5295-4a13-84b6-ea12743170ce, clientIf=5
08-24 14:20:21.217  3829  3840 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:20:21.217  4169  4209 D BtGatt.GattService: start scan with filters
08-24 14:20:21.220  4169  4189 D BtGatt.ScanManager: handling starting scan
,08-24 14:20:21.220  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:20:21.220  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 14:20:21.220  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:20:21.220  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:20:21.225  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 14:20:21.225  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.226  4169  4189 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:20:21.226  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:20:21.227  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:20:21.227  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:20:21.228   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:20:21.229  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 14:20:21.231  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:20:21.231  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.231  4169  4189 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 14:20:21.231  4169  4189 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 14:20:21.232  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.232  3829  3877 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 14:20:21.233  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:20:21.234  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:20:21.234  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:20:21.234   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:21.235  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.235  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.235  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 14:20:21.235   871  1304 D WifiStateMachine: Start Dhcp Watchdog 3
08-24 14:20:21.235  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.235  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1adedf3 removed from the list
08-24 14:20:21.235  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.236  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2808ab0 removed from the list
08-24 14:20:21.236  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:20:21.236  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.236  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.236  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 14:20:21.236  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.236  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.238  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2808ab0 not in the list
08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:20:21.238  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:20:21.238  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:20:21.238  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:20:21.239  3829  3877 D BluetoothAdapter: STATE_ON
08-24 14:20:21.239  4169  4209 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:20:21.240  4169  4207 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 14:20:21.240  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:20:21.240  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.240  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 14:20:21.241  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 14:20:21.241  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:20:21.241  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:20:21.241  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:20:21.242  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:20:21.242  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:20:21.242  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:20:21.242  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:20:21.242  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.243  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.243  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.243  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.243  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9af764f removed from the list
08-24 14:20:21.243  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:20:21.243  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:20:21.243  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.244  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:20:21.244  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.244  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.244  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162d8ae removed from the list
08-24 14:20:21.244  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:20:21.244  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.244  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e97286b added. We now have 2 listener(s)
08-24 14:20:21.246  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 14:20:21.246  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.246  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:20:21.246   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 14:20:21.246  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.246  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.246  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.247  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26effc8 added. We now have 9 listener(s)
08-24 14:20:21.247  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:20:21.247  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:20:21.249  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:20:21.252  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:20:21.252  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.252  4169  4189 D BtGatt.ScanManager: stopping BLe Batch
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:21.252  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:21.253   871  4227 D DhcpClient: Receive thread started
,08-24 14:20:21.254  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:20:21.254  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:20:21.254  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.254  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d14f86 added. We now have 3 listener(s)
,08-24 14:20:21.256  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:21.257  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:21.257  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 14:20:21.257  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.257  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:20:21.257  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:20:21.257  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fde047 added. We now have 10 listener(s)
08-24 14:20:21.257  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.257  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.257  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 14:20:21.258  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:20:21.258  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.258  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:20:21.258  4169  4189 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 14:20:21.258  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:20:21.258  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:20:21.261  3829  3877 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 14:20:21.261  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:20:21.263  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 14:20:21.263  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.264  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:20:21.264  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 14:20:21.265  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:20:21.267  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:20:21.267  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:20:21.267  3829  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 14:20:21.267  3829  3877 D BluetoothAdapter: STATE_ON
,08-24 14:20:21.269  4169  4179 D BtGatt.GattService: registerClient() - UUID=aa8e9a8b-07cc-4eed-aef0-0847f4e95b04
,08-24 14:20:21.269  4169  4185 D BtGatt.GattService: onClientRegistered() - UUID=aa8e9a8b-07cc-4eed-aef0-0847f4e95b04, clientIf=5
08-24 14:20:21.269  3829  3840 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 14:20:21.269  4169  4186 D BtGatt.GattService: start scan with filters
,08-24 14:20:21.271  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:20:21.271  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:20:21.271  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:20:21.271  4169  4189 D BtGatt.ScanManager: handling starting scan
,08-24 14:20:21.271  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:20:21.273  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:20:21.273  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:20:21.273  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:20:21.274  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:20:21.276  4169  4185 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 14:20:21.276  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.276  4169  4189 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 14:20:21.277  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:20:21.277  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:20:21.277  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:20:21.277  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.277  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.277  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 14:20:21.277  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.277  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e97286b removed from the list
08-24 14:20:21.277  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:20:21.278  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26effc8 removed from the list
08-24 14:20:21.278  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:20:21.278  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:20:21.278  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.278  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 14:20:21.278  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:20:21.278  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:20:21.279  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26effc8 not in the list
,08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 14:20:21.279  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:20:21.279  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 14:20:21.279  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:20:21.280  3829  3877 D BluetoothAdapter: STATE_ON
,08-24 14:20:21.280  4169  4208 D BtGatt.GattService: stopScan() - queue size =1
08-24 14:20:21.281  4169  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 14:20:21.281  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:20:21.281  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 14:20:21.281  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:20:21.281  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 14:20:21.281  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 14:20:21.281  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:20:21.281  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.281  4169  4189 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 14:20:21.281  4169  4189 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 14:20:21.282  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:20:21.282  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:20:21.282  3829  3877 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:20:21.282  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:20:21.282  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.283  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.283  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.283  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.283  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:20:21.283  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fde047 removed from the list
08-24 14:20:21.283  3829  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:20:21.283  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.283  3829  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:20:21.283  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:20:21.283  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.284  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.284  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d14f86 removed from the list
08-24 14:20:21.284  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.284  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42e39e3 added. We now have 2 listener(s)
08-24 14:20:21.286  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:20:21.286  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:20:21.286  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.286  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.286  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3ffe0 added. We now have 9 listener(s)
08-24 14:20:21.286  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.286  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:20:21.288  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:20:21.290  4169  4185 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 14:20:21.290  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:20:21.291  3829  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:20:21.293  3829  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:20:21.293  3829  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:20:21.293  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:20:21.293  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20cc95e added. We now have 3 listener(s)
08-24 14:20:21.294  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 14:20:21.294  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.294  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:20:21.294  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:20:21.294  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:20:21.294  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:20:21.295  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:20:21.295  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:20:21.295  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180913f added. We now have 10 listener(s)
,08-24 14:20:21.295  3829  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:20:21.295  3829  3877 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:20:21.295  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:20:21.295  3829  3877 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:20:21.295  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:20:21.295  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.296  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:20:21.296  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:20:21.296  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42e39e3 removed from the list
08-24 14:20:21.296  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:20:21.296  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3ffe0 removed from the list
08-24 14:20:21.296  3829  3877 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:20:21.296  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.296  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.296  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:20:21.297  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:20:21.297  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.297  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:20:21.297  3829  3877 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e3ffe0 not in the list
08-24 14:20:21.297  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.297  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.298  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:20:21.298  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:20:21.298  3829  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:20:21.298  3829  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180913f removed from the list
08-24 14:20:21.298  3829  3877 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:20:21.298  3829  3877 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:20:21.298  3829  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:20:21.299  3829  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 14:20:21.299  3829  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20cc95e removed from the list
08-24 14:20:21.299  4169  4185 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 14:20:21.299  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 14:20:21.299  4169  4189 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:20:21.299  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 14:20:21.299  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 14:20:21.299  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 14:20:21.300  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:20:21.300  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 14:20:21.300  3829  3877 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:20:21.304  4169  4185 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 14:20:21.304  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.304  4169  4189 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 14:20:21.306  3829  4228 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-24 14:20:21.306  3829  4228 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-24 14:20:21.306  3829  4228 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 14:20:21.308  3829  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
08-24 14:20:21.308  3829  4229 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-24 14:20:21.308  4169  4185 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 14:20:21.308  4169  4185 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 14:20:21.308  3829  4229 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 14:20:21.310  3829  3877 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 14:20:21.310  3829  3877 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 14:20:21.310  3829  3877 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 14:20:21.310  3829  3877 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 14:20:21.311  3829  3877 D com.test.thalitest.ThaliTestRunner: Total duration: 22725 ms
,08-24 14:20:21.312  3829  3877 I jxcore-log: Total number of executed tests:  80
08-24 14:20:21.312  3829  3877 I jxcore-log: 
,08-24 14:20:21.312  3829  3877 I jxcore-log: Number of passed tests:  80
08-24 14:20:21.312  3829  3877 I jxcore-log: 
08-24 14:20:21.312  3829  3877 I jxcore-log: Number of failed tests:  0
08-24 14:20:21.312  3829  3877 I jxcore-log: 
08-24 14:20:21.312  3829  3877 I jxcore-log: Number of ignored tests:  0
08-24 14:20:21.312  3829  3877 I jxcore-log: 
08-24 14:20:21.313  3829  3877 I jxcore-log: Total duration:  22725
08-24 14:20:21.313  3829  3877 I jxcore-log: 
,08-24 14:20:21.313  3829  3877 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 14:20:21.313  3829  3877 I jxcore-log: 
,08-24 14:20:21.316  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.316  3829  3877 I jxcore-log: 
08-24 14:20:21.319  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.319  3829  3877 I jxcore-log: 
08-24 14:20:21.320  3829  3829 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 14:20:21.321  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.321  3829  3877 I jxcore-log: 
08-24 14:20:21.322  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.322  3829  3877 I jxcore-log: 
08-24 14:20:21.322  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.322  3829  3877 I jxcore-log: 
08-24 14:20:21.323  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.323  3829  3877 I jxcore-log: 
08-24 14:20:21.325  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.325  3829  3877 I jxcore-log: 
08-24 14:20:21.327  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.327  3829  3877 I jxcore-log: 
08-24 14:20:21.328  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.328  3829  3877 I jxcore-log: 
08-24 14:20:21.328  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.328  3829  3877 I jxcore-log: 
08-24 14:20:21.329  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.329  3829  3877 I jxcore-log: 
08-24 14:20:21.330  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:20:21.330  3829  3877 I jxcore-log: 
08-24 14:20:21.331  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.331  3829  3877 I jxcore-log: 
08-24 14:20:21.331  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.331  3829  3877 I jxcore-log: 
08-24 14:20:21.332  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.332  3829  3877 I jxcore-log: 
08-24 14:20:21.332  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.332  3829  3877 I jxcore-log: 
08-24 14:20:21.333  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.333  3829  3877 I jxcore-log: 
08-24 14:20:21.334  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.334  3829  3877 I jxcore-log: 
08-24 14:20:21.334  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.334  3829  3877 I jxcore-log: 
08-24 14:20:21.335  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.335  3829  3877 I jxcore-log: 
08-24 14:20:21.336  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.336  3829  3877 I jxcore-log: 
08-24 14:20:21.336  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.336  3829  3877 I jxcore-log: 
08-24 14:20:21.337  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.337  3829  3877 I jxcore-log: 
08-24 14:20:21.337   871  1304 E native  : do suspend false
08-24 14:20:21.337  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.337  3829  3877 I jxcore-log: 
08-24 14:20:21.338  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.338  3829  3877 I jxcore-log: 
08-24 14:20:21.339  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:20:21.339  3829  3877 I jxcore-log: 
,08-24 14:20:21.339  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.339  3829  3877 I jxcore-log: 
08-24 14:20:21.340  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.340  3829  3877 I jxcore-log: 
,08-24 14:20:21.340  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.340  3829  3877 I jxcore-log: 
,08-24 14:20:21.341  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.341  3829  3877 I jxcore-log: 
,08-24 14:20:21.342  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.342  3829  3877 I jxcore-log: 
08-24 14:20:21.342  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.342  3829  3877 I jxcore-log: 
,08-24 14:20:21.343  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:20:21.343  3829  3877 I jxcore-log: 
,08-24 14:20:21.347   871  1900 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 14:20:21.385   871  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-24 14:20:21.385   871  1900 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-24 14:20:21.386   871  1900 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 14:20:21.398   871  4227 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 14:20:21.399   871  1900 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 14:20:21.400   372   870 D CommandListener: Setting iface cfg
,08-24 14:20:21.403   871  1900 D DhcpClient: Scheduling renewal in 86399s
,08-24 14:20:21.404   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[],
,08-24 14:20:21.406   871  1304 E native  : do suspend true
,08-24 14:20:21.419   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 14:20:21.420   871  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 14:20:21.421   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 14:20:21.423   871  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-24 14:20:21.426   871  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:20:21.465   871  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 14:20:21.465   871  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-24 14:20:21.467   871  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 14:20:21.469   871  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-24 14:20:21.471   871  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 14:20:21.478   871  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 14:20:21.481   871  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 14:20:21.481   871  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-24 14:20:21.481   871  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-24 14:20:21.481   871  1306 D ConnectivityService:    accepting network in place of null,
,08-24 14:20:21.482   871  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-24 14:20:21.482   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 14:20:21.482   871  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
08-24 14:20:21.488   871  4226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217859, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 14:20:21.510   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:21.540   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 14:20:21.547   871  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 14:20:21.548   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 14:20:21.553   871   888 D Tethering: MasterInitialState.processMessage what=3
08-24 14:20:21.553   871  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-24 14:20:21.567   871  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:4001:816::200e
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:20:21.572  3829  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:20:21.574  3829  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:20:21.576  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:20:21.576  3829  3877 I jxcore-log: 
08-24 14:20:21.583  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-24 14:20:21.589  1709  1709 D SystemUpdateService: onCreate
08-24 14:20:21.591  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 14:20:21.629  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 14:20:21.635   871  4225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:20:21 GMT], X-Android-Received-Millis=[1472041221634], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472041221608]}
08-24 14:20:21.635   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 14:20:21.635   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-24 14:20:21.636   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 14:20:21.636   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 14:20:21.645  1709  2444 I iu.UploadsManager: num queued entries: 0
08-24 14:20:21.646  1709  2444 I iu.UploadsManager: num updated entries: 0
08-24 14:20:21.646  1709  2444 I iu.SyncManager: NEXT; no task
,08-24 14:20:21.650  1709  4240 I SystemUpdateService: active receiver: enabled
,08-24 14:20:21.656  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:20:21.660  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-24 14:20:21.661  3941  3941 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:20:21.667  3829  3829 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:20:21.670  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:20:21.670  3829  3877 I jxcore-log: 
08-24 14:20:21.671  3941  3941 D SprintDMHelper: simOperator: 
08-24 14:20:21.671  3941  3941 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 14:20:21.691  1709  4242 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-24 14:20:21.692  1709  4242 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:20:21.693  1709  4242 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 14:20:21.705  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:20:21.727  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:20:21.734  1709  4240 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 14:20:21.744  3829  3829 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:20:21.746  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:20:21.746  3829  3877 I jxcore-log: 
,08-24 14:20:21.748  1709  4240 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 14:20:21.755  1709  4240 I SystemUpdateService: now status is 0 (complete)
,08-24 14:20:21.755  1709  4240 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 14:20:21.755  1709  4240 I SystemUpdateService: file has been verified
,08-24 14:20:21.759  1709  4240 I SystemUpdateService: OTA package size = 12249756
,08-24 14:20:21.779  1709  4240 I SystemUpdateService: showing system update notification
,08-24 14:20:21.784  3829  3829 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:20:21.786  3829  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:20:21.786  3829  3877 I jxcore-log: 
,08-24 14:20:21.811   871  2145 I ActivityManager: Start proc 4252:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
08-24 14:20:21.828  1709  1709 D SystemUpdateService: onDestroy
,08-24 14:20:21.834  2265  4247 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 14:20:21.874  4252  4252 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-24 14:20:21.899  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-24 14:20:21.899  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 14:20:21.899  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 14:20:21.899  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:20:21.988  4252  4265 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-24 14:20:22.007  1709  4242 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-24 14:20:22.031  4230  4230 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 14:20:22.036  4230  4230 D AndroidRuntime: CheckJNI is OFF
,08-24 14:20:22.078  4230  4230 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 14:20:22.121  4230  4230 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 14:20:22.127  4252  4265 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 14:20:22.143  4230  4230 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:20:22.160   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 14:20:22.161   871   884 I ActivityManager: Killing 3829:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-24 14:20:22.214  4252  4265 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:20:22.259  4286  4286 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1996792502.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1996792502.dex
,08-24 14:20:22.270   871   894 W PackageSettings: Skipping PackageSetting{334303f com.example.hello/10273} due to missing metadata
,08-24 14:20:22.294   871  1381 D GraphicsStats: Buffer count: 2
,08-24 14:20:22.295   871  1381 I WindowState: WIN DEATH: Window{5abd7f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:20:22.296   871  1305 D WifiService: Client connection lost with reason: 4
,08-24 14:20:22.319  4286  4286 I dex2oat : dex2oat took 60.899ms (threads: 4) arena alloc=412KB java alloc=29KB native alloc=1515KB free=1556KB
,08-24 14:20:22.327   871   894 I art     : Starting a blocking GC Explicit
,08-24 14:20:22.332   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-24 14:20:22.333   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-24 14:20:22.337   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-24 14:20:22.337   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 14:20:22.337   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.337   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.337   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:20:22.337   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-24 14:20:22.339   871   884 I ActivityManager:   Force finishing activity ActivityRecord{823b42d u0 com.test.thalitest/.MainActivity t2}
,08-24 14:20:22.346   871  1971 W ActivityManager: Spurious death for ProcessRecord{ebde97e 0:com.test.thalitest/u0a0}, curProc for 3829: null
,08-24 14:20:22.374  4252  4252 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-24 14:20:22.377   871   894 I art     : Explicit concurrent mark sweep GC freed 15818(1078KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 891us total 49.863ms
,08-24 14:20:22.406   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 14:20:22.410   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 14:20:22.410  4230  4230 I art     : System.exit called, status: 0
,08-24 14:20:22.411  4230  4230 I AndroidRuntime: VM exiting with result code 0.
,08-24 14:20:22.440   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-24 14:20:22.446  4169  4169 D BluetoothMapAppObserver: onReceive
,08-24 14:20:22.447  4169  4169 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-24 14:20:22.447  1866  1866 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-24 14:20:22.449  1882  2184 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:20:22.454   871  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:20:22.456  3653  3653 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-24 14:20:22.459  1866  4309 I Keyboard.Facilitator.DecoderInitializer: run()
,08-24 14:20:22.479  1866  4309 I Decoder : createOrResetDecoder
,08-24 14:20:22.494  1952  1952 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-24 14:20:22.500   871  1983 I ActivityManager: Start proc 4312:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-24 14:20:22.529  4312  4312 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-24 14:20:22.536  1508  1508 I ConfigService: onCreate
,08-24 14:20:22.555  1508  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 14:20:22.555  1508  4325 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 14:20:22.555  1508  4325 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-24 14:20:22.558   871  1976 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3829 uid 10000
,08-24 14:20:22.559  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-24 14:20:22.560   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 14:20:22.566  1508  4325 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-24 14:20:22.588  1866  4309 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 14:20:22.600  1965  2060 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-24 14:20:22.601   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-24 14:20:22.602   871   883 E PackageManager: Failed to write settings, restoring backup
08-24 14:20:22.602   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 14:20:22.602   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 14:20:22.602   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 14:20:22.602   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 14:20:22.602   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 14:20:22.602   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.602   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.602   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:20:22.607   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-24 14:20:22.607   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 14:20:22.607   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:20:22.607   871   884 E DropBoxManagerService: 	... 13 more
,08-24 14:20:22.612   871  1380 I ActivityManager: Start proc 4330:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-24 14:20:22.613  1965  2060 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 14:20:22.613  1965  2060 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1965
08-24 14:20:22.613  1965  2060 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.613  1965  2060 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:20:22.615   871  4336 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:20:22.615   871  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:20:22.615   871  4336 E DropBoxManagerService: 	... 5 more
08-24 14:20:22.615   871  2244 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 14:20:22.619  1965  2060 I Process : Sending signal. PID: 1965 SIG: 9
,08-24 14:20:22.641  4312  4312 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-24 14:20:22.643  1866  4309 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 14:20:22.645  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 14:20:22.645  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-24 14:20:22.648  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-24 14:20:22.648  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 14:20:22.649  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 14:20:22.649  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 14:20:22.649  1866  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 14:20:22.649  1866  4309 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-24 14:20:22.649  1866  4309 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 14:20:22.650  1866  4309 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 14:20:22.650  1866  4309 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 14:20:22.650  1866  4309 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 14:20:22.679  4312  4347 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-24 14:20:22.690   871  2177 I ActivityManager: Start proc 4349:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-24 14:20:22.724  4349  4349 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-24 14:20:22.756   871  1971 D GraphicsStats: Buffer count: 1
,08-24 14:20:22.757   871  2244 I WindowState: WIN DEATH: Window{10dd481 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-24 14:20:22.767   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1965) has died
,08-24 14:20:22.768   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-24 14:20:22.770   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 14:20:22.776  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 14:20:22.777  1508  1508 D AndroidRuntime: Shutting down VM
08-24 14:20:22.778  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
08-24 14:20:22.778  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
08-24 14:20:22.778  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 14:20:22.778  1508  1508 E AndroidRuntime: 	... 8 more
,08-24 14:20:22.793   871   884 I ActivityManager: Start proc 4366:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 14:20:22.797   871  1971 I ActivityManager: Killing 3706:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-24 14:20:22.799   871  4376 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:20:22.799   871  4376 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:20:22.799   871  4376 E DropBoxManagerService: 	... 5 more
,08-24 14:20:22.809  4312  4329 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.809  4312  4329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.809  4312  4329 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:20:22.841  4252  4273 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at gzq.a(SourceFile:1037)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at gzq.a(SourceFile:1060)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at hdi.b(SourceFile:148)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at hdm.run(SourceFile:124)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at hgy.run(SourceFile:40)
08-24 14:20:22.841  4252  4273 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-24 14:20:22.844  4252  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at gzq.b(SourceFile:1110)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at hdi.a(SourceFile:135)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at hdl.run(SourceFile:112)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at hgy.run(SourceFile:40)
08-24 14:20:22.844  4252  4272 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at gzq.b(SourceFile:1110)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at hdi.a(SourceFile:135)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at hdl.run(SourceFile:112)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at hgy.run(SourceFile:40)
08-24 14:20:22.844  4252  4272 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-24 14:20:22.848  4252  4272 W SQLiteOpenHelper: Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
,08-24 14:20:22.888  4312  4329 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-24 14:20:22.904  4312  4347 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.904  4312  4347 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 14:20:22.905  4312  4347 E AndroidRuntime: Process: android.process.acore, PID: 4312
08-24 14:20:22.905  4312  4347 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 14:20:22.905  4312  4347 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:20:22.905  4312  4347 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:20:22.906  4312  4329 I Process : Sending signal. PID: 4312 SIG: 9
,08-24 14:20:22.920  1508  1508 I Process : Sending signal. PID: 1508 SIG: 9
08-24 14:20:22.922   871  4385 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:20:22.922   871  4385 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:20:22.922   871  4385 E DropBoxManagerService: 	... 5 more
08-24 14:20:22.931   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
