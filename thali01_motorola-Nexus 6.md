#### Test 83444050adbb179_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-06 19:23:42.949  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:23:42.967  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:23:42.973  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:23:43.033  1501  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-06 19:23:43.033  1501  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 19:23:43.033  1501  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:23:43.033  1501  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 19:23:43.080  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 19:23:43.081  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 19:23:43.081  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-06 19:23:43.623  3803  3803 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 19:23:43.627  3803  3803 D AndroidRuntime: CheckJNI is OFF
09-06 19:23:43.662  3803  3803 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 19:23:43.704  3803  3803 I Radio-JNI: register_android_hardware_Radio DONE
09-06 19:23:43.723  3803  3803 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:23:43.727   875  2018 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:23:43.765   875  2018 I ActivityManager: Start proc 3812:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 19:23:43.791  3803  3803 D AndroidRuntime: Shutting down VM
09-06 19:23:43.929  3812  3812 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 19:23:43.959  3812  3812 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 19:23:43.971  3812  3812 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 2523-2529)
09-06 19:23:43.971  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:23:43.995  3812  3812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d71b649}
09-06 19:23:43.995  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:23:43.996  3812  3812 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:23:44.004  3812  3812 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 19:23:44.007  3812  3812 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:23:44.026  3812  3812 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:23:44.041  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:23:44.041  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:23:44.041  3812  3812 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:23:44.041  3812  3812 I Adreno  : Build Date                       : 10/20/15
09-06 19:23:44.041  3812  3812 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:23:44.041  3812  3812 I Adreno  : Local Branch                     : M14
09-06 19:23:44.041  3812  3812 I Adreno  : Remote Branch                    : 
09-06 19:23:44.041  3812  3812 I Adreno  : Remote Branch                    : 
09-06 19:23:44.041  3812  3812 I Adreno  : Reconstruct Branch               : 
,09-06 19:23:44.128   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6fe7f36:true
,09-06 19:23:44.189  3812  3812 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 19:23:44.206  3812  3812 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 19:23:44.284  3812  3850 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 19:23:44.304  3812  3836 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-06 19:23:44.365  3812  3850 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 19:23:44.478   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +728ms)
,09-06 19:23:44.489  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-06 19:23:44.563  3812  3812 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3812
,09-06 19:23:44.714  3812  3812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:23:44.870  3812  3852 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1681458896
,09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:23:44.878  3812  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7808d4 added. We now have 1 listener(s)
,09-06 19:23:44.881  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-06 19:23:44.882  3812  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:23:44.882  3812  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:44.883  3812  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:23:44.886  3812  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e215c3 added. We now have 1 listener(s)
09-06 19:23:44.886  3812  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:44.895   875  1307 D WifiService: New client listening to asynchronous messages
,09-06 19:23:44.897  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:23:44.897  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 19:23:44.897  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:23:44.897  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:23:44.898  3812  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:23:44.901  3812  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:23:44.901  3812  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-06 19:23:44.916  3812  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:44.917  3812  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:44.917  3812  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:23:44.918  3812  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:23:44.922  3812  3852 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:23:44.925  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:44.934  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:44.974  3812  3812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:23:45.819  3812  3858 W jxcore-log: Initializing JXcore engine
,09-06 19:23:45.819  3812  3858 W jxcore-log: JXcore engine is ready
,09-06 19:23:45.857  3858  3858 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-06 19:23:45.857  3858  3858 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11946]" dev="sockfs" ino=11946 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-06 19:23:45.857  3858  3858 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:23:45.857  3858  3858 W Thread-325: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25866]" dev="sockfs" ino=25866 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-06 19:23:45.874  3812  3858 W jxcore-log: Starting JXcore engine
,09-06 19:23:45.957  3812  3858 W jxcore-log: Platform android
09-06 19:23:45.957  3812  3858 W jxcore-log: 
,09-06 19:23:45.958  3812  3858 W jxcore-log: Process ARCH arm
09-06 19:23:45.958  3812  3858 W jxcore-log: 
,09-06 19:23:46.145  3812  3858 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:23:46.145  3812  3858 I jxcore-log: 
,09-06 19:23:46.146  3812  3858 W jxcore-log: JXcore engine is started
,09-06 19:23:46.160  3812  3852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:23:46.166  3812  3812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:23:55.662  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:23:55.662  3812  3858 I jxcore-log: 
,09-06 19:23:55.664  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:23:55.664  3812  3858 I jxcore-log: 
,09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:55.678  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:23:55.683  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:23:55.685  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:23:55.685  3812  3858 I jxcore-log: 
,09-06 19:23:55.687  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:23:55.687  3812  3858 I jxcore-log: 
,09-06 19:23:56.183  3812  3858 D executeNativeTests: Running unit tests
,09-06 19:23:56.241  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:23:56.241  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 added. We now have 2 listener(s)
09-06 19:23:56.242  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:23:56.242  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:23:56.242  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:23:56.242  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:56.242  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d added. We now have 2 listener(s)
09-06 19:23:56.242  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:56.243  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:23:56.246  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.266  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:23:56.268  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:23:56.268  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:23:56.270  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:23:56.270  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:23:56.270  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:23:56.272  3812  3858 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:23:56.272  3812  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-06 19:23:56.272  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 19:23:56.272  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:23:56.272  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:23:56.273  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.273  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.273  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.274  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:23:56.274  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.274  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:23:56.274  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:23:56.274  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 removed from the list
,09-06 19:23:56.274  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.274  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d removed from the list
,09-06 19:23:56.276  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:56.276  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.276  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.277  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.277  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.281  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.281  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.281  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.281  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.283  3812  3858 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:23:56.283  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.283  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.284  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.284  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.284  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.284  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.284  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.284  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.284  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.284  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.284  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.284  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.284  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.284  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.285  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.285  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.285  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.285  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.289  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:23:56.289  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:23:56.289  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:23:56.290  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:23:56.291  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:23:56.291  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.291  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.291  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.291  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.291  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.291  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.291  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.291  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.292  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.292  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.292  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.292  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.292  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.292  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.293  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.293  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.293  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.293  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.293  3812  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:23:56.295  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.303  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:56.305  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.305  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:56.305  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:56.305  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:23:56.305  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:23:56.305  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.306  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:23:56.308  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.310  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.312  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:23:56.312  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:23:56.319  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:23:56.321  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:23:56.322  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:23:56.325  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:23:56.328  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:23:56.328  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:23:56.329  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:23:56.330  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:23:56.331  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:23:56.334  2703  2901 D BtGatt.GattService: registerClient() - UUID=905ea4ee-9a4a-49fa-ac81-7173b7c25366
09-06 19:23:56.335  2703  2757 D BtGatt.GattService: onClientRegistered() - UUID=905ea4ee-9a4a-49fa-ac81-7173b7c25366, clientIf=5
09-06 19:23:56.336  3812  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:23:56.337  2703  2718 D BtGatt.GattService: start scan with filters
09-06 19:23:56.340  2703  2763 D BtGatt.ScanManager: handling starting scan
09-06 19:23:56.341  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:23:56.341  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:23:56.341  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:23:56.341  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:23:56.342  2703  2763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
09-06 19:23:56.343  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:23:56.344  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:23:56.344  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:23:56.346  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:23:56.349  3812  3858 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:23:56.349  2703  2757 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:23:56.349  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.350  2703  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:23:56.352  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.352  3812  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:23:56.352  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.352  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:23:56.352  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.352  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:23:56.352  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:23:56.352  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:23:56.352  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:23:56.352  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:23:56.353  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:23:56.353  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:23:56.354  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:23:56.355  2703  2714 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:23:56.356  2703  2901 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:23:56.356  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:23:56.356  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:23:56.356  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:23:56.356  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:23:56.356  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:23:56.358  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.358  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:23:56.358  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:23:56.359  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:56.359  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:56.360  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.360  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.360  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.360  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.360  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.360  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:56.360  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.360  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.360  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.361  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.361  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.361  3812  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:23:56.363  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:23:56.363  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.363  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.364  2703  2763 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:23:56.365  2703  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.367  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:56.371  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.372  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:56.372  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:23:56.372  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:23:56.372  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:23:56.372  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.373  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:23:56.373  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.376  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.377  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:23:56.377  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:23:56.384  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:23:56.386  2703  2757 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:23:56.391  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.386  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:23:56.391  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:23:56.402  2703  2757 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:23:56.402  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:23:56.402  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.403  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:23:56.403  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:23:56.405  3812  3858 D BluetoothAdapter: STATE_ON
,09-06 19:23:56.409  2703  2714 D BtGatt.GattService: registerClient() - UUID=e2b1410c-7a6f-44ce-98f6-a87f2d4940d3
,09-06 19:23:56.410  2703  2757 D BtGatt.GattService: onClientRegistered() - UUID=e2b1410c-7a6f-44ce-98f6-a87f2d4940d3, clientIf=5
,09-06 19:23:56.410  3812  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:23:56.410  2703  2901 D BtGatt.GattService: start scan with filters
,09-06 19:23:56.413  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:23:56.413  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.414  2703  2763 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:23:56.416  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:23:56.416  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:23:56.416  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:23:56.416  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:23:56.419  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:23:56.419  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:23:56.419  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:23:56.420  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:23:56.422  3812  3858 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:23:56.425  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:23:56.425  3812  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:23:56.425  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.425  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:23:56.425  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.425  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:23:56.425  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:23:56.425  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:23:56.425  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:23:56.425  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:23:56.425  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:23:56.425  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:23:56.427  2703  2757 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:23:56.427  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.427  2703  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:23:56.427  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:23:56.428  2703  2718 D BtGatt.GattService: stopScan() - queue size =0
09-06 19:23:56.429  2703  2714 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:23:56.429  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:23:56.429  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:23:56.429  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:23:56.429  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:23:56.429  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:23:56.430  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.431  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:23:56.431  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:23:56.431  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:56.431  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:56.433  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.433  2703  2757 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:23:56.433  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.433  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.433  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:23:56.434  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.434  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.434  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:56.434  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
,09-06 19:23:56.434  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.434  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
,09-06 19:23:56.434  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.435  2703  2763 D BtGatt.ScanManager: handling starting scan
,09-06 19:23:56.435  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.436  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.436  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.437  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.437  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.437  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.437  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
,09-06 19:23:56.437  3812  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:23:56.438  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.442  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:23:56.443  2703  2757 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:23:56.443  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:23:56.443  2703  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:23:56.444  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.444  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:23:56.446  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:23:56.446  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:23:56.446  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:23:56.446  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:23:56.446  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:23:56.446  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:56.449  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:56.450  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:23:56.450  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
09-06 19:23:56.453  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:23:56.453  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:23:56.453  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:23:56.453  2703  2763 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:23:56.453  2703  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:23:56.453  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 19:23:56.453  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:23:56.458  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:23:56.458  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:23:56.458  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:23:56.458  3812  3858 D BluetoothAdapter: STATE_ON
,09-06 19:23:56.460  2703  2714 D BtGatt.GattService: registerClient() - UUID=2d757e22-2126-405b-b6ba-4af8db86b6b4
,09-06 19:23:56.460  2703  2757 D BtGatt.GattService: onClientRegistered() - UUID=2d757e22-2126-405b-b6ba-4af8db86b6b4, clientIf=5
09-06 19:23:56.464  3812  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:23:56.464  2703  2718 D BtGatt.GattService: start scan with filters
09-06 19:23:56.466  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:23:56.466  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:23:56.466  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:23:56.466  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:23:56.468  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:23:56.469  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:23:56.469  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:23:56.470  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:23:56.471  2703  2757 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:23:56.471  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:23:56.472  3812  3858 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:23:56.472  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.472  3812  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:23:56.472  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:23:56.472  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:23:56.472  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.472  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:23:56.473  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:23:56.473  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:23:56.473  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:23:56.473  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:23:56.473  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:23:56.473  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:23:56.473  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:23:56.474  2703  2901 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:23:56.474  2703  2714 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:23:56.475  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:23:56.475  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:23:56.475  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:23:56.475  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:23:56.475  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:23:56.476  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.476  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:23:56.476  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:23:56.476  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:23:56.477  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:23:56.478  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:23:56.478  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.478  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.478  3812  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:23:56.478  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.478  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.478  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.478  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.478  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.478  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:23:56.478  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.479  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.479  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.479  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.479  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.479  2703  2757 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:23:56.479  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:23:56.479  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.479  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.480  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.480  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:23:56.481  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.481  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.481  3812  3858 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:23:56.482  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.482  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.482  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.482  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.482  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.482  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.482  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.482  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.482  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.482  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.482  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.482  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.482  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.482  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.483  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:23:56.483  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.483  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.483  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
,09-06 19:23:56.484  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:23:56.484  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.484  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:23:56.484  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.484  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.484  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.485  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.485  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
,09-06 19:23:56.485  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:23:56.485  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.485  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.485  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.485  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.485  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.485  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.486  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:23:56.486  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.486  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.486  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.486  3812  3858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:23:56.487  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.487  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.487  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.487  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.487  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.487  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.487  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:23:56.487  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.487  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.488  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.488  2703  2763 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:23:56.488  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.488  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.488  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.488  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.488  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.488  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.488  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.489  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.489  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.489  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.489  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-06 19:23:56.489  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.489  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.489  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.489  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.489  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.489  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.490  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.490  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.490  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.490  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:23:56.490  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.490  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.490  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.490  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.490  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:23:56.490  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.490  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.490  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.491  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:23:56.491  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:23:56.491  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 19:23:56.491  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:23:56.491  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:23:56.491  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:23:56.492  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.492  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:23:56.492  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.492  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:23:56.492  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.492  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.492  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.492  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.492  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.492  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.492  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.492  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.492  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.492  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.493  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.493  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.493  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.494  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
,09-06 19:23:56.494  2703  2757 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:23:56.494  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.494  2703  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:23:56.494  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:23:56.494  3812  3858 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-06 19:23:56.495  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:23:56.497  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:23:56.497  3812  3858 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:23:56.497  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:23:56.498  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-06 19:23:56.498  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:23:56.499  3812  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:23:56.499  3812  3858 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:23:56.499  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:23:56.499  3812  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:23:56.499  3812  3858 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-06 19:23:56.499  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:23:56.499  3812  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:23:56.499  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-06 19:23:56.501  2703  2757 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:23:56.501  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.502  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:23:56.503  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:23:56.503  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:23:56.503  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-06 19:23:56.503  2703  2763 D BtGatt.ScanManager: handling starting scan
09-06 19:23:56.503  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:23:56.503  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:23:56.504  3812  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:23:56.504  3812  3858 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:23:56.504  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.505  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.505  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.505  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.505  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.505  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.505  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:23:56.506  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.506  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.506  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.506  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.506  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.506  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.506  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.506  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.507  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:23:56.507  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.507  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.507  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.508  3812  3858 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:23:56.508  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:23:56.508  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.508  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.508  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.509  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.509  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.509  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.509  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.509  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.509  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.509  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.509  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.509  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.509  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.509  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.510  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.510  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.510  2703  2757 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:23:56.510  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.510  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.510  3812  3858 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:23:56.510  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.511  2703  2763 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:23:56.511  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:23:56.511  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.511  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.511  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.511  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.511  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.511  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.511  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.511  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.511  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.511  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.511  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.511  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.511  3812  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-06 19:23:56.512  3812  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
09-06 19:23:56.512  3812  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
09-06 19:23:56.513  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.513  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.513  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.513  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:23:56.515  3812  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:23:56.515  3812  3858 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-06 19:23:56.515  3812  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:23:56.515  3812  3858 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-06 19:23:56.515  3812  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:23:56.515  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:23:56.515  3812  3858 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:23:56.515  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.516  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.516  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.516  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:23:56.516  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.516  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.516  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.516  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.516  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.516  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.516  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.516  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.516  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.516  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.517  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.517  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.517  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:23:56.517  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.518  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.518  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.518  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.518  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.518  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.518  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
,09-06 19:23:56.518  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.518  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.518  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.518  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.519  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.519  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.519  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.519  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.519  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.519  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.519  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:23:56.519  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.519  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.519  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.519  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.519  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:23:56.519  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.519  2703  2763 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:23:56.519  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.519  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.519  2703  2763 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:23:56.519  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.519  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.519  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.519  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.519  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.519  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.520  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.520  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.520  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.520  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.522  3812  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-06 19:23:56.522  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.523  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:23:56.523  3812  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:23:56.523  3812  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:23:56.523  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:23:56.523  3812  3812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:23:56.523  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:23:56.524  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.524  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-06 19:23:56.524  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:23:56.524  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.524  3812  3812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:23:56.524  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.524  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:23:56.524  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.524  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.525  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.525  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.525  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.525  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.525  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:23:56.525  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.525  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:23:56.525  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.525  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.525  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.525  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.525  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.525  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.525  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.525  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.525  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.525  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.526  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.526  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.528  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:23:56.528  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.528  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.528  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.529  3812  3858 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:23:56.529  3812  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:23:56.529  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:23:56.529  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:23:56.529  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.529  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.530  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:23:56.530  2703  2757 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:23:56.530  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.530  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.530  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.530  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.530  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.530  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.530  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.530  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:23:56.530  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.530  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.530  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.530  3812  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:23:56.530  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:23:56.537  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.538  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:23:56.538  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:23:56.538  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:23:56.539  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:23:56.539  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:23:56.539  3812  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a902a4 not in the list
09-06 19:23:56.539  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:23:56.539  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.540  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:23:56.540  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:23:56.541  2703  2757 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:23:56.541  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.542  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9c480d not in the list
09-06 19:23:56.543  3812  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:23:56.543  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:23:56.544  3812  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:23:56.544  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:23:56.544  3812  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-06 19:23:56.544  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:23:56.545  2703  2757 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:23:56.545  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.546  2703  2763 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:23:56.549  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:23:56.549  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:23:56.549  2703  2757 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:23:56.549  2703  2757 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:23:56.551  3812  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:23:56.551  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:23:56.551  3812  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:23:56.551  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:23:56.551  3812  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:23:56.552  3812  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:23:56.553  3812  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:23:56.553  3812  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:23:56.554  3812  3858 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:23:56.554  3812  3858 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:23:56.554  3812  3858 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:23:56.554  3812  3858 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:23:56.555  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:56.555  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbae227 added. We now have 2 listener(s)
09-06 19:23:56.556  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:56.558  3812  3858 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:23:56.558   875  1479 D WifiService: setWifiEnabled: true pid=3812, uid=10000
09-06 19:23:56.559   875  1479 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:23:56.560  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:56.561  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a45cd4 added. We now have 3 listener(s)
09-06 19:23:56.561  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:56.566  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:56.566  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3c4e7d added. We now have 4 listener(s)
09-06 19:23:56.566  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:56.568  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:23:56.568  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@145b172 added. We now have 5 listener(s)
09-06 19:23:56.568  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:23:56.570   875  1391 D WifiService: setWifiEnabled: false pid=3812, uid=10000
09-06 19:23:56.570   875  1391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:23:56.575  2703  2753 D BluetoothAdapterState: Current state: ON, message: 23
09-06 19:23:56.575  2703  2753 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:23:56.575  2703  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:23:56.576  2703  2753 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:23:56.576  2703  2753 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:23:56.576  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:23:56.578  2703  2757 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:23:56.578  2703  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 19:23:56.579  2703  2703 D HeadsetService: Received stop request...Stopping profile...
09-06 19:23:56.579  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.579  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:56.579  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:56.580  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.581  2703  2703 V BluetoothAdapterState: isTurningOff()=true
09-06 19:23:56.581  1960  1974 D BluetoothHeadset: Proxy object disconnected
09-06 19:23:56.581  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:23:56.581  2703  2703 V BluetoothAdapterState: isTurningOn()=false
09-06 19:23:56.581  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:23:56.581  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:23:56.581   875   875 D BluetoothHeadset: Proxy object disconnected
,09-06 19:23:56.581  1363  2094 D BluetoothHeadset: Proxy object disconnected
09-06 19:23:56.581  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-06 19:23:56.581   875   875 D BluetoothHeadset: Proxy object disconnected
,09-06 19:23:56.581   875   875 D BluetoothHeadset: Proxy object disconnected
09-06 19:23:56.583  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.585  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:23:56.585  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.588   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:23:56.588   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:23:56.588   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:23:56.588   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:23:56.588  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:23:56.588  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:23:56.589  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.589  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:23:56.591  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.593  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.594  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:23:56.595   875  1306 E native  : do suspend true
,09-06 19:23:56.599   875   888 I ActivityManager: Start proc 3866:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-06 19:23:56.603  2703  2703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:23:56.603  2703  2703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:23:56.603  2703  2703 D BluetoothMapService: onReceive
09-06 19:23:56.603  2703  2757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:23:56.603  2703  2703 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:23:56.603  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:23:56.603  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:23:56.603  2703  2703 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:23:56.603  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:23:56.603  2703  2757 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-06 19:23:56.604  2703  2703 D A2dpService: Received stop request...Stopping profile...
09-06 19:23:56.605  2703  2904 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:23:56.606   875   875 D BluetoothA2dp: Proxy object disconnected
,09-06 19:23:56.606  2703  2703 D HidService: Received stop request...Stopping profile...
,09-06 19:23:56.606  2703  2703 D HidService: Stopping Bluetooth HidService
09-06 19:23:56.608  2703  2703 D HealthService: Received stop request...Stopping profile...
,09-06 19:23:56.608   875  2136 D DhcpClient: Clearing IP address
,09-06 19:23:56.609   372   873 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:23:56.610  2703  2703 D PanService: Received stop request...Stopping profile...
,09-06 19:23:56.611  2703  2703 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:23:56.611  2703  2703 D BluetoothMapService: stop()
,09-06 19:23:56.612  2703  2703 D BluetoothMapAppObserver: deinitObservers()
,09-06 19:23:56.612  2703  2703 D BluetoothMapAppObserver: removeReceiver()
,09-06 19:23:56.613   372   873 D CommandListener: Setting iface cfg
,09-06 19:23:56.613  2703  2703 I BtOppRfcommListener: stopping Accept Thread
,09-06 19:23:56.614  2703  3421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:23:56.614  2703  3421 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:23:56.615  2703  2703 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:23:56.615  2703  2703 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:23:56.615  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:23:56.615  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:23:56.615   875  2149 D DhcpClient: Receive thread stopped
,09-06 19:23:56.616  2703  2757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:23:56.616  2703  2703 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:23:56.616  2703  2703 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:23:56.616  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:23:56.616  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:23:56.616  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:23:56.616  2703  2883 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:23:56.616  2703  2883 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:23:56.617  2703  2883 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:23:56.617  2703  2883 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:23:56.617  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:23:56.617  2703  2703 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:23:56.617  2703  2703 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:23:56.618  2703  2703 V BluetoothAdapterState: isTurningOff()=true
09-06 19:23:56.618  2703  2703 V BluetoothAdapterState: isTurningOn()=false
09-06 19:23:56.618  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:23:56.618  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:23:56.618  2703  2703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:23:56.619  2703  2703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:23:56.619  2703  2757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:23:56.619  2703  2757 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:23:56.619  2703  2703 V BluetoothAdapterState: isTurningOff()=true
09-06 19:23:56.619  2703  2703 V BluetoothAdapterState: isTurningOn()=false
09-06 19:23:56.619  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:23:56.620  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:23:56.620  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-06 19:23:56.620  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-06 19:23:56.620  1363  1363 D HidProfile: Bluetooth service disconnected
09-06 19:23:56.621  2703  2703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:23:56.621  2703  2703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:23:56.621  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:23:56.621  1363  1363 D PanProfile: Bluetooth service disconnected
09-06 19:23:56.621  1363  1363 D BluetoothMap: Proxy object disconnected
09-06 19:23:56.621  1363  1363 D MapProfile: Bluetooth service disconnected
09-06 19:23:56.622  2703  2703 D BluetoothMapService: MAP Service closeService in
09-06 19:23:56.622  2703  2703 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:23:56.622  2703  2703 D ObexServerSockets0: shutdown(block = true)
09-06 19:23:56.622   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:23:56.622  2703  2909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 19:23:56.622   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-06 19:23:56.624  2703  2703 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:23:56.624  2703  2910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:23:56.624   396   396 E Parcel  : Reading a NULL string not supported here.
09-06 19:23:56.625  2703  2898 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:23:56.625  2703  2703 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:23:56.625  2703  2703 V BluetoothAdapterState: isTurningOff()=true
09-06 19:23:56.625  2703  2703 V BluetoothAdapterState: isTurningOn()=false
09-06 19:23:56.625  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:23:56.625  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:23:56.626  2703  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:23:56.626  2703  2753 D BluetoothAdapterProperties: Setting state to 15
09-06 19:23:56.626  2703  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:23:56.626   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-06 19:23:56.626  2703  2753 I BluetoothAdapterState: Entering BleOnState
09-06 19:23:56.626   875  1306 D WifiNa,tive-HAL: stopRssiMonitoring, cmdId 0
09-06 19:23:56.626   875  1306 E native  : do suspend true
09-06 19:23:56.627   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:23:56.627  2703  2703 D BluetoothMapService: cleanup()
09-06 19:23:56.627  1363  2072 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:23:56.627   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:23:56.629  1363  1375 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:23:56.627  2703  2703 D BluetoothMapService: MAP Service closeService in
09-06 19:23:56.632  1363  2072 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:23:56.632   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:23:56.632   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:23:56.632  1363  2094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:23:56.633   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:23:56.633  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:23:56.633  1363  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:23:56.634  1501  2541 V NativeCrypto: Read error: ssl=0x9a997400: I/O error during system call, Connection timed out
09-06 19:23:56.634  1960  1971 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:23:56.635  2703  2753 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:23:56.635  2703  2753 D BluetoothAdapterProperties: Setting state to 16
09-06 19:23:56.635  2703  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:23:56.635  2703  2753 D BluetoothAdapterProperties: onBleDisable
09-06 19:23:56.635  2703  2753 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:23:56.635  2703  2754 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:23:56.636  2703  2883 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:23:56.636  2703  2883 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:23:56.637  2703  2757 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:23:56.639  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:56.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:56.639  1501  2541 V NativeCrypto: SSL shutdown failed: ssl=0x9a997400: I/O error during system call, Broken pipe
09-06 19:23:56.640  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.640  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:23:56.642  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:56.642  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:56.642  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.642  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:23:56.644  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.645  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.665   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:23:56.666  1501  3792 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/74.125.133.95 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-06 19:23:56.685   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 19:23:56.685   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:23:56.685   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:23:56.686   372   873 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:23:56.688   875   892 D Tethering: MasterInitialState.processMessage what=3
09-06 19:23:56.689  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.690  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:23:56.692  3371  3371 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3c48a7d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-06 19:23:56.696  3866  3866 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-06 19:23:56.718  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:23:56.723   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d276a3:true
,09-06 19:23:56.724  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:23:56.735   372   873 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:23:56.736   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-06 19:23:56.743   875  2041 I ActivityManager: Start proc 3887:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-06 19:23:56.744   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:23:56.752  3866  3866 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 19:23:56.755  3866  3866 D BluetoothMap: Create BluetoothMap proxy object
,09-06 19:23:56.759   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:23:56.761  3866  3866 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 19:23:56.762  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:56.762  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:56.763  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.763  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:23:56.763   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:23:56.764  1878  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:23:56.764  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:56.764  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:56.765  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:23:56.765  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:23:56.776  3866  3866 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:23:56.781  3887  3887 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 19:23:56.783   875  2271 I ActivityManager: Killing 3371:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 19:23:56.840  2703  2757 I bt_hci  : shut_down
09-06 19:23:56.841  2703  2770 D bt_hwcfg: hw_epilog_process
,09-06 19:23:56.860  2703  2770 I bt_vendor: low_power_mode_cb
,09-06 19:23:56.888  2703  2770 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:23:56.888  2703  2770 I bt_vendor: epilog_cb
09-06 19:23:56.888  2703  2770 I bt_hci  : epilog_finished_callback
,09-06 19:23:56.892  2703  2757 I bt_hci_h4: hal_close
,09-06 19:23:56.893  2703  2757 I bt_userial_vendor: device fd = 51 close
,09-06 19:23:56.977  3887  3887 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:23:56.977  3887  3887 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:23:56.977  3887  3887 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.977  3887  3887 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:23:56.977  388,7  3887 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.977  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.978  3887  3887 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:2,3:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.978  3887  3887 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.978  3887  3887 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.978  3887  3887 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:23:56.978  3887  3887 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:23:56.982  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:23:56.990  3866  3866 D DockEventReceiver: finishStartingService: stopping service
09-06 19:23:56.993  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:23:57.009   875  1978 I ActivityManager: Killing 2279:com.google.android.talk/u0a61 (adj 15): empty #17
,09-06 19:23:57.026  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:23:57.100   875  1978 I ActivityManager: Start proc 3918:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-06 19:23:57.103  2703  2754 D bt_stack_manager: event_shut_down_stack finished.
09-06 19:23:57.104  2703  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:23:57.115  2703  2703 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:23:57.115  2703  2753 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:23:57.115  2703  2703 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:23:57.115  2703  2703 D BtGatt.GattService: stop()
,09-06 19:23:57.116  2703  2703 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:23:57.118  2703  2703 V BluetoothAdapterState: isTurningOff()=false
09-06 19:23:57.118  2703  2703 V BluetoothAdapterState: isTurningOn()=false
09-06 19:23:57.118  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:23:57.118  2703  2703 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:23:57.118  2703  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:23:57.119  2703  2753 D BluetoothAdapterProperties: Setting state to 10
09-06 19:23:57.119  2703  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 19:23:57.120  2703  2753 I BluetoothAdapterState: Entering OffState
,09-06 19:23:57.122   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:23:57.132  2703  2703 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 19:23:57.133  2703  2703 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:23:57.133  2703  2703 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:23:57.134  2703  2754 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.,
09-06 19:23:57.136  2703  2754 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:23:57.140  2703  2703 I art     : System.exit called, status: 0
,09-06 19:23:57.140  2703  2703 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:23:57.164  3918  3918 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-06 19:23:57.195   875   886 I ActivityManager: Process com.android.bluetooth (pid 2703) has died
,09-06 19:23:57.360  3918  3936 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-06 19:23:57.361  3918  3936 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:23:57.368  3918  3936 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
09-06 19:23:57.368  3918  3936 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:23:57.425  3918  3936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 19:23:57.425  3918  3936 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:23:57.427  3918  3936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:23:57.428  3918  3936 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-06 19:23:57.484  3918  3918 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:23:57.488  3918  3918 I Babel_Crash: startup - clean
,09-06 19:23:57.519  3918  3918 I Babel_telephony: TeleModule.launchCompleted
,09-06 19:23:57.539   875  1912 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 19:23:57.555  3918  3918 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-06 19:23:57.562  3918  3918 W Babel   : BAM#gBA: invalid account id: -1
09-06 19:23:57.562  3918  3918 W Babel   : BAM#gBA: invalid account id: -1
09-06 19:23:57.562  3918  3918 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-06 19:23:57.566  3918  3941 I Babel   : deleted: false for 0
,09-06 19:23:57.577   875  1382 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 19:23:57.602  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:23:57.611  1715  1715 D SystemUpdateService: onCreate
,09-06 19:23:57.619  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:23:57.644  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:23:57.647  1715  2519 I iu.UploadsManager: num queued entries: 0
,09-06 19:23:57.665  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:23:57.666  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:23:57.679  1715  3943 I SystemUpdateService: active receiver: enabled
,09-06 19:23:57.689   875  2041 I ActivityManager: Start proc 3945:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 19:23:57.693  1715  2519 I iu.UploadsManager: num updated entries: 0
,09-06 19:23:57.694  1715  2519 I iu.SyncManager: NEXT; no task
,09-06 19:23:57.719  3918  3918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:23:57.723  1715  3943 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:23:57.741  1715  3943 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 19:23:57.741  1715  3943 I SystemUpdateService: now status is 0 (complete)
09-06 19:23:57.741  1715  3943 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:23:57.741  1715  3943 I SystemUpdateService: file has been verified
09-06 19:23:57.741  1715  3943 I SystemUpdateService: OTA package size = 12249756
,09-06 19:23:57.784  3945  3945 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 19:23:57.796  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:23:57.799  1715  3943 I SystemUpdateService: showing system update notification
,09-06 19:23:57.801  3918  3918 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:23:57.814  3918  3918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:23:57.823  3918  3918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:23:57.827  3918  3918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:23:57.837  3945  3945 D SprintDMHelper: simOperator: 
09-06 19:23:57.838  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:23:57.843  3918  3918 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:23:57.872   875  1382 I ActivityManager: Start proc 3958:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-06 19:23:57.874   875  1912 I ActivityManager: Killing 3549:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-06 19:23:57.891  3887  3910 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:23:57.917  1715  1715 D SystemUpdateService: onDestroy
09-06 19:23:57.912   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6b082c:true
,09-06 19:23:57.926  3918  3918 I vclib   : onServiceConnected
,09-06 19:23:58.063   875  1912 I ActivityManager: Start proc 3974:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 19:23:58.067  3918  3973 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 19:23:58.071   875   885 I ActivityManager: Killing 3442:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 19:23:58.153  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 19:23:58.199  3974  3974 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:23:58.199  3974  3974 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:23:58.199  3974  3974 I GAv4    :   adb logcat -s GAv4
,09-06 19:23:58.210  3974  3974 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:23:58.216  3974  3974 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:23:58.242  3974  3992 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:23:58.331  3974  3974 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 19:23:58.376  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 19:23:58.383  3974  3974 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6939-6942)
,09-06 19:23:58.383  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:23:58.399  3974  3974 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bf20ced}
,09-06 19:23:58.400  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:23:58.400  3974  3974 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:23:58.407  3974  3974 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 19:23:58.408  3974  3974 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:23:58.421  3974  3974 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:23:58.432  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:23:58.432  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:23:58.432  3974  3974 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:23:58.432  3974  3974 I Adreno  : Build Date                       : 10/20/15
09-06 19:23:58.432  3974  3974 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:23:58.432  3974  3974 I Adreno  : Local Branch                     : M14
09-06 19:23:58.432  3974  3974 I Adreno  : Remote Branch                    : 
09-06 19:23:58.432  3974  3974 I Adreno  : Remote Branch                    : 
09-06 19:23:58.432  3974  3974 I Adreno  : Reconstruct Branch               : 
,09-06 19:23:58.490  3974  3974 I NSApplication: Starting up...
,09-06 19:23:58.498  3974  4020 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:23:58.511   875  1982 I ActivityManager: Start proc 4025:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-06 19:23:58.512   875  1982 I ActivityManager: Killing 3489:android.process.acore/u0a5 (adj 15): empty #17
,09-06 19:23:58.601  4025  4025 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 19:23:58.793   875  1479 I ActivityManager: Killing 3663:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 19:23:58.863   875  1978 I ActivityManager: Start proc 4039:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 19:23:58.977  4039  4039 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 19:23:59.032  4039  4039 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 19:23:59.051   875  2271 I ActivityManager: Killing 3678:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 19:23:59.586   875  2269 D WifiService: setWifiEnabled: true pid=3812, uid=10000
,09-06 19:23:59.586   875  2269 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:23:59.598   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:23:59.606  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:59.606  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:23:59.607  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:59.607  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:23:59.609  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:23:59.610  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:23:59.610  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:23:59.610  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:23:59.632   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:23:59.633   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-06 19:23:59.634   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-06 19:23:59.635   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:23:59.635   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 19:23:59.635   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:23:59.635   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:23:59.651   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 19:23:59.651   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:23:59.653   372   873 D CommandListener: Setting iface cfg
,09-06 19:23:59.663   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-06 19:23:59.663   875  1306 E native  : do suspend true
,09-06 19:23:59.663   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:23:59.678   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:23:59.700   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:23:59.702   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:24:00.945   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:24:00.987   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.75 rxSuccessRate=9.56 delta 1000 -> 1000
,09-06 19:24:00.989   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:24:00.989   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:24:01.005   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:24:01.038   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:24:01.040  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:24:01.464  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:24:01.512  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:24:01.513  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:24:01.517   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:24:01.536   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:24:01.536   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:24:01.536   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:24:01.553   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:24:01.562   372   873 D CommandListener: Setting iface cfg
,09-06 19:24:01.563   875  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:24:01.572   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:24:01.622   875  4074 D DhcpClient: Receive thread started
,09-06 19:24:01.707   875  1306 E native  : do suspend false
,09-06 19:24:01.718   875  2136 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:24:01.731   875  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172623, domain null
09-06 19:24:01.732   875  2136 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172623 seconds
,09-06 19:24:01.733   875  2136 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:24:01.746   875  4074 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:24:01.747   875  2136 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:24:01.751   372   873 D CommandListener: Setting iface cfg
,09-06 19:24:01.763   875  2136 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:24:01.765   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:24:01.767   875  1306 E native  : do suspend true
,09-06 19:24:01.786   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:24:01.789   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 19:24:01.790   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:24:01.791   875  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 19:24:01.802   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:24:01.832   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:24:01.832   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
,09-06 19:24:01.833   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-06 19:24:01.834   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 19:24:01.835   875  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 19:24:01.852   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:24:01.858   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-06 19:24:01.859   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-06 19:24:01.859   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-06 19:24:01.859   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:24:01.859   875  1308 D ConnectivityService:    accepting network in place of null
09-06 19:24:01.859   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:24:01.860   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:24:01.874   875  4073 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200433, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 19:24:01.887   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:01.914   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:01.920   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:24:01.920   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:24:01.922   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-06 19:24:01.925   875   892 D Tethering: MasterInitialState.processMessage what=3
09-06 19:24:01.937  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:24:01.937  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:24:01.938  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:01.938  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:24:01.944   875  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
,09-06 19:24:01.951  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:24:01.951  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:24:01.951  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:01.952  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:24:01.955  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:24:01.958  1715  1715 D SystemUpdateService: onCreate
,09-06 19:24:01.962  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:24:01.965  1715  4086 I SystemUpdateService: active receiver: enabled
,09-06 19:24:01.973  1715  4086 I SystemUpdateService: Already downloaded, skipping offpeak checks.,
,09-06 19:24:01.975  1715  4086 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:24:01.976  1715  4086 I SystemUpdateService: now status is 0 (complete)
09-06 19:24:01.976  1715  4086 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:24:01.976  1715  4086 I SystemUpdateService: file has been verified
09-06 19:24:01.976  1715  4086 I SystemUpdateService: OTA package size = 12249756
,09-06 19:24:01.984  1715  4086 I SystemUpdateService: showing system update notification
,09-06 19:24:01.985  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:24:01.987  1715  2519 I iu.UploadsManager: num queued entries: 0
,09-06 19:24:01.990  1715  2519 I iu.UploadsManager: num updated entries: 0
,09-06 19:24:01.994  1715  2519 I iu.SyncManager: NEXT; no task
,09-06 19:24:02.001  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:24:02.002  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:24:02.005  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:24:02.007  1715  4089 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 19:24:02.007  1715  4089 W BaseAppContext: Using Auth Proxy for data requests.
09-06 19:24:02.008  1715  4089 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
09-06 19:24:02.010  3945  3945 D SprintDMHelper: simOperator: 
09-06 19:24:02.010  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:24:02.013  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:02.015  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:02.020  1715  1715 D SystemUpdateService: onDestroy
,09-06 19:24:02.025   875  4072 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:24:02 GMT], X-Android-Received-Millis=[1473182642025], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473182641993]}
,09-06 19:24:02.026   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 19:24:02.026   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-06 19:24:02.026   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:24:02.028   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 19:24:02.054  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:24:02.054  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:24:02.055  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:02.055  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:02.083  1715  4089 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-06 19:24:02.134  1501  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 19:24:02.135  1501  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:24:02.135  1501  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:02.135  1501  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:02.144  2990  4093 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 19:24:02.144  2990  4093 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at blb.a(PG:3937)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at czp.a(PG:18188)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at czp.a(PG:9087)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:24:02.144  2990  4093 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	... 12 more
09-06 19:24:02.144  2990  4093 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at fal.a(PG:38)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:24:02.144  2990  4093 E HttpOperation: 	... 14 more
,09-06 19:24:02.184  3918  4096 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:24:02.316  1501  2039 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 19:24:02.316  1501  2039 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:24:02.316  1501  2039 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:02.316  1501  2039 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:02.330  2990  4106 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 19:24:02.330  2990  4106 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at blb.a(PG:3937)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at czp.a(PG:18188)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:24:02.330  2990  4106 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	... 12 more
09-06 19:24:02.330  2990  4106 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at fal.a(PG:38)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:24:02.330  2990  4106 E HttpOperation: 	... 14 more
,09-06 19:24:02.372  1501  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 19:24:02.372  1501  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:24:02.372  1501  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:02.372  1501  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:02.393  2990  4106 E HttpOperation: [getmobileexperiments] Unexpected exception
09-06 19:24:02.393  2990  4106 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at hec.a(PG:42)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at hee.a(PG:102)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at czr.a(PG:65)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at kka.a(PG:108)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at czp.a(PG:19176)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:24:02.393  2990  4106 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	... 15 more
09-06 19:24:02.393  2990  4106 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at fal.a(PG:38)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:24:02.393  2990  4106 E HttpOperation: 	... 17 more
,09-06 19:24:02.393  2990  4106 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-06 19:24:02.393  2990  4106 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jdm.a(PG:82)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jcs.o(PG:406)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jcn.a(PG:1379)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jcs.i(PG:143)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at hec.a(PG:42)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at hee.a(PG:102)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at czr.a(PG:65)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at kka.a(PG:108)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at czp.a(PG:19176)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at czp.a(PG:9081)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at czq.run(PG:1686)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jdj.a(PG:4091)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jdj.a(PG:1125)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at jdm.a(PG:77)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	... 15 more
09-06 19:24:02.393  2990  4106 E ExperimentLoader: Caused by: faj: BadAuthentication
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	at fal.a(PG:38)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	,at jdj.a(PG:4089)
09-06 19:24:02.393  2990  4106 E ExperimentLoader: 	... 17 more
,09-06 19:24:02.501   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125593, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-06 19:24:02.593   875  2271 D WifiService: setWifiEnabled: false pid=3812, uid=10000
,09-06 19:24:02.593   875  2271 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:24:02.614  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 19:24:02.617   875  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:24:02.618   875  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-06 19:24:02.619   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:24:02.619   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:24:02.632   875  1306 E native  : do suspend true
,09-06 19:24:02.639   875  2136 D DhcpClient: Clearing IP address
,09-06 19:24:02.640   372   873 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:24:02.643   372   873 D CommandListener: Setting iface cfg
,09-06 19:24:02.647  1501  4101 V NativeCrypto: Read error: ssl=0x99e3f800: I/O error during system call, Connection timed out
,09-06 19:24:02.650  1501  4101 V NativeCrypto: SSL shutdown failed: ssl=0x99e3f800: I/O error during system call, Broken pipe
,09-06 19:24:02.661   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 19:24:02.661   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-06 19:24:02.668   875  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-06 19:24:02.669   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:24:02.669   875  1306 E native  : do suspend true
,09-06 19:24:02.670   396   396 E Parcel  : Reading a NULL string not supported here.
,09-06 19:24:02.672   875  4074 D DhcpClient: Receive thread stopped
,09-06 19:24:02.676   875  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-06 19:24:02.727   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:02.761   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:02.761   372   873 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:24:02.762   875  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:24:02.763   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:24:02.768   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2,
09-06 19:24:02.769   875   892 D Tethering: MasterInitialState.processMessage what=3
09-06 19:24:02.773  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:02.773  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:02.773  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.774  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:02.776  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:02.776  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:02.776  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.776  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:02.783  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:24:02.791  1715  1715 D SystemUpdateService: onCreate
,09-06 19:24:02.792   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:24:02.796   875  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 19:24:02.796  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:02.796  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:02.796  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.796  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:02.797  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:02.797  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:02.797  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:02.798  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:02.799  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:24:02.802  1878  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:24:02.805  1715  4114 I SystemUpdateService: active receiver: enabled
09-06 19:24:02.808  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-06 19:24:02.809  1715  4114 I SystemUpdateService: Already downloaded, skipping offpeak checks.,
09-06 19:24:02.813  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-06 19:24:02.813  1715  2519 I iu.UploadsManager: num queued entries: 0
09-06 19:24:02.814  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:24:02.814  1715  4114 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 19:24:02.814  1715  4114 I SystemUpdateService: now status is 0 (complete)
09-06 19:24:02.814  1715  4114 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:24:02.815  1715  4114 I SystemUpdateService: file has been verified
09-06 19:24:02.815  1715  4114 I SystemUpdateService: OTA package size = 12249756
09-06 19:24:02.816  1715  2519 I iu.UploadsManager: num updated entries: 0
,09-06 19:24:02.817  1715  2519 I iu.SyncManager: NEXT; no task
09-06 19:24:02.818  1715  4114 I SystemUpdateService: showing system update notification
,09-06 19:24:02.830  1715  1715 D SystemUpdateService: onDestroy
,09-06 19:24:02.830  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:24:02.834  3945  3945 D SprintDMHelper: simOperator: 
,09-06 19:24:02.834  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:24:02.856   372   873 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:24:02.857   875  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-06 19:24:02.864  3918  4119 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 19:24:02.921   875  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 19:24:03.165   875  2018 I ActivityManager: Killing 2097:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 19:24:05.649   875   892 I ActivityManager: Start proc 4123:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:24:05.779  4123  4123 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:24:05.779  4123  4123 D AdapterServiceConfig: Adding A2dpService
09-06 19:24:05.779  4123  4123 D AdapterServiceConfig: Adding HidService
,09-06 19:24:05.779  4123  4123 D AdapterServiceConfig: Adding HealthService
09-06 19:24:05.779  4123  4123 D AdapterServiceConfig: Adding PanService
,09-06 19:24:05.780  4123  4123 D AdapterServiceConfig: Adding GattService
09-06 19:24:05.780  4123  4123 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:24:05.794  4123  4123 D BluetoothAdapterState: make() - Creating AdapterState
09-06 19:24:05.794   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a924757:true
,09-06 19:24:05.797  4123  4123 I bt_bluedroid: init
,09-06 19:24:05.797  4123  4135 I BluetoothAdapterState: Entering OffState
,09-06 19:24:05.802  4123  4136 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:24:05.803  4123  4136 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:24:05.803  4123  4136 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:24:05.803  4123  4136 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:24:05.805  4123  4123 I bt_bluedroid: get_profile_interface socket
,09-06 19:24:05.807  4123  4123 I bt_bluedroid: get_profile_interface sdp
,09-06 19:24:05.809  4123  4139 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:24:05.821  4123  4139 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:24:05.822  4123  4134 I bt_bluedroid: config_hci_snoop_log
,09-06 19:24:05.823   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:24:05.828  4123  4135 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:24:05.828  4123  4135 D BluetoothAdapterProperties: Setting state to 14
09-06 19:24:05.828  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:24:05.829  4123  4135 D BluetoothBondStateMachine: make
,09-06 19:24:05.832  4123  4140 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:24:05.835  4123  4123 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:24:05.835  4123  4135 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:24:05.837  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:05.837  4123  4123 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:24:05.838  4123  4123 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:24:05.838  4123  4123 D BtGatt.GattService: start()
09-06 19:24:05.838  4123  4123 I bt_bluedroid: get_profile_interface gatt
,09-06 19:24:05.839  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
09-06 19:24:05.839  4123  4123 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:24:05.843  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:24:05.843  4123  4123 V BluetoothAdapterState: isTurningOn()=false
09-06 19:24:05.843  4123  4123 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:24:05.844  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:05.844  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 19:24:05.844  4123  4135 I bt_bluedroid: enable
09-06 19:24:05.844  4123  4136 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 19:24:05.845  4123  4136 I bt_hci  : start_up
,09-06 19:24:05.851  4123  4136 I bt_vendor: alloc value 0xb3a4d189
09-06 19:24:05.851  4123  4136 I bt_vendor: init
,09-06 19:24:05.851  4123  4136 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:24:05.851  4123  4136 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:24:05.960  4123  4136 D bt_hci  : start_up starting async portion
,09-06 19:24:05.961  4123  4143 I bt_hci  : event_finish_startup
,09-06 19:24:05.961  4123  4143 I bt_hci_h4: hal_open
09-06 19:24:05.962  4123  4143 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:24:05.970  4123  4143 I bt_userial_vendor: device fd = 51 open
,09-06 19:24:06.002  4123  4143 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:24:06.034  4123  4143 D bt_hwcfg: Chipset BCM4354A2
09-06 19:24:06.034  4123  4143 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 19:24:06.035  4123  4143 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:24:06.698  4123  4143 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:24:06.700  4123  4143 D bt_hwcfg: Settlement delay -- 100 ms
,09-06 19:24:06.700  4123  4143 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:24:06.817  4123  4143 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:24:06.818  4123  4143 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:24:06.847  4123  4143 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:24:06.848  4123  4143 I bt_vendor: firmware callback
,09-06 19:24:06.848  4123  4143 I bt_hci  : firmware_config_callback
,09-06 19:24:06.859  4123  4145 I bt_btu  : btu_task pending for preload complete event
,09-06 19:24:06.859  4123  4145 I bt_btu_task: Bluetooth chip preload is complete
09-06 19:24:06.860  4123  4145 I bt_btu  : btu_task received preload complete event
,09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:24:06.868  4123  4145 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:24:06.869  4123  4145 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:24:07.002  4123  4145 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39cad9d
,09-06 19:24:07.003  4123  4145 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39cad9d 
,09-06 19:24:07.012  4123  4139 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:24:07.015  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:24:07.017  4123  4139 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:24:07.021  4123  4139 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:24:07.023  4123  4139 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:24:07.026  4123  4139 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:24:07.026  4123  4139 D bt_hci  : do_postload posting postload work item
,09-06 19:24:07.026  4123  4143 I bt_hci  : event_postload
09-06 19:24:07.026  4123  4143 I bt_vendor: sco_config_cb
,09-06 19:24:07.026  4123  4143 I bt_hci  : sco_config_callback postload finished.
09-06 19:24:07.029  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:07.029  4123  4139 D bt_bte_conf: Device ID record 1 : primary
,09-06 19:24:07.029  4123  4139 D bt_bte_conf:   vendorId            = 000f
,09-06 19:24:07.030  4123  4139 D bt_bte_conf:   vendorIdSource      = 0001
09-06 19:24:07.030  4123  4139 D bt_bte_conf:   product             = 1200
09-06 19:24:07.030  4123  4139 D bt_bte_conf:   version             = 1436
09-06 19:24:07.030  4123  4139 D bt_bte_conf:   clientExecutableURL = 
09-06 19:24:07.030  4123  4139 D bt_bte_conf:   serviceDescription  = 
09-06 19:24:07.031  4123  4139 D bt_bte_conf:   documentationURL    = 
09-06 19:24:07.031  4123  4139 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 19:24:07.031  4123  4136 D bt_stack_manager: event_start_up_stack finished
09-06 19:24:07.032  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:24:07.034  4123  4143 I bt_vendor: low_power_mode_cb
09-06 19:24:07.034  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:07.034  4123  4135 D BluetoothAdapterProperties: Setting state to 15
09-06 19:24:07.035  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 19:24:07.036  4123  4135 I BluetoothAdapterState: Entering BleOnState
09-06 19:24:07.042  4123  4135 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-06 19:24:07.042  4123  4135 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:24:07.042  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:24:07.054  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.055  4123  4123 D HeadsetService: Received start request. Starting profile...
09-06 19:24:07.059  4123  4123 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:24:07.059  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:07.059  4123  4123 D HeadsetStateMachine: make
,09-06 19:24:07.063  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:07.074  4123  4123 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:24:07.074  4123  4123 I bt_bluedroid: get_profile_interface handsfree
09-06 19:24:07.074  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 19:24:07.075  4123  4139 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-06 19:24:07.080  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.080  4123  4123 D A2dpService: Received start request. Starting profile...
09-06 19:24:07.080  4123  4135 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:24:07.081  4123  4123 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:24:07.082  4123  4123 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:24:07.089  4123  4123 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:24:07.089  4123  4123 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:24:07.089  4123  4123 D A2dpStateMachine: make
,09-06 19:24:07.091  4123  4123 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:24:07.092  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:24:07.096  4123  4154 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:24:07.097  4123  4123 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:24:07.100  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.104  4123  4123 D HidService: Received start request. Starting profile...
,09-06 19:24:07.103  3866  3866 D BluetoothInputDevice: Proxy object connected
09-06 19:24:07.106  3866  3866 D HidProfile: Bluetooth service connected
,09-06 19:24:07.107  4123  4123 I bt_bluedroid: get_profile_interface hidhost
09-06 19:24:07.107  4123  4139 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ac3e5
09-06 19:24:07.107  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 19:24:07.108  4123  4123 D HidService: setHidService(): set to: null
,09-06 19:24:07.113  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:24:07.116  4123  4123 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:24:07.117  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.118  4123  4123 D HealthService: Received start request. Starting profile...
,09-06 19:24:07.119  4123  4123 I bt_bluedroid: get_profile_interface health
,09-06 19:24:07.120  4123  4123 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:24:07.121  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.121  4123  4123 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:07.121  4123  4123 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:07.121  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:24:07.121  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:07.128  3866  3866 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:24:07.128  3866  3866 D PanProfile: Bluetooth service connected
09-06 19:24:07.128  4123  4123 D PanService: Received start request. Starting profile...
,09-06 19:24:07.128  4123  4123 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:24:07.129  4123  4123 I bt_bluedroid: get_profile_interface pan
09-06 19:24:07.130  4123  4139 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:24:07.132  4123  4151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:24:07.134  4123  4123 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:07.135  3866  3866 D BluetoothMap: Proxy object connected
,09-06 19:24:07.135  4123  4123 D BluetoothMapService: Received start request. Starting profile...
09-06 19:24:07.135  3866  3866 D MapProfile: Bluetooth service connected
09-06 19:24:07.135  4123  4123 D BluetoothMapService: start()
09-06 19:24:07.135  3866  3866 D BluetoothMap: getConnectedDevices()
09-06 19:24:07.136  3866  3866 D BluetoothMap: Bluetooth is Not enabled
,09-06 19:24:07.138  4123  4123 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:24:07.139  4123  4123 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:24:07.139  4123  4123 D BluetoothMapAppObserver: createReceiver()
,09-06 19:24:07.140  4123  4123 D BluetoothMapAppObserver: initObservers()
,09-06 19:24:07.140  4123  4123 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:24:07.145  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:24:07.145  4123  4123 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:07.145  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:07.145  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:07.146  4123  4123 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:07.146  4123  4123 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:24:07.146  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:07.146  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:07.147  4123  4123 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:07.147  4123  4123 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:07.147  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:07.147  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:07.148  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:07.149  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:24:07.149  4123  4135 D BluetoothAdapterProperties: ScanMode =  20
,09-06 19:24:07.149  4123  4135 D BluetoothAdapterProperties: State =  11
,09-06 19:24:07.152  4123  4139 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:24:07.153  4123  4135 D BluetoothAdapterProperties: Setting state to 12
09-06 19:24:07.153  4123  4139 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:24:07.153  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:24:07.153  4123  4135 I BluetoothAdapterState: Entering OnState
09-06 19:24:07.153  1363  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:24:07.155  1363  1363 D BluetoothInputDevice: Proxy object connected
09-06 19:24:07.155   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:07.155  1363  1363 D HidProfile: Bluetooth service connected
09-06 19:24:07.155  1363  2094 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:07.156  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:07.157  1363  1363 D BluetoothMap: Proxy object connected
09-06 19:24:07.157  1363  1363 D MapProfile: Bluetooth service connected
,09-06 19:24:07.157  1363  1363 D BluetoothMap: getConnectedDevices()
09-06 19:24:07.157  1363  2072 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:24:07.159  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:24:07.159  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:07.159  1363  1363 D PanProfile: Bluetooth service connected
09-06 19:24:07.159  3866  3879 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:24:07.159   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:07.159   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:24:07.159  3866  3876 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:24:07.159  3866  3879 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:24:07.161  1363  2094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:07.161  3866  3876 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:24:07.162   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:07.162  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:07.162  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:24:07.163   875   875 D BluetoothA2dp: Proxy object connected
,09-06 19:24:07.164  1363  1363 D BluetoothA2dp: Proxy object connected
,09-06 19:24:07.164  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:07.164  1363  2072 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:24:07.166  1960  1971 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:07.166  4123  4123 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:24:07.166  4123  4123 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 19:24:07.167   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:24:07.169  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:07.169  4123  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:24:07.170  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:07.171  4123  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:07.172  4123  4123 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:24:07.172  4123  4123 D ObexServerSockets0: startAccept()
09-06 19:24:07.173  4123  4123 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:24:07.173  3866  3866 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-06 19:24:07.175  4123  4123 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:24:07.175  4123  4123 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:24:07.175  4123  4160 D ObexServerSockets0: Accepting socket connection...
09-06 19:24:07.176  4123  4123 D BluetoothMapService: onReceive
09-06 19:24:07.176  4123  4123 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:24:07.176  4123  4123 D BluetoothMapService: STATE_ON
09-06 19:24:07.176  4123  4161 D ObexServerSockets0: Accepting socket connection...
09-06 19:24:07.176  3866  3866 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:24:07.182  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:24:07.184  3866  3866 D BluetoothA2dp: Proxy object connected
,09-06 19:24:07.187  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:24:07.192  3866  3866 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:24:07.196  3866  3866 D BluetoothPbap: Proxy object connected
,09-06 19:24:07.197  3866  3866 D PbapServerProfile: Bluetooth service connected
09-06 19:24:07.197  1363  1363 D BluetoothPbap: Proxy object connected
,09-06 19:24:07.197  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-06 19:24:07.203  4123  4123 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:24:07.203  4123  4123 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:24:07.206  4123  4165 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:07.225  4123  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:07.227  4123  4169 I BtOppRfcommListener: Accept thread started.
,09-06 19:24:07.257  1960  2128 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.257   875   875 D BluetoothHeadset: Proxy object connected
09-06 19:24:07.258  1363  2072 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.258  1363  1363 D HeadsetProfile: Bluetooth service connected
09-06 19:24:07.258   875   875 D BluetoothHeadset: Proxy object connected
09-06 19:24:07.258   875   875 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.259   875   892 D BluetoothHeadset: Proxy object connected
09-06 19:24:07.259   875   892 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.262  1363  1375 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.262  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-06 19:24:07.267  1960  1974 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.279  3866  3879 D BluetoothHeadset: Proxy object connected
,09-06 19:24:07.282  3866  3866 D HeadsetProfile: Bluetooth service connected
,09-06 19:24:08.610  4123  4135 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:24:08.611  4123  4135 D BluetoothAdapterProperties: Setting state to 13
09-06 19:24:08.611  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 19:24:08.614  4123  4135 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:24:08.623  4123  4123 D BluetoothMapService: onReceive
09-06 19:24:08.623  4123  4123 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:24:08.623  4123  4135 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:24:08.623  4123  4123 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:24:08.624  4123  4123 D BluetoothMapService: MAP Service closeService in
09-06 19:24:08.625  4123  4123 D BluetoothMapMasInstance0: MAP Service shutdown
,09-06 19:24:08.625  4123  4123 D ObexServerSockets0: shutdown(block = true)
09-06 19:24:08.626  4123  4160 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 19:24:08.627  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:08.628  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:08.630  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:08.631  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:08.631  4123  4139 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:24:08.632  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 19:24:08.633  4123  4123 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:24:08.634  4123  4161 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:24:08.636  4123  4148 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-06 19:24:08.638  4123  4123 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:24:08.639  4123  4123 I BtOppRfcommListener: stopping Accept Thread
,09-06 19:24:08.639  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:08.639  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:08.639  4123  4169 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:24:08.640  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:24:08.640  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:08.642  4123  4169 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:24:08.642  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:08.643  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:08.643  4123  4123 D HeadsetService: Received stop request...Stopping profile...
09-06 19:24:08.645  3866  3876 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.646  1960  2168 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.646   875   875 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.646  4123  4123 D A2dpService: Received stop request...Stopping profile...
09-06 19:24:08.646  1363  1374 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.646   875   875 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.646  4123  4154 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:24:08.646   875   875 D BluetoothHeadset: Proxy object disconnected
09-06 19:24:08.647  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:24:08.649  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-06 19:24:08.650  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-06 19:24:08.650   875   875 D BluetoothA2dp: Proxy object disconnected
09-06 19:24:08.651  3866  3866 D HeadsetProfile: Bluetooth service disconnected
09-06 19:24:08.651  4123  4123 D HidService: Received stop request...Stopping profile...
09-06 19:24:08.651  4123  4123 D HidService: Stopping Bluetooth HidService
,09-06 19:24:08.653  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-06 19:24:08.653  1363  1363 D HidProfile: Bluetooth service disconnected
09-06 19:24:08.653  4123  4123 D HealthService: Received stop request...Stopping profile...
,09-06 19:24:08.655  4123  4123 D PanService: Received stop request...Stopping profile...
,09-06 19:24:08.656  3866  3866 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:24:08.656  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:24:08.656  1363  1363 D PanProfile: Bluetooth service disconnected
09-06 19:24:08.658  4123  4123 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:24:08.658  4123  4123 D BluetoothMapService: stop()
09-06 19:24:08.658  3866  3866 D BluetoothA2dp: Proxy object disconnected
09-06 19:24:08.658  4123  4123 D BluetoothMapAppObserver: deinitObservers()
09-06 19:24:08.658  3866  3866 D BluetoothInputDevice: Proxy object disconnected
,09-06 19:24:08.658  4123  4123 D BluetoothMapAppObserver: removeReceiver()
09-06 19:24:08.658  3866  3866 D HidProfile: Bluetooth service disconnected
,09-06 19:24:08.659  3866  3866 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:24:08.659  3866  3866 D PanProfile: Bluetooth service disconnected
09-06 19:24:08.661  1363  1363 D BluetoothMap: Proxy object disconnected
09-06 19:24:08.661  1363  1363 D MapProfile: Bluetooth service disconnected
09-06 19:24:08.661  3866  3866 D BluetoothMap: Proxy object disconnected
09-06 19:24:08.661  3866  3866 D MapProfile: Bluetooth service disconnected
09-06 19:24:08.661  4123  4123 V BluetoothAdapterState: isTurningOff()=true
09-06 19:24:08.661  4123  4123 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:24:08.661  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:08.661  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:08.663  4123  4123 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:24:08.663  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:24:08.663  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:24:08.663  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:24:08.663  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:24:08.664  4123  4123 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:24:08.665  4123  4139 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:24:08.665  4123  4123 V BluetoothAdapterState: isTurningOff()=true
09-06 19:24:08.665  4123  4123 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:24:08.665  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:08.665  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:08.666  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:24:08.666  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:24:08.666  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:24:08.666  4123  4145 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:24:08.666  4123  4123 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:24:08.666  4123  4145 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 19:24:08.666  4123  4145 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:24:08.666  4123  4123 V BluetoothAdapterState: isTurningOn()=false
09-06 19:24:08.667  4123  4145 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:24:08.667  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:24:08.667  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:08.669  4123  4123 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:24:08.670  4123  4123 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:24:08.670  4123  4123 V BluetoothAdapterState: isTurningOff()=true
09-06 19:24:08.670  4123  4123 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:24:08.670  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:08.670  4123  4139 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:24:08.670  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:08.670  4123  4123 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:24:08.671  4123  4139 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:24:08.671  4123  4123 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 19:24:08.671  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:24:08.671  4123  4123 V BluetoothAdapterState: isTurningOff()=true
09-06 19:24:08.671  4123  4123 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:24:08.671  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:08.672  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:08.672  4123  4123 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:24:08.672  4123  4123 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:24:08.673  4123  4123 D BluetoothMapService: MAP Service closeService in
09-06 19:24:08.673  4123  4123 V BluetoothAdapterState: isTurningOff()=true
09-06 19:24:08.673  4123  4123 V BluetoothAdapterState: isTurningOn()=false
09-06 19:24:08.673  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:24:08.673  4123  4123 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:08.674  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:24:08.674  4123  4135 D BluetoothAdapterProperties: Setting state to 15
09-06 19:24:08.674  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:24:08.675  1363  2094 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:24:08.675   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:24:08.675  1363  2072 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:24:08.676  4123  4135 I BluetoothAdapterState: Entering BleOnState
09-06 19:24:08.676  4123  4123 D BluetoothMapService: cleanup()
09-06 19:24:08.676  4123  4123 D BluetoothMapService: MAP Service closeService in
09-06 19:24:08.676  3866  3876 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:24:08.677  1363  1375 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:24:08.678  1363  1363 D BluetoothPbap: Proxy object disconnected
,09-06 19:24:08.678  1363  1363 D PbapServerProfile: Bluetooth service disconnected
09-06 19:24:08.678  3866  3866 D BluetoothPbap: Proxy object disconnected
09-06 19:24:08.678  3866  3866 D PbapServerProfile: Bluetooth service disconnected
09-06 19:24:08.679  3866  3876 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:24:08.680   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:24:08.680  3866  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:24:08.682   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:24:08.682  3866  4173 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:24:08.683  3866  3876 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:24:08.684  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:24:08.684  3866  3879 D BluetoothPan: onBluetoothStateChange on: false
,09-06 19:24:08.686   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:24:08.687  1363  2072 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:24:08.687  1363  2094 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:24:08.688  1960  1971 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:24:08.688  4123  4135 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-06 19:24:08.688  4123  4135 D BluetoothAdapterProperties: Setting state to 16
09-06 19:24:08.688  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:24:08.689  4123  4135 D BluetoothAdapterProperties: onBleDisable
09-06 19:24:08.689  4123  4135 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:24:08.690  4123  4136 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:24:08.691  4123  4145 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:24:08.691  4123  4145 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:24:08.691  4123  4139 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:24:08.692  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:08.693  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:24:08.693  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:08.695  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:08.696  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:08.699  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:24:08.703  3866  3866 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:24:08.892  4123  4139 I bt_hci  : shut_down
,09-06 19:24:08.892  4123  4143 D bt_hwcfg: hw_epilog_process
,09-06 19:24:08.894  4123  4143 I bt_vendor: low_power_mode_cb
,09-06 19:24:08.915  4123  4143 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:24:08.916  4123  4143 I bt_vendor: epilog_cb
09-06 19:24:08.916  4123  4143 I bt_hci  : epilog_finished_callback
,09-06 19:24:08.925  4123  4139 I bt_hci_h4: hal_close
,09-06 19:24:08.927  4123  4139 I bt_userial_vendor: device fd = 51 close
,09-06 19:24:09.052  4123  4136 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:24:09.054  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:24:09.059  4123  4123 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:24:09.061  4123  4123 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 19:24:09.061  4123  4123 D BtGatt.GattService: stop()
,09-06 19:24:09.062  4123  4123 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:24:09.062  4123  4135 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 19:24:09.067  4123  4123 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:09.067  4123  4123 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:24:09.068  4123  4123 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:09.068  4123  4123 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:24:09.069  4123  4135 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:24:09.069  4123  4135 D BluetoothAdapterProperties: Setting state to 10
,09-06 19:24:09.070  4123  4135 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-06 19:24:09.071  4123  4135 I BluetoothAdapterState: Entering OffState
,09-06 19:24:09.073   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:24:09.097  4123  4123 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 19:24:09.097  4123  4123 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:24:09.098  4123  4136 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:24:09.105  4123  4136 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:24:09.105  4123  4123 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:24:09.110  4123  4123 I art     : System.exit called, status: 0
,09-06 19:24:09.111  4123  4123 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:24:09.182   875  2268 I ActivityManager: Process com.android.bluetooth (pid 4123) has died
,09-06 19:24:09.865   875  1308 D ConnectivityService: handlePromptUnvalidated 101
,09-06 19:24:11.609  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:24:11.609  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:24:12.444  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-06 19:24:12.458  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:12.462  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:12.515  1501  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-06 19:24:12.515  1501  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-06 19:24:12.516  1501  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:12.516  1501  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:12.565  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-06 19:24:12.566  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-06 19:24:12.569  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-06 19:24:14.617  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:24:14.618  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4547240 added. We now have 6 listener(s)
,09-06 19:24:14.618  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:24:14.622  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:24:14.622  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@445579 added. We now have 7 listener(s)
,09-06 19:24:14.622  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:14.624  3812  3858 I System.out: IsBluetoothEnabled
,09-06 19:24:14.637  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:14.687   875   892 I ActivityManager: Start proc 4180:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:24:14.819  4180  4180 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:24:14.820  4180  4180 D AdapterServiceConfig: Adding A2dpService
09-06 19:24:14.820  4180  4180 D AdapterServiceConfig: Adding HidService
09-06 19:24:14.820  4180  4180 D AdapterServiceConfig: Adding HealthService
09-06 19:24:14.820  4180  4180 D AdapterServiceConfig: Adding PanService
09-06 19:24:14.820  4180  4180 D AdapterServiceConfig: Adding GattService
,09-06 19:24:14.821  4180  4180 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:24:14.836   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f2c7a:true
,09-06 19:24:14.837  4180  4180 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 19:24:14.842  4180  4180 I bt_bluedroid: init
,09-06 19:24:14.843  4180  4192 I BluetoothAdapterState: Entering OffState
,09-06 19:24:14.849  4180  4193 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:24:14.849  4180  4193 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:24:14.849  4180  4193 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:24:14.850  4180  4193 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:24:14.852  4180  4180 I bt_bluedroid: get_profile_interface socket
,09-06 19:24:14.854  4180  4180 I bt_bluedroid: get_profile_interface sdp
,09-06 19:24:14.860  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:24:14.861  4180  4191 I bt_bluedroid: config_hci_snoop_log
09-06 19:24:14.863  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 19:24:14.864   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:24:14.878  4180  4192 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:24:14.879  4180  4192 D BluetoothAdapterProperties: Setting state to 14
09-06 19:24:14.879  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:24:14.884  4180  4192 D BluetoothBondStateMachine: make
,09-06 19:24:14.889  4180  4197 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:24:14.896  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:24:14.899  4180  4180 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:24:14.907  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:14.909  4180  4180 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:24:14.910  4180  4180 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:24:14.911  4180  4180 D BtGatt.GattService: start()
09-06 19:24:14.911  4180  4180 I bt_bluedroid: get_profile_interface gatt
,09-06 19:24:14.913  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
09-06 19:24:14.914  4180  4180 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:24:14.929  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:14.929  4180  4180 V BluetoothAdapterState: isTurningOn()=false
09-06 19:24:14.929  4180  4180 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:24:14.930  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:14.931  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 19:24:14.932  4180  4192 I bt_bluedroid: enable
,09-06 19:24:14.932  4180  4193 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-06 19:24:14.933  4180  4193 I bt_hci  : start_up
,09-06 19:24:14.953  4180  4193 I bt_vendor: alloc value 0xb3a4d189
,09-06 19:24:14.953  4180  4193 I bt_vendor: init
,09-06 19:24:14.954  4180  4193 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:24:14.954  4180  4193 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:24:15.064  4180  4193 D bt_hci  : start_up starting async portion
,09-06 19:24:15.065  4180  4200 I bt_hci  : event_finish_startup
,09-06 19:24:15.065  4180  4200 I bt_hci_h4: hal_open
,09-06 19:24:15.065  4180  4200 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:24:15.077  4180  4200 I bt_userial_vendor: device fd = 51 open
,09-06 19:24:15.107  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:24:15.138  4180  4200 D bt_hwcfg: Chipset BCM4354A2
09-06 19:24:15.138  4180  4200 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 19:24:15.139  4180  4200 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:24:16.034  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:24:16.036  4180  4200 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:24:16.036  4180  4200 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:24:16.154  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:24:16.156  4180  4200 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:24:16.183  4180  4200 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:24:16.184  4180  4200 I bt_vendor: firmware callback
09-06 19:24:16.184  4180  4200 I bt_hci  : firmware_config_callback
,09-06 19:24:16.193  1501  2182 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-06 19:24:16.196  4180  4202 I bt_btu  : btu_task pending for preload complete event
,09-06 19:24:16.197  4180  4202 I bt_btu_task: Bluetooth chip preload is complete
09-06 19:24:16.197  4180  4202 I bt_btu  : btu_task received preload complete event
,09-06 19:24:16.207  4180  4202 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:24:16.208  4180  4202 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:24:16.208  4180  4202 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:24:16.208  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:24:16.208  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:24:16.209  4180  4202 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:24:16.209  4180  4202 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:24:16.209  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:24:16.209  4180  4202 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:24:16.210  4180  4202 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:24:16.210  4180  4202 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:24:16.210  4180  4202 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:24:16.210  4180  4202 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:24:16.211  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:24:16.211  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:24:16.350  4180  4202 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39cad9d
,09-06 19:24:16.350  4180  4202 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39cad9d 
,09-06 19:24:16.363  4180  4196 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:24:16.365  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:24:16.366  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:24:16.370  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:24:16.374  4180  4196 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:24:16.375  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:24:16.375  4180  4196 D bt_hci  : do_postload posting postload work item
,09-06 19:24:16.375  4180  4200 I bt_hci  : event_postload
09-06 19:24:16.375  4180  4200 I bt_vendor: sco_config_cb
,09-06 19:24:16.375  4180  4200 I bt_hci  : sco_config_callback postload finished.
,09-06 19:24:16.378  4180  4196 D bt_bte_conf: Device ID record 1 : primary
09-06 19:24:16.379  4180  4196 D bt_bte_conf:   vendorId            = 000f
09-06 19:24:16.379  4180  4196 D bt_bte_conf:   vendorIdSource      = 0001
,09-06 19:24:16.379  4180  4196 D bt_bte_conf:   product             = 1200
09-06 19:24:16.379  4180  4196 D bt_bte_conf:   version             = 1436
09-06 19:24:16.379  4180  4196 D bt_bte_conf:   clientExecutableURL = 
09-06 19:24:16.380  4180  4196 D bt_bte_conf:   serviceDescription  = 
,09-06 19:24:16.380  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:16.380  4180  4196 D bt_bte_conf:   documentationURL    = 
09-06 19:24:16.380  4180  4196 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:24:16.380  4180  4193 D bt_stack_manager: event_start_up_stack finished
09-06 19:24:16.381  4180  4200 I bt_vendor: low_power_mode_cb
09-06 19:24:16.383  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-06 19:24:16.383  4180  4192 D BluetoothAdapterProperties: Setting state to 15
09-06 19:24:16.384  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 19:24:16.385  4180  4192 I BluetoothAdapterState: Entering BleOnState
09-06 19:24:16.390  4180  4192 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-06 19:24:16.391  4180  4192 D BluetoothAdapterProperties: Setting state to 11
09-06 19:24:16.391  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:24:16.402  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:16.403  4180  4180 D HeadsetService: Received start request. Starting profile...
,09-06 19:24:16.406  4180  4180 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
09-06 19:24:16.407  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:16.407  4180  4180 D HeadsetStateMachine: make
,09-06 19:24:16.421  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:24:16.429  4180  4180 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:24:16.429  4180  4180 I bt_bluedroid: get_profile_interface handsfree
,09-06 19:24:16.431  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-06 19:24:16.431  4180  4196 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:24:16.435  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:16.436  4180  4180 D A2dpService: Received start request. Starting profile...
,09-06 19:24:16.437  4180  4180 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:24:16.437  4180  4180 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:24:16.444  4180  4180 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:24:16.445  4180  4180 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:24:16.445  4180  4180 D A2dpStateMachine: make
09-06 19:24:16.446  4180  4180 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:24:16.447  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:24:16.449  4180  4211 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:24:16.450  4180  4180 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:24:16.451  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:16.451  4180  4180 D HidService: Received start request. Starting profile...
09-06 19:24:16.452  4180  4180 I bt_bluedroid: get_profile_interface hidhost
09-06 19:24:16.452  4180  4196 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ac3e5
,09-06 19:24:16.452  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:24:16.452  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 19:24:16.452  4180  4180 D HidService: setHidService(): set to: null
09-06 19:24:16.453  4180  4180 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:24:16.454  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:16.455  4180  4180 D HealthService: Received start request. Starting profile...
,09-06 19:24:16.457  4180  4180 I bt_bluedroid: get_profile_interface health
,09-06 19:24:16.458  4180  4180 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:24:16.459  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
,09-06 19:24:16.459  4180  4180 D PanService: Received start request. Starting profile...
09-06 19:24:16.460  4180  4180 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:24:16.460  4180  4180 I bt_bluedroid: get_profile_interface pan
,09-06 19:24:16.460  4180  4196 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:24:16.463  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b,
09-06 19:24:16.464  4180  4180 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:24:16.464  4180  4180 D BluetoothMapService: start()
,09-06 19:24:16.466  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:24:16.467  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:24:16.468  4180  4180 D BluetoothMapAppObserver: createReceiver()
,09-06 19:24:16.469  4180  4180 D BluetoothMapAppObserver: initObservers()
,09-06 19:24:16.469  4180  4180 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:24:16.481  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:24:16.481  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:16.481  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:16.481  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:16.484  4180  4209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:24:16.484  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:16.484  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:16.484  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:24:16.484  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:16.485  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:16.485  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:24:16.485  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:16.485  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:16.487  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:16.488  4180  4180 V BluetoothAdapterState: isTurningOff()=false
09-06 19:24:16.488  4180  4180 V BluetoothAdapterState: isTurningOn()=true
09-06 19:24:16.488  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:24:16.488  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:24:16.488  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:24:16.488  4180  4192 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:24:16.488  4180  4192 D BluetoothAdapterProperties: State =  11
09-06 19:24:16.488  4180  4192 D BluetoothAdapterProperties: Setting state to 12
,09-06 19:24:16.489  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:24:16.489  4180  4192 I BluetoothAdapterState: Entering OnState
09-06 19:24:16.489  1363  2094 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:24:16.489  4180  4196 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:24:16.490  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:24:16.492   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:16.492  1363  1374 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:16.493  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:16.493  3866  3876 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:24:16.495  1363  1363 D BluetoothInputDevice: Proxy object connected
,09-06 19:24:16.495  1363  1363 D HidProfile: Bluetooth service connected
09-06 19:24:16.495  1363  1375 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:24:16.497  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:16.497  3866  3879 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:24:16.498  1363  1363 D BluetoothMap: Proxy object connected
09-06 19:24:16.498  1363  1363 D MapProfile: Bluetooth service connected
09-06 19:24:16.498  1363  1363 D BluetoothMap: getConnectedDevices()
,09-06 19:24:16.499   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:24:16.499  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:24:16.499  3866  3876 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:24:16.499  1363  1363 D PanProfile: Bluetooth service connected
09-06 19:24:16.500  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:24:16.500  4180  4180 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-06 19:24:16.501   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:24:16.501  3866  4173 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:24:16.502  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:24:16.503  3866  3876 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:24:16.504  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:16.505  1363  2072 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:24:16.506  3866  3879 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:24:16.506  4180  4180 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:24:16.506  4180  4180 D ObexServerSockets0: startAccept()
09-06 19:24:16.506  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:24:16.508   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:24:16.508  4180  4180 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:24:16.508  4180  4180 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:24:16.508  1363  2094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:24:16.509  4180  4216 D ObexServerSockets0: Accepting socket connection...
09-06 19:24:16.509   875   875 D BluetoothA2dp: Proxy object connected
09-06 19:24:16.509  4180  4217 D ObexServerSockets0: Accepting socket connection...
,09-06 19:24:16.510  1363  2072 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:24:16.510  1363  1363 D BluetoothA2dp: Proxy object connected
09-06 19:24:16.511  1960  1974 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:24:16.512  3866  3866 D BluetoothInputDevice: Proxy object connected
,09-06 19:24:16.513   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:24:16.513  3866  3866 D HidProfile: Bluetooth service connected
09-06 19:24:16.514  4180  4180 D BluetoothMapService: onReceive
09-06 19:24:16.514  4180  4180 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:24:16.514  4180  4180 D BluetoothMapService: STATE_ON
09-06 19:24:16.514  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:16.515  3866  3866 D BluetoothMap: Proxy object connected
,09-06 19:24:16.515  3866  3866 D MapProfile: Bluetooth service connected
09-06 19:24:16.515  3866  3866 D BluetoothMap: getConnectedDevices()
09-06 19:24:16.517  3866  3866 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:24:16.517  3866  3866 D PanProfile: Bluetooth service connected
09-06 19:24:16.517  3866  3866 D BluetoothA2dp: Proxy object connected
,09-06 19:24:16.526  3866  3866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:24:16.531  3866  3866 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:24:16.535  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:24:16.548  3866  3866 D BluetoothPbap: Proxy object connected
,09-06 19:24:16.548  3866  3866 D PbapServerProfile: Bluetooth service connected
09-06 19:24:16.548  1363  1363 D BluetoothPbap: Proxy object connected
09-06 19:24:16.548  1363  1363 D PbapServerProfile: Bluetooth service connected
09-06 19:24:16.549  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:24:16.549  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:24:16.561  4180  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:16.584  4180  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:24:16.587  4180  4226 I BtOppRfcommListener: Accept thread started.
,09-06 19:24:16.596  3866  3879 D BluetoothHeadset: Proxy object connected
,09-06 19:24:16.596  3866  3866 D HeadsetProfile: Bluetooth service connected
09-06 19:24:16.597  1960  2168 D BluetoothHeadset: Proxy object connected
09-06 19:24:16.598   875   875 D BluetoothHeadset: Proxy object connected
09-06 19:24:16.600  1363  2072 D BluetoothHeadset: Proxy object connected
09-06 19:24:16.600  1363  1363 D HeadsetProfile: Bluetooth service connected
09-06 19:24:16.600   875   892 D BluetoothHeadset: Proxy object connected
,09-06 19:24:16.600   875   875 D BluetoothHeadset: Proxy object connected
09-06 19:24:16.601   875   875 D BluetoothHeadset: Proxy object connected
,09-06 19:24:16.602   875   892 D BluetoothHeadset: Proxy object connected
,09-06 19:24:16.606  1363  2094 D BluetoothHeadset: Proxy object connected
09-06 19:24:16.606  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-06 19:24:16.612  1960  1971 D BluetoothHeadset: Proxy object connected
,09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:16.657  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:16.662  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:16.663  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:16.663  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b972be added. We now have 8 listener(s)
,09-06 19:24:16.663  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:24:16.665   875  1913 D WifiService: setWifiEnabled: false pid=3812, uid=10000
09-06 19:24:16.666   875  1913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:24:16.675  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:16.676   875  1982 D WifiService: setWifiEnabled: true pid=3812, uid=10000
09-06 19:24:16.676   875  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:24:16.688   875  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:16.701  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:16.709  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:16.720   875  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:24:16.721   875  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 19:24:16.722   875  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:24:16.723   875  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:24:16.723   875  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 19:24:16.723   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:24:16.724   875  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:24:16.736   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-06 19:24:16.736   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:24:16.738   372   873 D CommandListener: Setting iface cfg
,09-06 19:24:16.791   875  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-06 19:24:16.792   875  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:24:16.797   875  1306 E native  : do suspend true
,09-06 19:24:16.802   875  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:24:16.819   875  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:24:16.835   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:17.698  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:17.706  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:17.715  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:24:17.717  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:24:17.722  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a9fd267 Bundle[{}]
,09-06 19:24:17.724  3812  3858 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:24:17.724  3812  3858 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:24:17.725  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:24:17.726  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:24:17.726  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:24:17.727  3812  3858 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:24:17.731  3812  3858 I System.out: Running OutgoingSocketThread
,09-06 19:24:17.732  3812  4234 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 419)
,09-06 19:24:17.733  3812  4234 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37529
09-06 19:24:17.734  3812  4234 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:24:18.149   875  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:24:18.264   875  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.56 rxSuccessRate=11.00 delta 1000 -> 994
,09-06 19:24:18.265   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:24:18.267   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:24:18.288   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:24:18.372   875  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:24:18.375  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:24:18.734  3812  3858 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 420)
,09-06 19:24:18.735  3812  3858 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 420)
,09-06 19:24:18.744  3812  3858 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 425)
,09-06 19:24:18.747  3812  3858 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:24:18.747  3812  3858 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,09-06 19:24:18.753  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:24:18.753  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfef1f added. We now have 2 listener(s)
,09-06 19:24:18.755  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:24:18.755  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.755  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.755  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.755  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e726c added. We now have 9 listener(s)
09-06 19:24:18.756  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.756  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:24:18.760  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:18.766  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:18.770  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:24:18.770  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:24:18.771  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:24:18.771  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.772  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a15fcca added. We now have 3 listener(s)
09-06 19:24:18.774  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:24:18.777  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:24:18.777  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.778  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.778  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:24:18.779  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9e5e3b added. We now have 10 listener(s)
09-06 19:24:18.779  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.779  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:24:18.780  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:24:18.780  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:24:18.780  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.780  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:24:18.780  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.781  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.781  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfef1f removed from the list
09-06 19:24:18.781  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.782  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e726c removed from the list
,09-06 19:24:18.782  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:24:18.782  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.783  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.784  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.785  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:24:18.785  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.785  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.785  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e726c not in the list
09-06 19:24:18.785  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.785  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:24:18.786  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.786  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.786  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:24:18.786  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9e5e3b removed from the list
09-06 19:24:18.787  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:24:18.787  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.787  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:24:18.787  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.787  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a15fcca removed from the list
09-06 19:24:18.788  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:24:18.788  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc64958 added. We now have 2 listener(s)
09-06 19:24:18.790  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.790  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.790  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.790  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.790  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd63ab1 added. We now have 9 listener(s)
,09-06 19:24:18.790  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.791  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:24:18.795  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:18.800  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:24:18.802  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:18.803  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:24:18.803  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:24:18.803  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0aa317 added. We now have 3 listener(s)
,09-06 19:24:18.806  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:24:18.806  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.806  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.806  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.806  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.806  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@602a304 added. We now have 10 listener(s)
09-06 19:24:18.806  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.806  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.806  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:24:18.807  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:24:18.807  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.807  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:24:18.810  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.811  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:24:18.811  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:24:18.815  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:24:18.816  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:24:18.816  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:24:18.825  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:24:18.825  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:24:18.825  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:24:18.826  3812  3858 D BluetoothAdapter: STATE_ON
,09-06 19:24:18.831  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:24:18.831  4180  4208 D BtGatt.GattService: registerClient() - UUID=360bcdca-1c23-4476-a620-196a0e816ff5
,09-06 19:24:18.832  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=360bcdca-1c23-4476-a620-196a0e816ff5, clientIf=5
,09-06 19:24:18.833  3812  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:24:18.837  4180  4190 D BtGatt.GattService: start scan with filters
,09-06 19:24:18.850  4180  4199 D BtGatt.ScanManager: handling starting scan
,09-06 19:24:18.850  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:24:18.851  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-06 19:24:18.851  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:24:18.851  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:24:18.854  4180  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c68388b
09-06 19:24:18.855  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:24:18.855  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:24:18.855  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:24:18.857  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:24:18.860  3812  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:24:18.860  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:24:18.860  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:24:18.860  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:24:18.860  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:24:18.860  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:24:18.860  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:24:18.860  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:24:18.860  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:24:18.861  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:24:18.861  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:24:18.862  3812  3858 D BluetoothAdapter: STATE_ON
,09-06 19:24:18.863  4180  4190 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:24:18.863  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:24:18.863  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:24:18.863  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.863  4180  4218 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:24:18.863  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-06 19:24:18.864  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:24:18.864  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:24:18.864  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:24:18.865  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:24:18.865  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:24:18.866  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.866  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:24:18.866  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:24:18.867  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:24:18.867  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:24:18.868  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.869  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.869  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.869  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.872  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:24:18.873  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:24:18.873  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:24:18.873  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.873  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.873  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.873  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.873  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc64958 removed from the list
09-06 19:24:18.873  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.873  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd63ab1 removed from the list
09-06 19:24:18.874  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:24:18.874  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 1 listener(s) left
09-06 19:24:18.874   875  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:24:18.877  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.877  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.878  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.878  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.878  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.878  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd63ab1 not in the list
09-06 19:24:18.879  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.879  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.880  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.880  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.880  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.880  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@602a304 removed from the list
09-06 19:24:18.880  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.880  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.880  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.880  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.880  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0aa317 removed from the list
09-06 19:24:18.881  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:24:18.881  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.882  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.882  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588eb70 added. We now have 2 listener(s)
09-06 19:24:18.882  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:24:18.882  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:24:18.884  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.884  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.884  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.884  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.884  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManage,rSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba88ee9 added. We now have 9 listener(s)
09-06 19:24:18.884  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.885  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:24:18.888   875  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-06 19:24:18.888  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.888   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:24:18.888   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:18.891  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:18.893  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:24:18.893  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.894  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:18.894  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:24:18.895  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.895  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@368de0f added. We now have 3 listener(s)
09-06 19:24:18.896  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.896  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.897  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.897  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.897  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e94e9c added. We now have 10 listener(s)
09-06 19:24:18.897  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.897  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.900  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:24:18.899  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.900  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.900  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:24:18.900  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.901  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.902  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:24:18.902  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.902  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:24:18.907   875  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:24:18.908  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:24:18.908  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:24:18.910  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:24:18.910  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.910  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:24:18.913  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:24:18.914  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:24:18.915  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:24:18.916  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:24:18.916  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.916  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:24:18.919   372   873 D CommandListener: Setting iface cfg
09-06 19:24:18.919   875  1306 D WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:24:18.920  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:24:18.920  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:24:18.920  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:24:18.921  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:24:18.921  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:24:18.921  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.922  4180  4218 D BtGatt.GattService: registerClient() - UUID=ac3ca8ce-44bb-44ce-90b7-3755ae515686
09-06 19:24:18.923  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=ac3ca8ce-44bb-44ce-90b7-3755ae515686, clientIf=5
09-06 19:24:18.923  3812  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:24:18.923  4180  4208 D BtGatt.GattService: start scan with filters
09-06 19:24:18.925  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:24:18.925  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:24:18.925  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:24:18.925  4180  4199 D BtGatt.ScanManager: handling starting scan
09-06 19:24:18.925  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:24:18.927   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-06 19:24:18.927  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:24:18.927  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:24:18.927  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:24:18.929  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:24:18.931  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:24:18.931  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.931  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.931  3812  3858 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:24:18.931  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:24:18.931  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:24:18.931  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:24:18.931  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:24:18.931  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.932  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.932  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:24:18.932  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.932  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@588eb70 removed from the list
09-06 19:24:18.932  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.932  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba88ee9 removed from the list
09-06 19:24:18.932  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:24:18.932  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.932  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.932  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:24:18.932  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.932  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.934  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.934  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.934  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.935  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba88ee9 not in the list
09-06 19:24:18.935  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:24:18.935  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:24:18.935  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:24:18.935  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:24:18.935  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:24:18.936  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:24:18.936  4180  4191 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:24:18.936  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:24:18.936  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.936  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:24:18.936  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:24:18.936  4180  4190 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:24:18.937  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:24:18.937  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:24:18.937  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:24:18.937  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:24:18.937  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:24:18.937  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.938  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:24:18.938  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:24:18.938  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:24:18.938  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.939  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.939  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.939  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.939  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.939  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.939  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.939  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e94e9c removed from the list
09-06 19:24:18.939  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.939  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.939  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.940  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.940  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@368de0f removed from the list
09-06 19:24:18.940  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.940  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ab888 added. We now have 2 listener(s)
09-06 19:24:18.942  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.942  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.942  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.942  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.942  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87a3221 added. We now have 9 listener(s)
09-06 19:24:18.942  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.942  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:24:18.945  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.946  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:24:18.946  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.946   875  4237 D DhcpClient: Receive thread started
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:18.947  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:18.949  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:18.949  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:24:18.950  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.950  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b048007 added. We now have 3 listener(s)
09-06 19:24:18.950  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.951  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:24:18.951  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.951  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.952  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.952  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.952  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.952  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.952  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c56d534 added. We now have 10 listener(s)
09-06 19:24:18.952  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.953  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.953  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:24:18.953  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:24:18.953  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.953  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:24:18.955  3812  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:24:18.955  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:24:18.956  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:24:18.956  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.957  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:24:18.958  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:24:18.959  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:24:18.959  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:24:18.961  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:24:18.961  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:24:18.961  3812  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:24:18.962  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:24:18.962  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:24:18.962  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.962  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:24:18.963  4180  4208 D BtGatt.GattService: registerClient() - UUID=c21ce40d-3f46-4a32-9752-8e3e62133d96
09-06 19:24:18.963  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=c21ce40d-3f46-4a32-9752-8e3e62133d96, clientIf=5
09-06 19:24:18.964  3812  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:24:18.964  4180  4218 D BtGatt.GattService: start scan with filters
09-06 19:24:18.965  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:24:18.965  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:24:18.966  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:24:18.966  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:24:18.967  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:24:18.967  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.968  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:24:18.968  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:24:18.968  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:24:18.968  4180  4199 D BtGatt.ScanManager: handling starting scan
09-06 19:24:18.969  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:24:18.972  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:24:18.972  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:24:18.972  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:24:18.972  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.972  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.972  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:24:18.972  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.972  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88ab888 removed from the list
09-06 19:24:18.972  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.972  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87a3221 removed from the list
09-06 19:24:18.973  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:24:18.973  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.973  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.973  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:24:18.973  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.973  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.974  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87a3221 not in the list
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:24:18.974  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:24:18.974  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:24:18.974  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:24:18.974  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:24:18.974  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:24:18.974  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:24:18.974  3812  3858 D BluetoothAdapter: STATE_ON
09-06 19:24:18.975  4180  4218 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:24:18.975  4180  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:24:18.976  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:24:18.976  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:24:18.976  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:24:18.976  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:24:18.976  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:24:18.976  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.977  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:24:18.977  3812  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:24:18.977  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:24:18.977  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.978  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.978  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:24:18.978  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:24:18.978  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.978  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.978  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.978  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c56d534 removed from the list
09-06 19:24:18.978  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.978  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.978  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.978  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.978  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b048007 removed from the list
09-06 19:24:18.979  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:24:18.979  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.979  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.979  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32610a0 added. We now have 2 listener(s)
09-06 19:24:18.979  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:24:18.979  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:24:18.980  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.980  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.980  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.980  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.980  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c060459 added. We now have 9 listener(s)
09-06 19:24:18.980  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.981  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:24:18.982  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:24:18.985  3812  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:24:18.986  3812  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:24:18.986  3812  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:24:18.987  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:24:18.987  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.987  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34368ff added. We now have 3 listener(s)
09-06 19:24:18.988  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:24:18.989  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:24:18.989  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:24:18.989  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.989  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:24:18.989  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:24:18.989  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:24:18.991  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb96cc added. We now have 10 listener(s)
09-06 19:24:18.991  3812  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:24:18.991  3812  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:24:18.991  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:24:18.991  3812  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:24:18.991  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.991  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.991  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:24:18.991  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.991  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32610a0 removed from the list
09-06 19:24:18.991  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.991  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c060459 removed from the list
09-06 19:24:18.991  3812  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:24:18.992  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.992  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.992  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.993  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.993  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.993  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.993  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:24:18.993  3812  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c060459 not in the list
,09-06 19:24:18.993  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.993  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.993  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.994  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:24:18.994  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:24:18.994  3812  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:24:18.994  3812  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb96cc removed from the list
09-06 19:24:18.994  3812  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:24:18.994  3812  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:24:18.994  3812  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:24:18.994  3812  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:24:18.994  3812  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34368ff removed from the list
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:24:18.995  3812  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:24:18.998  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:24:18.998  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:18.998  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:24:19.001  3812  4238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
09-06 19:24:19.001  3812  4238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: My test thread name)
09-06 19:24:19.001  3812  4238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:24:19.003  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:24:19.003  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:19.003  3812  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: My test thread name)
09-06 19:24:19.003  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:24:19.004  3812  4239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: My test thread name)
09-06 19:24:19.004  3812  4239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:24:19.006  3812  3858 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:24:19.006  3812  3858 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:24:19.006  3812  3858 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:24:19.006  3812  3858 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:24:19.006  3812  3858 D com.test.thalitest.ThaliTestRunner: Total duration: 22767 ms
09-06 19:24:19.007  3812  3858 I jxcore-log: *Native tests were executed*
09-06 19:24:19.007  3812  3858 I jxcore-log: 
09-06 19:24:19.007  3812  3858 I jxcore-log: Total number of executed tests:  80
09-06 19:24:19.007  3812  3858 I jxcore-log: 
09-06 19:24:19.008  3812  3858 I jxcore-log: Number of passed tests:  80
09-06 19:24:19.008  3812  3858 I jxcore-log: 
09-06 19:24:19.008  3812  3858 I jxcore-log: Number of failed tests:  0
09-06 19:24:19.008  3812  3858 I jxcore-log: 
09-06 19:24:19.008  3812  3858 I jxcore-log: Number of ignored tests:  0
09-06 19:24:19.008  3812  3858 I jxcore-log: 
09-06 19:24:19.008  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:24:19.008  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:24:19.008  3812  3858 I jxcore-log: Total duration:  22767
09-06 19:24:19.008  3812  3858 I jxcore-log: 
09-06 19:24:19.009  3812  3858 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:24:19.009  3812  3858 I jxcore-log: 
09-06 19:24:19.011  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.011  3812  3858 I jxcore-log: 
09-06 19:24:19.013  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.013  3812  3858 I jxcore-log: 
09-06 19:24:19.014  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.014  3812  3858 I jxcore-log: 
09-06 19:24:19.014  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.014  3812  3858 I jxcore-log: 
09-06 19:24:19.015  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.015  3812  3858 I jxcore-log: 
09-06 19:24:19.016  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.016  3812  3858 I jxcore-log: 
09-06 19:24:19.018  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.018  3812  3858 I jxcore-log: 
09-06 19:24:19.019  3812  3812 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:24:19.019  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.019  3812  3858 I jxcore-log: 
09-06 19:24:19.020  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.020  3812  3858 I jxcore-log: 
09-06 19:24:19.020  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.020  3812  3858 I jxcore-log: 
09-06 19:24:19.021  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.021  3812  3858 I jxcore-log: 
09-06 19:24:19.021  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:24:19.021  3812  3858 I jxcore-log: 
09-06 19:24:19.022  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.022  3812  3858 I jxcore-log: 
09-06 19:24:19.022  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.022  3812  3858 I jxcore-log: 
09-06 19:24:19.023  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.023  3812  3858 I jxcore-log: 
09-06 19:24:19.023  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.023  3812  3858 I jxcore-log: 
09-06 19:24:19.024  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.024  3812  3858 I jxcore-log: 
09-06 19:24:19.024  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.024  3812  3858 I jxcore-log: 
09-06 19:24:19.025  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.025  3812  3858 I jxcore-log: 
09-06 19:24:19.025  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.025  3812  3858 I jxcore-log: 
09-06 19:24:19.026   875  1306 E native  : do suspend false
09-06 19:24:19.026  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.026  3812  3858 I jxcore-log: 
09-06 19:24:19.026  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.026  3812  3858 I jxcore-log: 
09-06 19:24:19.027  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.027  3812  3858 I jxcore-log: 
09-06 19:24:19.027  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.027  3812  3858 I jxcore-log: 
09-06 19:24:19.027  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.027  3812  3858 I jxcore-log: 
09-06 19:24:19.028  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:24:19.028  3812  3858 I jxcore-log: 
09-06 19:24:19.028  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.028  3812  3858 I jxcore-log: 
09-06 19:24:19.029  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.029  3812  3858 I jxcore-log: 
09-06 19:24:19.029  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.029  3812  3858 I jxcore-log: 
09-06 19:24:19.030  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.030  3812  3858 I jxcore-log: 
09-06 19:24:19.030  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.030  3812  3858 I jxcore-log: 
09-06 19:24:19.031  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.031  3812  3858 I jxcore-log: 
09-06 19:24:19.031  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:24:19.031  3812  3858 I jxcore-log: 
,09-06 19:24:19.038   875  2136 D DhcpClient: Broadcasting DHCPDISCOVER
09-06 19:24:19.049   875  4237 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
09-06 19:24:19.049   875  2136 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
09-06 19:24:19.050   875  2136 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:24:19.063   875  4237 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:24:19.063   875  2136 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:24:19.064   372   873 D CommandListener: Setting iface cfg
,09-06 19:24:19.068   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:24:19.072   875  1306 E native  : do suspend true
,09-06 19:24:19.073   875  2136 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:24:19.085   875  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:24:19.086   875  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 19:24:19.087   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 19:24:19.089   875  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 19:24:19.090   875  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:24:19.140   875  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:24:19.141   875  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-06 19:24:19.142   875  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 19:24:19.143   875  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 19:24:19.145   875  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 19:24:19.152   875  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:24:19.159   875  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 19:24:19.159   875  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-06 19:24:19.159   875  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-06 19:24:19.159   875  1308 D ConnectivityService:    accepting network in place of null
09-06 19:24:19.159   875  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:24:19.160   875  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:24:19.160   875  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:24:19.169   875  4236 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217728, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 19:24:19.189   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:19.229   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:24:19.235   875  4235 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:803::200e
,09-06 19:24:19.236   875  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 19:24:19.237   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:24:19.246   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:24:19.252   875  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:24:19.252  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:24:19.256  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:24:19.257  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:24:19.257  3812  3858 I jxcore-log: 
09-06 19:24:19.267  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:24:19.275  1715  1715 D SystemUpdateService: onCreate
,09-06 19:24:19.284  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:24:19.310  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:24:19.312  1715  2519 I iu.UploadsManager: num queued entries: 0
,09-06 19:24:19.314   875  4235 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:24:19 GMT], X-Android-Received-Millis=[1473182659312], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473182659281]}
09-06 19:24:19.316   875  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 19:24:19.317   875  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-06 19:24:19.317   875  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:24:19.322  1715  4250 I SystemUpdateService: active receiver: enabled
,09-06 19:24:19.326  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:24:19.325   875  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:24:19.329  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:24:19.331  3945  3945 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:24:19.337  1715  2519 I iu.UploadsManager: num updated entries: 0
,09-06 19:24:19.345  1715  4252 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 19:24:19.345  1715  4252 W BaseAppContext: Using Auth Proxy for data requests.
09-06 19:24:19.345  1715  4250 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-06 19:24:19.346  3945  3945 D SprintDMHelper: simOperator: 
09-06 19:24:19.346  3945  3945 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:24:19.348  1715  4252 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:24:19.351  1715  2519 I iu.SyncManager: NEXT; no task
,09-06 19:24:19.352  1715  4250 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:24:19.352  1715  4250 I SystemUpdateService: now status is 0 (complete)
09-06 19:24:19.352  1715  4250 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:24:19.352  1715  4250 I SystemUpdateService: file has been verified
09-06 19:24:19.352  1715  4250 I SystemUpdateService: OTA package size = 12249756
,09-06 19:24:19.360  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:19.364  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:24:19.369  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:24:19.370  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:24:19.370  3812  3858 I jxcore-log: 
,09-06 19:24:19.401  1715  4250 I SystemUpdateService: showing system update notification
,09-06 19:24:19.439  1715  1715 D SystemUpdateService: onDestroy
,09-06 19:24:19.439  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:24:19.441  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:24:19.441  3812  3858 I jxcore-log: 
,09-06 19:24:19.456  1501  2039 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:24:19.457  1501  2039 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:24:19.457  1501  2039 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:24:19.457  1501  2039 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:24:19.476  1715  4252 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-06 19:24:19.479  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:24:19.483  3812  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:24:19.483  3812  3858 I jxcore-log: 
,09-06 19:24:19.490  3918  4256 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:24:19.733  4241  4241 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 19:24:19.738  4241  4241 D AndroidRuntime: CheckJNI is OFF
,09-06 19:24:19.781  4241  4241 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 19:24:19.828  4241  4241 I Radio-JNI: register_android_hardware_Radio DONE
,09-06 19:24:19.853  4241  4241 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:24:19.864   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 19:24:19.865   875   888 I ActivityManager: Killing 3812:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-06 19:24:19.981   875   898 W PackageSettings: Skipping PackageSetting{9d349cc com.example.hello/10273} due to missing metadata
,09-06 19:24:19.993   875  1307 D WifiService: Client connection lost with reason: 4
,09-06 19:24:19.995   875  2271 I WindowState: WIN DEATH: Window{6c321e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:24:19.994   875  2018 D GraphicsStats: Buffer count: 2
,09-06 19:24:20.004   875  1297 W Looper  : Ignoring unexpected epoll events 0x11 on fd 107 that is no longer registered.
,09-06 19:24:20.024   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-06 19:24:20.024   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-06 19:24:20.025   875   888 E ActivityManager: Failure starting process com.test.thalitest
09-06 19:24:20.025   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!,
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-06 19:24:20.025   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.025   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.025   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:24:20.025   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:24:20.025   875   888 I ActivityManager:   Force finishing activity ActivityRecord{ae1aee3 u0 com.test.thalitest/.MainActivity t2}
,09-06 19:24:20.037   875  1912 W ActivityManager: Spurious death for ProcessRecord{2a09a97 0:com.test.thalitest/u0a0}, curProc for 3812: null
,09-06 19:24:20.038   875   898 I art     : Starting a blocking GC Explicit
,09-06 19:24:20.091   875   898 I art     : Explicit concurrent mark sweep GC freed 52840(3MB) AllocSpace objects, 10(284KB) LOS objects, 33% free, 29MB/43MB, paused 743us total 52.918ms
,09-06 19:24:20.116   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-06 19:24:20.119  4241  4241 I art     : System.exit called, status: 0
09-06 19:24:20.119  4241  4241 I AndroidRuntime: VM exiting with result code 0.
,09-06 19:24:20.128   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-06 19:24:20.145   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-06 19:24:20.151  4180  4180 D BluetoothMapAppObserver: onReceive
,09-06 19:24:20.151  4180  4180 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-06 19:24:20.153   875  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:24:20.157  1878  2286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-06 19:24:20.154  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
09-06 19:24:20.158  3649  3649 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-06 19:24:20.170   875  2271 I ActivityManager: Start proc 4272:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-06 19:24:20.172  1960  1960 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 19:24:20.183  1890  4278 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 19:24:20.194  1890  4278 I Decoder : createOrResetDecoder
,09-06 19:24:20.217  1501  1501 I ConfigService: onCreate
,09-06 19:24:20.231  4272  4272 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 19:24:20.242   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:24:20.256  1890  4278 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 19:24:20.258   875  2041 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3812 uid 10000
,09-06 19:24:20.262   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-06 19:24:20.262  1975  2066 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-06 19:24:20.263   875   887 E PackageManager: Failed to write settings, restoring backup
09-06 19:24:20.263   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-06 19:24:20.263   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-06 19:24:20.263   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-06 19:24:20.263   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-06 19:24:20.263   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-06 19:24:20.263   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.263   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.263   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.265   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-06 19:24:20.265   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:24:20.265   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.265   875   888 E DropBoxManagerService: 	... 13 more
,09-06 19:24:20.266  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-06 19:24:20.274   875  1982 I ActivityManager: Start proc 4287:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-06 19:24:20.275  1975  2066 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-06 19:24:20.275  1975  2066 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1975
09-06 19:24:20.275  1975  2066 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: ,	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.275  1975  2066 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.278   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:24:20.282  1975  2066 I Process : Sending signal. PID: 1975 SIG: 9
,09-06 19:24:20.296   875  4292 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:24:20.296   875  4292 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.296   875  4292 E DropBoxManagerService: 	... 5 more
,09-06 19:24:20.319  1890  4278 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-06 19:24:20.321  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-06 19:24:20.321  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-06 19:24:20.323  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-06 19:24:20.323  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-06 19:24:20.323  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-06 19:24:20.324  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-06 19:24:20.324  1890  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-06 19:24:20.324  1890  4278 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-06 19:24:20.324  1890  4278 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-06 19:24:20.324  1890  4278 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-06 19:24:20.325  1890  4278 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-06 19:24:20.325  1890  4278 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 19:24:20.345   875  1391 D GraphicsStats: Buffer count: 1
,09-06 19:24:20.345   875  2268 I WindowState: WIN DEATH: Window{3defc3f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-06 19:24:20.352  4272  4272 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-06 19:24:20.362   875  1913 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1975) has died
,09-06 19:24:20.363   875  1913 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-06 19:24:20.364   875  1913 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:24:20.378  4272  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.378  4272  4302 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.380   875   888 I ActivityManager: Start proc 4305:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.386  4272  4302 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.399   875  2271 I ActivityManager: Start proc 4312:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-06 19:24:20.423  4272  4310 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:24:20.429  4312  4312 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-06 19:24:20.440  4305  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:24:20.440  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:24:20.440  4305  4305 D AndroidRuntime: Shutting down VM
,09-06 19:24:20.447  4305  4305 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:24:20.447  4305  4305 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4305
09-06 19:24:20.447  4305  4305 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:24:20.447  4305  4305 E AndroidRuntime: 	... 10 more
,09-06 19:24:20.450   875  1479 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:24:20.451   875  4331 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:24:20.451   875  4331 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.451   875  4331 E DropBoxManagerService: 	... 5 more
09-06 19:24:20.451  4305  4305 I Process : Sending signal. PID: 4305 SIG: 9
,09-06 19:24:20.481  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-06 19:24:20.483  1501  1501 D AndroidRuntime: Shutting down VM
09-06 19:24:20.483   875  2268 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4305) has died
,09-06 19:24:20.484   875  2268 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:24:20.484  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:24:20.484  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-06 19:24:20.484  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-06 19:24:20.484  1501  1501 E AndroidRuntime: 	... 8 more
,09-06 19:24:20.488   875  4335 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:24:20.488   875  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.488   875  4335 E DropBoxManagerService: 	... 5 more
,09-06 19:24:20.499   875   888 I ActivityManager: Start proc 4337:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:24:20.502  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,09-06 19:24:20.504   875  2269 I ActivityManager: Killing 3702:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 19:24:20.546  4272  4302 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-06 19:24:20.551  4272  4310 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.551  4272  4310 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.551  4272  4310 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 19:24:20.551  4272  4310 E AndroidRuntime: Process: android.process.acore, PID: 4272
09-06 19:24:20.551  4272  4310 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.551  4272  4310 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:24:20.552  4272  4302 I Process : Sending signal. PID: 4272 SIG: 9
,09-06 19:24:20.558   875  1307 D WifiService: Client connection lost with reason: 4
,09-06 19:24:20.574   875  2268 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
09-06 19:24:20.575   875  2268 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-06 19:24:20.575   875  2268 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
09-06 19:24:20.575   875  2268 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
09-06 19:24:20.575   875  2268 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
,09-06 19:24:20.585  1715  1715 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-06 19:24:20.605   875  1978 I ActivityManager: Start proc 4349:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-06 19:24:20.610   875  4355 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:24:20.610   875  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.610   875  4355 E DropBoxManagerService: 	... 5 more
,09-06 19:24:20.619  4337  4337 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:24:20.619  4337  4337 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:24:20.620  4337  4337 D AndroidRuntime: Shutting down VM
,09-06 19:24:20.636  4337  4337 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:24:20.636  4337  4337 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4337
09-06 19:24:20.636  4337  4337 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:24:20.636  4337  4337 E AndroidRuntime: 	... 10 more
,09-06 19:24:20.640  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-06 19:24:20.640  1715  1715 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-06 19:24:20.645  4349  4349 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-06 19:24:20.646   875  2041 I ActivityManager: Process android.process.acore (pid 4272) has died
,09-06 19:24:20.646   875  2041 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-06 19:24:20.650   875  4364 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:24:20.650   875  4364 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:24:20.650   875  4364 E DropBoxManagerService: 	... 5 more
,09-06 19:24:20.651   875  1382 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:24:20.651  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games

```
