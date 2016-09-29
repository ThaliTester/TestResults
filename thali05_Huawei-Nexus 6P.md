#### Test 87116923cb17c22_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-29 05:21:29.365   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-29 05:21:29.366   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 05:21:31.373  5551  5551 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-29 05:21:31.378  5551  5551 D AndroidRuntime: CheckJNI is OFF
09-29 05:21:31.378   928  2891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-29 05:21:31.405  5551  5551 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-29 05:21:31.437  5551  5551 I Radio-JNI: register_android_hardware_Radio DONE
09-29 05:21:31.452  5551  5551 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-29 05:21:31.469   928  3071 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-29 05:21:31.531   928  3071 I ActivityManager: Start proc 5560:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-29 05:21:31.546  5551  5551 D AndroidRuntime: Shutting down VM
,09-29 05:21:31.872   928   939 I WindowManager: Screenshot max retries 4 of Token{c93d1e8 ActivityRecord{5216f0b u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7a6b483 u0 Starting com.test.thalitest} drawState=2
,09-29 05:21:31.944  5560  5560 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-29 05:21:31.979  5560  5560 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-29 05:21:32.007  5560  5560 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 1014-1034)
,09-29 05:21:32.007  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-29 05:21:32.030  5560  5560 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7364f67}
,09-29 05:21:32.030  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-29 05:21:32.031  5560  5560 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-29 05:21:32.036  5560  5560 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-29 05:21:32.038  5560  5560 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-29 05:21:32.080  5560  5560 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-29 05:21:32.095  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-29 05:21:32.095  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 05:21:32.095  5560  5560 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-29 05:21:32.095  5560  5560 I Adreno  : Build Date                       : 12/06/15
09-29 05:21:32.095  5560  5560 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-29 05:21:32.095  5560  5560 I Adreno  : Local Branch                     : mybranch17112971
09-29 05:21:32.095  5560  5560 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-29 05:21:32.095  5560  5560 I Adreno  : Remote Branch                    : NONE
09-29 05:21:32.095  5560  5560 I Adreno  : Reconstruct Branch               : NOTHING
,09-29 05:21:32.143   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f030fb:true
,09-29 05:21:32.172   951   951 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[31160]" dev="sockfs" ino=31160 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.172   951   951 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31160]" dev="sockfs" ino=31160 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.184  5560  5560 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-29 05:21:32.193  5560  5560 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-29 05:21:32.222   951   951 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34276]" dev="sockfs" ino=34276 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.223  5560  5597 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-29 05:21:32.222   951   951 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34276]" dev="sockfs" ino=34276 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.225  3795  3795 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[20772]" dev="sockfs" ino=20772 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.225  3795  3795 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[20772]" dev="sockfs" ino=20772 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:32.230  5560  5584 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-29 05:21:32.264  5560  5597 I OpenGLRenderer: Initialized EGL, version 1.4
,09-29 05:21:32.358   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +481ms (total +854ms)
,09-29 05:21:32.389  5560  5560 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5560
,09-29 05:21:32.489  5560  5560 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-29 05:21:32.683  5560  5600 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -584316624
,09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-29 05:21:32.693  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc3f76c added. We now have 1 listener(s)
,09-29 05:21:32.697  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-29 05:21:32.697  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 05:21:32.698  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:21:32.698  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-29 05:21:32.702  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaf1e58 added. We now have 1 listener(s)
09-29 05:21:32.703  5560  5600 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:21:32.707   928  2892 D WifiService: New client listening to asynchronous messages
,09-29 05:21:32.708  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:21:32.708  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-29 05:21:32.708  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-29 05:21:32.708  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-29 05:21:32.708  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-29 05:21:32.712  5560  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:32.713  5560  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-29 05:21:32.718  5560  5600 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:21:32.718  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:21:32.718  5560  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-29 05:21:32.718  5560  5600 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:21:32.718  5560  5600 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-29 05:21:33.027  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:33.034  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:33.045  5560  5560 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-29 05:21:33.366  5560  5569 I art     : Background sticky concurrent mark sweep GC freed 77819(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 2.132ms total 213.546ms
,09-29 05:21:33.898  5560  5606 W jxcore-log: Initializing JXcore engine
,09-29 05:21:33.898  5560  5606 W jxcore-log: JXcore engine is ready
,09-29 05:21:33.975  5606  5606 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11654 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-29 05:21:33.975  5606  5606 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16451]" dev="sockfs" ino=16451 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-29 05:21:33.975  5606  5606 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-29 05:21:33.975  5606  5606 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33099]" dev="sockfs" ino=33099 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-29 05:21:33.995  5560  5606 W jxcore-log: Starting JXcore engine
,09-29 05:21:34.066  5560  5606 W jxcore-log: Platform android
09-29 05:21:34.066  5560  5606 W jxcore-log: 
09-29 05:21:34.066  5560  5606 W jxcore-log: Process ARCH arm
09-29 05:21:34.066  5560  5606 W jxcore-log: 
,09-29 05:21:34.165  5560  5606 I jxcore-log: JXcore Cordova bridge is ready!
09-29 05:21:34.165  5560  5606 I jxcore-log: 
,09-29 05:21:34.166  5560  5606 W jxcore-log: JXcore engine is started
,09-29 05:21:34.177  5560  5600 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-29 05:21:34.184  5560  5560 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-29 05:21:39.367   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:40.368   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:41.221  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-29 05:21:41.221  5560  5606 I jxcore-log: 
,09-29 05:21:41.222  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-29 05:21:41.222  5560  5606 I jxcore-log: 
,09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:21:41.227  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:21:41.228  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:21:41.230  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-29 05:21:41.230  5560  5606 I jxcore-log: 
,09-29 05:21:41.231  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-29 05:21:41.231  5560  5606 I jxcore-log: 
,09-29 05:21:41.369   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:41.469  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:21:41.469  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b36eaf2 added. We now have 2 listener(s)
09-29 05:21:41.470  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:41.470  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:21:41.470  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 05:21:41.470  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:21:41.470  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b23f543 added. We now have 2 listener(s)
,09-29 05:21:41.471  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:21:41.471  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:21:41.473  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:21:41.476  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:21:41.477  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:41.477  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 05:21:41.478  5560  5606 D ExecuteNativeTests: Running unit tests
,09-29 05:21:41.478  5560  5606 D BluetoothAdapter: enable(): BT is already enabled..!
,09-29 05:21:41.479   928  3789 D WifiService: setWifiEnabled: true pid=5560, uid=10077
09-29 05:21:41.479   928  3789 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:21:41.484  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:41.491  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:42.371   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:43.373   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:44.374   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 05:21:49.375   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:50.376   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:51.322   928  2893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 05:21:51.377   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:51.485  5560  5606 I com.test.thalitest.ThaliTestRunner: Running UT
,09-29 05:21:51.553  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:21:51.553  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68bedd added. We now have 3 listener(s)
09-29 05:21:51.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:51.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:21:51.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 05:21:51.554  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:21:51.554  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aeca52 added. We now have 3 listener(s)
09-29 05:21:51.554  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 05:21:51.555  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 05:21:51.557  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:21:51.560  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:21:51.562  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:21:51.562  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 05:21:51.566  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-29 05:21:51.566  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-29 05:21:51.566  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 05:21:51.566  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:51.566  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:51.567  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-29 05:21:51.567  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 05:21:51.567  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 05:21:51.567  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:51.567  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:51.567  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:51.568  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,09-29 05:21:51.568  5560  5606 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-29 05:21:51.570  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-29 05:21:51.571  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-29 05:21:51.571  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-29 05:21:51.573  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:51.578  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:51.579  5560  5606 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 05:21:51.579  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-29 05:21:51.579  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-29 05:21:51.579  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:51.580  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 05:21:51.580  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:21:51.580  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:21:51.580  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 05:21:51.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:21:51.581  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:21:51.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:21:51.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 05:21:51.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:21:51.581  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:21:51.581  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-29 05:21:51.584  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:21:51.584  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:21:51.585  5560  5608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:51.590  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:21:51.585  4543  4543 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34914]" dev="sockfs" ino=34914 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:51.590  5560  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 05:21:51.591  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:21:51.591  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:21:51.589  4543  4543 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34914]" dev="sockfs" ino=34914 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:51.592  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-29 05:21:51.592  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:51.593  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-29 05:21:51.593  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:51.593  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:51.593  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 05:21:51.594  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:21:51.597  4522  4544 D BtGatt.GattService: registerClient() - UUID=59e3a05c-7672-4d28-84d0-6f1fcc2c1982
09-29 05:21:51.599  4522  4593 D BtGatt.GattService: onClientRegistered() - UUID=59e3a05c-7672-4d28-84d0-6f1fcc2c1982, clientIf=5
09-29 05:21:51.600  5560  5570 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 05:21:51.603  4522  4595 D BtGatt.AdvertiseManager: message : 0
09-29 05:21:51.606  4522  4595 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 05:21:51.623  4522  4593 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-29 05:21:51.632  4522  4593 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-29 05:21:51.633  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 05:21:51.634  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:21:51.635  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:21:51.636  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
09-29 05:21:51.636  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:51.636  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 05:21:51.636  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 05:21:51.637  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:21:51.637  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 05:21:51.637  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-29 05:21:51.640  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-29 05:21:51.641  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:21:52.138  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-29 05:21:52.139  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-29 05:21:52.140  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-29 05:21:52.141  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 05:21:52.141  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-29 05:21:52.141  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:21:52.142  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 05:21:52.142  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 05:21:52.143  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-29 05:21:52.143  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 05:21:52.144  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:21:52.144  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:21:52.144  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:21:52.145  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:21:52.145  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:21:52.145  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:21:52.145  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 05:21:52.145  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:21:52.146  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:21:52.146  5560  5608 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 05:21:52.146  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:21:52.146  5560  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 05:21:52.146  5560  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:21:52.147  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:21:52.149  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:21:52.149  5560  5606 D BluetoothLeScanner: could not find callback wrapper
09-29 05:21:52.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:21:52.150  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 05:21:52.151  4522  4595 D BtGatt.AdvertiseManager: message : 1
09-29 05:21:52.153  4522  4595 D BtGatt.AdvertiseManager: stop advertise for client 5
09-29 05:21:52.164  4522  4593 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-29 05:21:52.164  4522  4593 D BtGatt.GattService: Client app is not null!
,09-29 05:21:52.166  4522  4543 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:21:52.166  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-29 05:21:52.167  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:21:52.167  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-29 05:21:52.167  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 05:21:52.167  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 05:21:52.169  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:21:52.169  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:21:52.170  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:21:52.170  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 05:21:52.172  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 05:21:52.172  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 05:21:52.173  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:52.173  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 05:21:52.173  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:52.173  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:21:52.174  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 05:21:52.174  5560  5606 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 05:21:52.174  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-29 05:21:52.174  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-29 05:21:52.175  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:52.175  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 05:21:52.175  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:21:52.175  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:52.177  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 05:21:52.177  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:21:52.177  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:21:52.178  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:21:52.178  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:21:52.178  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 05:21:52.178  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:21:52.178  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:21:52.179  5560  5611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:52.182  4742  4742 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33140]" dev="sockfs" ino=33140 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:52.182  4742  4742 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33140]" dev="sockfs" ino=33140 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:52.184  5560  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-29 05:21:52.184  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:21:52.184  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 05:21:52.189  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:21:52.190  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:21:52.190  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:21:52.193  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 05:21:52.193  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:52.193  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-29 05:21:52.194  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.194  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.194  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 05:21:52.194  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:21:52.198  4522  4742 D BtGatt.GattService: registerClient() - UUID=2bdf34aa-a906-47fc-ae43-99f74ccb80f6
09-29 05:21:52.198  4522  4593 D BtGatt.GattService: onClientRegistered() - UUID=2bdf34aa-a906-47fc-ae43-99f74ccb80f6, clientIf=5
09-29 05:21:52.198  5560  5571 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 05:21:52.200  4522  4595 D BtGatt.AdvertiseManager: message : 0
,09-29 05:21:52.202  4522  4595 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 05:21:52.213  4522  4593 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 05:21:52.219  4522  4593 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 05:21:52.219  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-29 05:21:52.219  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:21:52.221  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:21:52.222  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
09-29 05:21:52.222  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:52.222  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-29 05:21:52.222  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 05:21:52.222  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:21:52.222  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 05:21:52.222  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 05:21:52.225  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:21:52.225  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:21:52.378   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:21:52.725  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-29 05:21:52.726  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-29 05:21:52.726  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 05:21:52.726  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:21:52.726  5560  5606 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 05:21:52.726  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 05:21:52.727  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-29 05:21:52.727  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-29 05:21:52.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-29 05:21:52.731  4522  4595 D BtGatt.AdvertiseManager: message : 1
09-29 05:21:52.732  4522  4595 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 05:21:52.746  4522  4593 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 05:21:52.746  4522  4593 D BtGatt.GattService: Client app is not null!
09-29 05:21:52.747  4522  4544 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 05:21:52.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:21:52.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:21:52.748  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 05:21:52.748  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-29 05:21:52.748  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:52.749  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-29 05:21:52.749  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.749  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.749  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-29 05:21:52.751  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:21:52.756  4522  4742 D BtGatt.GattService: registerClient() - UUID=7db79567-0e61-4e0d-b5ef-a2462ead2fd6
,09-29 05:21:52.756  4522  4593 D BtGatt.GattService: onClientRegistered() - UUID=7db79567-0e61-4e0d-b5ef-a2462ead2fd6, clientIf=5
09-29 05:21:52.757  5560  5570 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 05:21:52.760  4522  4595 D BtGatt.AdvertiseManager: message : 0
,09-29 05:21:52.768  4522  4595 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 05:21:52.782  4522  4593 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 05:21:52.789  4522  4593 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-29 05:21:52.790  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 05:21:52.790  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 05:21:52.790  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:21:52.790  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:21:52.790  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-29 05:21:52.790  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 05:21:52.790  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
09-29 05:21:52.791  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-29 05:21:52.791  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:21:52.791  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 05:21:52.792  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-29 05:21:52.792  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-29 05:21:52.792  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-29 05:21:52.792  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:21:52.792  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:21:52.792  5560  5611 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-29 05:21:52.792  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:21:52.792  5560  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 05:21:52.792  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:21:52.792  5560  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:21:52.792  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:21:52.792  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 05:21:52.792  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-29 05:21:52.792  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:21:52.792  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:21:52.792  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:21:52.793  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:21:52.793  5560  5606 D BluetoothLeScanner: could not find callback wrapper
09-29 05:21:52.794  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-29 05:21:52.794  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 05:21:52.795  4522  4595 D BtGatt.AdvertiseManager: message : 1
09-29 05:21:52.795  4522  4595 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 05:21:52.803  4522  4593 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 05:21:52.803  4522  4593 D BtGatt.GattService: Client app is not null!
09-29 05:21:52.804  4522  4543 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:21:52.804  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:21:52.804  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:21:52.804  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-29 05:21:52.804  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-29 05:21:52.804  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-29 05:21:52.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:21:52.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 05:21:52.806  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:21:52.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:21:52.808  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:21:52.808  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 05:21:52.808  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-29 05:21:52.808  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:52.808  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:52.808  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:21:52.813  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,09-29 05:21:52.813  5560  5606 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-29 05:21:52.814  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-29 05:21:52.815  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 05:21:52.815  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-29 05:21:52.815  5560  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-29 05:21:52.816  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-29 05:21:52.816  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-29 05:21:52.817  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-29 05:21:52.817  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.817  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:52.817  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.817  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 05:21:52.818  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-29 05:21:52.818  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:21:52.819  5560  5606 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 05:21:52.819  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 05:21:52.823  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:21:52.823  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-29 05:21:52.823  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 05:21:52.823  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 05:21:52.823  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 05:21:52.824  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 05:21:52.825  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 05:21:52.825  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-29 05:21:52.826  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:21:52.826  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-29 05:21:52.826  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:21:52.826  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:21:52.826  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-29 05:21:52.826  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:21:52.826  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 05:21:52.826  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-29 05:21:52.832  4742  4742 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32194]" dev="sockfs" ino=32194 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:52.835  4742  4742 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32194]" dev="sockfs" ino=32194 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:52.831  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-29 05:21:52.832  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-29 05:21:52.832  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-29 05:21:52.833  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-29 05:21:52.833  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-29 05:21:52.833  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-29 05:21:52.833  5560  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-29 05:21:52.834  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 05:21:52.834  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-29 05:21:52.834  5560  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-29 05:21:52.834  5560  5615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:52.836  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-29 05:21:52.837  5560  5606 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-29 05:21:52.838  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-29 05:21:52.838  5560  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-29 05:21:52.838  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-29 05:21:52.839  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-29 05:21:52.839  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 05:21:52.839  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 05:21:52.839  5560  5606 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 05:21:52.839  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 05:21:52.839  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 05:21:52.839  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-29 05:21:52.840  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-29 05:21:52.840  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 05:21:52.840  5560  5606 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 05:21:52.840  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-29 05:21:52.840  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-29 05:21:52.840  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:52.840  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 05:21:52.840  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:21:52.841  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:52.841  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 05:21:52.842  4544  4544 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34302]" dev="sockfs" ino=34302 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:52.842  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:21:52.842  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:21:52.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:21:52.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 05:21:52.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:21:52.842  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:21:52.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 05:21:52.843  5560  5616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:52.845  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 05:21:52.845  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 05:21:52.846  5560  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-29 05:21:52.845  4544  4544 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34302]" dev="sockfs" ino=34302 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:21:52.848  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:21:52.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:21:52.849  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:21:52.850  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 05:21:52.850  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:21:52.851  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-29 05:21:52.851  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.851  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:21:52.851  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 05:21:52.851  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:21:52.853  4522  4543 D BtGatt.GattService: registerClient() - UUID=21aaa649-6438-4ea3-8a37-d9d282981cf1
09-29 05:21:52.854  4522  4593 D BtGatt.GattService: onClientRegistered() - UUID=21aaa649-6438-4ea3-8a37-d9d282981cf1, clientIf=5
,09-29 05:21:52.854  5560  5570 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 05:21:52.855  4522  4595 D BtGatt.AdvertiseManager: message : 0
,09-29 05:21:52.856  4522  4595 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 05:21:52.865  4522  4593 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 05:21:52.870  4522  4593 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 05:21:52.870  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 05:21:52.870  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:21:52.871  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 05:21:52.872  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
,09-29 05:21:52.872  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:21:52.872  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 05:21:52.872  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 05:21:52.873  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:21:52.873  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 05:21:52.873  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 05:21:52.875  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-29 05:21:52.875  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:21:53.373  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:21:53.373  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:21:53.373  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-29 05:21:53.373  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-29 05:21:53.374  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:21:53.374  5560  5616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 05:21:53.374  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:21:53.374  5560  5616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-29 05:21:53.374  5560  5616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:21:53.374  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:21:53.375  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 05:21:53.375  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-29 05:21:53.375  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-29 05:21:53.376  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-29 05:21:53.377  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68bedd removed from the list
09-29 05:21:53.377  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:21:53.378  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 05:21:53.378  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:21:53.378  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:21:53.378  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:21:53.379  5560  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
09-29 05:21:53.379   539   539 I ServiceManager: Waiting for service AtCmdFwd...
09-29 05:21:53.379  5560  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
,09-29 05:21:53.380  5560  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-29 05:21:53.380  5560  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-29 05:21:53.381  4522  4740 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-29 05:21:53.381  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:21:53.382  5560  5606 D BluetoothLeScanner: could not find callback wrapper
09-29 05:21:53.382  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-29 05:21:53.382  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 05:21:53.384  4522  4595 D BtGatt.AdvertiseManager: message : 1
09-29 05:21:53.386  4522  4595 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 05:21:53.402  4522  4593 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 05:21:53.402  4522  4593 D BtGatt.GattService: Client app is not null!
09-29 05:21:53.403  4522  4543 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 05:21:53.404  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:21:53.404  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:21:53.404  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-29 05:21:53.404  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 05:21:53.404  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 05:21:53.405  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:21:53.406  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-29 05:21:53.406  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-29 05:21:53.406  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:21:53.407  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aeca52 removed from the list
,09-29 05:21:53.408  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:21:53.408  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:53.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:53.408  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:53.408  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:21:53.410  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
09-29 05:21:53.411  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:21:53.411  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:53.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 05:21:53.415  4543  4543 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33154]" dev="sockfs" ino=33154 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:53.415  4543  4543 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33154]" dev="sockfs" ino=33154 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:21:53.413  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-29 05:21:53.413  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:21:53.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:21:53.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:21:53.413  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:21:53.414  5560  5618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:53.414  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-29 05:21:53.415  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-29 05:21:53.416  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-29 05:21:53.416  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 05:21:53.416  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:53.416  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 05:21:53.417  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-29 05:21:53.417  5560  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-29 05:21:53.424  5560  5606 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-29 05:21:53.426  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:21:53.426  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:21:53.426  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:21:53.426  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:21:53.426  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:53.426  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:21:53.426  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68bedd not in the list
09-29 05:21:53.426  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 05:21:53.426  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:21:53.426  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 05:21:53.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:21:53.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:21:53.427  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:21:53.427  5560  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 05:21:53.427  5560  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 05:21:53.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:53.427  5560  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:21:53.429  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:21:53.429  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aeca52 not in the list
09-29 05:21:53.429  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:53.429  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 05:21:53.429  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:21:53.429  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:21:53.429  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:53.429  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 05:21:53.429  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:21:53.431  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-29 05:21:53.431  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-29 05:21:53.432  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 05:21:53.432  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-29 05:21:53.432  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 05:21:53.432  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-29 05:21:53.432  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 05:21:53.433  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,09-29 05:21:53.434  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-29 05:21:53.435  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-29 05:21:53.436  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-29 05:21:53.436  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-29 05:21:53.436  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,09-29 05:21:53.437  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-29 05:21:53.437  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 05:21:53.437  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-29 05:21:53.437  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 05:21:53.437  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-29 05:21:53.437  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-29 05:21:53.438  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-29 05:21:53.438  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-29 05:21:53.438  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-29 05:21:53.438  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,09-29 05:21:53.439  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-29 05:21:53.439  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-29 05:21:53.439  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-29 05:21:53.439  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-29 05:21:53.440  5560  5606 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-29 05:21:53.440  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 05:21:53.440  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a6c02 added. We now have 3 listener(s)
,09-29 05:21:53.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 05:21:53.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:21:53.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:21:53.442  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:21:53.442  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4c913 added. We now have 3 listener(s)
09-29 05:21:53.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:21:53.443  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:21:53.446  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:21:53.450  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:21:53.451  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:21:53.451  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 05:21:53.453  5560  5606 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 05:21:53.453   928   938 D WifiService: setWifiEnabled: true pid=5560, uid=10077
09-29 05:21:53.453   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 05:21:53.454  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:53.455  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-29 05:21:53.457  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.457  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-29 05:21:53.458  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-29 05:21:53.461   928   938 D WifiService: setWifiEnabled: false pid=5560, uid=10077
,09-29 05:21:53.461   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:21:53.465   928  2891 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 05:21:53.465   928  2891 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 05:21:53.465   928  2891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 05:21:53.465   928  2891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:21:53.473   928  5295 D DhcpClient: Clearing IP address
09-29 05:21:53.474   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:21:53.476   507   921 D CommandListener: Setting iface cfg
,09-29 05:21:53.478   928  5296 D DhcpClient: Receive thread stopped
,09-29 05:21:53.480  3499  5348 V NativeCrypto: Read error: ssl=0x7fa324ba00: I/O error during system call, Connection timed out
,09-29 05:21:53.482  3499  5348 V NativeCrypto: SSL shutdown failed: ssl=0x7fa324ba00: I/O error during system call, Broken pipe
,09-29 05:21:53.485   928  3718 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-29 05:21:53.485   928  5293 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-29 05:21:53.488   928  2893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-29 05:21:53.488   928  2893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-29 05:21:53.491   537   537 E Parcel  : Reading a NULL string not supported here.
09-29 05:21:53.492   928   928 D RttService: SCAN_AVAILABLE : 1
09-29 05:21:53.492   928  3000 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:21:53.496   928  5293 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-29 05:21:53.498   928  2893 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-29 05:21:53.500  3670  3821 W QCNEJ   : |CORE| network lost: 100
09-29 05:21:53.501  3670  3821 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-29 05:21:53.506   928  2891 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-29 05:21:53.514   928  2891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 05:21:53.532   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:21:53.552   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:21:53.553   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-29 05:21:53.553   928  2893 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-29 05:21:53.554   928  2893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 05:21:53.554   507   921 D TetherController: Setting IP forward enable = 0
,09-29 05:21:53.556   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-29 05:21:53.558  5207  5207 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c7862c3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-29 05:21:53.562  4961  4985 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 05:21:53.562  4961  4985 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-29 05:21:53.562  4961  4985 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 05:21:53.563  4961  4985 E SarControlService: no key has been found,reset the power
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:53.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:53.563  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-29 05:21:53.563  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 05:21:53.563  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 05:21:53.563   928  2891 D DhcpClient: doQuit
09-29 05:21:53.564   928  2891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 05:21:53.564  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:21:53.564  4986  4986 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 05:21:53.564   928  5295 D DhcpClient: onQuitting
09-29 05:21:53.566  3368  3368 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 05:21:53.566  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:53.570  3804  3804 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 05:21:53.566  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-29 05:21:53.571  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 05:21:53.571  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 05:21:53.571  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8e5da81 HexData = [00000000ea03000000000000ffffffff]
09-29 05:21:53.571  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:21:53.571  4986  5000 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:53.572  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:53.572  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:21:53.573  4986  4986 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 05:21:53.574  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:53.576  3804  3804 D SystemUpdateService: onCreate
09-29 05:21:53.577  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:21:53.578  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:53.579  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:53.581  3368  3368 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 05:21:53.583  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:53.585  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8e5da81 HexData = [00000000eb03000000000000ffffffff]
09-29 05:21:53.585  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:21:53.585  4986  5000 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-29 05:21:53.587  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:21:53.587  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:53.587  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:53.588  3368  3368 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-29 05:21:53.588  3804  3804 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 05:21:53.589   507   914 W SocketClient: write error (Broken pipe)
09-29 05:21:53.589   507   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-29 05:21:53.589   507   914 W SocketListener: Error sending broadcast (Broken pipe)
09-29 05:21:53.593  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:53.595  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:53.597  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.599  3804  3804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-29 05:21:53.610  3804  5638 I SystemUpdateService: active receiver: enabled
,09-29 05:21:53.613  3804  3804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 05:21:53.613   507   921 E Netd    : netlink response contains error (No such file or directory)
,09-29 05:21:53.614   507   921 D TetherController: Setting IP forward enable = 0
09-29 05:21:53.614  3804  3804 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-29 05:21:53.615   928  2893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 05:21:53.615  3804  5321 I iu.UploadsManager: num queued entries: 0
,09-29 05:21:53.616  3804  5321 I iu.UploadsManager: num updated entries: 0
09-29 05:21:53.617  3804  5321 I iu.SyncManager: NEXT; no task
,09-29 05:21:53.619  3804  5638 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 05:21:53.620  3368  3368 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-29 05:21:53.621  3804  5638 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-29 05:21:53.621  3804  5638 I SystemUpdateService: now status is 0 (complete)
09-29 05:21:53.621  3804  5638 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 05:21:53.621  3804  5638 I SystemUpdateService: file has been verified
09-29 05:21:53.621  3804  5638 I SystemUpdateService: OTA package size = 21989297
,09-29 05:21:53.626   928  3795 I ActivityManager: Start proc 5643:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-29 05:21:53.629  3804  5638 I SystemUpdateService: showing system update notification
,09-29 05:21:53.636  3368  3368 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:21:53.645  3804  3804 D SystemUpdateService: onDestroy
,09-29 05:21:53.666  5643  5643 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-29 05:21:53.670  5643  5643 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 05:21:53.678  5643  5643 D SprintDMHelper: simOperator: 
,09-29 05:21:53.678  5643  5643 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 05:21:53.690   928  3756 I ActivityManager: Start proc 5656:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-29 05:21:53.690   928  3756 I ActivityManager: Killing 4901:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-29 05:21:53.741   928  2891 D wifi    : In wifi stop Hal
,09-29 05:21:53.741  4936  4936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:21:53.741   928  2891 D wifi    : halHandle = 0x7f90a99180, mVM = 0x7fad0cd140, mCls = 0x100a02
,09-29 05:21:53.741   928  3367 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 05:21:53.742   928  3367 D WifiHAL : Got a signal to exit!!!
09-29 05:21:53.742   928  3367 I WifiHAL : Exit wifi_event_loop
,09-29 05:21:53.742   928  2891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 05:21:53.742   928  2891 E WifiHAL : Event processing terminated
09-29 05:21:53.742   928  2891 D wifi    : In wifi cleaned up handler
09-29 05:21:53.743   928  2891 I WifiHAL : Internal cleanup completed
,09-29 05:21:53.743  4023  4151 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:21:53.745  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.746  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.748  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.767   928  3367 D wifi    : set interface wlan0 flags (DOWN)
,09-29 05:21:53.767   928  2891 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 05:21:53.778  4936  5670 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 05:21:53.791   928  3789 I ActivityManager: Start proc 5671:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-29 05:21:53.792   928  3789 I ActivityManager: Killing 5036:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-29 05:21:53.829  5671  5671 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-29 05:21:53.836   928  3754 I ActivityManager: Killing 5367:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-29 05:21:53.930  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:21:53.967  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:53.969   928  3076 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,09-29 05:21:53.969   928  3076 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:21:53.970   928   945 D Tethering: InitialState.processMessage what=4
,09-29 05:21:53.973   507   921 D SoftapController: Softap fwReload - Ok
09-29 05:21:53.973   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 05:21:53.976   507   921 D CommandListener: Setting iface cfg
,09-29 05:21:53.976   507   921 D CommandListener: Trying to bring down wlan0
,09-29 05:21:53.977   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:21:53.980   928  2891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 05:21:54.380   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 05:21:54.472   928  3789 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,09-29 05:21:54.473   928  3789 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:21:54.575   928  2891 D wifi    : set interface wlan0 flags (UP)
09-29 05:21:54.576   928  2891 I WifiHAL : Initializing wifi
,09-29 05:21:54.576   928  2891 I WifiHAL : Creating socket
,09-29 05:21:54.581   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-29 05:21:54.588   928  2891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 05:21:54.589   928  2891 D wifi    : Did set static halHandle = 0x7f90a99180
09-29 05:21:54.589   928  2891 D wifi    : halHandle = 0x7f90a99180, mVM = 0x7fad0cd140, mCls = 0x101996
09-29 05:21:54.589   928  2891 D wifi    : array field set
09-29 05:21:54.589   928  2891 I WifiNative-HAL: interface[0] = wlan0
,09-29 05:21:54.591   928  5687 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547887878528
09-29 05:21:54.591   928  5687 D wifi    : waitForHalEvents called, vm = 0x7fad0cd140, obj = 0x101996, env = 0x7f9263ab40
,09-29 05:21:54.675  5688  5688 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 05:21:54.693   928  2891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 05:21:54.697  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-29 05:21:54.705  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:54.708  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:54.709  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:54.719  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:21:54.719  5688  5688 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 05:21:54.736   928  2891 D WifiConfigStore: Loading config and enabling all networks 
,09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:54.739  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:54.742  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:54.744   928  2891 D WifiConfigStore: loaded 0 passpoint configs
,09-29 05:21:54.745   928  2891 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-29 05:21:54.746   928  2891 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:54.746  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:54.747   928  2891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-29 05:21:54.748   928  2891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:21:54.748   928  2891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 05:21:54.748   928  2891 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 05:21:54.748   928  2891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-29 05:21:54.749  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:54.752   928  2891 D WifiNative-HAL: Setting external_sim to 1
,09-29 05:21:54.752   928  2891 D wifi    : setting dfs flag to true, 0x7f94b66bc0
,09-29 05:21:54.753   928  2891 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 05:21:54.753   928  2891 D wifi    : setting scan oui 0x7f94b66bc0
09-29 05:21:54.753   928  2891 D WifiHAL : Sending mac address OUI
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:54.754  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:54.755  4936  4936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:21:54.756  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:54.758   928  2891 E native  : do suspend false
,09-29 05:21:54.766   928  2891 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 05:21:54.766   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 05:21:54.766   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 05:21:54.766   928  3000 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:21:54.767   507   921 D CommandListener: Setting iface cfg
,09-29 05:21:54.770   928  2890 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-29 05:21:54.770   928  2890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 05:21:54.780   928  2890 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 05:21:54.781   928  2890 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 05:21:54.786   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=243813 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-29 05:21:54.977  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:54.984  4522  4588 D BluetoothAdapterState: Current state: ON, message: 23
,09-29 05:21:54.984  4522  4588 D BluetoothAdapterProperties: Setting state to 13
09-29 05:21:54.984  4522  4588 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 05:21:54.985  4522  4588 D BluetoothAdapterProperties: onBluetoothDisable()
,09-29 05:21:54.985  4522  4588 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:54.987  4522  4593 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:21:54.987  4522  4588 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-29 05:21:54.990  4522  4522 D HeadsetService: Received stop request...Stopping profile...
,09-29 05:21:54.990  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:54.991  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:54.991   928   928 D BluetoothHeadset: Proxy object disconnected
,09-29 05:21:54.992   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:21:54.992  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:54.992  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:54.992  3703  3946 D BluetoothHeadset: Proxy object disconnected
09-29 05:21:54.992  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:54.993  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:54.993  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:54.993   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 05:21:54.993  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:54.993  4522  4522 D A2dpService: Received stop request...Stopping profile...
09-29 05:21:54.993  3034  3046 D BluetoothHeadset: Proxy object disconnected
09-29 05:21:54.993  4522  4745 D A2dpStateMachine: Exit Disconnected: -1
09-29 05:21:54.994  3034  3034 D HeadsetProfile: Bluetooth service disconnected
,09-29 05:21:54.999   928   928 D BluetoothA2dp: Proxy object disconnected
09-29 05:21:55.000  3034  3034 D BluetoothA2dp: Proxy object disconnected
,09-29 05:21:55.000  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:55.000  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:55.000  4522  4522 D HidService: Received stop request...Stopping profile...
09-29 05:21:55.000  4522  4522 D HidService: Stopping Bluetooth HidService
09-29 05:21:55.001  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:55.001  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:55.001  3034  3034 D BluetoothInputDevice: Proxy object disconnected
09-29 05:21:55.001  3034  3034 D HidProfile: Bluetooth service disconnected
,09-29 05:21:55.003  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:21:55.003  4522  4522 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 05:21:55.003  4522  4522 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:55.003  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:55.003  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.003  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.003  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.004  4522  4522 D HealthService: Received stop request...Stopping profile...
09-29 05:21:55.004  4522  4593 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 05:21:55.004  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:55.004  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:55.004  4522  4593 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-29 05:21:55.005  4522  4522 D PanService: Received stop request...Stopping profile...
,09-29 05:21:55.006  3034  3034 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:21:55.006  3034  3034 D PanProfile: Bluetooth service disconnected
09-29 05:21:55.007  4522  4522 D BluetoothMapService: Received stop request...Stopping profile...
09-29 05:21:55.007  4522  4522 D BluetoothMapService: stop()
09-29 05:21:55.007  4522  4522 D BluetoothMapAppObserver: deinitObservers()
09-29 05:21:55.008  4522  4522 D BluetoothMapAppObserver: removeReceiver()
09-29 05:21:55.008  3034  3034 D BluetoothMap: Proxy object disconnected
09-29 05:21:55.008  3034  3034 D MapProfile: Bluetooth service disconnected
09-29 05:21:55.009  4522  4522 D SapService: Received stop request...Stopping profile...
09-29 05:21:55.009  4522  4522 V SapService: stop()
,09-29 05:21:55.010  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:55.010  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.010  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.010  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:21:55.011  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.011  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:55.011  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.011  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.011  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.011  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.011  4522  4593 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 05:21:55.011  4522  4728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-29 05:21:55.012  4522  4728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:21:55.012  4522  4728 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:21:55.012  4522  4728 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:21:55.012  4522  4522 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 05:21:55.012  4522  4522 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 05:21:55.012  4522  4593 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 05:21:55.012  4522  4522 V BluetoothAdapterState: isTurningOff()=true
,09-29 05:21:55.012  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.013  4522  4522 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 05:21:55.013  4522  4593 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 05:21:55.013  4522  4522 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.013  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.014  4522  4522 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-29 05:21:55.014  4522  4522 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 05:21:55.015  4522  4522 D BluetoothMapService: MAP Service closeService in
09-29 05:21:55.015  4522  4522 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 05:21:55.015  4522  4522 D ObexServerSockets0: shutdown(block = true)
09-29 05:21:55.015  4522  4522 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:21:55.015  4522  4761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-29 05:21:55.015  4522  4522 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:21:55.015  4522  4762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 05:21:55.015  4522  4740 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 05:21:55.016  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:55.016  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.016  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 05:21:55.016  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.016  4522  4522 D BluetoothMapService: cleanup()
09-29 05:21:55.016  4522  4522 D BluetoothMapService: MAP Service closeService in
09-29 05:21:55.017  4522  4522 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:55.017  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.017  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.017  4522  4522 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.017  4522  4588 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 05:21:55.017  4522  4588 D BluetoothAdapterProperties: Setting state to 15
09-29 05:21:55.017  4522  4588 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 05:21:55.017  4522  4588 I BluetoothAdapterState: Entering BleOnState
,09-29 05:21:55.037  4522  4522 I BtOppRfcommListener: stopping Accept Thread
09-29 05:21:55.038  4522  5221 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 05:21:55.038  4522  5221 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-29 05:21:55.039  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:55.041  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:55.042  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:55.047   928   941 I ActivityManager: Start proc 5692:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-29 05:21:55.049  3703  3729 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 05:21:55.050  3034  3048 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:21:55.051  3034  3898 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:55.051  3034  3945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:21:55.052  3034  3046 D BluetoothPan: onBluetoothStateChange on: false
09-29 05:21:55.052   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:21:55.052   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:55.053   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:55.053  3034  3048 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:21:55.053   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:55.053  3034  3898 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 05:21:55.055  4522  4588 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 05:21:55.055  4522  4588 D BluetoothAdapterProperties: Setting state to 16
09-29 05:21:55.055  4522  4588 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 05:21:55.056  4522  4588 D BluetoothAdapterProperties: onBleDisable
09-29 05:21:55.056  4522  4588 I BluetoothAdapterState: Entering PendingCommandState
09-29 05:21:55.056  4522  4589 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 05:21:55.057  4522  4728 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 05:21:55.057  4522  4728 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:55.058  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:55.058  4522  4593 D BluetoothAdapterProperties: Scan Mode:20
,09-29 05:21:55.060  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:55.061  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:55.064  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:55.068  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:55.070  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:55.092  5692  5692 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-29 05:21:55.103  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 05:21:55.107   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@334a94a:true
,09-29 05:21:55.109  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:21:55.122   928  3795 I ActivityManager: Start proc 5704:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-29 05:21:55.134  5692  5692 D LocalBluetoothProfileManager: Adding local MAP profile
,09-29 05:21:55.137  5692  5692 D BluetoothMap: Create BluetoothMap proxy object
,09-29 05:21:55.150  5692  5692 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-29 05:21:55.160  5704  5704 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-29 05:21:55.163  5692  5692 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:21:55.172   928  3796 I ActivityManager: Killing 5207:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-29 05:21:55.266  4522  4593 I bt_hci  : shut_down
,09-29 05:21:55.270  4522  4598 D bt_hwcfg: hw_epilog_process
,09-29 05:21:55.270  4522  4598 I bt_vendor: low_power_mode_cb
,09-29 05:21:55.272  4522  4598 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-29 05:21:55.272  4522  4598 I bt_vendor: epilog_cb
09-29 05:21:55.273  4522  4598 I bt_hci  : epilog_finished_callback
,09-29 05:21:55.275  4522  4593 I bt_hci_h4: hal_close
,09-29 05:21:55.275  4522  4593 I bt_userial_vendor: device fd = 54 close
,09-29 05:21:55.373  5704  5704 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 05:21:55.373  5704  5704 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.373  5704  5704 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.373  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.379  5704  5704 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.379  5704  5704 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:583)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.379  5704  5704 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.379  5704  5704 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.379  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.380  5704  5704 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 05:21:55.380  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 05:21:55.384  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:21:55.390  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:21:55.390  4522  4589 D bt_stack_manager: event_shut_down_stack finished.
09-29 05:21:55.390  4522  4588 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-29 05:21:55.393  4522  4588 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 05:21:55.393  4522  4522 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:21:55.394  5692  5692 D DockEventReceiver: finishStartingService: stopping service
09-29 05:21:55.396  4522  4522 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 05:21:55.396  4522  4522 D BtGatt.GattService: stop()
09-29 05:21:55.396  4522  4522 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 05:21:55.397  4522  4522 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:55.397  4522  4522 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.397  4522  4522 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:55.397  4522  4522 V BluetoothAdapterState: isBleTurningOff()=true
09-29 05:21:55.398  4522  4588 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 05:21:55.398  4522  4588 D BluetoothAdapterProperties: Setting state to 10
09-29 05:21:55.398  4522  4588 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 05:21:55.398  4522  4588 I BluetoothAdapterState: Entering OffState
09-29 05:21:55.399   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-29 05:21:55.400   928  3795 I ActivityManager: Killing 4603:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-29 05:21:55.435  4522  4522 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 05:21:55.435  4522  4522 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 05:21:55.435  4522  4522 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 05:21:55.436  4522  4589 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-29 05:21:55.445  4522  4522 I art     : System.exit called, status: 0
09-29 05:21:55.445  4522  4522 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 05:21:55.483  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:55.484   928  3506 I ActivityManager: Process com.android.bluetooth (pid 4522) has died
,09-29 05:21:55.496   928   945 I ActivityManager: Start proc 5736:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 05:21:55.556  5736  5736 D AdapterServiceConfig: Adding HeadsetService
,09-29 05:21:55.556  5736  5736 D AdapterServiceConfig: Adding A2dpService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding HidService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding HealthService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding PanService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding GattService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding BluetoothMapService
09-29 05:21:55.557  5736  5736 D AdapterServiceConfig: Adding SapService
,09-29 05:21:55.565   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95ef823:true
,09-29 05:21:55.565  5736  5736 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 05:21:55.567  5736  5736 I bt_bluedroid: init
,09-29 05:21:55.567  5736  5748 I BluetoothAdapterState: Entering OffState
,09-29 05:21:55.569  5736  5749 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 05:21:55.569  5736  5749 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-29 05:21:55.569  5736  5749 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 05:21:55.569  5736  5749 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 05:21:55.570  5736  5736 I bt_bluedroid: get_profile_interface socket
,09-29 05:21:55.571  5736  5736 I bt_bluedroid: get_profile_interface sdp
09-29 05:21:55.571  5736  5752 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:21:55.572  5736  5752 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:21:55.574  5736  5747 I bt_bluedroid: config_hci_snoop_log
09-29 05:21:55.574   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-29 05:21:55.578  5736  5748 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 05:21:55.578  5736  5748 D BluetoothAdapterProperties: Setting state to 14
09-29 05:21:55.578  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 05:21:55.579  5736  5748 D BluetoothBondStateMachine: make
,09-29 05:21:55.581  5736  5753 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 05:21:55.583  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:55.584  5736  5736 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 05:21:55.586  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:55.587  5736  5736 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 05:21:55.587  5736  5736 D BtGatt.GattService: Received start request. Starting profile...
09-29 05:21:55.587  5736  5736 D BtGatt.GattService: start()
09-29 05:21:55.587  5736  5736 I bt_bluedroid: get_profile_interface gatt
,09-29 05:21:55.588  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
09-29 05:21:55.588  5736  5736 D BtGatt.AdvertiseManager: advertise manager created
,09-29 05:21:55.592  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:21:55.593  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:55.593  5736  5736 V BluetoothAdapterState: isBleTurningOn()=true
09-29 05:21:55.593  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:55.593  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 05:21:55.595  5736  5748 I bt_bluedroid: bt_bluedroid
,09-29 05:21:55.595  5736  5749 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-29 05:21:55.595  5736  5749 I bt_hci  : start_up
,09-29 05:21:55.600  5736  5749 I bt_vendor: alloc value 0xf3d5d871
,09-29 05:21:55.600  5736  5749 I bt_vendor: init
09-29 05:21:55.600  5736  5749 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 05:21:55.600  5736  5749 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 05:21:55.628  5704  5723 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-29 05:21:55.639   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e55438:true
,09-29 05:21:55.710  5736  5749 D bt_hci  : start_up starting async portion
,09-29 05:21:55.710  5736  5756 I bt_hci  : event_finish_startup
09-29 05:21:55.710  5736  5756 I bt_hci_h4: hal_open
09-29 05:21:55.710  5736  5756 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 05:21:55.709  5759  5759 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-29 05:21:55.711  5736  5756 I bt_userial_vendor: device fd = 54 open
,09-29 05:21:55.723  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:21:55.725  5736  5756 D bt_hwcfg: Chipset BCM4358A3
,09-29 05:21:55.725  5736  5756 D bt_hwcfg: Target name = [BCM4358A3]
09-29 05:21:55.725  5736  5756 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 05:21:55.994  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-29 05:21:56.123  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 05:21:56.123  5736  5756 D bt_hwcfg: Settlement delay -- 100 ms
09-29 05:21:56.124  5736  5756 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 05:21:56.248  5736  5756 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-29 05:21:56.249  5736  5756 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-29 05:21:56.251  5736  5756 I bt_hwcfg: vendor lib fwcfg completed
09-29 05:21:56.251  5736  5756 I bt_vendor: firmware callback
09-29 05:21:56.251  5736  5756 I bt_hci  : firmware_config_callback
,09-29 05:21:56.259  5736  5761 I bt_btu  : btu_task pending for preload complete event
,09-29 05:21:56.259  5736  5761 I bt_btu_task: Bluetooth chip preload is complete
09-29 05:21:56.259  5736  5761 I bt_btu  : btu_task received preload complete event
,09-29 05:21:56.268  5736  5761 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 05:21:56.268  5736  5761 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 05:21:56.268  5736  5761 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 05:21:56.269  5736  5761 I         : BTE_InitTraceLevels -- TRC_GAP
,09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_SMP
,09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 05:21:56.270  5736  5761 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 05:21:56.353  5736  5761 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cdb549
09-29 05:21:56.353  5736  5761 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cdb549 
,09-29 05:21:56.377  5736  5752 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 05:21:56.378  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 05:21:56.379  5736  5752 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:21:56.381  5736  5752 D BluetoothAdapterProperties: Name is: Nexus 6P
09-29 05:21:56.382  5736  5752 D BluetoothAdapterProperties: Scan Mode:20
,09-29 05:21:56.383  5736  5752 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-29 05:21:56.383  5736  5752 D bt_hci  : do_postload posting postload work item
09-29 05:21:56.383  5736  5756 I bt_hci  : event_postload
,09-29 05:21:56.383  5736  5756 I bt_vendor: sco_config_cb
09-29 05:21:56.383  5736  5756 I bt_hci  : sco_config_callback postload finished.
09-29 05:21:56.386  5736  5752 D bt_bte_conf: Device ID record 1 : primary
09-29 05:21:56.387  5736  5752 D bt_bte_conf:   vendorId            = 000f
09-29 05:21:56.387  5736  5752 D bt_bte_conf:   vendorIdSource      = 0001
,09-29 05:21:56.387  5736  5752 D bt_bte_conf:   product             = 1200
09-29 05:21:56.387  5736  5752 D bt_bte_conf:   version             = 1436
09-29 05:21:56.387  5736  5752 D bt_bte_conf:   clientExecutableURL = 
,09-29 05:21:56.387  5736  5752 D bt_bte_conf:   serviceDescription  = 
09-29 05:21:56.387  5736  5752 D bt_bte_conf:   documentationURL    = 
09-29 05:21:56.387  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.387  5736  5752 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 05:21:56.387  5736  5749 D bt_stack_manager: event_start_up_stack finished
09-29 05:21:56.391  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.393  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 05:21:56.393  5736  5748 D BluetoothAdapterProperties: Setting state to 15
,09-29 05:21:56.393  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 05:21:56.394  5736  5748 I BluetoothAdapterState: Entering BleOnState
,09-29 05:21:56.394  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.397  5736  5748 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-29 05:21:56.397  5736  5748 D BluetoothAdapterProperties: Setting state to 11
09-29 05:21:56.397  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 05:21:56.402  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.402  5736  5736 D HeadsetService: Received start request. Starting profile...
09-29 05:21:56.405  5736  5736 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 05:21:56.405  5736  5736 D HeadsetStateMachine: make
09-29 05:21:56.405  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.408  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.409  5736  5756 I bt_vendor: low_power_mode_cb
,09-29 05:21:56.410  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.416  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:56.417  5736  5736 D HeadsetStateMachine: max_hf_connections = 1
,09-29 05:21:56.417  5736  5736 I bt_bluedroid: get_profile_interface handsfree
09-29 05:21:56.418  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 05:21:56.418  5736  5752 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-29 05:21:56.420  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.421  5736  5736 D A2dpService: Received start request. Starting profile...
,09-29 05:21:56.421  5736  5736 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 05:21:56.422  5736  5736 I bt_bluedroid: get_profile_interface avrcp
,09-29 05:21:56.427  5736  5736 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 05:21:56.427  5736  5736 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 05:21:56.427  5736  5736 D A2dpStateMachine: make
09-29 05:21:56.428  5736  5736 I bt_bluedroid: get_profile_interface a2dp
,09-29 05:21:56.429  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-29 05:21:56.429  5736  5769 D A2dpStateMachine: Enter Disconnected: -2
,09-29 05:21:56.430  5736  5736 I BluetoothHidServiceJni: classInitNative: succeeds
09-29 05:21:56.431  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.432  5692  5692 D BluetoothInputDevice: Proxy object connected
09-29 05:21:56.432  5692  5692 D HidProfile: Bluetooth service connected
,09-29 05:21:56.433  5736  5736 D HidService: Received start request. Starting profile...
09-29 05:21:56.433  5736  5736 I bt_bluedroid: get_profile_interface hidhost
09-29 05:21:56.433  5736  5736 D HidService: setHidService(): set to: null
09-29 05:21:56.433  5736  5752 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cbc56d
09-29 05:21:56.433  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 05:21:56.434  5736  5736 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 05:21:56.435  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
09-29 05:21:56.436  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:21:56.436  5736  5736 D HealthService: Received start request. Starting profile...
,09-29 05:21:56.437  5736  5736 I bt_bluedroid: get_profile_interface health
,09-29 05:21:56.438  5736  5736 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 05:21:56.439  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.440  5692  5692 D BluetoothPan: BluetoothPAN Proxy object connected
,09-29 05:21:56.440  5736  5736 D PanService: Received start request. Starting profile...
09-29 05:21:56.440  5736  5736 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 05:21:56.440  5736  5736 I bt_bluedroid: get_profile_interface pan
09-29 05:21:56.440  5692  5692 D PanProfile: Bluetooth service connected
09-29 05:21:56.440  5736  5752 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 05:21:56.442  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.443  5736  5736 D BluetoothMapService: Received start request. Starting profile...
,09-29 05:21:56.443  5692  5692 D BluetoothMap: Proxy object connected
09-29 05:21:56.443  5736  5736 D BluetoothMapService: start()
09-29 05:21:56.444  5692  5692 D MapProfile: Bluetooth service connected
09-29 05:21:56.444  5692  5692 D BluetoothMap: getConnectedDevices()
09-29 05:21:56.445  5692  5692 D BluetoothMap: Bluetooth is Not enabled
,09-29 05:21:56.446  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 05:21:56.447  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 05:21:56.447  5736  5736 D BluetoothMapAppObserver: createReceiver()
,09-29 05:21:56.449  5736  5736 D BluetoothMapAppObserver: initObservers()
09-29 05:21:56.449  5736  5736 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 05:21:56.456  5736  5736 V SapService: SapBinder()
,09-29 05:21:56.456  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:56.456  5736  5736 D SapService: Received start request. Starting profile...
09-29 05:21:56.456  5736  5736 V SapService: start()
,09-29 05:21:56.458  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:21:56.458  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.458  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.459  5736  5767 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.459  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isTurningOn()=true
,09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.460  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.462  5736  5736 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:56.462  5736  5736 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:56.462  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.462  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.462  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 05:21:56.462  5736  5748 D BluetoothAdapterProperties: ScanMode =  20
09-29 05:21:56.462  5736  5748 D BluetoothAdapterProperties: State =  11
,09-29 05:21:56.463  5736  5748 D BluetoothAdapterProperties: Setting state to 12
09-29 05:21:56.463  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 05:21:56.464  3703  3727 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 05:21:56.464  5736  5748 I BluetoothAdapterState: Entering OnState
09-29 05:21:56.464  5736  5752 D BluetoothAdapterProperties: Scan Mode:21
09-29 05:21:56.464  5736  5752 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-29 05:21:56.465  5692  5702 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-29 05:21:56.465  5692  5703 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:21:56.466  5692  5702 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:21:56.466  3034  3898 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:21:56.467  5560  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-29 05:21:56.468  3034  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:56.468  3034  3034 D BluetoothMap: Proxy object connected
09-29 05:21:56.468  3034  3034 D MapProfile: Bluetooth service connected
09-29 05:21:56.468  3034  3034 D BluetoothMap: getConnectedDevices()
09-29 05:21:56.468  3034  3048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:21:56.470  3034  3898 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:21:56.472  3034  3034 D BluetoothA2dp: Proxy object connected
09-29 05:21:56.472   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:21:56.472   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:56.472   928   928 D BluetoothA2dp: Proxy object connected
09-29 05:21:56.473  5560  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-29 05:21:56.473  3034  3034 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:21:56.473  3034  3034 D PanProfile: Bluetooth service connected
09-29 05:21:56.473   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:56.473  3034  3046 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:21:56.474  5736  5736 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 05:21:56.475  5736  5736 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 05:21:56.476  3034  3034 D BluetoothInputDevice: Proxy object connected
09-29 05:21:56.476  3034  3034 D HidProfile: Bluetooth service connected
,09-29 05:21:56.477   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:56.477  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:56.477  3034  3898 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:56.477  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:56.479  5692  5703 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:21:56.480  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:56.481  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:21:56.483   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:56.484  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:56.486  5736  5736 D ObexServerSockets: Succeed to create listening sockets 
,09-29 05:21:56.486  5736  5736 D ObexServerSockets0: startAccept()
,09-29 05:21:56.486  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:56.486  5736  5736 D ObexServerSockets0: prepareForNewConnect()
09-29 05:21:56.487  5692  5692 D LocalBluetoothProfileManager: Adding local A2DP profile
09-29 05:21:56.488  5736  5736 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 05:21:56.488  5736  5736 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 05:21:56.489  5736  5736 D BluetoothMapService: onReceive
09-29 05:21:56.489  5736  5736 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 05:21:56.489  5736  5736 D BluetoothMapService: STATE_ON
09-29 05:21:56.489  5736  5777 D ObexServerSockets0: Accepting socket connection...
09-29 05:21:56.489  5736  5776 D ObexServerSockets0: Accepting socket connection...
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:56.490  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:56.491  5736  5778 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:56.492  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:56.492  5692  5692 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-29 05:21:56.492  5736  5778 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 05:21:56.492  5736  5778 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 05:21:56.495  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.496  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.496  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.498  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.498  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:21:56.498  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:56.499  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-29 05:21:56.500  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-29 05:21:56.501  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.502  5736  5748 D BluetoothAdapterState: Current state: ON, message: 23
09-29 05:21:56.503  5736  5748 D BluetoothAdapterProperties: Setting state to 13
09-29 05:21:56.503  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 05:21:56.503  5736  5748 D BluetoothAdapterProperties: onBluetoothDisable()
,09-29 05:21:56.503  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:56.505  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 05:21:56.505  5736  5752 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:21:56.506  5736  5736 D BluetoothMapService: onReceive
09-29 05:21:56.506  5736  5736 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 05:21:56.506  5736  5736 D BluetoothMapService: STATE_TURNING_OFF
09-29 05:21:56.506  5736  5736 D BluetoothMapService: MAP Service closeService in
09-29 05:21:56.507  5736  5736 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 05:21:56.507  5736  5736 D ObexServerSockets0: shutdown(block = true)
09-29 05:21:56.507  5736  5736 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-29 05:21:56.507  5736  5736 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 05:21:56.507  5736  5777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 05:21:56.507  5736  5776 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-29 05:21:56.507  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:56.507  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:56.508  5736  5763 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 05:21:56.508  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 05:21:56.508  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:56.508  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:56.510  5692  5692 D BluetoothA2dp: Proxy object connected
09-29 05:21:56.511  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:56.512  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:56.512  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 05:21:56.512  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:56.513  5736  5736 D HeadsetService: Received stop request...Stopping profile...
09-29 05:21:56.514  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.515  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.517  5736  5736 D A2dpService: Received stop request...Stopping profile...
,09-29 05:21:56.517  5692  5692 D DockEventReceiver: finishStartingService: stopping service
09-29 05:21:56.517  5736  5769 D A2dpStateMachine: Exit Disconnected: -1
09-29 05:21:56.518   928   928 D BluetoothA2dp: Proxy object disconnected
,09-29 05:21:56.520  5692  5692 D BluetoothA2dp: Proxy object disconnected
,09-29 05:21:56.521  5736  5736 D HidService: Received stop request...Stopping profile...
,09-29 05:21:56.522  5736  5736 D HidService: Stopping Bluetooth HidService
09-29 05:21:56.522  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:21:56.523  5692  5692 D BluetoothInputDevice: Proxy object disconnected
09-29 05:21:56.523  5692  5692 D HidProfile: Bluetooth service disconnected
,09-29 05:21:56.524  5736  5736 D HealthService: Received stop request...Stopping profile...
,09-29 05:21:56.526  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.526  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.526  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.526  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:21:56.527  5736  5736 D PanService: Received stop request...Stopping profile...
,09-29 05:21:56.527  3034  3034 D BluetoothA2dp: Proxy object disconnected
09-29 05:21:56.527  3034  3034 D BluetoothInputDevice: Proxy object disconnected
09-29 05:21:56.527  3034  3034 D HidProfile: Bluetooth service disconnected
09-29 05:21:56.527  3034  3034 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:21:56.527  3034  3034 D PanProfile: Bluetooth service disconnected
09-29 05:21:56.529  5736  5736 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 05:21:56.529  5736  5736 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 05:21:56.529  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.529  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.529  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.529  5736  5736 D BluetoothMapService: Received stop request...Stopping profile...
,09-29 05:21:56.529  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 05:21:56.529  5736  5736 D BluetoothMapService: stop()
09-29 05:21:56.529  5736  5752 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-29 05:21:56.530  5736  5736 D BluetoothMapAppObserver: deinitObservers()
09-29 05:21:56.530  5736  5736 D BluetoothMapAppObserver: removeReceiver()
09-29 05:21:56.531  3034  3034 D BluetoothMap: Proxy object disconnected
09-29 05:21:56.531  5736  5736 D SapService: Received stop request...Stopping profile...
09-29 05:21:56.531  3034  3034 D MapProfile: Bluetooth service disconnected
09-29 05:21:56.531  5736  5736 V SapService: stop()
09-29 05:21:56.532  5692  5692 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 05:21:56.532  5692  5692 D PanProfile: Bluetooth service disconnected
09-29 05:21:56.532  5692  5692 D BluetoothMap: Proxy object disconnected
09-29 05:21:56.532  5692  5692 D MapProfile: Bluetooth service disconnected
09-29 05:21:56.532  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.532  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.532  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.532  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.533  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.533  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.534  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 05:21:56.534  5736  5761 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:21:56.534  5736  5761 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 05:21:56.534  5736  5761 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 05:21:56.534  5736  5761 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-29 05:21:56.542  3034  3034 D BluetoothPbap: Proxy object connected
,09-29 05:21:56.542  5692  5692 D BluetoothPbap: Proxy object connected
09-29 05:21:56.542  3034  3034 D PbapServerProfile: Bluetooth service connected
09-29 05:21:56.542  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.543  5692  5692 D PbapServerProfile: Bluetooth service connected
09-29 05:21:56.543  5736  5736 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 05:21:56.543  5736  5736 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 05:21:56.543  5736  5752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.543  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:21:56.548  5736  5736 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-29 05:21:56.548  5736  5752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 05:21:56.548  5736  5736 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 05:21:56.548  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.549  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.549  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.549  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 05:21:56.549  5736  5736 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-29 05:21:56.549  5736  5736 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 05:21:56.550  5736  5736 D BluetoothMapService: MAP Service closeService in
09-29 05:21:56.550  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.550  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.550  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.550  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.550  5736  5736 D BluetoothMapService: cleanup()
09-29 05:21:56.550  5736  5736 D BluetoothMapService: MAP Service closeService in
09-29 05:21:56.550  5736  5736 V BluetoothAdapterState: isTurningOff()=true
09-29 05:21:56.551  5736  5736 V BluetoothAdapterState: isTurningOn()=false
,09-29 05:21:56.551  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.551  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:56.551  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 05:21:56.551  5736  5748 D BluetoothAdapterProperties: Setting state to 15
09-29 05:21:56.551  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 05:21:56.551  5736  5748 I BluetoothAdapterState: Entering BleOnState
09-29 05:21:56.552  3703  3946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.552  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 05:21:56.552  5692  5702 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.552  5692  5703 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:21:56.553  5692  5702 D BluetoothPan: onBluetoothStateChange on: false
,09-29 05:21:56.553  5692  5703 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:21:56.553  3034  3048 D BluetoothMap: onBluetoothStateChange: up=false
09-29 05:21:56.554  5692  5702 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:21:56.554  3034  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.555  3034  3046 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:21:56.555  3034  3898 D BluetoothPan: onBluetoothStateChange on: false
09-29 05:21:56.555   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 05:21:56.555   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.555   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.556  3034  3046 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 05:21:56.556   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 05:21:56.556  3034  3898 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 05:21:56.558  5692  5703 D BluetoothPbap: onBluetoothStateChange: up=false
,09-29 05:21:56.558  5736  5748 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 05:21:56.558  5736  5748 D BluetoothAdapterProperties: Setting state to 16
09-29 05:21:56.558  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 05:21:56.559  5736  5748 D BluetoothAdapterProperties: onBleDisable
09-29 05:21:56.560  5736  5749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 05:21:56.561  5736  5752 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:21:56.559  5736  5748 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:56.563  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.563  5736  5761 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 05:21:56.563  5736  5761 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 05:21:56.565  5692  5692 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:21:56.566  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.568  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:56.569  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:21:56.571  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:56.575  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 05:21:56.580  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:21:56.580  5692  5692 D DockEventReceiver: finishStartingService: stopping service
,09-29 05:21:56.764  5736  5752 I bt_hci  : shut_down
09-29 05:21:56.764  5736  5756 D bt_hwcfg: hw_epilog_process
09-29 05:21:56.765  5736  5756 I bt_vendor: low_power_mode_cb
09-29 05:21:56.767  5736  5756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-29 05:21:56.768  5736  5756 I bt_vendor: epilog_cb
09-29 05:21:56.768  5736  5756 I bt_hci  : epilog_finished_callback
09-29 05:21:56.768  5736  5752 I bt_hci_h4: hal_close
09-29 05:21:56.769  5736  5752 I bt_userial_vendor: device fd = 54 close
,09-29 05:21:56.880  5736  5749 D bt_stack_manager: event_shut_down_stack finished.
09-29 05:21:56.881  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 05:21:56.883  5736  5748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-29 05:21:56.883  5736  5736 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:21:56.884  5736  5736 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 05:21:56.884  5736  5736 D BtGatt.GattService: stop()
09-29 05:21:56.885  5736  5736 D BtGatt.AdvertiseManager: advertise clients cleared
,09-29 05:21:56.887  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,09-29 05:21:56.887  5736  5736 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:56.887  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:56.887  5736  5736 V BluetoothAdapterState: isBleTurningOff()=true
,09-29 05:21:56.888  5736  5748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 05:21:56.888  5736  5748 D BluetoothAdapterProperties: Setting state to 10
09-29 05:21:56.888  5736  5748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 05:21:56.889  5736  5748 I BluetoothAdapterState: Entering OffState
,09-29 05:21:56.890   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-29 05:21:56.901  5736  5736 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-29 05:21:56.901  5736  5736 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 05:21:56.901  5736  5749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-29 05:21:56.902  5736  5736 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-29 05:21:56.905  5736  5736 I art     : System.exit called, status: 0
,09-29 05:21:56.905  5736  5736 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 05:21:56.928   928  3506 I ActivityManager: Process com.android.bluetooth (pid 5736) has died
,09-29 05:21:57.003  5560  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:57.003  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:57.003  5560  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 05:21:57.003  5560  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:57.007  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:57.019   928   945 I ActivityManager: Start proc 5789:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding HeadsetService
09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding A2dpService
09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding HidService
09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding HealthService
09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding PanService
09-29 05:21:57.076  5789  5789 D AdapterServiceConfig: Adding GattService
09-29 05:21:57.077  5789  5789 D AdapterServiceConfig: Adding BluetoothMapService
09-29 05:21:57.077  5789  5789 D AdapterServiceConfig: Adding SapService
,09-29 05:21:57.086   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d56c1d1:true
,09-29 05:21:57.087  5789  5789 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 05:21:57.089  5789  5789 I bt_bluedroid: init
09-29 05:21:57.090  5789  5801 I BluetoothAdapterState: Entering OffState
,09-29 05:21:57.092  5789  5802 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-29 05:21:57.092  5789  5802 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 05:21:57.092  5789  5802 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 05:21:57.092  5789  5802 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 05:21:57.092  5789  5789 I bt_bluedroid: get_profile_interface socket
,09-29 05:21:57.094  5789  5805 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:21:57.094  5789  5789 I bt_bluedroid: get_profile_interface sdp
09-29 05:21:57.095  5789  5805 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:21:57.099  5789  5800 I bt_bluedroid: config_hci_snoop_log
,09-29 05:21:57.100   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 05:21:57.103  5789  5801 D BluetoothAdapterState: Current state: OFF, message: 0
09-29 05:21:57.103  5789  5801 D BluetoothAdapterProperties: Setting state to 14
09-29 05:21:57.103  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 05:21:57.105  5789  5801 D BluetoothBondStateMachine: make
,09-29 05:21:57.106  5789  5806 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 05:21:57.108  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:57.109  5789  5789 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 05:21:57.111  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
09-29 05:21:57.112  5789  5789 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 05:21:57.113  5789  5789 D BtGatt.GattService: Received start request. Starting profile...
,09-29 05:21:57.113  5789  5789 D BtGatt.GattService: start()
09-29 05:21:57.113  5789  5789 I bt_bluedroid: get_profile_interface gatt
,09-29 05:21:57.113  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
09-29 05:21:57.114  5789  5789 D BtGatt.AdvertiseManager: advertise manager created
,09-29 05:21:57.118  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:57.118  5789  5789 V BluetoothAdapterState: isTurningOn()=false
09-29 05:21:57.118  5789  5789 V BluetoothAdapterState: isBleTurningOn()=true
09-29 05:21:57.118  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:57.118  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 05:21:57.119  5789  5801 I bt_bluedroid: bt_bluedroid
,09-29 05:21:57.120  5789  5802 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 05:21:57.120  5789  5802 I bt_hci  : start_up
,09-29 05:21:57.124  5789  5802 I bt_vendor: alloc value 0xf3d5d871
,09-29 05:21:57.125  5789  5802 I bt_vendor: init
09-29 05:21:57.125  5789  5802 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 05:21:57.125  5789  5802 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 05:21:57.236  5789  5802 D bt_hci  : start_up starting async portion
,09-29 05:21:57.236  5789  5809 I bt_hci  : event_finish_startup
09-29 05:21:57.236  5789  5809 I bt_hci_h4: hal_open
09-29 05:21:57.237  5789  5809 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 05:21:57.235  5810  5810 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-29 05:21:57.240  5789  5809 I bt_userial_vendor: device fd = 54 open
,09-29 05:21:57.255  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 05:21:57.258  5789  5809 D bt_hwcfg: Chipset BCM4358A3
,09-29 05:21:57.258  5789  5809 D bt_hwcfg: Target name = [BCM4358A3]
09-29 05:21:57.258  5789  5809 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 05:21:57.514  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-29 05:21:57.663  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 05:21:57.664  5789  5809 D bt_hwcfg: Settlement delay -- 100 ms
09-29 05:21:57.664  5789  5809 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 05:21:57.789  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-29 05:21:57.790  5789  5809 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 05:21:57.791  5789  5809 I bt_hwcfg: vendor lib fwcfg completed
09-29 05:21:57.791  5789  5809 I bt_vendor: firmware callback
09-29 05:21:57.791  5789  5809 I bt_hci  : firmware_config_callback
,09-29 05:21:57.800  5789  5812 I bt_btu  : btu_task pending for preload complete event
,09-29 05:21:57.800  5789  5812 I bt_btu_task: Bluetooth chip preload is complete
09-29 05:21:57.800  5789  5812 I bt_btu  : btu_task received preload complete event
,09-29 05:21:57.806  5789  5812 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_A2D
,09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 05:21:57.807  5789  5812 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_PAN
,09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 05:21:57.808  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 05:21:57.890  5789  5812 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cdb549
,09-29 05:21:57.891  5789  5812 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cdb549 
,09-29 05:21:57.913  5789  5805 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 05:21:57.914  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 05:21:57.914  5789  5805 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 05:21:57.917  5789  5805 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 05:21:57.920  5789  5805 D BluetoothAdapterProperties: Scan Mode:20
09-29 05:21:57.920  5789  5805 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 05:21:57.920  5789  5805 D bt_hci  : do_postload posting postload work item
09-29 05:21:57.920  5789  5809 I bt_hci  : event_postload
09-29 05:21:57.921  5789  5809 I bt_vendor: sco_config_cb
09-29 05:21:57.921  5789  5809 I bt_hci  : sco_config_callback postload finished.
,09-29 05:21:57.925  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:57.926  5789  5809 I bt_vendor: low_power_mode_cb
09-29 05:21:57.926  5789  5805 D bt_bte_conf: Device ID record 1 : primary
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   vendorId            = 000f
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   vendorIdSource      = 0001
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   product             = 1200
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   version             = 1436
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   clientExecutableURL = 
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   serviceDescription  = 
09-29 05:21:57.927  5789  5805 D bt_bte_conf:   documentationURL    = 
09-29 05:21:57.927  5789  5805 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-29 05:21:57.927  5789  5802 D bt_stack_manager: event_start_up_stack finished
09-29 05:21:57.927  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:57.928  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 05:21:57.928  5789  5801 D BluetoothAdapterProperties: Setting state to 15
09-29 05:21:57.928  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 05:21:57.929  5789  5801 I BluetoothAdapterState: Entering BleOnState
,09-29 05:21:57.934  5789  5801 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-29 05:21:57.934  5789  5801 D BluetoothAdapterProperties: Setting state to 11
09-29 05:21:57.934  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-29 05:21:57.939  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.944  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:21:57.947  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:21:57.948  5692  5703 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.950   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.950   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.950  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:57.951  5789  5789 D HeadsetService: Received start request. Starting profile...
09-29 05:21:57.951  3703  3729 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.951   928   928 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.952  3034  3898 D BluetoothHeadset: Proxy object connected
09-29 05:21:57.952  3034  3034 D HeadsetProfile: Bluetooth service connected
,09-29 05:21:57.953  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:57.953  5789  5789 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 05:21:57.953  5789  5789 D HeadsetStateMachine: make
,09-29 05:21:57.956  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 05:21:57.957  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
,09-29 05:21:57.960  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-29 05:21:57.961  5789  5789 D HeadsetStateMachine: max_hf_connections = 1
09-29 05:21:57.961  5789  5789 I bt_bluedroid: get_profile_interface handsfree
09-29 05:21:57.962  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 05:21:57.962  5789  5805 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-29 05:21:57.955  5692  5692 D HeadsetProfile: Bluetooth service connected
,09-29 05:21:57.966  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.967  5789  5789 D A2dpService: Received start request. Starting profile...
,09-29 05:21:57.967  5789  5789 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 05:21:57.968  5789  5789 I bt_bluedroid: get_profile_interface avrcp
,09-29 05:21:57.972  5789  5789 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 05:21:57.973  5789  5789 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 05:21:57.973  5789  5789 D A2dpStateMachine: make
,09-29 05:21:57.974  5789  5789 I bt_bluedroid: get_profile_interface a2dp
,09-29 05:21:57.975  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-29 05:21:57.976  5789  5821 D A2dpStateMachine: Enter Disconnected: -2
,09-29 05:21:57.977  5789  5789 I BluetoothHidServiceJni: classInitNative: succeeds
,09-29 05:21:57.977  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.978  5789  5789 D HidService: Received start request. Starting profile...
09-29 05:21:57.978  5789  5789 I bt_bluedroid: get_profile_interface hidhost
,09-29 05:21:57.978  5789  5805 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cbc56d
09-29 05:21:57.978  5789  5789 D HidService: setHidService(): set to: null
09-29 05:21:57.979  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 05:21:57.979  5789  5789 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-29 05:21:57.980  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.981  5789  5789 D HealthService: Received start request. Starting profile...
,09-29 05:21:57.982  5789  5789 I bt_bluedroid: get_profile_interface health
,09-29 05:21:57.982  5789  5789 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 05:21:57.983  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.984  5789  5789 D PanService: Received start request. Starting profile...
,09-29 05:21:57.984  5789  5789 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 05:21:57.984  5789  5789 I bt_bluedroid: get_profile_interface pan
09-29 05:21:57.984  5789  5805 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 05:21:57.986  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.986  5789  5789 D BluetoothMapService: Received start request. Starting profile...
09-29 05:21:57.986  5789  5789 D BluetoothMapService: start()
09-29 05:21:57.989  5789  5789 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 05:21:57.989  5789  5789 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-29 05:21:57.990  5789  5789 D BluetoothMapAppObserver: createReceiver()
09-29 05:21:57.991  5789  5789 D BluetoothMapAppObserver: initObservers()
09-29 05:21:57.991  5789  5789 D BluetoothMapAppObserver: getEnabledAccountItems()
09-29 05:21:57.996  5789  5789 V SapService: SapBinder()
09-29 05:21:57.996  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:21:57.997  5789  5789 D SapService: Received start request. Starting profile...
,09-29 05:21:57.997  5789  5789 V SapService: start()
,09-29 05:21:57.999  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:57.999  5789  5789 V BluetoothAdapterState: isTurningOn()=true
,09-29 05:21:57.999  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:57.999  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.000  5789  5819 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 05:21:58.000  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.000  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.000  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.001  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.002  5789  5789 V BluetoothAdapterState: isTurningOff()=false
09-29 05:21:58.002  5789  5789 V BluetoothAdapterState: isTurningOn()=true
09-29 05:21:58.002  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
09-29 05:21:58.002  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
09-29 05:21:58.002  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 05:21:58.002  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-29 05:21:58.002  5789  5801 D BluetoothAdapterProperties: ScanMode =  20
09-29 05:21:58.002  5789  5801 D BluetoothAdapterProperties: State =  11
09-29 05:21:58.002  5789  5801 D BluetoothAdapterProperties: Setting state to 12
,09-29 05:21:58.003  5789  5805 D BluetoothAdapterProperties: Scan Mode:21
,09-29 05:21:58.004  5789  5805 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-29 05:21:58.003  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 05:21:58.006  3703  3946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 05:21:58.006  5789  5801 I BluetoothAdapterState: Entering OnState
09-29 05:21:58.006  5692  5703 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:58.007  5692  5818 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.008  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:58.009  5692  5702 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:21:58.010  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:58.010  5692  5818 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:21:58.012  3034  3945 D BluetoothMap: onBluetoothStateChange: up=true
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.014  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:58.014  3034  3034 D BluetoothMap: Proxy object connected
09-29 05:21:58.014  5692  5703 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:21:58.014  3034  3034 D MapProfile: Bluetooth service connected
09-29 05:21:58.014  3034  3034 D BluetoothMap: getConnectedDevices()
,09-29 05:21:58.016  5789  5789 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 05:21:58.016  3034  3048 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 05:21:58.016  3034  3945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:21:58.016  5789  5789 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 05:21:58.016  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.017  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:58.018  3034  3046 D BluetoothPan: onBluetoothStateChange on: true
09-29 05:21:58.018  5789  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:58.019  5692  5692 D BluetoothInputDevice: Proxy object connected
09-29 05:21:58.019  5692  5692 D HidProfile: Bluetooth service connected
09-29 05:21:58.019  5560  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:58.020  5789  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:21:58.020   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 05:21:58.020  5560  5606 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-29 05:21:58.020   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:58.020   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:58.020  3034  3048 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 05:21:58.020  3034  3034 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:21:58.020  3034  3034 D PanProfile: Bluetooth service connected
09-29 05:21:58.021   928  3796 D WifiService: setWifiEnabled: false pid=5560, uid=10077
09-29 05:21:58.021   928  3796 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 05:21:58.021  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:58.022  5789  5789 D ObexServerSockets: Succeed to create listening sockets 
09-29 05:21:58.022  5789  5789 D ObexServerSockets0: startAccept()
09-29 05:21:58.022  5789  5789 D ObexServerSockets0: prepareForNewConnect()
09-29 05:21:58.022   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 05:21:58.022  3034  3046 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:21:58.022  3034  3034 D BluetoothInputDevice: Proxy object connected
09-29 05:21:58.022  3034  3034 D HidProfile: Bluetooth service connected
,09-29 05:21:58.024  5789  5789 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 05:21:58.024  5789  5789 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 05:21:58.025  5789  5830 D ObexServerSockets0: Accepting socket connection...
09-29 05:21:58.025  5692  5818 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 05:21:58.025   928   928 D RttService: SCAN_AVAILABLE : 1
09-29 05:21:58.026  5789  5829 D ObexServerSockets0: Accepting socket connection...
09-29 05:21:58.026   928  3000 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-29 05:21:58.026   928   928 D BluetoothA2dp: Proxy object connected
09-29 05:21:58.027  3034  3034 D BluetoothA2dp: Proxy object connected
09-29 05:21:58.028  5692  5692 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 05:21:58.028  5692  5692 D PanProfile: Bluetooth service connected
09-29 05:21:58.028   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 05:21:58.028  5692  5692 D BluetoothMap: Proxy object connected
09-29 05:21:58.028  5692  5692 D MapProfile: Bluetooth service connected
09-29 05:21:58.028  5692  5692 D BluetoothMap: getConnectedDevices()
09-29 05:21:58.029   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-29 05:21:58.029  5789  5789 D BluetoothMapService: onReceive
09-29 05:21:58.029  5789  5789 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 05:21:58.029  5789  5789 D BluetoothMapService: STATE_ON
09-29 05:21:58.031  5692  5692 D BluetoothA2dp: Proxy object connected
09-29 05:21:58.032  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:58.033  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:58.034  5789  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:21:58.035   928  2891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 05:21:58.035   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-29 05:21:58.035  5789  5832 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 05:21:58.035  5789  5832 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 05:21:58.037  5692  5692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 05:21:58.043   928  2891 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 05:21:58.043  5692  5692 D DockEventReceiver: finishStartingService: stopping service
09-29 05:21:58.043  5688  5688 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-29 05:21:58.051  3499  3499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.053  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 05:21:58.055  5789  5789 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 05:21:58.055  5692  5692 D BluetoothPbap: Proxy object connected
09-29 05:21:58.055  5789  5789 D ObexServerSockets0: prepareForNewConnect()
09-29 05:21:58.055  5692  5692 D PbapServerProfile: Bluetooth service connected
09-29 05:21:58.055  3034  3034 D BluetoothPbap: Proxy object connected
09-29 05:21:58.055  3034  3034 D PbapServerProfile: Bluetooth service connected
09-29 05:21:58.056  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:58.058  5789  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:21:58.059  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.061  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:58.064  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:58.080  5789  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 05:21:58.081  5789  5840 I BtOppRfcommListener: Accept thread started.
,09-29 05:21:58.084  5688  5688 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 05:21:58.096  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 05:21:58.101  4936  4936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 05:21:58.101   928  2891 D wifi    : In wifi stop Hal
09-29 05:21:58.101   928  2891 D wifi    : halHandle = 0x7f90a99180, mVM = 0x7fad0cd140, mCls = 0x101996
09-29 05:21:58.101   928  5687 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 05:21:58.101   928  5687 D WifiHAL : Got a signal to exit!!!
09-29 05:21:58.101   928  5687 I WifiHAL : Exit wifi_event_loop
,09-29 05:21:58.101   928  2891 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 05:21:58.101   928  2891 E WifiHAL : Event processing terminated
09-29 05:21:58.102   928  2891 D wifi    : In wifi cleaned up handler
09-29 05:21:58.102   928  2891 I WifiHAL : Internal cleanup completed
09-29 05:21:58.103  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:58.104  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 05:21:58.104  4023  4151 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:21:58.125   928  5687 D wifi    : set interface wlan0 flags (DOWN)
,09-29 05:21:58.125   928  2891 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 05:21:58.330   928   945 D Tethering: InitialState.processMessage what=4
,09-29 05:21:58.336   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:58.531  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:58.536  5560  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 05:21:58.538   928  3795 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,09-29 05:21:58.538   928  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 05:21:58.540  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:58.544   507   921 D SoftapController: Softap fwReload - Ok
,09-29 05:21:58.547   507   921 D CommandListener: Setting iface cfg
,09-29 05:21:58.547   507   921 D CommandListener: Trying to bring down wlan0
09-29 05:21:58.549   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-29 05:21:58.553   928  2891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 05:21:59.045   928   939 D WifiService: setWifiEnabled: true pid=5560, uid=10077
09-29 05:21:59.051   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 05:21:59.133   928  2891 D wifi    : set interface wlan0 flags (UP)
,09-29 05:21:59.134   928  2891 I WifiHAL : Initializing wifi
09-29 05:21:59.134   928  2891 I WifiHAL : Creating socket
,09-29 05:21:59.138   928  2891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 05:21:59.138   928  2891 D wifi    : Did set static halHandle = 0x7f90a99180
09-29 05:21:59.138   928  2891 D wifi    : halHandle = 0x7f90a99180, mVM = 0x7fad0cd140, mCls = 0x10192a
09-29 05:21:59.139   928  2891 D wifi    : array field set
09-29 05:21:59.139   928  2891 I WifiNative-HAL: interface[0] = wlan0
,09-29 05:21:59.143   928  5843 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547887878528
09-29 05:21:59.144   928  5843 D wifi    : waitForHalEvents called, vm = 0x7fad0cd140, obj = 0x10192a, env = 0x7f9263bd40
,09-29 05:21:59.147   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-29 05:21:59.186  5844  5844 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 05:21:59.208  5844  5844 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:21:59.238  5844  5844 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 05:21:59.238  5844  5844 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 05:21:59.243   928  2891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 05:21:59.251  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:59.252  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:21:59.264   928  2891 D WifiConfigStore: Loading config and enabling all networks 
,09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:59.270  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:59.272  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:59.276  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:59.277   928  2891 D WifiConfigStore: loaded 0 passpoint configs
,09-29 05:21:59.277   928  2891 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:21:59.278   928  2891 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-29 05:21:59.278  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:59.278   928  2891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-29 05:21:59.280   928  2891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 05:21:59.280   928  2891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-29 05:21:59.280   928  2891 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 05:21:59.280   928  2891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 05:21:59.284   928  2891 D WifiNative-HAL: Setting external_sim to 1
,09-29 05:21:59.284  4936  4936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 05:21:59.284   928  2891 D wifi    : setting dfs flag to true, 0x7f94bbe020
,09-29 05:21:59.285   928  2891 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 05:21:59.285   928  2891 D wifi    : setting scan oui 0x7f94bbe020
09-29 05:21:59.285   928  2891 D WifiHAL : Sending mac address OUI
,09-29 05:21:59.289   928  2891 E native  : do suspend false
,09-29 05:21:59.296   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 05:21:59.296   928  2891 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 05:21:59.296   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-29 05:21:59.297   928  3000 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 05:21:59.297   507   921 D CommandListener: Setting iface cfg
,09-29 05:21:59.301   928  2890 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-29 05:21:59.301   928  2890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 05:21:59.310   928  2890 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 05:21:59.314   928  2890 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 05:21:59.314   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=248341 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:21:59.562  5560  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:21:59.568  5560  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:21:59.572  5560  5606 D BluetoothAdapter: enable(): BT is already enabled..!
,09-29 05:21:59.573   928  3789 D WifiService: setWifiEnabled: true pid=5560, uid=10077
09-29 05:21:59.573   928  3789 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 05:21:59.574  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 05:21:59.574  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:21:59.574  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 05:21:59.575  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:21:59.575  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a6c02 removed from the list
,09-29 05:21:59.575  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:21:59.575  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4c913 removed from the list
09-29 05:21:59.575  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:21:59.576  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 05:21:59.576  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:21:59.579  5560  5606 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
09-29 05:21:59.580  5560  5606 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
09-29 05:21:59.586  5560  5846 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-29 05:21:59.586  5560  5846 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 05:22:00.095  5560  5846 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-29 05:22:00.096  5560  5846 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:22:00.097  5560  5846 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:22:00.097  5560  5846 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:22:00.099  5560  5846 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 05:22:00.099  5560  5848 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-29 05:22:00.101  5560  5848 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:22:00.101  5560  5848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:22:00.101  5560  5850 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Sender)
09-29 05:22:00.102  5560  5848 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:22:00.103  5560  5848 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 05:22:00.104  5560  5851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Receiver)
09-29 05:22:00.104  5560  5852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender)
09-29 05:22:00.104  5560  5851 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: OutgoingSocketThread/Receiver)
09-29 05:22:00.105  5560  5851 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 05:22:00.105  5560  5851 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 05:22:00.106  5560  5853 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Receiver)
,09-29 05:22:00.111  5560  5853 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: IncomingSocketThread/Receiver)
,09-29 05:22:00.111  5560  5853 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 05:22:00.111  5560  5853 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 05:22:00.591  5560  5606 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-29 05:22:00.594  5560  5606 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
09-29 05:22:00.596  5560  5606 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
09-29 05:22:00.599  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
09-29 05:22:00.600  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-29 05:22:00.602  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,09-29 05:22:00.603  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-29 05:22:00.604  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-29 05:22:00.609  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-29 05:22:00.609  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@656c775 Bundle[{}]
09-29 05:22:00.610  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-29 05:22:00.610  5560  5606 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 05:22:00.610  5560  5606 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-29 05:22:00.611  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-29 05:22:00.611  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-29 05:22:00.611  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-29 05:22:00.612  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-29 05:22:00.612  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-29 05:22:00.612  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-29 05:22:00.613  5560  5606 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-29 05:22:00.614  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-29 05:22:00.615  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
09-29 05:22:00.618  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-29 05:22:00.619  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-29 05:22:00.620  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
09-29 05:22:00.621  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
09-29 05:22:00.621  5560  5606 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
09-29 05:22:00.623  5560  5606 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-29 05:22:00.626  5560  5856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-29 05:22:00.626  5560  5856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 05:22:00.630  5560  5856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-29 05:22:00.630  5560  5856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-29 05:22:00.630  5560  5856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:22:00.631  5560  5856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:22:00.632  5560  5859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Sender)
09-29 05:22:00.633  5560  5858 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-29 05:22:00.633  5560  5858 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 05:22:00.633  5560  5858 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 05:22:00.633  5560  5856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 05:22:00.634  5560  5858 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:22:00.634  5560  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: OutgoingSocketThread/Receiver)
,09-29 05:22:00.635  5560  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Sender)
09-29 05:22:00.635  5560  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: OutgoingSocketThread/Receiver)
09-29 05:22:00.635  5560  5858 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-29 05:22:00.635  5560  5860 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 05:22:00.635  5560  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 05:22:00.636  5560  5862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: IncomingSocketThread/Receiver)
,09-29 05:22:00.637  5560  5862 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: IncomingSocketThread/Receiver)
09-29 05:22:00.637  5560  5862 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 05:22:00.637  5560  5862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 05:22:01.130  5560  5606 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-29 05:22:01.133  5560  5606 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-29 05:22:01.134  5560  5606 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-29 05:22:01.138  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-29 05:22:01.141  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-29 05:22:01.142  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
09-29 05:22:01.143  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
,09-29 05:22:01.144  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
09-29 05:22:01.145  5560  5606 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-29 05:22:01.145  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 189)
09-29 05:22:01.146  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-29 05:22:01.147  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
09-29 05:22:01.148  5560  5606 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
09-29 05:22:01.150  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 05:22:01.150  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57ed87c added. We now have 3 listener(s)
,09-29 05:22:01.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 05:22:01.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 05:22:01.152  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 05:22:01.152  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 05:22:01.152  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e02505 added. We now have 3 listener(s)
,09-29 05:22:01.153  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 05:22:01.154  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 05:22:01.157  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 05:22:01.161  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 05:22:01.164  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 05:22:01.164  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 05:22:01.167  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:22:01.169  5560  5606 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-29 05:22:01.169  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 05:22:01.170  5560  5606 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,09-29 05:22:01.170  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-29 05:22:01.170  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-29 05:22:01.171  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:22:01.171  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-29 05:22:01.171  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:22:01.171  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:22:01.172  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 05:22:01.173  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:22:01.173  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-29 05:22:01.174  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:22:01.174  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:22:01.174  5560  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:22:01.174  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-29 05:22:01.174  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:22:01.175  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 05:22:01.175  5826  5826 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33401]" dev="sockfs" ino=33401 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:22:01.179  5560  5863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 05:22:01.175  5826  5826 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33401]" dev="sockfs" ino=33401 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:22:01.181  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 05:22:01.181  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 05:22:01.185  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:22:01.186  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:22:01.186  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:22:01.188  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 05:22:01.189  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 05:22:01.189  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-29 05:22:01.189  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:22:01.189  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:22:01.189  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 05:22:01.190  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:22:01.194  5789  5826 D BtGatt.GattService: registerClient() - UUID=65e4d817-a17b-40b3-862d-ddefccbcdd06
09-29 05:22:01.195  5789  5805 D BtGatt.GattService: onClientRegistered() - UUID=65e4d817-a17b-40b3-862d-ddefccbcdd06, clientIf=5
09-29 05:22:01.195  5560  5571 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 05:22:01.198  5789  5807 D BtGatt.AdvertiseManager: message : 0
,09-29 05:22:01.200  5789  5807 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 05:22:01.214  5789  5805 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 05:22:01.221  5789  5805 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 05:22:01.222  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 05:22:01.222  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-29 05:22:01.223  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 05:22:01.225  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:22:01.225  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 05:22:01.225  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 05:22:01.225  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:22:01.225  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-29 05:22:01.225  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 05:22:01.228  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:22:01.229  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:22:01.730  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 05:22:01.730  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:22:01.730  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 05:22:02.525   928  2891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 05:22:02.526   928  2891 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 05:22:02.527   928  2891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:22:02.536   928  2891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 05:22:02.570   928  2891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 05:22:02.571  5844  5844 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 05:22:03.018  5844  5844 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 05:22:03.091  5844  5844 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 05:22:03.093  5844  5844 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 05:22:03.111   928  2891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 05:22:03.112   928  2891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-29 05:22:03.112   928  2893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 05:22:03.131   928  2891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 05:22:03.145   507   921 D CommandListener: Setting iface cfg
,09-29 05:22:03.152   928  2891 D WifiStateMachine: Start Dhcp Watchdog 2
,09-29 05:22:03.160   928  5868 D DhcpClient: Receive thread started
,09-29 05:22:03.163   928  2893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:22:03.163   928  2891 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 05:22:03.163   928  2893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-29 05:22:03.245   928  2891 E native  : do suspend false
,09-29 05:22:03.259   928  5867 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 05:22:03.273   928  5868 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172588, domain null
,09-29 05:22:03.274   928  5867 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172588 seconds
,09-29 05:22:03.276   928  5867 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 05:22:03.293   928  5868 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 05:22:03.294   928  5867 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-29 05:22:03.296   507   921 D CommandListener: Setting iface cfg
09-29 05:22:03.300   928  2891 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 05:22:03.305   928  5867 D DhcpClient: Scheduling renewal in 86399s
,09-29 05:22:03.313   928  2891 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-29 05:22:03.313   928  2891 D WifiConfigStore: No blacklist allowed without epno enabled
09-29 05:22:03.314   928  2893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-29 05:22:03.316   928  2893 D ConnectivityService: Adding iface wlan0 to network 101
09-29 05:22:03.324   928  2891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 05:22:03.363   928  2893 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-29 05:22:03.363   928  2893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-29 05:22:03.368   928  2893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
,09-29 05:22:03.370   928  2893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-29 05:22:03.371   928  2893 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-29 05:22:03.381   928  2893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:22:03.386   928  2893 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-29 05:22:03.386   928  2893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-29 05:22:03.386   928  2893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-29 05:22:03.386   928  2891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 05:22:03.386   928  2893 D ConnectivityService:    accepting network in place of null
09-29 05:22:03.386   928  2891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 05:22:03.387   928  2893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 05:22:03.400   928  5866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 05:22:03.410   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:22:03.431   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 05:22:03.434   928  2893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-29 05:22:03.434   928  2893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 05:22:03.434  3670  3821 W QCNEJ   : |CORE| network available: 101
,09-29 05:22:03.436   928  2893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-29 05:22:03.436   928   945 D Tethering: MasterInitialState.processMessage what=3
09-29 05:22:03.439  3670  3821 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 05:22:03.441  3670  3821 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-29 05:22:03.442  3670  3821 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:22:03.445  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 05:22:03.448  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:22:03.453  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:22:03.454  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 05:22:03.458  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 05:22:03.460  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 05:22:03.463  4961  4985 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 05:22:03.463  4961  4985 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 05:22:03.463  4961  4985 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-29 05:22:03.463  4961  4985 E SarControlService: no key has been found,reset the power
09-29 05:22:03.463  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 05:22:03.463  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 05:22:03.463  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 05:22:03.464  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:22:03.464  4986  4986 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 05:22:03.465  4961  4998 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 05:22:03.465  4961  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 05:22:03.465  4961  4998 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 05:22:03.466  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 05:22:03.466  4986  4986 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-29 05:22:03.470  3804  3804 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 05:22:03.471  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8e5da81 HexData = [00000000ec03000000000000ffffffff]
09-29 05:22:03.471  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:22:03.471  4986  5000 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-29 05:22:03.473  4986  5000 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8e5da81 HexData = [00000000ed03000000000000ffffffff]
09-29 05:22:03.473  4986  5000 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 05:22:03.473  4986  5000 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-29 05:22:03.474  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 05:22:03.474  4961  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 05:22:03.474  3804  3804 D SystemUpdateService: onCreate
09-29 05:22:03.475  4986  4986 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 05:22:03.475  4961  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 05:22:03.478  3804  3804 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 05:22:03.479   928  5865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,09-29 05:22:03.488  3804  3804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-29 05:22:03.493  3804  5321 I iu.UploadsManager: num queued entries: 0
,09-29 05:22:03.493  3804  5321 I iu.UploadsManager: num updated entries: 0
,09-29 05:22:03.494  3804  5321 I iu.SyncManager: NEXT; no task
,09-29 05:22:03.497  3804  5878 I SystemUpdateService: active receiver: enabled
,09-29 05:22:03.500  3804  3804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 05:22:03.501  3804  3804 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 05:22:03.503  5643  5643 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 05:22:03.507  5643  5643 D SprintDMHelper: simOperator: 
09-29 05:22:03.507  5643  5643 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 05:22:03.531  3804  5878 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 05:22:03.537   928  5865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 09:22:03 GMT], X-Android-Received-Millis=[1475140923536], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475140923505]}
,09-29 05:22:03.537   928  2893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 05:22:03.538   928  2893 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-29 05:22:03.538   928  2893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-29 05:22:03.539   928  2893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 05:22:03.546  3804  5878 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-29 05:22:03.546  3804  5878 I SystemUpdateService: now status is 0 (complete)
09-29 05:22:03.546  3804  5878 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 05:22:03.546  3804  5878 I SystemUpdateService: file has been verified
09-29 05:22:03.546  3804  5878 I SystemUpdateService: OTA package size = 21989297
,09-29 05:22:03.551  3804  5878 I SystemUpdateService: showing system update notification
,09-29 05:22:03.560  3804  3804 D SystemUpdateService: onDestroy
,09-29 05:22:03.629  4936  5883 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-29 05:22:04.383   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:22:04.436   928  2893 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-29 05:22:04.727  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-29 05:22:04.728  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-29 05:22:04.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:22:04.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:22:04.728  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:22:04.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-29 05:22:04.729  5560  5863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 05:22:04.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 05:22:04.729  5560  5863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 05:22:04.729  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 05:22:04.729  5560  5863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-29 05:22:04.729  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 05:22:04.729  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:22:04.730  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:22:04.730  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-29 05:22:04.730  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:22:04.732  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:22:04.732  5560  5606 D BluetoothLeScanner: could not find callback wrapper
09-29 05:22:04.732  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-29 05:22:04.733  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 05:22:04.735  5789  5807 D BtGatt.AdvertiseManager: message : 1
09-29 05:22:04.737  5789  5807 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 05:22:04.751  5789  5805 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-29 05:22:04.752  5789  5805 D BtGatt.GattService: Client app is not null!
,09-29 05:22:04.753  5789  5800 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:22:04.754  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-29 05:22:04.754  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:22:04.755  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-29 05:22:04.755  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 05:22:04.755  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 05:22:04.758  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:22:04.758  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-29 05:22:04.758  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:22:04.760  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 05:22:04.764  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 05:22:04.764  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 05:22:04.764  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 05:22:04.764  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:22:04.764  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 05:22:04.764  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:22:04.767  5560  5606 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,09-29 05:22:04.767  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 05:22:04.769  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:22:04.769  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 05:22:04.769  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 05:22:04.769  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 05:22:04.770  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 05:22:04.775  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 05:22:04.775  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 05:22:04.782  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:22:04.783  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:22:04.783  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 05:22:04.789  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 05:22:04.789  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:22:04.790  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 05:22:04.791  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:22:04.795  5789  5831 D BtGatt.GattService: registerClient() - UUID=1d1a1040-75ff-4648-a7af-e6113a80615c
,09-29 05:22:04.796  5789  5805 D BtGatt.GattService: onClientRegistered() - UUID=1d1a1040-75ff-4648-a7af-e6113a80615c, clientIf=5
09-29 05:22:04.796  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 05:22:04.798  5789  5800 D BtGatt.GattService: start scan with filters
,09-29 05:22:04.803  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-29 05:22:04.803  5789  5808 D BtGatt.ScanManager: handling starting scan
09-29 05:22:04.804  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-29 05:22:04.804  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 05:22:04.804  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 05:22:04.808  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 05:22:04.808  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 05:22:04.808  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 05:22:04.811  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 05:22:04.812  5789  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce54fe
,09-29 05:22:04.822  5789  5805 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-29 05:22:04.822  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:04.823  5789  5808 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 05:22:04.833  5789  5805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-29 05:22:04.833  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:04.834  5789  5808 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:22:04.834  5789  5808 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 05:22:04.847  5789  5805 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 05:22:04.847  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:22:04.854  5789  5805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 05:22:04.854  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:22:05.309  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 05:22:05.310  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 05:22:05.310  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 05:22:05.384   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:22:06.184   928  2893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:22:06.385   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:22:07.389   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:22:07.818  5560  5606 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-29 05:22:07.818  5560  5606 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-29 05:22:07.818  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-29 05:22:07.819  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 05:22:07.819  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 05:22:07.825  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:22:07.827  5789  5831 D BtGatt.GattService: stopScan() - queue size =1
09-29 05:22:07.831  5789  5800 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:22:07.833  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:22:07.833  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:22:07.834  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 05:22:07.834  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 05:22:07.834  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 05:22:07.834  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-29 05:22:07.836  5560  5606 D BluetoothAdapter: STATE_ON
,09-29 05:22:07.841  5789  5789 D BtGatt.ScanManager: awakened up at time 256868
,09-29 05:22:07.841  5789  5827 D BtGatt.GattService: registerClient() - UUID=55566b5b-3b3d-40ea-a73a-8c6c14917963
09-29 05:22:07.843  5789  5805 D BtGatt.GattService: onClientRegistered() - UUID=55566b5b-3b3d-40ea-a73a-8c6c14917963, clientIf=5
09-29 05:22:07.843  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 05:22:07.844  5789  5817 D BtGatt.GattService: start scan with filters
,09-29 05:22:07.845  5789  5805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 05:22:07.845  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.846  5789  5808 D BtGatt.ScanManager: stopping BLe Batch
,09-29 05:22:07.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-29 05:22:07.847  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-29 05:22:07.852  5789  5805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 05:22:07.861  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.861  5789  5808 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 05:22:07.848  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-29 05:22:07.862  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 05:22:07.862  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 05:22:07.862  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 05:22:07.863  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 05:22:07.863  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 05:22:07.864  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 05:22:07.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 05:22:07.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 05:22:07.864  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 05:22:07.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 05:22:07.864  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 05:22:07.864  5560  5891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 05:22:07.865  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:22:07.865  5789  5800 D BtGatt.GattService: stopScan() - queue size =0
09-29 05:22:07.865  5831  5831 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 05:22:07.868  5560  5891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 05:22:07.867  5789  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:22:07.865  5831  5831 W Binder_6: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32412]" dev="sockfs" ino=32412 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 05:22:07.868  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:22:07.868  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 05:22:07.868  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 05:22:07.868  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 05:22:07.868  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 05:22:07.869  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 05:22:07.873  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 05:22:07.875  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 05:22:07.875  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 05:22:07.876  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
,09-29 05:22:07.876  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:22:07.876  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 05:22:07.876  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 05:22:07.876  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:22:07.877  5789  5805 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-29 05:22:07.877  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.877  5789  5805 D BtGatt.GattService: current time is 256904686758
09-29 05:22:07.877  5789  5805 D BtGatt.GattService: Batch record : [-9, -41, -38, 3, -84, 69, 1, -128, -96, 51, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -74, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
09-29 05:22:07.879  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 05:22:07.879  5789  5800 D BtGatt.GattService: registerClient() - UUID=23604c48-dde5-48b6-8b9e-40aac52c92a2
,09-29 05:22:07.879  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-29 05:22:07.880  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-29 05:22:07.880  5789  5808 D BtGatt.ScanManager: handling starting scan
09-29 05:22:07.880  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 05:22:07.880  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-29 05:22:07.880  5789  5805 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-29 05:22:07.880  5789  5805 E BtGatt.ContextMap: Context not found for ID 5
09-29 05:22:07.881  5789  5805 D BtGatt.GattService: onClientRegistered() - UUID=23604c48-dde5-48b6-8b9e-40aac52c92a2, clientIf=5
09-29 05:22:07.881  5560  5571 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 05:22:07.882  5789  5807 D BtGatt.AdvertiseManager: message : 0
,09-29 05:22:07.884  5789  5807 D BtGatt.AdvertiseManager: starting multi advertising
09-29 05:22:07.885  5789  5805 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 05:22:07.885  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.885  5789  5808 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 05:22:07.892  5789  5805 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 05:22:07.896  5789  5805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 05:22:07.896  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.896  5789  5808 D BtGatt.ScanManager: Starting BLE batch scan
09-29 05:22:07.896  5789  5808 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 05:22:07.900  5789  5805 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 05:22:07.901  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 05:22:07.901  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-29 05:22:07.902  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 05:22:07.903  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 05:22:07.903  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:22:07.903  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 05:22:07.903  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 05:22:07.903  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 05:22:07.903  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-29 05:22:07.903  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 05:22:07.905  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:22:07.906  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 05:22:07.909  5789  5805 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-29 05:22:07.909  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:22:07.913  5789  5805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 05:22:07.913  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:22:07.918  5789  5805 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 05:22:07.918  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.918  5789  5808 D BtGatt.ScanManager: stopping BLe Batch
,09-29 05:22:07.922  5789  5805 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 05:22:07.922  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 05:22:07.922  5789  5808 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 05:22:07.927  5789  5805 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-29 05:22:07.927  5789  5805 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 05:22:08.390   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 05:22:08.406  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 05:22:08.407  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:22:08.407  5560  5560 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 05:22:09.216   928  2893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 05:22:09.390   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 05:22:09.778   928  2891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 17 -> obsolete
,09-29 05:22:11.381   928  2891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 17 -> obsolete
,09-29 05:22:11.389   928  2893 D ConnectivityService: handlePromptUnvalidated 101
,09-29 05:22:11.407  5560  5606 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-29 05:22:11.408  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 05:22:11.408  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 05:22:11.408  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 05:22:11.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 05:22:11.409  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 05:22:11.409  5560  5891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 05:22:11.409  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-29 05:22:11.409  5560  5891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-29 05:22:11.409  5560  5891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 05:22:11.409  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 05:22:11.409  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-29 05:22:11.410  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57ed87c removed from the list
09-29 05:22:11.410  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 05:22:11.410  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 05:22:11.410  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 05:22:11.410  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 05:22:11.410  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 05:22:11.410  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 05:22:11.413  5560  5606 D BluetoothAdapter: STATE_ON
09-29 05:22:11.413  5560  5606 D BluetoothLeScanner: could not find callback wrapper
09-29 05:22:11.413  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 05:22:11.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-29 05:22:11.415  5789  5807 D BtGatt.AdvertiseManager: message : 1
09-29 05:22:11.416  5789  5807 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 05:22:11.431  5789  5805 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 05:22:11.431  5789  5805 D BtGatt.GattService: Client app is not null!
,09-29 05:22:11.433  5789  5817 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 05:22:11.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 05:22:11.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 05:22:11.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-29 05:22:11.434  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 05:22:11.434  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-29 05:22:11.437  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:22:11.437  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-29 05:22:11.437  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 05:22:11.438  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 05:22:11.441  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e02505 removed from the list
09-29 05:22:11.441  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
09-29 05:22:11.441  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 05:22:11.441  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 05:22:11.441  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 05:22:11.441  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 05:22:11.445  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-29 05:22:11.445  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-29 05:22:11.445  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 05:22:11.445  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-29 05:22:11.445  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 05:22:11.446  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-29 05:22:11.446  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-29 05:22:11.447  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,09-29 05:22:11.448  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
09-29 05:22:11.449  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-29 05:22:11.450  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-29 05:22:11.451  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-29 05:22:11.452  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,09-29 05:22:11.453  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,09-29 05:22:11.454  5560  5606 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
09-29 05:22:11.456  5560  5606 I StreamCopyingThreadTest: Starting test: testRun
09-29 05:22:11.459  5560  5893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: My test thread name)
,09-29 05:22:11.942  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 05:22:12.922  5560  5893 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 202
,09-29 05:22:12.922  5560  5893 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 202, name: My test thread name)
09-29 05:22:12.922  5560  5893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-29 05:22:12.963  5560  5606 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-29 05:22:12.966  5560  5895 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
,09-29 05:22:12.966  5560  5895 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 204, thread name: My test thread name)
09-29 05:22:12.966  5560  5895 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-29 05:22:12.969  5560  5606 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-29 05:22:12.971  5560  5606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 05:22:12.975  5560  5606 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-29 05:22:12.979  5560  5896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: My test thread name)
09-29 05:22:12.980  5560  5896 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 208, thread name: My test thread name): Test exception.
09-29 05:22:12.980  5560  5896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-29 05:22:12.988  5560  5606 I jxcore-log: *Native tests were executed*
09-29 05:22:12.988  5560  5606 I jxcore-log: 
,09-29 05:22:12.988  5560  5606 I jxcore-log: Total number of executed tests:  82
09-29 05:22:12.988  5560  5606 I jxcore-log: 
,09-29 05:22:12.989  5560  5606 I jxcore-log: Number of passed tests:  82
09-29 05:22:12.989  5560  5606 I jxcore-log: 
,09-29 05:22:12.990  5560  5606 I jxcore-log: Number of failed tests:  0
09-29 05:22:12.990  5560  5606 I jxcore-log: 
,09-29 05:22:12.990  5560  5606 I jxcore-log: Number of ignored tests:  0
09-29 05:22:12.990  5560  5606 I jxcore-log: 
,09-29 05:22:12.991  5560  5606 I jxcore-log: Total duration:  21432
09-29 05:22:12.991  5560  5606 I jxcore-log: 
09-29 05:22:12.991  5560  5606 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-29 05:22:12.991  5560  5606 I jxcore-log: 
,09-29 05:22:12.999  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:12.999  5560  5606 I jxcore-log: 
09-29 05:22:13.005  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.005  5560  5606 I jxcore-log: 
09-29 05:22:13.008  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.008  5560  5606 I jxcore-log: 
09-29 05:22:13.012  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 05:22:13.012  5560  5606 I jxcore-log: 
09-29 05:22:13.013  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 05:22:13.013  5560  5606 I jxcore-log: 
09-29 05:22:13.014  5560  5560 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-29 05:22:13.016  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 05:22:13.016  5560  5606 I jxcore-log: 
09-29 05:22:13.019  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.019  5560  5606 I jxcore-log: 
09-29 05:22:13.021  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.021  5560  5606 I jxcore-log: 
09-29 05:22:13.023  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.023  5560  5606 I jxcore-log: 
09-29 05:22:13.024  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.024  5560  5606 I jxcore-log: 
09-29 05:22:13.025  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.025  5560  5606 I jxcore-log: 
,09-29 05:22:13.026  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-29 05:22:13.026  5560  5606 I jxcore-log: 
,09-29 05:22:13.027  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.027  5560  5606 I jxcore-log: 
,09-29 05:22:13.028  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.028  5560  5606 I jxcore-log: 
,09-29 05:22:13.030  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.030  5560  5606 I jxcore-log: 
09-29 05:22:13.031  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.031  5560  5606 I jxcore-log: 
,09-29 05:22:13.032  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.032  5560  5606 I jxcore-log: 
,09-29 05:22:13.033  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.033  5560  5606 I jxcore-log: 
,09-29 05:22:13.034  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.034  5560  5606 I jxcore-log: 
,09-29 05:22:13.035  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.035  5560  5606 I jxcore-log: 
09-29 05:22:13.036  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.036  5560  5606 I jxcore-log: 
,09-29 05:22:13.036  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.036  5560  5606 I jxcore-log: 
,09-29 05:22:13.037  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.037  5560  5606 I jxcore-log: 
09-29 05:22:13.038  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.038  5560  5606 I jxcore-log: 
09-29 05:22:13.039  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.039  5560  5606 I jxcore-log: 
,09-29 05:22:13.040  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.040  5560  5606 I jxcore-log: 
09-29 05:22:13.040  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.040  5560  5606 I jxcore-log: 
,09-29 05:22:13.041  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.041  5560  5606 I jxcore-log: 
,09-29 05:22:13.042  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.042  5560  5606 I jxcore-log: 
09-29 05:22:13.043  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 05:22:13.043  5560  5606 I jxcore-log: 
,09-29 05:22:13.044  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.044  5560  5606 I jxcore-log: 
,09-29 05:22:13.045  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.045  5560  5606 I jxcore-log: 
,09-29 05:22:13.046  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.046  5560  5606 I jxcore-log: 
,09-29 05:22:13.047  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 05:22:13.047  5560  5606 I jxcore-log: 
09-29 05:22:13.048  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 05:22:13.048  5560  5606 I jxcore-log: 
09-29 05:22:13.048  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.048  5560  5606 I jxcore-log: 
09-29 05:22:13.049  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.049  5560  5606 I jxcore-log: 
09-29 05:22:13.049  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 05:22:13.049  5560  5606 I jxcore-log: 
,09-29 05:22:13.050  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-29 05:22:13.050  5560  5606 I jxcore-log: 
,09-29 05:22:13.052  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 05:22:13.052  5560  5606 I jxcore-log: 
,09-29 05:22:13.053  5560  5606 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-29 05:22:13.053  5560  5606 I jxcore-log: 
,09-29 05:22:13.507  5897  5897 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-29 05:22:13.513  5897  5897 D AndroidRuntime: CheckJNI is OFF
,09-29 05:22:13.544  5897  5897 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-29 05:22:13.577  5897  5897 I Radio-JNI: register_android_hardware_Radio DONE
,09-29 05:22:13.593  5897  5897 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-29 05:22:13.600   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-29 05:22:13.601   928   941 I ActivityManager: Killing 5560:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-29 05:22:13.651   928  2892 D WifiService: Client connection lost with reason: 4
,09-29 05:22:13.651   928  3506 D GraphicsStats: Buffer count: 2
09-29 05:22:13.651   928  3796 I WindowState: WIN DEATH: Window{5d68806 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-29 05:22:13.746   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-29 05:22:13.747   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-29 05:22:13.748   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-29 05:22:13.748   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-29 05:22:13.748   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:22:13.748   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:13.748   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:22:13.748   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 05:22:13.748   928   941 I ActivityManager:   Force finishing activity ActivityRecord{5216f0b u0 com.test.thalitest/.MainActivity t2}
,09-29 05:22:13.749   928   953 I art     : Starting a blocking GC Explicit
,09-29 05:22:13.755   928   938 W ActivityManager: Spurious death for ProcessRecord{47b4d51 0:com.test.thalitest/u0a77}, curProc for 5560: null
09-29 05:22:13.761   928   946 W WindowManager: Attempted to add application window with unknown token Token{c93d1e8 ActivityRecord{5216f0b u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
09-29 05:22:13.761   928   946 W WindowManager: Token{c93d1e8 ActivityRecord{5216f0b u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{c93d1e8 ActivityRecord{5216f0b u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-29 05:22:13.762   928   946 W WindowManager: view not successfully added to wm, removing view
09-29 05:22:13.762   928   946 W WindowManager: Exception when adding starting window
09-29 05:22:13.762   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{bec2890 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-29 05:22:13.762   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-29 05:22:13.762   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-29 05:22:13.762   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-29 05:22:13.762   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-29 05:22:13.762   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-29 05:22:13.762   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:22:13.762   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:13.762   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:22:13.762   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 05:22:13.845   928   953 I art     : Explicit concurrent mark sweep GC freed 46465(2MB) AllocSpace objects, 9(288KB) LOS objects, 33% free, 28MB/43MB, paused 2.192ms total 95.278ms
,09-29 05:22:13.867   928   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-29 05:22:13.870  5897  5897 I art     : System.exit called, status: 0
09-29 05:22:13.870  5897  5897 I AndroidRuntime: VM exiting with result code 0.
,09-29 05:22:13.874   928   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-29 05:22:13.888   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-29 05:22:13.891  3577  3577 I Keyboard.Facilitator: resetDictionaries() : en_US
09-29 05:22:13.894  5789  5789 D BluetoothMapAppObserver: onReceive
09-29 05:22:13.894  5789  5789 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-29 05:22:13.902   928  2857 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-29 05:22:13.903  4023  4109 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-29 05:22:13.920  3577  5908 I Keyboard.Facilitator.DecoderInitializer: run()
,09-29 05:22:13.926  3577  5908 I Decoder : createOrResetDecoder
,09-29 05:22:13.949  3703  3703 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-29 05:22:13.952   390   390 W kworker/3:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:22:13.959   390   390 W kworker/3:2: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:22:13.957  3499  3499 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-29 05:22:13.957  3499  3499 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-29 05:22:13.967   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-29 05:22:13.965   390   390 W kworker/3:2: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 05:22:13.973  3733  3839 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-29 05:22:13.973   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-29 05:22:13.974  3315  5911 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-29 05:22:13.974   928   940 E PackageManager: Failed to write settings, restoring backup
09-29 05:22:13.974   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-29 05:22:13.974   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-29 05:22:13.974   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-29 05:22:13.974   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-29 05:22:13.974   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-29 05:22:13.974   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:22:13.974   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:13.974   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 05:22:13.976   928   941 E DropBoxManagerService: Can't write: system_server_wtf
09-29 05:22:13.976   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 05:22:13.976   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 05:22:13.976   928   941 E DropBoxManagerService: 	... 13 more
,09-29 05:22:13.988   928  3516 I ActivityManager: Start proc 5915:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-29 05:22:13.989  3733  3839 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-29 05:22:13.989  3733  3839 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3733
09-29 05:22:13.989  3733  3839 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:13.989  3733  3839 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 05:22:13.991  3499  3499 I ConfigService: onCreate
,09-29 05:22:13.994   928  3789 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 05:22:13.997   928  5922 E DropBoxManagerService: Can't write: system_app_crash
09-29 05:22:13.997   928  5922 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 05:22:13.997   928  5922 E DropBoxManagerService: 	... 5 more
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-29 05:22:13.999  3499  5921 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the data,base in read/write mode.
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-29 05:22:13.999  3499  5921 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-29 05:22:13.999  3733  3839 I Process : Sending signal. PID: 3733 SIG: 9
09-29 05:22:14.001  3499  5921 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-29 05:22:14.015  3577  5908 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-29 05:22:14.019  3804  5914 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-29 05:22:14.026  3315  3338 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB6B3A294C) - 
,09-29 05:22:14.027  3315  3338 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-29 05:22:14.027  3315  3338 E AndroidRuntime: Process: android.process.acore, PID: 3315
09-29 05:22:14.027  3315  3338 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 05:22:14.027  3315  3338 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 05:22:14.029   928  5930 E DropBoxManagerService: Can't write: system_app_crash
09-29 05:22:14.029   928  5930 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 05:22:14.029   928  5930 E DropBoxManagerService: 	... 5 more
,09-29 05:22:14.032  3804  5914 D AccountUtils: Clearing selected account for com.test.thalitest
,09-29 05:22:14.047  3315  5911 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-29 05:22:14.048  3315  5911 I Process : Sending signal. PID: 3315 SIG: 9
,09-29 05:22:14.104   928  3789 D GraphicsStats: Buffer count: 1
,09-29 05:22:14.104   928  3756 I WindowState: WIN DEATH: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,09-29 05:22:14.110   928   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3733) has died
,09-29 05:22:14.110   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-29 05:22:14.121   928  3076 I ActivityManager: Process android.process.acore (pid 3315) has died
,09-29 05:22:14.122   928  3076 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-29 05:22:14.126   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,09-29 05:22:14.127   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
09-29 05:22:14.127   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
09-29 05:22:14.127   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-29 05:22:14.127   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-29 05:22:14.128   928   946 E WindowState: getStack: Window{b50a860 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{f39f832 token=Token{d4e783d ActivityRecord{56d05e7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,09-29 05:22:14.316   928  2891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,09-29 05:22:14.346   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
