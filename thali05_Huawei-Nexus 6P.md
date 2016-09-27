#### Test 869304906629475_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 13:22:38.636   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-27 13:22:38.637   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 13:22:39.156  5655  5655 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 13:22:39.161  5655  5655 D AndroidRuntime: CheckJNI is OFF
09-27 13:22:39.186  5655  5655 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 13:22:39.218  5655  5655 I Radio-JNI: register_android_hardware_Radio DONE
09-27 13:22:39.233  5655  5655 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 13:22:39.242   928  3434 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 13:22:39.287   928  3434 I ActivityManager: Start proc 5664:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 13:22:39.292  5655  5655 D AndroidRuntime: Shutting down VM
,09-27 13:22:39.637   928   939 I WindowManager: Screenshot max retries 4 of Token{da11edc ActivityRecord{958c74f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7605147 u0 Starting com.test.thalitest} drawState=4
,09-27 13:22:39.704  5664  5664 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 13:22:39.738  5664  5664 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 13:22:39.764  5664  5664 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 854-874)
09-27 13:22:39.764  5664  5664 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 13:22:39.784  5664  5664 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ac936ad}
,09-27 13:22:39.785  5664  5664 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 13:22:39.785  5664  5664 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 13:22:39.790  5664  5664 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-27 13:22:39.792  5664  5664 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 13:22:39.826  5664  5664 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 13:22:39.839  5664  5664 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 13:22:39.839  5664  5664 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 13:22:39.839  5664  5664 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 13:22:39.839  5664  5664 I Adreno  : Build Date                       : 12/06/15
09-27 13:22:39.839  5664  5664 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 13:22:39.839  5664  5664 I Adreno  : Local Branch                     : mybranch17112971
09-27 13:22:39.839  5664  5664 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 13:22:39.839  5664  5664 I Adreno  : Remote Branch                    : NONE
09-27 13:22:39.839  5664  5664 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 13:22:39.893   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c25a26a:true
,09-27 13:22:39.927   696   696 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33964]" dev="sockfs" ino=33964 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 13:22:39.927   696   696 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33964]" dev="sockfs" ino=33964 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 13:22:39.939  5664  5664 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 13:22:39.947  5664  5664 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 13:22:40.037   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34884]" dev="sockfs" ino=34884 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 13:22:40.037   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34884]" dev="sockfs" ino=34884 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 13:22:40.042  5664  5701 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-27 13:22:40.044   939   939 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33975]" dev="sockfs" ino=33975 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-27 13:22:40.044   939   939 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33975]" dev="sockfs" ino=33975 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 13:22:40.055  5664  5688 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 13:22:40.087  5664  5701 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 13:22:40.164   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +526ms (total +909ms)
,09-27 13:22:40.189  5664  5664 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5664
,09-27 13:22:40.335  5664  5664 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 13:22:40.474  5664  5704 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -560723664
,09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 13:22:40.481  5664  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f54fab added. We now have 1 listener(s)
,09-27 13:22:40.485  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 13:22:40.486  5664  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:22:40.486  5664  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 13:22:40.486  5664  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-27 13:22:40.489  5664  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@760fc6 added. We now have 1 listener(s)
09-27 13:22:40.489  5664  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:22:40.493   928  2998 D WifiService: New client listening to asynchronous messages
,09-27 13:22:40.494  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:22:40.494  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-27 13:22:40.494  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 13:22:40.494  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 13:22:40.494  5664  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-27 13:22:40.496  5664  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:22:40.497  5664  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 13:22:40.501  5664  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:22:40.502  5664  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:22:40.502  5664  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 13:22:40.502  5664  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:22:40.502  5664  5704 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 13:22:40.647  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:22:40.654  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:22:40.661  5664  5664 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 13:22:40.951   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:22:41.066  5664  5710 W jxcore-log: Initializing JXcore engine
,09-27 13:22:41.066  5664  5710 W jxcore-log: JXcore engine is ready
,09-27 13:22:41.076  5664  5673 I art     : Background sticky concurrent mark sweep GC freed 84143(8MB) AllocSpace objects, 18(1892KB) LOS objects, 25% free, 24MB/32MB, paused 3.032ms total 288.106ms
,09-27 13:22:41.094  5710  5710 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12171 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-27 13:22:41.094  5710  5710 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12506]" dev="sockfs" ino=12506 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-27 13:22:41.094  5710  5710 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 13:22:41.094  5710  5710 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34862]" dev="sockfs" ino=34862 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 13:22:41.106  5664  5710 W jxcore-log: Starting JXcore engine
,09-27 13:22:41.161  5664  5710 W jxcore-log: Platform android
09-27 13:22:41.161  5664  5710 W jxcore-log: 
,09-27 13:22:41.162  5664  5710 W jxcore-log: Process ARCH arm
09-27 13:22:41.162  5664  5710 W jxcore-log: 
,09-27 13:22:41.262  5664  5710 I jxcore-log: JXcore Cordova bridge is ready!
09-27 13:22:41.262  5664  5710 I jxcore-log: 
,09-27 13:22:41.262  5664  5710 W jxcore-log: JXcore engine is started
,09-27 13:22:41.269  5664  5704 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 13:22:41.273  5664  5664 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 13:22:48.638   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:49.639   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:50.640   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:50.794  5664  5710 I jxcore-log: 2016-09-27 17:22:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-27 13:22:50.794  5664  5710 I jxcore-log: 
,09-27 13:22:50.796  5664  5710 I jxcore-log: 2016-09-27 17:22:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-27 13:22:50.796  5664  5710 I jxcore-log: 
,09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:22:50.800  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:22:50.801  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:22:50.803  5664  5710 I jxcore-log: 2016-09-27 17:22:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-27 13:22:50.803  5664  5710 I jxcore-log: 
,09-27 13:22:50.805  5664  5710 I jxcore-log: 2016-09-27 17:22:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-27 13:22:50.805  5664  5710 I jxcore-log: 
,09-27 13:22:51.050  5664  5710 I jxcore-log: 2016-09-27 17:22:51 - DEBUG UnitTest_app: 'Running unit tests'
09-27 13:22:51.050  5664  5710 I jxcore-log: 
,09-27 13:22:51.051  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:22:51.051  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5443f4 added. We now have 2 listener(s)
,09-27 13:22:51.052  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:22:51.052  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 13:22:51.052  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 13:22:51.052  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:22:51.052  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24d771d added. We now have 2 listener(s)
09-27 13:22:51.052  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:22:51.053  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:22:51.055  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:22:51.058  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:22:51.059  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.059  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:22:51.059  5664  5710 D executeNativeTests: Running unit tests
,09-27 13:22:51.063  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:22:51.068  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:22:51.096  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 13:22:51.096  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 added. We now have 3 listener(s)
,09-27 13:22:51.097  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 13:22:51.097  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:22:51.097  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:22:51.097  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 13:22:51.097  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 added. We now have 3 listener(s)
09-27 13:22:51.097  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:22:51.097  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:22:51.099  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:22:51.101  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:22:51.102  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.102  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:22:51.103  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 13:22:51.103  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 13:22:51.103  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 13:22:51.103  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 13:22:51.104  5664  5710 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-27 13:22:51.104  5664  5710 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 13:22:51.104  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 13:22:51.104  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:22:51.104  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:22:51.104  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:22:51.105  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:22:51.105  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:22:51.105  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:22:51.105  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:22:51.105  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.105  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:22:51.106  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:22:51.106  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:22:51.106  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 removed from the list
09-27 13:22:51.106  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:22:51.106  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 removed from the list
,09-27 13:22:51.107  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:22:51.112  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:22:51.112  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:22:51.112  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.113  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:22:51.113  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.113  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:22:51.113  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 13:22:51.113  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:22:51.113  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:51.114  5664  5710 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-27 13:22:51.114  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:22:51.114  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:22:51.114  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:22:51.115  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:22:51.115  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:22:51.115  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.115  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:22:51.115  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:22:51.115  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:22:51.115  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:51.115  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:22:51.115  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.115  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:22:51.115  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.115  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.115  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:22:51.115  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:22:51.115  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:22:51.115  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 13:22:51.118  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 13:22:51.119  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:22:51.119  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:22:51.119  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:22:51.119  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:22:51.119  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.119  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.119  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:22:51.119  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:22:51.119  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:22:51.119  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:51.119  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:22:51.119  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.119  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.120  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:51.120  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:51.120  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:22:51.120  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:22:51.120  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:22:51.120  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:51.120  5664  5710 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-27 13:22:51.121  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:22:51.125  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:22:51.127  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:22:51.127  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:22:51.127  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:22:51.127  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:22:51.127  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:22:51.127  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:22:51.127  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 13:22:51.129  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:22:51.130  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 13:22:51.130  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 13:22:51.131  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:22:51.134  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 13:22:51.136  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:22:51.136  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 13:22:51.137  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-27 13:22:51.138  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-27 13:22:51.138  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 13:22:51.138  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:22:51.139  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-27 13:22:51.139  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:22:51.139  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-27 13:22:51.139  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:22:51.141  4602  4616 D BtGatt.GattService: registerClient() - UUID=3f3b0989-db23-4acf-b066-8829bb17427a
09-27 13:22:51.142  4602  4665 D BtGatt.GattService: onClientRegistered() - UUID=3f3b0989-db23-4acf-b066-8829bb17427a, clientIf=5
09-27 13:22:51.142  5664  5674 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 13:22:51.143  4602  4814 D BtGatt.GattService: start scan with filters
09-27 13:22:51.148  4602  4668 D BtGatt.ScanManager: handling starting scan
09-27 13:22:51.148  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 13:22:51.148  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 13:22:51.148  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:22:51.148  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-27 13:22:51.148  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:22:51.148  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:22:51.149  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 13:22:51.149  4602  4668 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:22:51.150  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:22:51.150  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:22:51.150  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:22:51.150  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 13:22:51.151  5664  5710 I io.jxcore.node.ConnectionHelper: start: OK
09-27 13:22:51.156  4602  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 13:22:51.156  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:51.157  4602  4668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 13:22:51.163  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 13:22:51.163  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:51.163  4602  4668 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:22:51.163  4602  4668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 13:22:51.173  4602  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 13:22:51.173  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:51.180  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 13:22:51.180  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:22:51.642   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:51.652  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 13:22:51.652  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:22:51.653  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-27 13:22:51.736   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 13:22:51.742   928  2999 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-27 13:22:52.643   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:53.644   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 13:22:54.766   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 13:22:54.774   928  2999 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-27 13:22:56.156  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:22:56.156  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 13:22:56.156  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 13:22:56.156  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:56.156  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 13:22:56.156  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:22:56.156  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 13:22:56.156  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:22:56.157  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:22:56.157  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:22:56.157  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:22:56.158  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 13:22:56.159  5664  5710 D BluetoothAdapter: STATE_ON
,09-27 13:22:56.159  4602  4616 D BtGatt.GattService: stopScan() - queue size =1
09-27 13:22:56.160  4602  4814 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:22:56.161  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-27 13:22:56.161  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 13:22:56.162  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 13:22:56.163  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:22:56.163  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:22:56.163  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-27 13:22:56.163  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 13:22:56.164  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 13:22:56.164  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:22:56.166  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:22:56.166  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:22:56.166  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 13:22:56.167  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:22:56.166  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:22:56.167  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:22:56.167  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:22:56.167  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:22:56.167  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 13:22:56.167  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:22:56.167  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:22:56.167  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:22:56.169  4602  4602 D BtGatt.ScanManager: awakened up at time 237279
,09-27 13:22:56.180  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 13:22:56.180  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:56.180  4602  4668 D BtGatt.ScanManager: stopping BLe Batch
,09-27 13:22:56.190  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 13:22:56.190  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:56.190  4602  4668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 13:22:56.213  4602  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-27 13:22:56.213  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:22:56.213  4602  4665 D BtGatt.GattService: current time is 237324030386
09-27 13:22:56.214  4602  4665 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -75, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -75, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -71, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-27 13:22:56.215  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-27 13:22:56.217  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 13:22:56.218  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-27 13:22:56.218  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 13:22:56.219  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 13:22:56.219  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-27 13:22:56.668  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:22:57.794   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 13:22:58.645   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:22:59.647   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:00.648   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:01.172  5664  5710 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-27 13:23:01.178  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:01.189  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:23:01.194  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:01.194  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 13:23:01.195  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:23:01.195  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:23:01.195  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:23:01.195  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:23:01.195  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 13:23:01.200  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:01.201  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 13:23:01.201  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 13:23:01.204  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:01.208  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 13:23:01.209  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:23:01.210  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 13:23:01.216  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 13:23:01.216  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:23:01.216  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-27 13:23:01.216  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:23:01.216  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-27 13:23:01.217  5664  5710 D BluetoothAdapter: STATE_ON
,09-27 13:23:01.222  4602  4616 D BtGatt.GattService: registerClient() - UUID=e267ada9-3372-4f2e-b9ce-7e048af3ee73
,09-27 13:23:01.223  4602  4665 D BtGatt.GattService: onClientRegistered() - UUID=e267ada9-3372-4f2e-b9ce-7e048af3ee73, clientIf=5
,09-27 13:23:01.224  5664  5674 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 13:23:01.224  4602  4814 D BtGatt.GattService: start scan with filters
,09-27 13:23:01.230  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 13:23:01.230  4602  4668 D BtGatt.ScanManager: handling starting scan
09-27 13:23:01.230  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 13:23:01.230  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:23:01.230  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-27 13:23:01.230  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:23:01.230  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:23:01.231  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 13:23:01.238  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:23:01.239  4602  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 13:23:01.239  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.239  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:23:01.239  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:23:01.239  4602  4668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 13:23:01.241  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 13:23:01.246  5664  5710 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 13:23:01.247  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 13:23:01.248  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.248  4602  4668 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:23:01.248  4602  4668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 13:23:01.249  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:01.249  5664  5710 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-27 13:23:01.250  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:01.250  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 13:23:01.250  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:01.250  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 13:23:01.250  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:01.250  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 13:23:01.250  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:23:01.250  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:23:01.250  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:23:01.250  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:23:01.250  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 13:23:01.251  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:23:01.252  4602  4814 D BtGatt.GattService: stopScan() - queue size =1
09-27 13:23:01.252  4602  4832 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:23:01.254  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-27 13:23:01.254  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 13:23:01.254  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 13:23:01.256  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:23:01.256  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:23:01.256  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-27 13:23:01.257  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 13:23:01.257  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 13:23:01.257  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 13:23:01.259  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:01.259  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:01.259  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:23:01.259  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:01.259  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
,09-27 13:23:01.259  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:01.259  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:23:01.260  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:01.260  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:01.260  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:23:01.260  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:01.260  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:23:01.260  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:01.260  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:01.261  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:01.261  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:01.261  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:01.262  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:01.262  4602  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 13:23:01.262  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.262  5664  5710 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-27 13:23:01.265  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:23:01.269  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 13:23:01.269  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:01.270  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:01.273  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:01.273  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:23:01.274  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 13:23:01.274  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:23:01.274  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:23:01.274  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:23:01.274  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 13:23:01.278  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:01.279  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 13:23:01.279  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.280  4602  4668 D BtGatt.ScanManager: stopping BLe Batch
09-27 13:23:01.280  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 13:23:01.280  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 13:23:01.281  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:01.287  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 13:23:01.287  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.287  4602  4668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 13:23:01.287  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 13:23:01.288  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:23:01.289  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 13:23:01.292  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 13:23:01.292  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:23:01.292  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-27 13:23:01.292  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:23:01.292  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-27 13:23:01.293  4602  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 13:23:01.293  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:23:01.293  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:23:01.295  4602  4814 D BtGatt.GattService: registerClient() - UUID=0b3841aa-deb8-4eba-82e3-14ea212a4dc3
,09-27 13:23:01.296  4602  4665 D BtGatt.GattService: onClientRegistered() - UUID=0b3841aa-deb8-4eba-82e3-14ea212a4dc3, clientIf=5
09-27 13:23:01.296  5664  5675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 13:23:01.296  4602  4615 D BtGatt.GattService: start scan with filters
,09-27 13:23:01.299  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 13:23:01.299  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 13:23:01.299  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:23:01.299  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-27 13:23:01.299  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:23:01.299  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:23:01.299  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 13:23:01.300  4602  4668 D BtGatt.ScanManager: handling starting scan
,09-27 13:23:01.302  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 13:23:01.302  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:23:01.302  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 13:23:01.304  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 13:23:01.306  5664  5710 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 13:23:01.307  4602  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 13:23:01.307  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.307  4602  4668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 13:23:01.312  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 13:23:01.312  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:01.313  4602  4668 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:23:01.313  4602  4668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 13:23:01.322  4602  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 13:23:01.323  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:23:01.328  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 13:23:01.328  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:23:01.650   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:01.804  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 13:23:01.804  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:23:01.804  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-27 13:23:02.651   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:03.651   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 13:23:06.307  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:06.307  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:06.307  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 13:23:06.307  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:06.308  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 13:23:06.308  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:06.308  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 13:23:06.308  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:23:06.308  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:23:06.308  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:23:06.308  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:23:06.309  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-27 13:23:06.311  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:23:06.313  4602  4814 D BtGatt.GattService: stopScan() - queue size =1
09-27 13:23:06.315  4602  4616 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 13:23:06.316  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:23:06.316  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:23:06.316  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 13:23:06.317  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:23:06.317  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-27 13:23:06.317  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-27 13:23:06.317  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 13:23:06.317  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 13:23:06.320  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:23:06.320  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:23:06.320  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-27 13:23:06.320  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 13:23:06.321  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 13:23:06.321  4602  4602 D BtGatt.ScanManager: awakened up at time 247431
09-27 13:23:06.322  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:23:06.325  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 13:23:06.325  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:23:06.325  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 13:23:06.330  4602  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 13:23:06.330  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:06.330  4602  4668 D BtGatt.ScanManager: stopping BLe Batch
,09-27 13:23:06.339  4602  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 13:23:06.339  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:23:06.339  4602  4668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 13:23:06.356  4602  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-27 13:23:06.356  4602  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:23:06.356  4602  4665 D BtGatt.GattService: current time is 247466979981
09-27 13:23:06.357  4602  4665 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -74, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-27 13:23:06.357  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 13:23:06.357  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 13:23:06.358  4602  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-27 13:23:06.827  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:23:06.827  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:06.827  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-27 13:23:11.326  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:11.327  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.327  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.327  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:23:11.327  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.327  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 13:23:11.328  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.328  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
,09-27 13:23:11.328  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:11.328  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.328  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:11.328  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.330  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.330  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.333  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.334  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 13:23:11.334  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.334  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:11.336  5664  5710 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-27 13:23:11.340  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:11.340  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.340  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.341  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.341  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.341  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.341  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:11.341  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.341  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.341  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.342  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.342  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.342  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.342  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.342  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.344  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 13:23:11.344  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.344  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.344  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.346  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 13:23:11.346  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.346  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.346  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.346  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:23:11.346  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.346  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.346  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:11.346  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.347  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.347  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.347  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.347  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:11.347  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.347  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.347  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.348  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.348  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.348  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.348  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.349  5664  5710 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-27 13:23:11.350  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:11.350  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.350  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.350  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.350  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.350  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.350  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:11.350  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.350  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.350  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.350  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.350  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.350  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.350  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:11.350  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.352  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.352  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.352  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.352  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.353  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-27 13:23:11.353  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.353  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.353  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.353  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.353  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.353  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.353  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.354  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
,09-27 13:23:11.354  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.354  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.354  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.354  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.354  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.354  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:11.354  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.355  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.355  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.355  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.355  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:11.356  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 13:23:11.357  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:23:11.357  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 13:23:11.357  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 13:23:11.357  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.357  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.357  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.358  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.358  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.358  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.358  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.358  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.358  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.358  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.358  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:11.358  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.358  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.358  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.358  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.360  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.360  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.360  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.360  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.361  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 13:23:11.361  5664  5710 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-27 13:23:11.361  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 13:23:11.364  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 13:23:11.364  5664  5710 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 13:23:11.364  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 13:23:11.365  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 13:23:11.366  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 13:23:11.366  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 13:23:11.366  5664  5710 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 13:23:11.367  5664  5710 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 13:23:11.367  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 13:23:11.367  5664  5710 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-27 13:23:11.367  5664  5710 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 13:23:11.368  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 13:23:11.368  5664  5710 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 13:23:11.368  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-27 13:23:11.371  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-27 13:23:11.372  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-27 13:23:11.372  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-27 13:23:11.373  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-27 13:23:11.373  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-27 13:23:11.373  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-27 13:23:11.373  5664  5710 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 13:23:11.373  5664  5710 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 13:23:11.374  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.374  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-27 13:23:11.374  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 13:23:11.374  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.374  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.374  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-27 13:23:11.374  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.374  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-27 13:23:11.374  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.374  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:11.374  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-27 13:23:11.374  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-27 13:23:11.375  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.375  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.375  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.375  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.375  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.376  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:11.376  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.376  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.376  5664  5712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-27 13:23:11.377  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.377  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.377  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:11.377  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.378  5664  5711 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-27 13:23:11.378  5664  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:11.378  5664  5710 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-27 13:23:11.379  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.379  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.379  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 13:23:11.379  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:23:11.379  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:11.379  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.379  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.379  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.379  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.379  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.379  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.379  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.379  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.379  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.379  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.381  4615  4615 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32061]" dev="sockfs" ino=32061 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 13:23:11.381  4615  4615 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32061]" dev="sockfs" ino=32061 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 13:23:11.381  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.381  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.381  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.381  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.382  5664  5710 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-27 13:23:11.382  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.382  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:11.382  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.383  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.383  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.383  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:11.383  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.383  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.383  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.384  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.384  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.384  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.384  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:11.384  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.384  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.385  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.385  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.385  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.385  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-27 13:23:11.386  5664  5710 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 13:23:11.386  5664  5710 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 13:23:11.386  5664  5710 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 13:23:11.386  5664  5710 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 13:23:11.386  5664  5710 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 13:23:11.386  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 13:23:11.386  5664  5710 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-27 13:23:11.387  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:11.387  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 13:23:11.387  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:11.387  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:11.387  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.387  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.387  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.387  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.387  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.387  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.387  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:11.387  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.387  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.387  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.387  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.388  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:11.388  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:11.388  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.389  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:11.389  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:23:11.389  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.389  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:11.389  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:11.389  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:11.390  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:11.390  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:11.390  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:11.390  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:11.390  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:13.652   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:14.653   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:15.654   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:15.949   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 13:23:16.390  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:16.391  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:16.391  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.391  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:16.391  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:16.391  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:23:16.392  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:16.392  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 13:23:16.392  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 13:23:16.392  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:16.392  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:23:16.393  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.393  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.393  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:16.393  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
,09-27 13:23:16.393  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.393  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.394  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:16.394  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:16.394  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.394  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.394  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.397  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 13:23:16.398  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:16.398  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.398  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.403  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 13:23:16.405  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:23:16.407  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 13:23:16.409  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 13:23:16.409  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-27 13:23:16.410  5664  5713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-27 13:23:16.409  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-27 13:23:16.411  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 13:23:16.411  5664  5664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-27 13:23:16.411  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 13:23:16.412  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.412  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 13:23:16.412  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 13:23:16.412  5664  5713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-27 13:23:16.411  4814  4814 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29505]" dev="sockfs" ino=29505 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 13:23:16.411  4814  4814 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29505]" dev="sockfs" ino=29505 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 13:23:16.412  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:16.412  5664  5664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 13:23:16.412  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.412  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 13:23:16.412  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:23:16.412  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.413  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.415  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:23:16.415  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.415  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 13:23:16.415  5664  5713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 13:23:16.415  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:23:16.415  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:16.415  5664  5713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 13:23:16.415  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:23:16.415  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:16.415  5664  5713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 13:23:16.415  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 13:23:16.415  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.416  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.416  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.416  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-27 13:23:16.416  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:16.416  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.416  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:16.416  5664  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 13:23:16.416  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:16.416  5664  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:16.416  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.416  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.416  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.416  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.418  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:16.418  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:16.418  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.418  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:16.419  5664  5710 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-27 13:23:16.420  5664  5710 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 13:23:16.420  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-27 13:23:16.420  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:23:16.420  5664  5710 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 13:23:16.420  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:16.420  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:16.420  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:23:16.420  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.420  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.420  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.420  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:16.421  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:16.421  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:16.421  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.421  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:16.421  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.421  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.421  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.421  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:16.423  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 13:23:16.423  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:16.423  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.423  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:16.428  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:16.428  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:16.428  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 13:23:16.428  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.428  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.428  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.428  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:16.428  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
09-27 13:23:16.428  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.428  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.429  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:16.429  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.429  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.429  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.429  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.431  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:16.431  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 13:23:16.431  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.431  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.432  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:23:16.432  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:23:16.432  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 13:23:16.432  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:23:16.432  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.432  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.432  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:23:16.433  5664  5710 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3eb53 not in the list
,09-27 13:23:16.433  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.433  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
09-27 13:23:16.433  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:16.433  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.433  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:16.433  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:16.433  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:16.434  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:23:16.434  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:23:16.434  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:16.434  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f0ac90 not in the list
,09-27 13:23:16.436  5664  5710 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-27 13:23:16.436  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 13:23:16.436  5664  5710 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 13:23:16.436  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 13:23:16.436  5664  5710 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-27 13:23:16.436  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-27 13:23:16.439  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-27 13:23:16.439  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 13:23:16.440  5664  5710 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-27 13:23:16.441  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-27 13:23:16.441  5664  5710 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 13:23:16.441  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 13:23:16.441  5664  5710 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-27 13:23:16.441  5664  5710 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 13:23:16.442  5664  5710 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 13:23:16.442  5664  5710 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 13:23:16.442  5664  5710 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 13:23:16.442  5664  5710 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-27 13:23:16.442  5664  5710 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-27 13:23:16.443  5664  5710 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-27 13:23:16.443  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:23:16.444  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64a6cf2 added. We now have 3 listener(s)
09-27 13:23:16.444  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:16.445  5664  5710 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 13:23:16.446   928  3435 D WifiService: setWifiEnabled: true pid=5664, uid=10077
09-27 13:23:16.446   928  3435 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:23:16.507  4602  4807 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-27 13:23:16.507  4602  4812 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-27 13:23:16.507  5664  5711 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-27 13:23:16.508  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-27 13:23:16.508  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,09-27 13:23:16.655   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:16.916  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:23:17.656   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:18.656   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 13:23:18.972   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 13:23:20.955   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:23:21.451  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 13:23:21.452  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4f43 added. We now have 4 listener(s)
,09-27 13:23:21.452  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:21.465  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:21.465  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4f43 removed from the list
,09-27 13:23:21.465  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:21.466  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:21.466  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:21.468  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:23:21.468  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31059c0 added. We now have 4 listener(s)
09-27 13:23:21.468  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:21.474  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:21.475  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31059c0 removed from the list
09-27 13:23:21.475  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:21.475  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:21.475  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:21.476  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:23:21.476  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cee6f9 added. We now have 4 listener(s)
09-27 13:23:21.476  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:21.479   928   939 D WifiService: setWifiEnabled: false pid=5664, uid=10077
,09-27 13:23:21.479   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:23:21.483   928  2997 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 13:23:21.483   928  2997 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-27 13:23:21.484   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 13:23:21.484   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 13:23:21.488  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:23:21.491  4602  4661 D BluetoothAdapterState: Current state: ON, message: 23
09-27 13:23:21.491  4602  4661 D BluetoothAdapterProperties: Setting state to 13
09-27 13:23:21.491  4602  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 13:23:21.492  4602  4661 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 13:23:21.495  4602  4661 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:21.497  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.497  4602  4602 D BluetoothMapService: onReceive
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:21.497  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:21.497  4602  4602 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 13:23:21.497  4602  4602 D BluetoothMapService: STATE_TURNING_OFF
09-27 13:23:21.497  4602  4602 D BluetoothMapService: MAP Service closeService in
09-27 13:23:21.497  4602  4602 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 13:23:21.497  4602  4602 D ObexServerSockets0: shutdown(block = true)
09-27 13:23:21.497  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.498  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:21.498  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:23:21.498  4602  4835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-27 13:23:21.498  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 13:23:21.499  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-27 13:23:21.499  4602  4836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 13:23:21.500  4602  4812 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 13:23:21.501   928  5415 D DhcpClient: Clearing IP address
09-27 13:23:21.501   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-27 13:23:21.502  4602  4602 I BtOppRfcommListener: stopping Accept Thread
09-27 13:23:21.502  4602  5356 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 13:23:21.502  4602  5356 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 13:23:21.503  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.505  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:21.510   509   921 D CommandListener: Setting iface cfg
,09-27 13:23:21.512   928   941 I ActivityManager: Start proc 5717:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-27 13:23:21.513  4602  4665 D BluetoothAdapterProperties: Scan Mode:20
09-27 13:23:21.513  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:21.514  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:21.514  4602  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 13:23:21.515  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.516  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:21.522  3599  5470 V NativeCrypto: Read error: ssl=0x7f9a439b00: I/O error during system call, Connection timed out
,09-27 13:23:21.524  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:21.524  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:21.524  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.524  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:21.525   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-27 13:23:21.525  3599  5470 V NativeCrypto: SSL shutdown failed: ssl=0x7f9a439b00: I/O error during system call, Broken pipe
09-27 13:23:21.525   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-27 13:23:21.525  4602  4602 D HeadsetService: Received stop request...Stopping profile...
,09-27 13:23:21.527  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.527  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:23:21.528  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.528  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:21.529   535   535 E Parcel  : Reading a NULL string not supported here.
09-27 13:23:21.532  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.532  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:21.533  3154  3387 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:21.533   928   928 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:21.533   928   928 D BluetoothHeadset: Proxy object disconnected
,09-27 13:23:21.533  3821  4017 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:21.533  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.534  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:21.534  3154  3154 D HeadsetProfile: Bluetooth service disconnected
09-27 13:23:21.534   928   928 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:21.535   928   928 D RttService: SCAN_AVAILABLE : 1
09-27 13:23:21.535  4602  4602 D A2dpService: Received stop request...Stopping profile...
09-27 13:23:21.536   928  3107 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 13:23:21.536  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.537  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:23:21.537  4602  4817 D A2dpStateMachine: Exit Disconnected: -1
09-27 13:23:21.537  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.537  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:21.539   928  2999 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-27 13:23:21.540  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.541  3768  3933 W QCNEJ   : |CORE| network lost: 100
09-27 13:23:21.541  3768  3933 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 13:23:21.542   928   928 D BluetoothA2dp: Proxy object disconnected
,09-27 13:23:21.543   928  5416 D DhcpClient: Receive thread stopped
,09-27 13:23:21.543  4602  4602 D HidService: Received stop request...Stopping profile...
09-27 13:23:21.543  4602  4602 D HidService: Stopping Bluetooth HidService
09-27 13:23:21.544  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.544  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.545  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.545  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 13:23:21.545  4602  4602 D HealthService: Received stop request...Stopping profile...
09-27 13:23:21.548  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 13:23:21.549  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 13:23:21.549  4602  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 13:23:21.549  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.549  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.549  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.549  4602  4665 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 13:23:21.549  4602  4602 D PanService: Received stop request...Stopping profile...
,09-27 13:23:21.551   928  2997 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-27 13:23:21.553  4602  4602 D BluetoothMapService: Received stop request...Stopping profile...
09-27 13:23:21.554  4602  4602 D BluetoothMapService: stop()
09-27 13:23:21.554  4602  4602 D BluetoothMapAppObserver: deinitObservers()
09-27 13:23:21.554  4602  4602 D BluetoothMapAppObserver: removeReceiver()
09-27 13:23:21.556  4602  4602 D SapService: Received stop request...Stopping profile...
09-27 13:23:21.556  4602  4602 V SapService: stop()
,09-27 13:23:21.558  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.558  4602  4602 V BluetoothAdapterState: isTurningOn()=false
,09-27 13:23:21.558  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.558  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 13:23:21.559  4602  4602 V BluetoothAdapterState: isTurningOff()=true
,09-27 13:23:21.559  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.559  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.559  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.559  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:21.559  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.560  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 13:23:21.560  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 13:23:21.560  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.560  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.560  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.560  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:21.560  4602  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 13:23:21.560  4602  4807 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 13:23:21.560  4602  4807 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 13:23:21.560  4602  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 13:23:21.560  4602  4807 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 13:23:21.560  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 13:23:21.560  4602  4807 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 13:23:21.560  4602  4665 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 13:23:21.561  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 13:23:21.561  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.561  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.561  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.561  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:21.561  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 13:23:21.561  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 13:23:21.562   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 13:23:21.562  4602  4602 D BluetoothMapService: MAP Service closeService in
,09-27 13:23:21.562  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.562  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.562  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.562  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:21.562  4602  4602 D BluetoothMapService: cleanup()
09-27 13:23:21.562  4602  4602 D BluetoothMapService: MAP Service closeService in
09-27 13:23:21.563  3154  3154 D BluetoothA2dp: Proxy object disconnected
09-27 13:23:21.563  4602  4602 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:21.563  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.563  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.563  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:21.563  4602  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 13:23:21.563  4602  4661 D BluetoothAdapterProperties: Setting state to 15
09-27 13:23:21.563  4602  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 13:23:21.564  3154  3154 D BluetoothInputDevice: Proxy object disconnected
09-27 13:23:21.564  3154  3154 D HidProfile: Bluetooth service disconnected
09-27 13:23:21.564  3154  3154 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 13:23:21.564  3154  3154 D PanProfile: Bluetooth service disconnected
09-27 13:23:21.564  3154  3154 D BluetoothMap: Proxy object disconnected
09-27 13:23:21.564  3154  3154 D MapProfile: Bluetooth service disconnected
09-27 13:23:21.565  4602  4661 I BluetoothAdapterState: Entering BleOnState
09-27 13:23:21.566  3154  3166 D BluetoothMap: onBluetoothStateChange: up=false
09-27 13:23:21.567  3154  3387 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 13:23:21.568   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 13:23:21.568   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:21.569  3821  3850 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:21.570  3154  3166 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 13:23:21.570   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:21.571  3154  3165 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-27 13:23:21.571   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:21.571   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:21.571  3154  3387 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:21.572  3154  3166 D BluetoothPan: onBluetoothStateChange on: false
09-27 13:23:21.572  4602  4661 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 13:23:21.573  4602  4661 D BluetoothAdapterProperties: Setting state to 16
09-27 13:23:21.573  4602  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 13:23:21.573  4602  4661 D BluetoothAdapterProperties: onBleDisable
09-27 13:23:21.573  4602  4661 I BluetoothAdapterState: Entering PendingCommandState
09-27 13:23:21.574  4602  4662 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 13:23:21.574  4602  4665 D BluetoothAdapterProperties: Scan Mode:20
09-27 13:23:21.575  4602  4807 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 13:23:21.575  4602  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:21.576  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.576  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:21.579  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.579  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:21.581  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:2,3:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.581  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 13:23:21.585  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:21.587  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.588  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.588  5717  5717 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-27 13:23:21.591   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:21.591   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 13:23:21.592   509   921 D TetherController: Setting IP forward enable = 0
09-27 13:23:21.593   928  2999 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-27 13:23:21.593   928  2999 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 13:23:21.593   928  2997 D DhcpClient: doQuit
09-27 13:23:21.594   928  2997 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 13:23:21.594   928  5415 D DhcpClient: onQuitting
,09-27 13:23:21.596   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-27 13:23:21.597  3467  3467 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 13:23:21.598  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.600  5313  5313 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f7a8e69 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-27 13:23:21.601  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.601  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:21.602  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.602  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:21.605  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.605  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:21.606  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.606  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:21.607  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-27 13:23:21.609  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:21.609  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:21.609  5077  5101 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 13:23:21.609  5077  5101 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 13:23:21.609  5077  5101 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 13:23:21.609  5077  5101 E SarControlService: no key has been found,reset the power
09-27 13:23:21.609  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 13:23:21.610  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 13:23:21.610  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 13:23:21.610  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:21.610  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:21.610  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:23:21.610  5102  5102 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-27 13:23:21.611  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 13:23:21.612  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 13:23:21.612  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.612  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 13:23:21.613  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:23:21.613  5102  5102 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 13:23:21.613  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.615  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000ea03000000000000ffffffff]
09-27 13:23:21.615  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 13:23:21.615  5102  5116 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,09-27 13:23:21.616  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 13:23:21.617  5077  5087 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-27 13:23:21.624  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000eb03000000000000ffffffff]
,09-27 13:23:21.624  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 13:23:21.624  5102  5116 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-27 13:23:21.625  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:23:21.626  5077  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 13:23:21.626  3467  3467 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 13:23:21.627  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 13:23:21.632   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b0d1d2:true
,09-27 13:23:21.632  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 13:23:21.633  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 13:23:21.633   509   914 W SocketClient: write error (Broken pipe)
09-27 13:23:21.633   509   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-27 13:23:21.633   509   914 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 13:23:21.646   928  3931 I ActivityManager: Start proc 5748:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-27 13:23:21.653   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-27 13:23:21.655  3467  3467 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-27 13:23:21.657   928  2999 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-27 13:23:21.657   509   921 D TetherController: Setting IP forward enable = 0
,09-27 13:23:21.660  5717  5717 D LocalBluetoothProfileManager: Adding local MAP profile
,09-27 13:23:21.664  5717  5717 D BluetoothMap: Create BluetoothMap proxy object
,09-27 13:23:21.673  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 13:23:21.678  5717  5717 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 13:23:21.694  5748  5748 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 13:23:21.697  5717  5717 D DockEventReceiver: finishStartingService: stopping service
,09-27 13:23:21.706   928  3434 I ActivityManager: Killing 5002:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 13:23:21.775  5050  5050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 13:23:21.775   928  2997 D wifi    : In wifi stop Hal
,09-27 13:23:21.775   928  2997 D wifi    : halHandle = 0x7f8c3df900, mVM = 0x7fa4f4d140, mCls = 0x100a02
,09-27 13:23:21.775   928  3465 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 13:23:21.775   928  3465 D WifiHAL : Got a signal to exit!!!
09-27 13:23:21.775   928  3465 I WifiHAL : Exit wifi_event_loop
09-27 13:23:21.776   928  2997 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-27 13:23:21.776   928  2997 E WifiHAL : Event processing terminated
09-27 13:23:21.777   928  2997 D wifi    : In wifi cleaned up handler
09-27 13:23:21.777   928  2997 I WifiHAL : Internal cleanup completed
09-27 13:23:21.777  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.778  4081  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 13:23:21.779  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:21.780  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:21.782  4602  4665 I bt_hci  : shut_down
,09-27 13:23:21.789  4602  4669 I bt_vendor: low_power_mode_cb
,09-27 13:23:21.791  4602  4669 D bt_hwcfg: hw_epilog_process
,09-27 13:23:21.793  4602  4669 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 13:23:21.793  4602  4669 I bt_vendor: epilog_cb
09-27 13:23:21.793  4602  4669 I bt_hci  : epilog_finished_callback
,09-27 13:23:21.796  4602  4665 I bt_hci_h4: hal_close
,09-27 13:23:21.796  4602  4665 I bt_userial_vendor: device fd = 54 close
,09-27 13:23:21.799   928  3465 D wifi    : set interface wlan0 flags (DOWN)
,09-27 13:23:21.799   928  2997 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 13:23:21.898  5748  5748 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.898  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.899  5748  5748 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 13:23:21.899  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 13:23:21.902  4602  4662 D bt_stack_manager: event_shut_down_stack finished.
09-27 13:23:21.902  4602  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-27 13:23:21.904  4602  4602 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 13:23:21.905  4602  4661 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 13:23:21.905  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 13:23:21.905  4602  4602 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 13:23:21.905  4602  4602 D BtGatt.GattService: stop()
09-27 13:23:21.905  4602  4602 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 13:23:21.909  4602  4602 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:21.909  4602  4602 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:21.909  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:21.909  5717  5717 D DockEventReceiver: finishStartingService: stopping service
09-27 13:23:21.909  4602  4602 V BluetoothAdapterState: isBleTurningOff()=true
09-27 13:23:21.909  4602  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 13:23:21.910  4602  4661 D BluetoothAdapterProperties: Setting state to 10
09-27 13:23:21.910  4602  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 13:23:21.910  4602  4661 I BluetoothAdapterState: Entering OffState
09-27 13:23:21.911   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-27 13:23:21.911  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 13:23:21.912   928  3856 I ActivityManager: Killing 5444:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-27 13:23:21.948  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-27 13:23:21.949  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 13:23:21.949  4602  4602 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 13:23:21.950  4602  4662 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-27 13:23:21.960  4602  4662 D bt_stack_manager: event_clean_up_stack finished.
09-27 13:23:21.961  4602  4602 I art     : System.exit called, status: 0
09-27 13:23:21.961  4602  4602 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 13:23:21.992  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 13:23:21.995  3732  3732 D SystemUpdateService: onCreate
,09-27 13:23:21.998  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 13:23:22.001   928   945 D Tethering: InitialState.processMessage what=4
,09-27 13:23:22.004   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 13:23:22.007  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 13:23:22.013   928  3856 I ActivityManager: Process com.android.bluetooth (pid 4602) has died
,09-27 13:23:22.015  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 13:23:22.016  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 13:23:22.017  3732  5441 I iu.UploadsManager: num queued entries: 0
09-27 13:23:22.018  3732  5441 I iu.UploadsManager: num updated entries: 0
,09-27 13:23:22.019  3732  5441 I iu.SyncManager: NEXT; no task
,09-27 13:23:22.020  3732  5783 I SystemUpdateService: active receiver: enabled
,09-27 13:23:22.029   928  3948 I ActivityManager: Start proc 5785:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-27 13:23:22.039  3732  5783 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 13:23:22.059  3732  5783 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 13:23:22.059  3732  5783 I SystemUpdateService: now status is 0 (complete)
09-27 13:23:22.059  3732  5783 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 13:23:22.059  3732  5783 I SystemUpdateService: file has been verified
,09-27 13:23:22.064  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-27 13:23:22.066  3732  5783 I SystemUpdateService: OTA package size = 21989297
,09-27 13:23:22.070  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 13:23:22.078  5785  5785 D SprintDMHelper: simOperator: 
,09-27 13:23:22.078  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 13:23:22.087  3732  5783 I SystemUpdateService: showing system update notification
,09-27 13:23:22.090  5050  5797 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 13:23:22.101   928  2959 I ActivityManager: Start proc 5798:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 13:23:22.135  5798  5798 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 13:23:22.148  3732  3732 D SystemUpdateService: onDestroy
,09-27 13:23:22.149   928  3854 I ActivityManager: Killing 5313:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 13:23:22.183   928  3854 I ActivityManager: Killing 4675:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-27 13:23:22.262  5748  5774 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 13:23:22.270   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cacaae7:true
,09-27 13:23:26.501   928  5426 D WifiService: setWifiEnabled: true pid=5664, uid=10077
,09-27 13:23:26.502   928  5426 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:23:26.511   509   921 D SoftapController: Softap fwReload - Ok
,09-27 13:23:26.516   509   921 D CommandListener: Setting iface cfg
,09-27 13:23:26.517   509   921 D CommandListener: Trying to bring down wlan0
09-27 13:23:26.518   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 13:23:26.523   928  2997 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 13:23:27.097   928  2997 D wifi    : set interface wlan0 flags (UP)
,09-27 13:23:27.100   928  2997 I WifiHAL : Initializing wifi
,09-27 13:23:27.100   928  2997 I WifiHAL : Creating socket
,09-27 13:23:27.101   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-27 13:23:27.103   928  2997 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 13:23:27.103   928  2997 D wifi    : Did set static halHandle = 0x7f8c3df900
,09-27 13:23:27.103   928  2997 D wifi    : halHandle = 0x7f8c3df900, mVM = 0x7fa4f4d140, mCls = 0x193e
09-27 13:23:27.103   928  2997 D wifi    : array field set
09-27 13:23:27.103   928  2997 I WifiNative-HAL: interface[0] = wlan0
09-27 13:23:27.105   928  5815 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547813718272
09-27 13:23:27.105   928  5815 D wifi    : waitForHalEvents called, vm = 0x7fa4f4d140, obj = 0x193e, env = 0x7f8d83d2c0
,09-27 13:23:27.173  5816  5816 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 13:23:27.185  5816  5816 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 13:23:27.206   928  2997 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 13:23:27.209  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:27.210  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:27.210  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:27.262  5816  5816 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 13:23:27.262  5816  5816 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 13:23:27.279   928  2997 D WifiConfigStore: Loading config and enabling all networks 
,09-27 13:23:27.281  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:27.282  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 13:23:27.282  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.282  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:27.285  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:27.285  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 13:23:27.285  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.285  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:27.288  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:27.288  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:27.288  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:27.288  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:27.293   928  2997 D WifiConfigStore: loaded 0 passpoint configs
,09-27 13:23:27.293   928  2997 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 13:23:27.294   928  2997 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 13:23:27.295   928  2997 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 13:23:27.297   928  2997 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 13:23:27.297   928  2997 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 13:23:27.297   928  2997 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 13:23:27.297   928  2997 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 13:23:27.301   928  2997 D WifiNative-HAL: Setting external_sim to 1
,09-27 13:23:27.301  5050  5050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 13:23:27.302   928  2997 D wifi    : setting dfs flag to true, 0x7f8a863a80
,09-27 13:23:27.303   928  2997 D WifiStateMachine: Setting OUI to DA-A1-19
,09-27 13:23:27.303   928  2997 D wifi    : setting scan oui 0x7f8a863a80
09-27 13:23:27.304   928  2997 D WifiHAL : Sending mac address OUI
,09-27 13:23:27.308   928  2997 E native  : do suspend false
,09-27 13:23:27.315   928   928 D RttService: SCAN_AVAILABLE : 3
,09-27 13:23:27.315   928  2997 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 13:23:27.315   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 13:23:27.315   928  3107 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 13:23:27.316   509   921 D CommandListener: Setting iface cfg
,09-27 13:23:27.320   928  2994 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 13:23:27.320   928  2994 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 13:23:27.329   928  2994 D WifiNative-HAL: p2pGetDeviceAddress
09-27 13:23:27.329   928  2994 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 13:23:27.334   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268445 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-27 13:23:30.517  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:23:30.522  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:23:30.529  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:23:30.534  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:23:30.609   928  2997 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 13:23:30.611   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-27 13:23:30.611   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 13:23:30.622   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 13:23:30.655   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 13:23:30.658  5816  5816 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 13:23:31.082  5816  5816 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 13:23:31.117  5816  5816 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 13:23:31.118  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 13:23:31.131   928  2997 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 13:23:31.132   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 13:23:31.132   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 13:23:31.154   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 13:23:31.168   509   921 D CommandListener: Setting iface cfg
,09-27 13:23:31.175   928  2997 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 13:23:31.182   928  5822 D DhcpClient: Receive thread started
,09-27 13:23:31.186   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 13:23:31.186   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 13:23:31.186   928  2999 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-27 13:23:31.268   928  2997 E native  : do suspend false
,09-27 13:23:31.282   928  5821 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 13:23:31.296   928  5822 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-27 13:23:31.296   928  5821 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
09-27 13:23:31.298   928  5821 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 13:23:31.314   928  5822 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 13:23:31.315   928  5821 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 13:23:31.319   509   921 D CommandListener: Setting iface cfg
09-27 13:23:31.324   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 13:23:31.329   928  5821 D DhcpClient: Scheduling renewal in 86399s
,09-27 13:23:31.339   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 13:23:31.340   928  2997 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 13:23:31.342   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-27 13:23:31.344   928  2999 D ConnectivityService: Adding iface wlan0 to network 101
,09-27 13:23:31.353   928  2997 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 13:23:31.393   928  2999 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 13:23:31.394   928  2999 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-27 13:23:31.398   928  2999 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-27 13:23:31.401   928  2999 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-27 13:23:31.404   928  2999 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-27 13:23:31.411   928  2999 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 13:23:31.415   928  2999 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-27 13:23:31.415   928  2999 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-27 13:23:31.415   928  2999 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-27 13:23:31.415   928  2999 D ConnectivityService:    accepting network in place of null
09-27 13:23:31.415   928  2997 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 13:23:31.415   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 13:23:31.416   928  2999 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 13:23:31.433   928  5820 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 13:23:31.439   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:31.461   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:31.464   928  2999 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-27 13:23:31.464   928  2999 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 13:23:31.464  3768  3933 W QCNEJ   : |CORE| network available: 101
,09-27 13:23:31.465   928  2999 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-27 13:23:31.466   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-27 13:23:31.467  3768  3933 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-27 13:23:31.468  3768  3933 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 13:23:31.468  3768  3933 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-27 13:23:31.472  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:31.472  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:31.472  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.472  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:31.474  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:31.475  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:31.475  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.475  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:31.477  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:23:31.477  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:23:31.477  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.477  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:23:31.479  5077  5101 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-27 13:23:31.479  5077  5101 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 13:23:31.480  5077  5101 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 13:23:31.480  5077  5101 E SarControlService: no key has been found,reset the power
09-27 13:23:31.480  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 13:23:31.480  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 13:23:31.480  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 13:23:31.480  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:23:31.481  5102  5102 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 13:23:31.482  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 13:23:31.482  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 13:23:31.482  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 13:23:31.482  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-27 13:23:31.482  5102  5102 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 13:23:31.483  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-27 13:23:31.486  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 13:23:31.488  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000ec03000000000000ffffffff]
09-27 13:23:31.488  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 13:23:31.488  5102  5116 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-27 13:23:31.490  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000ed03000000000000ffffffff]
09-27 13:23:31.490  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 13:23:31.490  5102  5116 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-27 13:23:31.491  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:23:31.491  5077  5087 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 13:23:31.492  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 13:23:31.493  3732  3732 D SystemUpdateService: onCreate
09-27 13:23:31.495  5077  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 13:23:31.497  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 13:23:31.507  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 13:23:31.508   928  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-27 13:23:31.510   928  3434 D WifiService: setWifiEnabled: false pid=5664, uid=10077
09-27 13:23:31.510   928  3434 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:23:31.511   928  2997 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 13:23:31.511   928  2997 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 13:23:31.511   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 13:23:31.511   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 13:23:31.511  3732  5441 I iu.UploadsManager: num queued entries: 0
09-27 13:23:31.512  3732  5441 I iu.UploadsManager: num updated entries: 0
,09-27 13:23:31.518   928  5821 D DhcpClient: Clearing IP address
,09-27 13:23:31.518   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 13:23:31.519  3732  5832 I SystemUpdateService: active receiver: enabled
,09-27 13:23:31.519   509   921 D CommandListener: Setting iface cfg
09-27 13:23:31.521  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-27 13:23:31.522  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 13:23:31.524  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 13:23:31.527   928  5819 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-27 13:23:31.528   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-27 13:23:31.528  5785  5785 D SprintDMHelper: simOperator: 
09-27 13:23:31.528  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 13:23:31.532   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-27 13:23:31.532   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-27 13:23:31.534   535   535 E Parcel  : Reading a NULL string not supported here.
09-27 13:23:31.535   928   928 D RttService: SCAN_AVAILABLE : 1
09-27 13:23:31.536   928  3107 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 13:23:31.540   928  2997 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-27 13:23:31.542   928  2999 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-27 13:23:31.545  3768  3933 W QCNEJ   : |CORE| network lost: 101
09-27 13:23:31.545   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 13:23:31.545  3768  3933 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 13:23:31.546   928  5822 D DhcpClient: Receive thread stopped
09-27 13:23:31.546  3732  5441 I iu.SyncManager: NEXT; no task
,09-27 13:23:31.547  3732  5832 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 13:23:31.556  3732  5832 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-27 13:23:31.556  3732  5832 I SystemUpdateService: now status is 0 (complete)
09-27 13:23:31.556  3732  5832 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-27 13:23:31.556  3732  5832 I SystemUpdateService: file has been verified
09-27 13:23:31.557  3732  5832 I SystemUpdateService: OTA package size = 21989297
,09-27 13:23:31.567  3732  5832 I SystemUpdateService: showing system update notification
,09-27 13:23:31.567   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:31.579  3732  3732 D SystemUpdateService: onDestroy
,09-27 13:23:31.586   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:23:31.586   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-27 13:23:31.587   928  2999 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-27 13:23:31.587   928  2999 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 13:23:31.590   928   945 D Tethering: MasterInitialState.processMessage what=3
09-27 13:23:31.592   928  2997 D DhcpClient: doQuit
,09-27 13:23:31.593   928  2997 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 13:23:31.593   928  5821 D DhcpClient: onQuitting
09-27 13:23:31.593  5816  5816 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 13:23:31.593  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:31.594  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:31.594  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.594  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:31.602  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:31.602  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:31.602  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.602  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:31.603  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:31.603  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:31.603  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.603  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:31.603  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-27 13:23:31.607  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:31.607  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:31.607  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:31.607  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:31.608  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:31.608  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:31.610  5816  5816 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-27 13:23:31.617  5077  5101 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-27 13:23:31.617  5077  5101 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 13:23:31.617  5077  5101 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 13:23:31.617  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 13:23:31.618  5077  5101 E SarControlService: no key has been found,reset the power
09-27 13:23:31.618  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 13:23:31.618  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 13:23:31.618  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-27 13:23:31.619  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:23:31.619  5102  5102 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 13:23:31.621  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 13:23:31.622  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-27 13:23:31.624  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 13:23:31.625  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 13:23:31.625  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000ee03000000000000ffffffff]
,09-27 13:23:31.625  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 13:23:31.625  5102  5116 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-27 13:23:31.626  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:23:31.626  5102  5102 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 13:23:31.627  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:23:31.627  5077  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 13:23:31.628  3732  3732 D SystemUpdateService: onCreate
09-27 13:23:31.629  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000ef03000000000000ffffffff]
09-27 13:23:31.629  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 13:23:31.629  5102  5116 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-27 13:23:31.630  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:23:31.630  5077  5087 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 13:23:31.633  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 13:23:31.636  3732  5848 I SystemUpdateService: active receiver: enabled
,09-27 13:23:31.642   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-27 13:23:31.643   928  2999 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-27 13:23:31.643   928  2999 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 13:23:31.643  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 13:23:31.646  5816  5816 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 13:23:31.647  3732  5441 I iu.UploadsManager: num queued entries: 0
09-27 13:23:31.648  3732  5441 I iu.UploadsManager: num updated entries: 0
09-27 13:23:31.648  3732  5441 I iu.SyncManager: NEXT; no task
,09-27 13:23:31.651  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 13:23:31.652  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 13:23:31.654  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 13:23:31.657  5785  5785 D SprintDMHelper: simOperator: 
09-27 13:23:31.657  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-27 13:23:31.659  3732  5848 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 13:23:31.663  5816  5816 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 13:23:31.672  3732  5848 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 13:23:31.672  3732  5848 I SystemUpdateService: now status is 0 (complete)
09-27 13:23:31.672  3732  5848 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 13:23:31.672  3732  5848 I SystemUpdateService: file has been verified
09-27 13:23:31.672  3732  5848 I SystemUpdateService: OTA package size = 21989297
,09-27 13:23:31.687  3732  5848 I SystemUpdateService: showing system update notification
,09-27 13:23:31.696  3732  3732 D SystemUpdateService: onDestroy
,09-27 13:23:31.768   928  2997 D wifi    : In wifi stop Hal
09-27 13:23:31.768   928  2997 D wifi    : halHandle = 0x7f8c3df900, mVM = 0x7fa4f4d140, mCls = 0x193e
,09-27 13:23:31.768   928  5815 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 13:23:31.768   928  5815 D WifiHAL : Got a signal to exit!!!
09-27 13:23:31.769   928  5815 I WifiHAL : Exit wifi_event_loop
09-27 13:23:31.770   928  2997 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 13:23:31.770   928  2997 E WifiHAL : Event processing terminated
09-27 13:23:31.770   928  2997 D wifi    : In wifi cleaned up handler
09-27 13:23:31.770   928  2997 I WifiHAL : Internal cleanup completed
09-27 13:23:31.770  5050  5050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 13:23:31.771  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:31.772  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:31.773  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:31.773  4081  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 13:23:31.793   928  5815 D wifi    : set interface wlan0 flags (DOWN)
,09-27 13:23:31.793   928  2997 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 13:23:31.999   928   945 D Tethering: InitialState.processMessage what=4
09-27 13:23:32.006   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 13:23:32.464   928  2999 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 13:23:33.658   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:34.659   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:35.660   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:36.545   928   945 I ActivityManager: Start proc 5853:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 13:23:36.647  5853  5853 D AdapterServiceConfig: Adding HeadsetService
,09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding A2dpService
09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding HidService
09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding HealthService
09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding PanService
09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding GattService
09-27 13:23:36.648  5853  5853 D AdapterServiceConfig: Adding BluetoothMapService
09-27 13:23:36.649  5853  5853 D AdapterServiceConfig: Adding SapService
,09-27 13:23:36.660   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:36.662   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7849cec:true
,09-27 13:23:36.662  5853  5853 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 13:23:36.666  5853  5853 I bt_bluedroid: init
,09-27 13:23:36.666  5853  5865 I BluetoothAdapterState: Entering OffState
,09-27 13:23:36.668  5853  5866 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 13:23:36.668  5853  5866 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 13:23:36.669  5853  5866 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 13:23:36.669  5853  5866 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 13:23:36.669  5853  5853 I bt_bluedroid: get_profile_interface socket
,09-27 13:23:36.671  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 13:23:36.672  5853  5853 I bt_bluedroid: get_profile_interface sdp
09-27 13:23:36.673  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 13:23:36.677  5853  5864 I bt_bluedroid: config_hci_snoop_log
,09-27 13:23:36.678   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 13:23:36.682  5853  5865 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 13:23:36.682  5853  5865 D BluetoothAdapterProperties: Setting state to 14
09-27 13:23:36.682  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-27 13:23:36.683  5853  5865 D BluetoothBondStateMachine: make
,09-27 13:23:36.685  5853  5870 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 13:23:36.687  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:36.689  5853  5853 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 13:23:36.692  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:36.692  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 13:23:36.693  5853  5853 D BtGatt.GattService: Received start request. Starting profile...
09-27 13:23:36.693  5853  5853 D BtGatt.GattService: start()
09-27 13:23:36.693  5853  5853 I bt_bluedroid: get_profile_interface gatt
,09-27 13:23:36.694  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:36.694  5853  5853 D BtGatt.AdvertiseManager: advertise manager created
,09-27 13:23:36.699  5853  5853 V BluetoothAdapterState: isTurningOff()=false
,09-27 13:23:36.699  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:36.699  5853  5853 V BluetoothAdapterState: isBleTurningOn()=true
09-27 13:23:36.699  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:36.700  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 13:23:36.701  5853  5865 I bt_bluedroid: bt_bluedroid
09-27 13:23:36.701  5853  5866 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 13:23:36.701  5853  5866 I bt_hci  : start_up
,09-27 13:23:36.706  5853  5866 I bt_vendor: alloc value 0xf41eb871
,09-27 13:23:36.706  5853  5866 I bt_vendor: init
09-27 13:23:36.707  5853  5866 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 13:23:36.707  5853  5866 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 13:23:36.816  5853  5866 D bt_hci  : start_up starting async portion
,09-27 13:23:36.817  5853  5873 I bt_hci  : event_finish_startup
09-27 13:23:36.817  5853  5873 I bt_hci_h4: hal_open
,09-27 13:23:36.817  5853  5873 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 13:23:36.820  5853  5873 I bt_userial_vendor: device fd = 54 open
09-27 13:23:36.814  5874  5874 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 13:23:36.834  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 13:23:36.837  5853  5873 D bt_hwcfg: Chipset BCM4358A3
,09-27 13:23:36.838  5853  5873 D bt_hwcfg: Target name = [BCM4358A3]
09-27 13:23:36.838  5853  5873 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 13:23:37.241  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 13:23:37.242  5853  5873 D bt_hwcfg: Settlement delay -- 100 ms
09-27 13:23:37.242  5853  5873 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 13:23:37.376  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-27 13:23:37.376  5853  5873 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 13:23:37.378  5853  5873 I bt_hwcfg: vendor lib fwcfg completed
09-27 13:23:37.378  5853  5873 I bt_vendor: firmware callback
,09-27 13:23:37.378  5853  5873 I bt_hci  : firmware_config_callback
,09-27 13:23:37.390  5853  5876 I bt_btu  : btu_task pending for preload complete event
,09-27 13:23:37.390  5853  5876 I bt_btu_task: Bluetooth chip preload is complete
,09-27 13:23:37.390  5853  5876 I bt_btu  : btu_task received preload complete event
,09-27 13:23:37.396  5853  5876 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTM
,09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_GAP
,09-27 13:23:37.397  5853  5876 I         : BTE_InitTraceLevels -- TRC_PAN
,09-27 13:23:37.398  5853  5876 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 13:23:37.398  5853  5876 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 13:23:37.398  5853  5876 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 13:23:37.398  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 13:23:37.398  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 13:23:37.479  5853  5876 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
09-27 13:23:37.479  5853  5876 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-27 13:23:37.494  5853  5869 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 13:23:37.495  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 13:23:37.496  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 13:23:37.498  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 13:23:37.500  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
,09-27 13:23:37.501  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 13:23:37.501  5853  5869 D bt_hci  : do_postload posting postload work item
09-27 13:23:37.501  5853  5873 I bt_hci  : event_postload
09-27 13:23:37.501  5853  5873 I bt_vendor: sco_config_cb
,09-27 13:23:37.501  5853  5873 I bt_hci  : sco_config_callback postload finished.
,09-27 13:23:37.505  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:37.506  5853  5869 D bt_bte_conf: Device ID record 1 : primary
,09-27 13:23:37.506  5853  5869 D bt_bte_conf:   vendorId            = 000f
09-27 13:23:37.506  5853  5869 D bt_bte_conf:   vendorIdSource      = 0001
09-27 13:23:37.506  5853  5869 D bt_bte_conf:   product             = 1200
09-27 13:23:37.507  5853  5869 D bt_bte_conf:   version             = 1436
09-27 13:23:37.507  5853  5869 D bt_bte_conf:   clientExecutableURL = 
09-27 13:23:37.507  5853  5869 D bt_bte_conf:   serviceDescription  = 
09-27 13:23:37.507  5853  5869 D bt_bte_conf:   documentationURL    = 
09-27 13:23:37.507  5853  5869 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-27 13:23:37.507  5853  5866 D bt_stack_manager: event_start_up_stack finished
09-27 13:23:37.508  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 13:23:37.509  5853  5865 D BluetoothAdapterProperties: Setting state to 15
09-27 13:23:37.509  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 13:23:37.510  5853  5865 I BluetoothAdapterState: Entering BleOnState
09-27 13:23:37.511  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.515  5853  5873 I bt_vendor: low_power_mode_cb
09-27 13:23:37.517  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.518  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-27 13:23:37.518  5853  5865 D BluetoothAdapterProperties: Setting state to 11
,09-27 13:23:37.518  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 13:23:37.524  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.526  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.526  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:37.527  5853  5853 D HeadsetService: Received start request. Starting profile...
,09-27 13:23:37.528  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:37.529  5853  5853 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 13:23:37.529  5853  5853 D HeadsetStateMachine: make
,09-27 13:23:37.536  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:37.537  5853  5853 D HeadsetStateMachine: max_hf_connections = 1
09-27 13:23:37.537  5853  5853 I bt_bluedroid: get_profile_interface handsfree
,09-27 13:23:37.537  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 13:23:37.538  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-27 13:23:37.540  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:37.541  5853  5853 D A2dpService: Received start request. Starting profile...
,09-27 13:23:37.541  5853  5853 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 13:23:37.541  5853  5853 I bt_bluedroid: get_profile_interface avrcp
,09-27 13:23:37.546  5853  5853 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 13:23:37.546  5853  5853 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 13:23:37.546  5853  5853 D A2dpStateMachine: make
09-27 13:23:37.547  5853  5853 I bt_bluedroid: get_profile_interface a2dp
,09-27 13:23:37.548  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 13:23:37.549  5853  5885 D A2dpStateMachine: Enter Disconnected: -2
,09-27 13:23:37.550  5853  5853 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 13:23:37.550  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:37.552  5853  5853 D HidService: Received start request. Starting profile...
,09-27 13:23:37.552  5853  5853 I bt_bluedroid: get_profile_interface hidhost
09-27 13:23:37.552  5853  5853 D HidService: setHidService(): set to: null
09-27 13:23:37.552  5853  5869 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-27 13:23:37.552  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 13:23:37.554  5853  5853 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 13:23:37.554  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:37.555  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 13:23:37.555  5717  5717 D BluetoothInputDevice: Proxy object connected
09-27 13:23:37.556  5853  5853 D HealthService: Received start request. Starting profile...
09-27 13:23:37.556  5717  5717 D HidProfile: Bluetooth service connected
09-27 13:23:37.557  5853  5853 I bt_bluedroid: get_profile_interface health
09-27 13:23:37.557  5853  5853 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 13:23:37.558  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:37.559  5853  5853 D PanService: Received start request. Starting profile...
,09-27 13:23:37.559  5717  5717 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 13:23:37.559  5853  5853 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 13:23:37.559  5853  5853 I bt_bluedroid: get_profile_interface pan
09-27 13:23:37.559  5717  5717 D PanProfile: Bluetooth service connected
09-27 13:23:37.560  5853  5869 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 13:23:37.563  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:37.564  5853  5853 D BluetoothMapService: Received start request. Starting profile...
,09-27 13:23:37.564  5853  5853 D BluetoothMapService: start()
09-27 13:23:37.566  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-27 13:23:37.567  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 13:23:37.567  5853  5853 D BluetoothMapAppObserver: createReceiver()
09-27 13:23:37.568  5853  5853 D BluetoothMapAppObserver: initObservers()
09-27 13:23:37.568  5853  5853 D BluetoothMapAppObserver: getEnabledAccountItems()
09-27 13:23:37.573  5717  5717 D BluetoothMap: Proxy object connected
,09-27 13:23:37.573  5717  5717 D MapProfile: Bluetooth service connected
09-27 13:23:37.573  5717  5717 D BluetoothMap: getConnectedDevices()
09-27 13:23:37.574  5717  5717 D BluetoothMap: Bluetooth is Not enabled
,09-27 13:23:37.574  5853  5853 V SapService: SapBinder()
09-27 13:23:37.574  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:37.575  5853  5853 D SapService: Received start request. Starting profile...
09-27 13:23:37.575  5853  5853 V SapService: start()
,09-27 13:23:37.576  5853  5853 V BluetoothAdapterState: isTurningOff()=false
,09-27 13:23:37.576  5853  5853 V BluetoothAdapterState: isTurningOn()=true
,09-27 13:23:37.576  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.577  5853  5883 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.577  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 13:23:37.578  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.579  5853  5853 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:37.579  5853  5853 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:37.579  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:37.579  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:37.579  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 13:23:37.579  5853  5865 D BluetoothAdapterProperties: ScanMode =  20
09-27 13:23:37.579  5853  5865 D BluetoothAdapterProperties: State =  11
,09-27 13:23:37.580  5853  5869 D BluetoothAdapterProperties: Scan Mode:21
09-27 13:23:37.580  5853  5865 D BluetoothAdapterProperties: Setting state to 12
09-27 13:23:37.580  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 13:23:37.580  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 13:23:37.581  3154  3387 D BluetoothMap: onBluetoothStateChange: up=true
09-27 13:23:37.581  5853  5865 I BluetoothAdapterState: Entering OnState
09-27 13:23:37.581  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-27 13:23:37.584  3154  3154 D BluetoothMap: Proxy object connected
09-27 13:23:37.584  3154  3154 D MapProfile: Bluetooth service connected
09-27 13:23:37.584  3154  3154 D BluetoothMap: getConnectedDevices()
09-27 13:23:37.584  5717  5731 D BluetoothPan: onBluetoothStateChange on: true
,09-27 13:23:37.584  3154  3165 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 13:23:37.586   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:37.587  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:37.588  5717  5728 D BluetoothMap: onBluetoothStateChange: up=true
09-27 13:23:37.588   928   928 D BluetoothA2dp: Proxy object connected
09-27 13:23:37.589   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:37.589  3821  3848 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:37.589  3154  3166 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 13:23:37.589  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:37.591  3154  3154 D BluetoothInputDevice: Proxy object connected
09-27 13:23:37.591  3154  3154 D HidProfile: Bluetooth service connected
,09-27 13:23:37.591  5717  5731 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 13:23:37.591   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 13:23:37.591  3154  3165 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:37.592  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:37.592  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 13:23:37.593   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 13:23:37.593  3154  3387 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:37.594  3154  3154 D BluetoothA2dp: Proxy object connected
09-27 13:23:37.594  3154  3165 D BluetoothPan: onBluetoothStateChange on: true
09-27 13:23:37.595  5853  5853 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-27 13:23:37.596  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:37.598  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:37.598  3154  3154 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 13:23:37.598  5717  5728 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 13:23:37.598  3154  3154 D PanProfile: Bluetooth service connected
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:37.600  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 13:23:37.602  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:37.602  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:37.602  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-27 13:23:37.602  5717  5717 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-27 13:23:37.603   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 13:23:37.603  5853  5853 D ObexServerSockets: Succeed to create listening sockets 
09-27 13:23:37.603  5853  5853 D ObexServerSockets0: startAccept()
09-27 13:23:37.603  5853  5853 D ObexServerSockets0: prepareForNewConnect()
09-27 13:23:37.603  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.605  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.606  5853  5853 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 13:23:37.606  5853  5853 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 13:23:37.606  5853  5853 D BluetoothMapService: onReceive
09-27 13:23:37.607  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 13:23:37.607  5853  5893 D ObexServerSockets0: Accepting socket connection...
,09-27 13:23:37.607  5853  5853 D BluetoothMapService: STATE_ON
09-27 13:23:37.607  5853  5892 D ObexServerSockets0: Accepting socket connection...
09-27 13:23:37.607  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:37.608  5717  5717 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-27 13:23:37.608  5853  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:37.611  5853  5894 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 13:23:37.611  5853  5894 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 13:23:37.614  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 13:23:37.616  5717  5717 D BluetoothA2dp: Proxy object connected
,09-27 13:23:37.621  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 13:23:37.624  5717  5717 D DockEventReceiver: finishStartingService: stopping service
,09-27 13:23:37.630  3154  3154 D BluetoothPbap: Proxy object connected
,09-27 13:23:37.630  3154  3154 D PbapServerProfile: Bluetooth service connected
,09-27 13:23:37.633  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 13:23:37.633  5853  5853 D ObexServerSockets0: prepareForNewConnect()
,09-27 13:23:37.635  5853  5898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:37.635  5717  5717 D BluetoothPbap: Proxy object connected
,09-27 13:23:37.636  5717  5717 D PbapServerProfile: Bluetooth service connected
,09-27 13:23:37.649  5853  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:37.650  5853  5902 I BtOppRfcommListener: Accept thread started.
,09-27 13:23:37.661   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:37.690  3154  3165 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.690   928   945 D BluetoothHeadset: Proxy object connected
09-27 13:23:37.690  3154  3154 D HeadsetProfile: Bluetooth service connected
09-27 13:23:37.690   928   928 D BluetoothHeadset: Proxy object connected
09-27 13:23:37.691   928   928 D BluetoothHeadset: Proxy object connected
09-27 13:23:37.691  3821  4017 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.691   928   928 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.693   928   945 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.694  3154  3166 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.694  3154  3154 D HeadsetProfile: Bluetooth service connected
,09-27 13:23:37.710  5717  5728 D BluetoothHeadset: Proxy object connected
,09-27 13:23:37.710  5717  5717 D HeadsetProfile: Bluetooth service connected
,09-27 13:23:38.661   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 13:23:39.422   928  2999 D ConnectivityService: handlePromptUnvalidated 101
,09-27 13:23:41.526  5853  5865 D BluetoothAdapterState: Current state: ON, message: 23
,09-27 13:23:41.526  5853  5865 D BluetoothAdapterProperties: Setting state to 13
09-27 13:23:41.526  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-27 13:23:41.527  5853  5865 D BluetoothAdapterProperties: onBluetoothDisable()
,09-27 13:23:41.529  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:41.533  5853  5853 D BluetoothMapService: onReceive
09-27 13:23:41.534  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 13:23:41.534  5853  5853 D BluetoothMapService: STATE_TURNING_OFF
09-27 13:23:41.534  5853  5853 D BluetoothMapService: MAP Service closeService in
,09-27 13:23:41.534  5853  5853 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 13:23:41.535  5853  5853 D ObexServerSockets0: shutdown(block = true)
09-27 13:23:41.536  5853  5853 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 13:23:41.536  5853  5892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 13:23:41.537  5853  5853 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 13:23:41.537  5853  5878 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 13:23:41.537  5853  5893 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-27 13:23:41.540  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:41.540  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:41.542  5853  5853 I BtOppRfcommListener: stopping Accept Thread
,09-27 13:23:41.543  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 13:23:41.543  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:41.543  5853  5902 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-27 13:23:41.544  5853  5902 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 13:23:41.546  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
09-27 13:23:41.548  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 13:23:41.550  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 13:23:41.551  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:41.552  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:41.553  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:41.554  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:41.555  5853  5853 D HeadsetService: Received stop request...Stopping profile...
,09-27 13:23:41.558  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:41.558  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:41.559  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 13:23:41.559  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:41.562  5717  5717 D DockEventReceiver: finishStartingService: stopping service
09-27 13:23:41.564  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:41.566  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:41.568  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.570  3154  3387 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.570   928   928 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.570   928   928 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.571  5717  5731 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.571  5853  5853 D A2dpService: Received stop request...Stopping profile...
09-27 13:23:41.571  5853  5885 D A2dpStateMachine: Exit Disconnected: -1
09-27 13:23:41.571  3821  3850 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.571   928   928 D BluetoothHeadset: Proxy object disconnected
09-27 13:23:41.572  5717  5717 D HeadsetProfile: Bluetooth service disconnected
09-27 13:23:41.572   928   928 D BluetoothA2dp: Proxy object disconnected
09-27 13:23:41.575  5853  5853 D HidService: Received stop request...Stopping profile...
09-27 13:23:41.575  5853  5853 D HidService: Stopping Bluetooth HidService
09-27 13:23:41.575  5717  5717 D BluetoothA2dp: Proxy object disconnected
09-27 13:23:41.576  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 13:23:41.577  3154  3154 D HeadsetProfile: Bluetooth service disconnected
09-27 13:23:41.577  3154  3154 D BluetoothA2dp: Proxy object disconnected
09-27 13:23:41.577  3154  3154 D BluetoothInputDevice: Proxy object disconnected
,09-27 13:23:41.578  3154  3154 D HidProfile: Bluetooth service disconnected
09-27 13:23:41.578  5853  5853 D HealthService: Received stop request...Stopping profile...
09-27 13:23:41.580  5853  5853 D PanService: Received stop request...Stopping profile...
09-27 13:23:41.581  3154  3154 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 13:23:41.581  3154  3154 D PanProfile: Bluetooth service disconnected
,09-27 13:23:41.582  5853  5853 D BluetoothMapService: Received stop request...Stopping profile...
,09-27 13:23:41.582  5853  5853 D BluetoothMapService: stop()
09-27 13:23:41.582  5853  5853 D BluetoothMapAppObserver: deinitObservers()
09-27 13:23:41.582  5853  5853 D BluetoothMapAppObserver: removeReceiver()
09-27 13:23:41.583  3154  3154 D BluetoothMap: Proxy object disconnected
09-27 13:23:41.584  3154  3154 D MapProfile: Bluetooth service disconnected
09-27 13:23:41.584  5717  5717 D BluetoothInputDevice: Proxy object disconnected
09-27 13:23:41.584  5717  5717 D HidProfile: Bluetooth service disconnected
09-27 13:23:41.584  5717  5717 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 13:23:41.584  5853  5853 D SapService: Received stop request...Stopping profile...
09-27 13:23:41.584  5717  5717 D PanProfile: Bluetooth service disconnected
09-27 13:23:41.584  5853  5853 V SapService: stop()
09-27 13:23:41.584  5717  5717 D BluetoothMap: Proxy object disconnected
,09-27 13:23:41.584  5717  5717 D MapProfile: Bluetooth service disconnected
09-27 13:23:41.585  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.586  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.586  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.586  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 13:23:41.587  5853  5853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-27 13:23:41.588  5853  5853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 13:23:41.588  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:41.588  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:41.588  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.588  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:41.588  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.588  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.588  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:41.588  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 13:23:41.588  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-27 13:23:41.589  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 13:23:41.589  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:41.590  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 13:23:41.590  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 13:23:41.590  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 13:23:41.590  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 13:23:41.590  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-27 13:23:41.591  3154  3154 D BluetoothPbap: Proxy object disconnected
09-27 13:23:41.591  3154  3154 D PbapServerProfile: Bluetooth service disconnected
09-27 13:23:41.591  5717  5717 D BluetoothPbap: Proxy object disconnected
09-27 13:23:41.591  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.591  5717  5717 D PbapServerProfile: Bluetooth service disconnected
09-27 13:23:41.591  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.591  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.591  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 13:23:41.592  5853  5853 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 13:23:41.592  5853  5853 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 13:23:41.592  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 13:23:41.593  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.593  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.593  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.593  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:41.593  5853  5853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 13:23:41.593  5853  5869 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 13:23:41.593  5853  5853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 13:23:41.594  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.594  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.594  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.594  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:41.594  5853  5853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-27 13:23:41.594  5853  5853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 13:23:41.595  5853  5853 D BluetoothMapService: MAP Service closeService in
09-27 13:23:41.595  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.595  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.595  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.595  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:41.595  5853  5853 D BluetoothMapService: cleanup()
09-27 13:23:41.596  5853  5853 D BluetoothMapService: MAP Service closeService in
09-27 13:23:41.596  5853  5853 V BluetoothAdapterState: isTurningOff()=true
09-27 13:23:41.596  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.596  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:41.596  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:41.598  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 13:23:41.598  5853  5865 D BluetoothAdapterProperties: Setting state to 15
09-27 13:23:41.598  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 13:23:41.599  5853  5865 I BluetoothAdapterState: Entering BleOnState
,09-27 13:23:41.599  3154  3387 D BluetoothMap: onBluetoothStateChange: up=false
,09-27 13:23:41.608  5717  5728 D BluetoothPan: onBluetoothStateChange on: false
,09-27 13:23:41.613  3154  3165 D BluetoothPbap: onBluetoothStateChange: up=false
,09-27 13:23:41.614  5717  5731 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-27 13:23:41.614   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 13:23:41.614  5717  5728 D BluetoothMap: onBluetoothStateChange: up=false
09-27 13:23:41.615   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:41.615  3821  3848 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 13:23:41.615  3154  3166 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 13:23:41.616  5717  5731 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-27 13:23:41.617   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 13:23:41.617  3154  3387 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 13:23:41.617   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:41.617  3154  3165 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:41.618  5717  5728 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 13:23:41.627  3154  3166 D BluetoothPan: onBluetoothStateChange on: false
09-27 13:23:41.628  5717  5731 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 13:23:41.629  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 13:23:41.629  5853  5865 D BluetoothAdapterProperties: Setting state to 16
09-27 13:23:41.629  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 13:23:41.629  5853  5865 D BluetoothAdapterProperties: onBleDisable
09-27 13:23:41.630  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
09-27 13:23:41.630  5853  5866 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 13:23:41.632  5853  5876 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 13:23:41.632  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 13:23:41.632  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.632  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
09-27 13:23:41.633  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.635  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.637  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.637  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 13:23:41.639  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.640  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:41.645  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 13:23:41.648  5717  5717 D DockEventReceiver: finishStartingService: stopping service
,09-27 13:23:41.843  5853  5869 I bt_hci  : shut_down
,09-27 13:23:41.848  5853  5873 D bt_hwcfg: hw_epilog_process
,09-27 13:23:41.849  5853  5873 I bt_vendor: low_power_mode_cb
,09-27 13:23:41.852  5853  5873 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 13:23:41.852  5853  5873 I bt_vendor: epilog_cb
09-27 13:23:41.852  5853  5873 I bt_hci  : epilog_finished_callback
,09-27 13:23:41.860  5853  5869 I bt_hci_h4: hal_close
,09-27 13:23:41.860  5853  5869 I bt_userial_vendor: device fd = 54 close
,09-27 13:23:41.978  5853  5866 D bt_stack_manager: event_shut_down_stack finished.
,09-27 13:23:41.978  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 13:23:41.983  5853  5865 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-27 13:23:41.983  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 13:23:41.984  5853  5853 D BtGatt.GattService: Received stop request...Stopping profile...
,09-27 13:23:41.985  5853  5853 D BtGatt.GattService: stop()
09-27 13:23:41.985  5853  5853 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 13:23:41.988  5853  5853 V BluetoothAdapterState: isTurningOff()=false
,09-27 13:23:41.988  5853  5853 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:41.988  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 13:23:41.988  5853  5853 V BluetoothAdapterState: isBleTurningOff()=true
,09-27 13:23:41.989  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-27 13:23:41.989  5853  5865 D BluetoothAdapterProperties: Setting state to 10
,09-27 13:23:41.990  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 13:23:41.991  5853  5865 I BluetoothAdapterState: Entering OffState
09-27 13:23:41.991   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 13:23:42.004  5853  5853 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 13:23:42.004  5853  5853 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 13:23:42.004  5853  5853 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-27 13:23:42.007  5853  5866 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 13:23:42.012  5853  5853 I art     : System.exit called, status: 0
,09-27 13:23:42.013  5853  5853 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 13:23:42.054   928  3177 I ActivityManager: Process com.android.bluetooth (pid 5853) has died
,09-27 13:23:46.522  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:46.522  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:46.528  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 13:23:46.528  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cee6f9 removed from the list
,09-27 13:23:46.528  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:46.528  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:23:46.528  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:46.531  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:23:46.531  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63c9c9f added. We now have 4 listener(s)
09-27 13:23:46.531  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:23:46.533  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:46.533  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63c9c9f removed from the list
09-27 13:23:46.533  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:23:46.534  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:46.534  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:23:46.535  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:23:46.536  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18151ec added. We now have 4 listener(s)
,09-27 13:23:46.536  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:51.546  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:51.586   928   945 I ActivityManager: Start proc 5910:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 13:23:51.673  5910  5910 D AdapterServiceConfig: Adding HeadsetService
,09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding A2dpService
09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding HidService
09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding HealthService
09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding PanService
09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding GattService
09-27 13:23:51.674  5910  5910 D AdapterServiceConfig: Adding BluetoothMapService
09-27 13:23:51.675  5910  5910 D AdapterServiceConfig: Adding SapService
,09-27 13:23:51.685   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a76d275:true
,09-27 13:23:51.685  5910  5910 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 13:23:51.688  5910  5910 I bt_bluedroid: init
,09-27 13:23:51.688  5910  5922 I BluetoothAdapterState: Entering OffState
,09-27 13:23:51.690  5910  5923 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 13:23:51.690  5910  5923 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 13:23:51.690  5910  5923 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 13:23:51.690  5910  5923 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-27 13:23:51.691  5910  5910 I bt_bluedroid: get_profile_interface socket
,09-27 13:23:51.693  5910  5910 I bt_bluedroid: get_profile_interface sdp
,09-27 13:23:51.693  5910  5926 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 13:23:51.695  5910  5926 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 13:23:51.698  5910  5921 I bt_bluedroid: config_hci_snoop_log
09-27 13:23:51.699   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 13:23:51.703  5910  5922 D BluetoothAdapterState: Current state: OFF, message: 0
09-27 13:23:51.703  5910  5922 D BluetoothAdapterProperties: Setting state to 14
09-27 13:23:51.703  5910  5922 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 13:23:51.704  5910  5922 D BluetoothBondStateMachine: make
,09-27 13:23:51.707  5910  5927 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 13:23:51.709  5910  5922 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:51.710  5910  5910 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 13:23:51.712  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:51.713  5910  5910 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 13:23:51.713  5910  5910 D BtGatt.GattService: Received start request. Starting profile...
09-27 13:23:51.714  5910  5910 D BtGatt.GattService: start()
09-27 13:23:51.714  5910  5910 I bt_bluedroid: get_profile_interface gatt
,09-27 13:23:51.715  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:51.715  5910  5910 D BtGatt.AdvertiseManager: advertise manager created
,09-27 13:23:51.720  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:51.720  5910  5910 V BluetoothAdapterState: isTurningOn()=false
09-27 13:23:51.720  5910  5910 V BluetoothAdapterState: isBleTurningOn()=true
,09-27 13:23:51.720  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:51.721  5910  5922 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 13:23:51.722  5910  5922 I bt_bluedroid: bt_bluedroid
09-27 13:23:51.722  5910  5923 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-27 13:23:51.722  5910  5923 I bt_hci  : start_up
,09-27 13:23:51.727  5910  5923 I bt_vendor: alloc value 0xf41eb871
09-27 13:23:51.727  5910  5923 I bt_vendor: init
09-27 13:23:51.727  5910  5923 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-27 13:23:51.727  5910  5923 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 13:23:51.837  5910  5923 D bt_hci  : start_up starting async portion
09-27 13:23:51.838  5910  5930 I bt_hci  : event_finish_startup
,09-27 13:23:51.838  5910  5930 I bt_hci_h4: hal_open
09-27 13:23:51.838  5910  5930 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-27 13:23:51.837  5931  5931 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 13:23:51.841  5910  5930 I bt_userial_vendor: device fd = 54 open
,09-27 13:23:51.858  5910  5930 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 13:23:51.861  5910  5930 D bt_hwcfg: Chipset BCM4358A3
,09-27 13:23:51.861  5910  5930 D bt_hwcfg: Target name = [BCM4358A3]
09-27 13:23:51.862  5910  5930 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 13:23:52.382  5910  5930 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 13:23:52.383  5910  5930 D bt_hwcfg: Settlement delay -- 100 ms
09-27 13:23:52.383  5910  5930 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 13:23:52.515  5910  5930 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 13:23:52.516  5910  5930 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 13:23:52.517  5910  5930 I bt_hwcfg: vendor lib fwcfg completed
09-27 13:23:52.517  5910  5930 I bt_vendor: firmware callback
09-27 13:23:52.517  5910  5930 I bt_hci  : firmware_config_callback
,09-27 13:23:52.527  5910  5933 I bt_btu  : btu_task pending for preload complete event
09-27 13:23:52.528  5910  5933 I bt_btu_task: Bluetooth chip preload is complete
09-27 13:23:52.528  5910  5933 I bt_btu  : btu_task received preload complete event
,09-27 13:23:52.533  5910  5933 I         : BTE_InitTraceLevels -- TRC_HCI
09-27 13:23:52.533  5910  5933 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 13:23:52.533  5910  5933 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_PAN
,09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 13:23:52.534  5910  5933 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 13:23:52.635  5910  5933 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
09-27 13:23:52.635  5910  5933 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-27 13:23:52.669  5910  5926 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 13:23:52.672  5910  5926 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 13:23:52.673  5910  5926 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 13:23:52.675  5910  5926 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 13:23:52.677  5910  5926 D BluetoothAdapterProperties: Scan Mode:20
,09-27 13:23:52.678  5910  5926 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 13:23:52.678  5910  5926 D bt_hci  : do_postload posting postload work item
09-27 13:23:52.678  5910  5930 I bt_hci  : event_postload
09-27 13:23:52.678  5910  5930 I bt_vendor: sco_config_cb
,09-27 13:23:52.678  5910  5930 I bt_hci  : sco_config_callback postload finished.
,09-27 13:23:52.683  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:52.687  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:52.688  5910  5930 I bt_vendor: low_power_mode_cb
,09-27 13:23:52.689  5910  5926 D bt_bte_conf: Device ID record 1 : primary
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   vendorId            = 000f
,09-27 13:23:52.689  5910  5926 D bt_bte_conf:   vendorIdSource      = 0001
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   product             = 1200
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   version             = 1436
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   clientExecutableURL = 
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   serviceDescription  = 
09-27 13:23:52.689  5910  5926 D bt_bte_conf:   documentationURL    = 
09-27 13:23:52.689  5910  5926 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 13:23:52.690  5910  5923 D bt_stack_manager: event_start_up_stack finished
09-27 13:23:52.691  5910  5922 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 13:23:52.691  5910  5922 D BluetoothAdapterProperties: Setting state to 15
09-27 13:23:52.691  5910  5922 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-27 13:23:52.692  5910  5922 I BluetoothAdapterState: Entering BleOnState
,09-27 13:23:52.696  5910  5922 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 13:23:52.696  5910  5922 D BluetoothAdapterProperties: Setting state to 11
09-27 13:23:52.696  5910  5922 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 13:23:52.706  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:52.707  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:52.707  5910  5910 D HeadsetService: Received start request. Starting profile...
09-27 13:23:52.709  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:52.710  5910  5910 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 13:23:52.711  5910  5910 D HeadsetStateMachine: make
,09-27 13:23:52.719  5910  5922 I BluetoothAdapterState: Entering PendingCommandState
,09-27 13:23:52.721  5910  5910 D HeadsetStateMachine: max_hf_connections = 1
09-27 13:23:52.721  5910  5910 I bt_bluedroid: get_profile_interface handsfree
09-27 13:23:52.721  5910  5926 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 13:23:52.721  5910  5926 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-27 13:23:52.726  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
,09-27 13:23:52.726  5910  5910 D A2dpService: Received start request. Starting profile...
09-27 13:23:52.727  5910  5910 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 13:23:52.727  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 13:23:52.728  5910  5910 I bt_bluedroid: get_profile_interface avrcp
,09-27 13:23:52.734  5910  5910 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-27 13:23:52.734  5910  5910 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 13:23:52.734  5910  5910 D A2dpStateMachine: make
,09-27 13:23:52.735  5910  5910 I bt_bluedroid: get_profile_interface a2dp
,09-27 13:23:52.737  5910  5942 D A2dpStateMachine: Enter Disconnected: -2
,09-27 13:23:52.738  5910  5910 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 13:23:52.738  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:52.739  5910  5910 D HidService: Received start request. Starting profile...
09-27 13:23:52.739  5910  5910 I bt_bluedroid: get_profile_interface hidhost
09-27 13:23:52.739  5910  5910 D HidService: setHidService(): set to: null
09-27 13:23:52.739  5910  5926 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-27 13:23:52.740  5910  5926 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-27 13:23:52.740  5910  5926 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 13:23:52.740  5910  5910 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 13:23:52.741  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:52.741  5910  5910 D HealthService: Received start request. Starting profile...
,09-27 13:23:52.742  5910  5910 I bt_bluedroid: get_profile_interface health
09-27 13:23:52.743  5910  5910 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 13:23:52.744  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:52.745  5910  5910 D PanService: Received start request. Starting profile...
,09-27 13:23:52.745  5910  5910 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 13:23:52.745  5910  5910 I bt_bluedroid: get_profile_interface pan
09-27 13:23:52.746  5910  5926 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-27 13:23:52.747  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:52.748  5910  5910 D BluetoothMapService: Received start request. Starting profile...
09-27 13:23:52.748  5910  5910 D BluetoothMapService: start()
,09-27 13:23:52.751  5910  5910 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-27 13:23:52.752  5910  5910 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 13:23:52.752  5910  5910 D BluetoothMapAppObserver: createReceiver()
,09-27 13:23:52.753  5910  5910 D BluetoothMapAppObserver: initObservers()
09-27 13:23:52.754  5910  5910 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 13:23:52.760  5910  5910 V SapService: SapBinder()
,09-27 13:23:52.760  5910  5910 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:23:52.761  5910  5910 D SapService: Received start request. Starting profile...
09-27 13:23:52.761  5910  5910 V SapService: start()
,09-27 13:23:52.762  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.762  5910  5910 V BluetoothAdapterState: isTurningOn()=true
,09-27 13:23:52.762  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.762  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.763  5910  5940 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOn()=true
,09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.763  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isTurningOff()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isTurningOn()=true
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOn()=false
09-27 13:23:52.764  5910  5910 V BluetoothAdapterState: isBleTurningOff()=false
09-27 13:23:52.765  5910  5922 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 13:23:52.765  5910  5922 D BluetoothAdapterProperties: ScanMode =  20
09-27 13:23:52.765  5910  5922 D BluetoothAdapterProperties: State =  11
,09-27 13:23:52.766  5910  5926 D BluetoothAdapterProperties: Scan Mode:21
,09-27 13:23:52.766  5910  5922 D BluetoothAdapterProperties: Setting state to 12
09-27 13:23:52.766  5910  5922 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 13:23:52.766  5910  5926 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 13:23:52.767  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-27 13:23:52.767  3154  3387 D BluetoothMap: onBluetoothStateChange: up=true
09-27 13:23:52.768  5910  5922 I BluetoothAdapterState: Entering OnState
,09-27 13:23:52.771  3154  3154 D BluetoothMap: Proxy object connected
09-27 13:23:52.771  3154  3154 D MapProfile: Bluetooth service connected
09-27 13:23:52.771  3154  3154 D BluetoothMap: getConnectedDevices()
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:52.772  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:52.773  5717  5728 D BluetoothPan: onBluetoothStateChange on: true
09-27 13:23:52.774  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:52.775  3154  3165 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 13:23:52.777  5717  5717 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 13:23:52.777  5717  5717 D PanProfile: Bluetooth service connected
,09-27 13:23:52.777  5717  5728 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:52.778  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:23:52.779  5910  5910 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-27 13:23:52.779   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 13:23:52.780  5910  5910 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 13:23:52.780  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:23:52.780  5717  5731 D BluetoothMap: onBluetoothStateChange: up=true
09-27 13:23:52.781  5910  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:52.782   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:52.782  3821  3850 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:52.782  3154  3166 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 13:23:52.783  5910  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 13:23:52.784  5717  5728 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 13:23:52.784  5717  5717 D BluetoothMap: Proxy object connected
,09-27 13:23:52.784  5717  5717 D MapProfile: Bluetooth service connected
09-27 13:23:52.784  5717  5717 D BluetoothMap: getConnectedDevices()
09-27 13:23:52.784  5910  5910 D ObexServerSockets: Succeed to create listening sockets 
09-27 13:23:52.785  5910  5910 D ObexServerSockets0: startAccept()
09-27 13:23:52.785  5910  5910 D ObexServerSockets0: prepareForNewConnect()
09-27 13:23:52.787  5910  5910 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 13:23:52.787  5910  5910 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 13:23:52.787   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:52.788  3154  3387 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 13:23:52.788  5910  5948 D ObexServerSockets0: Accepting socket connection...
09-27 13:23:52.789   928   928 D BluetoothA2dp: Proxy object connected
09-27 13:23:52.789  5717  5717 D BluetoothA2dp: Proxy object connected
09-27 13:23:52.789  5910  5949 D ObexServerSockets0: Accepting socket connection...
,09-27 13:23:52.791   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:52.791  3154  3154 D BluetoothA2dp: Proxy object connected
09-27 13:23:52.791  3154  3166 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 13:23:52.792  5717  5728 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 13:23:52.794  3154  3154 D BluetoothInputDevice: Proxy object connected
09-27 13:23:52.794  3154  3154 D HidProfile: Bluetooth service connected
09-27 13:23:52.794  3154  3165 D BluetoothPan: onBluetoothStateChange on: true
,09-27 13:23:52.796  3154  3154 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 13:23:52.796  3154  3154 D PanProfile: Bluetooth service connected
09-27 13:23:52.796  5717  5947 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 13:23:52.801  5717  5717 D BluetoothInputDevice: Proxy object connected
09-27 13:23:52.801  5717  5717 D HidProfile: Bluetooth service connected
,09-27 13:23:52.802  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-27 13:23:52.802  5910  5910 D BluetoothMapService: onReceive
09-27 13:23:52.802  5910  5910 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 13:23:52.802  5910  5910 D BluetoothMapService: STATE_ON
09-27 13:23:52.802   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-27 13:23:52.803  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:23:52.804  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:23:52.807  5910  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:52.808  5910  5951 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 13:23:52.808  5910  5951 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 13:23:52.809  5717  5717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 13:23:52.815  3599  3599 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 13:23:52.817  5717  5717 D DockEventReceiver: finishStartingService: stopping service
,09-27 13:23:52.822  5717  5717 D BluetoothPbap: Proxy object connected
,09-27 13:23:52.822  5717  5717 D PbapServerProfile: Bluetooth service connected
,09-27 13:23:52.828  3154  3154 D BluetoothPbap: Proxy object connected
09-27 13:23:52.828  3154  3154 D PbapServerProfile: Bluetooth service connected
,09-27 13:23:52.829  5910  5910 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 13:23:52.829  5910  5910 D ObexServerSockets0: prepareForNewConnect()
,09-27 13:23:52.830  5910  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:52.844  5910  5959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 13:23:52.845  5910  5959 I BtOppRfcommListener: Accept thread started.
,09-27 13:23:52.884  3154  3166 D BluetoothHeadset: Proxy object connected
,09-27 13:23:52.884   928   928 D BluetoothHeadset: Proxy object connected
09-27 13:23:52.884   928   928 D BluetoothHeadset: Proxy object connected
09-27 13:23:52.884  3154  3154 D HeadsetProfile: Bluetooth service connected
,09-27 13:23:52.885  5717  5728 D BluetoothHeadset: Proxy object connected
,09-27 13:23:52.885  3821  3848 D BluetoothHeadset: Proxy object connected
09-27 13:23:52.885   928   928 D BluetoothHeadset: Proxy object connected
09-27 13:23:52.887  5717  5717 D HeadsetProfile: Bluetooth service connected
09-27 13:23:52.888   928   945 D BluetoothHeadset: Proxy object connected
,09-27 13:23:52.891   928   945 D BluetoothHeadset: Proxy object connected
,09-27 13:23:52.892  3154  3165 D BluetoothHeadset: Proxy object connected
09-27 13:23:52.892  3154  3154 D HeadsetProfile: Bluetooth service connected
,09-27 13:23:52.894  5717  5947 D BluetoothHeadset: Proxy object connected
,09-27 13:23:52.895  5717  5717 D HeadsetProfile: Bluetooth service connected
,09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:23:56.561  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 13:23:56.568  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:23:56.568  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:23:56.569  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18151ec removed from the list
,09-27 13:23:56.569  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:23:56.569  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:23:56.569  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:23:56.571  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 13:23:56.572  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38df9b5 added. We now have 4 listener(s)
09-27 13:23:56.572  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:23:56.575   928  3856 D WifiService: setWifiEnabled: false pid=5664, uid=10077
09-27 13:23:56.575   928  3856 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:23:58.662   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:23:59.663   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:00.665   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:01.585  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:01.586   928  3434 D WifiService: setWifiEnabled: true pid=5664, uid=10077
09-27 13:24:01.586   928  3434 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 13:24:01.597   509   921 D SoftapController: Softap fwReload - Ok
,09-27 13:24:01.602   509   921 D CommandListener: Setting iface cfg
,09-27 13:24:01.603   509   921 D CommandListener: Trying to bring down wlan0
09-27 13:24:01.605   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 13:24:01.611   928  2997 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 13:24:01.666   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:02.266   928  2997 D wifi    : set interface wlan0 flags (UP)
,09-27 13:24:02.267   928  2997 I WifiHAL : Initializing wifi
,09-27 13:24:02.268   928  2997 I WifiHAL : Creating socket
09-27 13:24:02.273   928  2997 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-27 13:24:02.274   928  2997 D wifi    : Did set static halHandle = 0x7f8c3df900
,09-27 13:24:02.274   928  2997 D wifi    : halHandle = 0x7f8c3df900, mVM = 0x7fa4f4d140, mCls = 0x16ce
09-27 13:24:02.274   928  2997 D wifi    : array field set
09-27 13:24:02.274   928  2997 I WifiNative-HAL: interface[0] = wlan0
09-27 13:24:02.275   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-27 13:24:02.277   928  5964 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547813718272
,09-27 13:24:02.277   928  5964 D wifi    : waitForHalEvents called, vm = 0x7fa4f4d140, obj = 0x16ce, env = 0x7f8d83ee80
,09-27 13:24:02.344  5965  5965 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 13:24:02.367  5965  5965 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 13:24:02.380   928  2997 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 13:24:02.387  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:02.393  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:02.397  5965  5965 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 13:24:02.397  5965  5965 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 13:24:02.411   928  2997 D WifiConfigStore: Loading config and enabling all networks 
,09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:24:02.416  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:24:02.418  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 13:24:02.421  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 13:24:02.423   928  2997 D WifiConfigStore: loaded 0 passpoint configs
09-27 13:24:02.423  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 13:24:02.424   928  2997 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 13:24:02.424   928  2997 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 13:24:02.425   928  2997 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 13:24:02.426   928  2997 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 13:24:02.426   928  2997 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-27 13:24:02.426   928  2997 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 13:24:02.427   928  2997 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 13:24:02.431   928  2997 D WifiNative-HAL: Setting external_sim to 1
,09-27 13:24:02.432  5050  5050 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 13:24:02.432   928  2997 D wifi    : setting dfs flag to true, 0x7f8a863980
09-27 13:24:02.432   928  2997 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 13:24:02.433   928  2997 D wifi    : setting scan oui 0x7f8a863980
09-27 13:24:02.433   928  2997 D WifiHAL : Sending mac address OUI
,09-27 13:24:02.438   928  2997 E native  : do suspend false
,09-27 13:24:02.448   928  2997 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 13:24:02.448   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 13:24:02.449   928   928 D RttService: SCAN_AVAILABLE : 3
,09-27 13:24:02.449   928  3107 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 13:24:02.450   509   921 D CommandListener: Setting iface cfg
,09-27 13:24:02.454   928  2994 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-27 13:24:02.454   928  2994 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 13:24:02.464   928  2994 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 13:24:02.470   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303580 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
09-27 13:24:02.470   928  2994 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 13:24:02.667   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:03.668   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 13:24:05.615  5965  5965 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:24:05.620  5965  5965 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:24:05.625  5965  5965 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:24:05.631  5965  5965 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 13:24:05.706   928  2997 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 13:24:05.708   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 13:24:05.709   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 13:24:05.720   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 13:24:05.756   928  2997 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 13:24:05.759  5965  5965 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 13:24:06.184  5965  5965 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 13:24:06.220  5965  5965 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 13:24:06.222  5965  5965 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 13:24:06.236   928  2997 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 13:24:06.236   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-27 13:24:06.237   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 13:24:06.255   928  2997 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 13:24:06.267   509   921 D CommandListener: Setting iface cfg
,09-27 13:24:06.272   928  2997 D WifiStateMachine: Start Dhcp Watchdog 3
,09-27 13:24:06.278   928  5970 D DhcpClient: Receive thread started
,09-27 13:24:06.283   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:24:06.283   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 13:24:06.283   928  2999 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-27 13:24:06.364   928  2997 E native  : do suspend false
,09-27 13:24:06.377   928  5969 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 13:24:06.391   928  5970 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-27 13:24:06.392   928  5969 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-27 13:24:06.395   928  5969 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 13:24:06.408   928  5970 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 13:24:06.409   928  5969 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 13:24:06.413   509   921 D CommandListener: Setting iface cfg
09-27 13:24:06.418   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 13:24:06.421   928  5969 D DhcpClient: Scheduling renewal in 86399s
,09-27 13:24:06.431   928  2997 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 13:24:06.433   928  2997 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 13:24:06.434   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-27 13:24:06.436   928  2999 D ConnectivityService: Adding iface wlan0 to network 102
,09-27 13:24:06.443   928  2997 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 13:24:06.485   928  2999 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 13:24:06.485   928  2999 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-27 13:24:06.486   928  2999 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-27 13:24:06.488   928  2999 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-27 13:24:06.490   928  2999 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-27 13:24:06.496   928  2999 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:24:06.499   928  2999 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-27 13:24:06.500   928  2999 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-27 13:24:06.500   928  2999 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-27 13:24:06.500   928  2999 D ConnectivityService:    accepting network in place of null
09-27 13:24:06.500   928  2997 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 13:24:06.500   928  2997 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 13:24:06.500   928  2999 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 13:24:06.512   928  5968 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307622, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 13:24:06.523   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:24:06.546   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 13:24:06.550   928  2999 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-27 13:24:06.550   928  2999 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 13:24:06.550  3768  3933 W QCNEJ   : |CORE| network available: 102
09-27 13:24:06.551   928  2999 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-27 13:24:06.552   928   945 D Tethering: MasterInitialState.processMessage what=3
09-27 13:24:06.556  3768  3933 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 13:24:06.557  3768  3933 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 13:24:06.557  3768  3933 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:06.561  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:06.564  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:06.568  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:06.571  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:24:06.571  5077  5101 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-27 13:24:06.571  5077  5101 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 13:24:06.571  5077  5101 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 13:24:06.571  5077  5101 E SarControlService: no key has been found,reset the power
09-27 13:24:06.572  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 13:24:06.572  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 13:24:06.572  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 13:24:06.572  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:24:06.572  5102  5102 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 13:24:06.574  5077  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 13:24:06.574  5077  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 13:24:06.574  5077  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 13:24:06.575  4935  4935 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-27 13:24:06.576  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 13:24:06.576  5102  5102 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-27 13:24:06.578  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 13:24:06.579  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000f003000000000000ffffffff]
09-27 13:24:06.579  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 13:24:06.579  5102  5116 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-27 13:24:06.581   928  5967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-27 13:24:06.582  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a8fa2d7 HexData = [00000000f103000000000000ffffffff]
09-27 13:24:06.582  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 13:24:06.582  5102  5116 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-27 13:24:06.583  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:24:06.584  5077  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 13:24:06.584  3732  3732 D SystemUpdateService: onCreate
09-27 13:24:06.585  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 13:24:06.586  5077  5087 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 13:24:06.590  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 13:24:06.600  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:06.603  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:24:06.606  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:06.606  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:06.606  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38df9b5 removed from the list
09-27 13:24:06.606  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:24:06.607  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:06.607  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:24:06.607  3732  5441 I iu.UploadsManager: num queued entries: 0
09-27 13:24:06.608  3732  5441 I iu.UploadsManager: num updated entries: 0
09-27 13:24:06.609  3732  5441 I iu.SyncManager: NEXT; no task
,09-27 13:24:06.610  5664  5984 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-27 13:24:06.610  5664  5984 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-27 13:24:06.611  3732  5980 I SystemUpdateService: active receiver: enabled
,09-27 13:24:06.613  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 13:24:06.615  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 13:24:06.616  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-27 13:24:06.619  5785  5785 D SprintDMHelper: simOperator: 
09-27 13:24:06.619  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 13:24:06.633   928  5967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 17:24:06 GMT], X-Android-Received-Millis=[1474997046632], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474997046606]}
,09-27 13:24:06.633   928  2999 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 13:24:06.633   928  2999 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-27 13:24:06.633   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:24:06.635   928  2999 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-27 13:24:06.642  3732  5980 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 13:24:06.655  3732  5980 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 13:24:06.655  3732  5980 I SystemUpdateService: now status is 0 (complete)
09-27 13:24:06.655  3732  5980 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 13:24:06.655  3732  5980 I SystemUpdateService: file has been verified
09-27 13:24:06.655  3732  5980 I SystemUpdateService: OTA package size = 21989297
,09-27 13:24:06.662  3732  5980 I SystemUpdateService: showing system update notification
,09-27 13:24:06.672  3732  3732 D SystemUpdateService: onDestroy
,09-27 13:24:06.747  5050  5985 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 13:24:09.302   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:24:09.635  5664  5993 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-27 13:24:09.635  5664  5984 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-27 13:24:09.637  5664  5993 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-27 13:24:09.637  5664  5984 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 13:24:09.638  5664  5984 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 13:24:09.638  5664  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 13:24:09.640  5664  5984 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 13:24:09.640  5664  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 13:24:09.643  5664  5984 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-27 13:24:09.645  5664  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.645  5664  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-27 13:24:09.646  5664  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.646  5664  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:09.648  5664  5993 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 13:24:09.649  5664  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.649  5664  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:09.649  5664  5998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.649  5664  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-27 13:24:09.650  5664  5997 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.650  5664  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:09.651  5664  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:09.651  5664  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:09.651  5664  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:09.651  5664  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:09.651  5664  5998 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.651  5664  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-27 13:24:09.652  5664  5996 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: OutgoingSocketThread/Sender): Socket closed
09-27 13:24:09.652  5664  5996 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.652  5664  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 13:24:09.653  5664  5996 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-27 13:24:09.653  5664  5996 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-27 13:24:09.651  5664  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:09.651  5664  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-27 13:24:09.653  5664  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:09.653  5664  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:09.654  5664  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:09.654  5664  5998 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:09.654  5664  5998 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-27 13:24:09.654  5664  5996 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.654  5664  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 13:24:09.654  5664  5998 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 13:24:09.654  5664  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:09.654  5664  5998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.654  5664  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 13:24:09.654  5664  5997 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:09.655  5664  5997 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-27 13:24:09.655  5664  5997 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 13:24:09.655  5664  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:09.655  5664  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 13:24:09.655  5664  5995 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): Socket closed
09-27 13:24:09.656  5664  5995 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.656  5664  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 13:24:09.656  5664  5995 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-27 13:24:09.656  5664  5995 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-27 13:24:09.656  5664  5995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:09.656  5664  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 13:24:12.618  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-27 13:24:12.619  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-27 13:24:12.628  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6883feb Bundle[{}]
,09-27 13:24:12.629  5664  5710 I io.jxcore.node.LifeCycleMonitor: start: OK
09-27 13:24:12.630  5664  5710 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-27 13:24:12.631  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-27 13:24:12.631  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-27 13:24:12.633  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-27 13:24:12.635  5664  5710 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-27 13:24:12.641  5664  5710 I System.out: Running OutgoingSocketThread
,09-27 13:24:12.644  5664  5999 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 13:24:12.644  5664  5999 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 13:24:14.506   928  2999 D ConnectivityService: handlePromptUnvalidated 102
,09-27 13:24:15.654  5664  6000 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-27 13:24:15.654  5664  5999 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-27 13:24:15.654  5664  6000 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 13:24:15.654  5664  5999 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 13:24:15.655  5664  5999 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 13:24:15.655  5664  6000 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 13:24:15.656  5664  5999 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 13:24:15.657  5664  6000 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 13:24:15.660  5664  6002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.660  5664  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-27 13:24:15.662  5664  5999 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 13:24:15.662  5664  6000 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 13:24:15.666  5664  6003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.666  5664  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:15.667  5664  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.667  5664  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-27 13:24:15.668  5664  6005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.668  5664  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-27 13:24:15.669  5664  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:15.669  5664  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-27 13:24:15.669  5664  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:15.669  5664  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:15.669  5664  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.669  5664  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:15.670  5664  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:15.670  5664  6002 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: IncomingSocketThread/Sender): Socket closed
,09-27 13:24:15.670  5664  6005 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:15.670  5664  6005 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-27 13:24:15.670  5664  6002 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.670  5664  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-27 13:24:15.670  5664  6005 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 13:24:15.670  5664  6002 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-27 13:24:15.670  5664  6002 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-27 13:24:15.670  5664  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.670  5664  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 13:24:15.670  5664  6002 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.670  5664  6002 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-27 13:24:15.670  5664  6004 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.670  5664  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:15.670  5664  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:15.670  5664  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:15.670  5664  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-27 13:24:15.671  5664  6004 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-27 13:24:15.671  5664  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 13:24:15.673  5664  6003 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): Socket closed
09-27 13:24:15.673  5664  6003 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.673  5664  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-27 13:24:15.674  5664  6003 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-27 13:24:15.674  5664  6003 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-27 13:24:15.674  5664  6003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-27 13:24:15.674  5664  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-27 13:24:17.466   928  2997 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-27 13:24:18.657  5664  5710 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-27 13:24:18.659  5664  5710 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-27 13:24:18.659  5664  5710 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-27 13:24:18.665  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 13:24:18.666  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c86a84a added. We now have 3 listener(s)
,09-27 13:24:18.668  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 13:24:18.668  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.669  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.669  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.669  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd863bb added. We now have 4 listener(s)
09-27 13:24:18.669  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:24:18.671  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 13:24:18.677  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:18.685  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:18.689  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:24:18.689  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:24:18.689  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.692  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.693  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f17c31 added. We now have 4 listener(s)
09-27 13:24:18.695  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.695  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.695  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.695  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.695  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.695  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68eff16 added. We now have 5 listener(s)
09-27 13:24:18.695  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.696  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:24:18.696  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.696  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:24:18.696  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:24:18.696  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.697  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.697  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.697  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.697  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c86a84a removed from the list
09-27 13:24:18.697  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.697  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd863bb removed from the list
09-27 13:24:18.697  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:24:18.697  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:24:18.698  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.698  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 13:24:18.700  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 13:24:18.700  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.700  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.701  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd863bb not in the list
09-27 13:24:18.701  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.701  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.702  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.702  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.702  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.702  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68eff16 removed from the list
,09-27 13:24:18.702  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.702  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.703  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.703  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.703  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.703  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f17c31 removed from the list
,09-27 13:24:18.704  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.704  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9f8097 added. We now have 3 listener(s)
09-27 13:24:18.706  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.707  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.707  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 13:24:18.707  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.707  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e1f284 added. We now have 4 listener(s)
09-27 13:24:18.707  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:24:18.708  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 13:24:18.713  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:18.718  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:18.721  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:24:18.721  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:24:18.721  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.721  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f3f6a2 added. We now have 4 listener(s)
09-27 13:24:18.724  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.724  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.724  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.724  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.724  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.724  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4518f33 added. We now have 5 listener(s)
09-27 13:24:18.724  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.724  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:18.724  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:24:18.724  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:24:18.724  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:24:18.724  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 13:24:18.726  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:18.728  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 13:24:18.728  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 13:24:18.731  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 13:24:18.731  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:24:18.731  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 13:24:18.734  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 13:24:18.734  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:24:18.734  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-27 13:24:18.734  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:24:18.734  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-27 13:24:18.735  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:24:18.737  5910  5921 D BtGatt.GattService: registerClient() - UUID=cbeefb09-c6fc-4714-83cc-b19fbc56f29d
09-27 13:24:18.739  5910  5926 D BtGatt.GattService: onClientRegistered() - UUID=cbeefb09-c6fc-4714-83cc-b19fbc56f29d, clientIf=5
,09-27 13:24:18.740  5664  5674 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 13:24:18.740  5910  5939 D BtGatt.GattService: start scan with filters
,09-27 13:24:18.745  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 13:24:18.745  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-27 13:24:18.745  5910  5929 D BtGatt.ScanManager: handling starting scan
09-27 13:24:18.745  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.745  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-27 13:24:18.745  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:24:18.745  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:24:18.745  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 13:24:18.747  5910  5929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2268b5c
09-27 13:24:18.747  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:24:18.748  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:24:18.748  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:24:18.749  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 13:24:18.751  5664  5710 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-27 13:24:18.751  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.751  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 13:24:18.751  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.751  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 13:24:18.751  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-27 13:24:18.751  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 13:24:18.751  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:24:18.751  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:24:18.751  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:24:18.752  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:24:18.752  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 13:24:18.753  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:24:18.754  5910  5921 D BtGatt.GattService: stopScan() - queue size =1
09-27 13:24:18.754  5910  5926 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 13:24:18.754  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.754  5910  5939 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:24:18.755  5910  5929 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 13:24:18.755  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-27 13:24:18.755  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 13:24:18.755  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 13:24:18.757  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:24:18.757  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:24:18.757  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-27 13:24:18.757  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-27 13:24:18.757  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 13:24:18.758  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.760  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:24:18.760  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 13:24:18.760  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:24:18.762  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 13:24:18.762  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:18.762  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:24:18.762  5910  5929 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:24:18.762  5910  5929 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 13:24:18.762  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.762  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:24:18.763  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:24:18.763  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.764  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.764  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.764  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.764  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9f8097 removed from the list
,09-27 13:24:18.764  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.764  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e1f284 removed from the list
09-27 13:24:18.764  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:24:18.764  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.765  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.765  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.766  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.766  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.766  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.766  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e1f284 not in the list
09-27 13:24:18.766  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.767  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.767  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.768  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.768  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.768  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4518f33 removed from the list
09-27 13:24:18.768  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.768  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.768  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.768  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.768  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.768  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f3f6a2 removed from the list
09-27 13:24:18.768  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.769  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0beb8f added. We now have 3 listener(s)
09-27 13:24:18.770  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 13:24:18.770  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.770  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.770  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.770  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5730e1c added. We now have 4 listener(s)
09-27 13:24:18.770  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.772  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:24:18.772  5910  5926 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 13:24:18.772  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.774  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:24:18.778  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 13:24:18.778  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:18.778  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:18.780  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:24:18.780  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:24:18.780  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.780  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c41b7fa added. We now have 4 listener(s)
09-27 13:24:18.781  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.782  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.782  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.782  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.782  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@365b1ab added. We now have 5 listener(s)
09-27 13:24:18.782  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.782  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:18.782  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.783  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:18.783  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:24:18.784  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:24:18.784  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:24:18.784  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 13:24:18.785  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 13:24:18.785  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.785  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.786  5910  5929 D BtGatt.ScanManager: stopping BLe Batch
,09-27 13:24:18.787  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 13:24:18.787  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 13:24:18.791  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 13:24:18.792  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 13:24:18.792  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:18.792  5910  5929 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 13:24:18.792  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:24:18.792  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 13:24:18.796  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 13:24:18.796  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:24:18.796  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-27 13:24:18.796  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:24:18.797  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-27 13:24:18.797  5910  5926 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 13:24:18.797  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:24:18.797  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:18.799  5910  5939 D BtGatt.GattService: registerClient() - UUID=3c64b9b0-f0e7-472b-b776-a190c951111d
09-27 13:24:18.799  5910  5926 D BtGatt.GattService: onClientRegistered() - UUID=3c64b9b0-f0e7-472b-b776-a190c951111d, clientIf=5
,09-27 13:24:18.799  5664  5674 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 13:24:18.800  5910  5920 D BtGatt.GattService: start scan with filters
09-27 13:24:18.801  5910  5929 D BtGatt.ScanManager: handling starting scan
,09-27 13:24:18.801  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 13:24:18.802  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 13:24:18.802  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.802  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-27 13:24:18.802  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:24:18.802  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:24:18.802  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 13:24:18.804  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:24:18.804  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:24:18.804  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:24:18.805  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 13:24:18.806  5910  5926 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 13:24:18.807  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.807  5910  5929 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 13:24:18.807  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 13:24:18.807  5664  5710 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-27 13:24:18.807  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:24:18.808  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.808  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:24:18.808  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.808  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.808  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 13:24:18.808  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.808  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.808  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0beb8f removed from the list
09-27 13:24:18.808  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.808  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5730e1c removed from the list
09-27 13:24:18.808  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:24:18.808  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.808  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:24:18.809  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-27 13:24:18.809  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.809  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.810  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5730e1c not in the list
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:24:18.810  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:24:18.810  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:24:18.810  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 13:24:18.811  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:24:18.811  5910  5920 D BtGatt.GattService: stopScan() - queue size =1
09-27 13:24:18.811  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 13:24:18.811  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.811  5910  5921 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 13:24:18.811  5910  5929 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:24:18.811  5910  5929 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:24:18.812  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-27 13:24:18.812  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 13:24:18.812  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 13:24:18.813  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 13:24:18.813  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:24:18.813  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-27 13:24:18.813  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 13:24:18.813  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 13:24:18.814  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.814  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.814  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.814  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.814  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@365b1ab removed from the list
09-27 13:24:18.815  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:24:18.815  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 13:24:18.815  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.815  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:24:18.815  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.815  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.815  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:24:18.815  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.815  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c41b7fa removed from the list
09-27 13:24:18.815  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.815  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74bbd87 added. We now have 3 listener(s)
09-27 13:24:18.817  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.817  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.817  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.817  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.817  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6904b4 added. We now have 4 listener(s)
09-27 13:24:18.817  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 13:24:18.818  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:24:18.820  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 13:24:18.821  5910  5926 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 13:24:18.821  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:18.824  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 13:24:18.827  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 13:24:18.827  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:24:18.827  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 13:24:18.827  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.827  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.827  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ab4c52 added. We now have 4 listener(s)
09-27 13:24:18.828  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.828  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 13:24:18.828  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.828  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.828  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89cab23 added. We now have 5 listener(s)
09-27 13:24:18.828  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.828  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:18.828  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 13:24:18.828  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 13:24:18.829  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:24:18.829  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 13:24:18.829  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:18.831  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.832  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 13:24:18.832  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.833  5910  5929 D BtGatt.ScanManager: stopping BLe Batch
09-27 13:24:18.833  5664  5710 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 13:24:18.833  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 13:24:18.835  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 13:24:18.836  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 13:24:18.837  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 13:24:18.837  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 13:24:18.837  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.837  5910  5929 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 13:24:18.840  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 13:24:18.840  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 13:24:18.840  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-27 13:24:18.840  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 13:24:18.840  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-27 13:24:18.842  5910  5926 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-27 13:24:18.842  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.842  5664  5710 D BluetoothAdapter: STATE_ON
,09-27 13:24:18.845  5910  5920 D BtGatt.GattService: registerClient() - UUID=de787b85-0c2e-4378-bd0e-23afde965f6d
09-27 13:24:18.845  5910  5926 D BtGatt.GattService: onClientRegistered() - UUID=de787b85-0c2e-4378-bd0e-23afde965f6d, clientIf=5
,09-27 13:24:18.845  5664  5765 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 13:24:18.845  5910  5950 D BtGatt.GattService: start scan with filters
,09-27 13:24:18.848  5910  5929 D BtGatt.ScanManager: handling starting scan
,09-27 13:24:18.849  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 13:24:18.849  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 13:24:18.849  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.849  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-27 13:24:18.849  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-27 13:24:18.849  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 13:24:18.849  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 13:24:18.851  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 13:24:18.851  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 13:24:18.851  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 13:24:18.852  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 13:24:18.853  5910  5926 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 13:24:18.853  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.853  5910  5929 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 13:24:18.856  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:24:18.856  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.856  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:24:18.856  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.856  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.856  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 13:24:18.856  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.857  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.857  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74bbd87 removed from the list
09-27 13:24:18.857  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.857  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6904b4 removed from the list
09-27 13:24:18.857  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
09-27 13:24:18.857  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.857  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.857  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-27 13:24:18.857  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:24:18.857  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.858  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 13:24:18.858  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.858  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.858  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.858  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.858  5910  5929 D BtGatt.ScanManager: Starting BLE batch scan
09-27 13:24:18.859  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6904b4 not in the list
09-27 13:24:18.859  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 13:24:18.859  5910  5929 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 13:24:18.859  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 13:24:18.859  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 13:24:18.859  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 13:24:18.859  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 13:24:18.859  5664  5710 D BluetoothAdapter: STATE_ON
09-27 13:24:18.860  5910  5939 D BtGatt.GattService: stopScan() - queue size =1
,09-27 13:24:18.861  5910  5920 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 13:24:18.861  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-27 13:24:18.861  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-27 13:24:18.861  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 13:24:18.863  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:24:18.863  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 13:24:18.863  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-27 13:24:18.863  5664  5710 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 13:24:18.863  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 13:24:18.863  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.864  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.864  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.864  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.864  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89cab23 removed from the list
09-27 13:24:18.864  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.864  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 13:24:18.864  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.865  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.865  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.865  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ab4c52 removed from the list
09-27 13:24:18.865  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:24:18.865  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 13:24:18.865  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 13:24:18.865  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 13:24:18.865  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e84d67f added. We now have 3 listener(s)
09-27 13:24:18.866  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.866  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 13:24:18.867  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.867  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.867  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24364c added. We now have 4 listener(s)
09-27 13:24:18.867  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.867  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 13:24:18.867  5910  5926 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 13:24:18.867  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.869  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 13:24:18.872  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 13:24:18.872  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 13:24:18.873  5664  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 13:24:18.874  5664  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 13:24:18.875  5664  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 13:24:18.875  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 13:24:18.875  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47813aa added. We now have 4 listener(s)
09-27 13:24:18.876  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 13:24:18.876  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 13:24:18.876  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 13:24:18.876  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 13:24:18.876  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9a5b9b added. We now have 5 listener(s)
09-27 13:24:18.876  5664  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 13:24:18.877  5664  5710 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 13:24:18.877  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:18.877  5664  5710 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 13:24:18.877  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 13:24:18.877  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.877  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.877  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 13:24:18.877  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.877  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.877  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e84d67f removed from the list
,09-27 13:24:18.877  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.877  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24364c removed from the list
09-27 13:24:18.877  5910  5926 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 13:24:18.877  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.877  5910  5929 D BtGatt.ScanManager: stopping BLe Batch
09-27 13:24:18.879  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 13:24:18.879  5664  5710 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 13:24:18.879  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.880  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.880  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.881  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.881  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 13:24:18.881  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.881  5664  5710 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d24364c not in the list
09-27 13:24:18.882  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.882  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.882  5910  5926 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 13:24:18.882  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 13:24:18.882  5910  5929 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 13:24:18.883  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 13:24:18.883  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 13:24:18.883  5664  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 13:24:18.883  5664  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9a5b9b removed from the list
09-27 13:24:18.883  5664  5710 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 13:24:18.884  5664  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 13:24:18.884  5664  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 13:24:18.884  5664  5710 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-27 13:24:18.884  5664  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 13:24:18.884  5664  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47813aa removed from the list
,09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-27 13:24:18.885  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 13:24:18.887  5910  5926 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-27 13:24:18.887  5910  5926 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 13:24:19.262  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:24:19.316  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:24:19.365  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 13:24:21.035  5664  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-27 13:24:21.035  5664  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:21.824  5664  6006 W !!      : call onHalfStreamCopied
,09-27 13:24:21.824  5664  6006 I testCopyDataAndClose: closing input stream
,09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-27 13:24:22.598  5664  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-27 13:24:26.394  5664  6007 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:26.394  5664  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:28.394  5664  5710 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-27 13:24:28.394  5664  5710 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:28.394  5664  5710 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-27 13:24:28.507  5664  6007 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-27 13:24:28.507  5664  6007 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:28.507  5664  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-27 13:24:28.533  5664  6008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-27 13:24:28.533  5664  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:28.669   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 13:24:28.669   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-27 13:24:30.135  5664  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-27 13:24:33.886  5664  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.887  5664  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-27 13:24:33.888  5664  5710 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 13:24:33.891  5664  6010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.891  5664  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-27 13:24:33.891  5664  6010 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
09-27 13:24:33.891  5664  6010 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.891  5664  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 13:24:33.891  5664  6010 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-27 13:24:33.892  5664  6010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-27 13:24:33.892  5664  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 13:24:33.895  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-27 13:24:33.895  5664  5710 I jxcore-log: 
09-27 13:24:33.895  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Number of passed tests:  83'
09-27 13:24:33.895  5664  5710 I jxcore-log: 
09-27 13:24:33.896  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Number of failed tests:  1'
09-27 13:24:33.896  5664  5710 I jxcore-log: 
09-27 13:24:33.896  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-27 13:24:33.896  5664  5710 I jxcore-log: 
09-27 13:24:33.896  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Total duration:  102798'
09-27 13:24:33.896  5664  5710 I jxcore-log: 
,09-27 13:24:33.897  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Failures: 
09-27 13:24:33.897  5664  5710 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-27 13:24:33.897  5664  5710 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-27 13:24:33.897  5664  5710 I jxcore-log:      but: was ""
09-27 13:24:33.897  5664  5710 I jxcore-log: '
09-27 13:24:33.897  5664  5710 I jxcore-log: 
09-27 13:24:33.898  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-27 13:24:33.898  5664  5710 I jxcore-log: 
,09-27 13:24:33.899  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-27 13:24:33.899  5664  5710 I jxcore-log: 
,09-27 13:24:33.902  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.902  5664  5710 I jxcore-log: 
09-27 13:24:33.903  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.903  5664  5710 I jxcore-log: 
,09-27 13:24:33.903  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.903  5664  5710 I jxcore-log: 
09-27 13:24:33.904  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.904  5664  5710 I jxcore-log: 
09-27 13:24:33.904  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 13:24:33.904  5664  5710 I jxcore-log: 
,09-27 13:24:33.904  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.904  5664  5710 I jxcore-log: 
09-27 13:24:33.905  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.905  5664  5710 I jxcore-log: 
09-27 13:24:33.905  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.905  5664  5710 I jxcore-log: 
09-27 13:24:33.905  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 13:24:33.905  5664  5710 I jxcore-log: 
09-27 13:24:33.905  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.905  5664  5710 I jxcore-log: 
,09-27 13:24:33.906  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.906  5664  5710 I jxcore-log: 
09-27 13:24:33.906  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.906  5664  5710 I jxcore-log: 
09-27 13:24:33.906  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.906  5664  5710 I jxcore-log: 
09-27 13:24:33.906  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.906  5664  5710 I jxcore-log: 
09-27 13:24:33.907  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.907  5664  5710 I jxcore-log: 
,09-27 13:24:33.907  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.907  5664  5710 I jxcore-log: 
09-27 13:24:33.907  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.907  5664  5710 I jxcore-log: 
09-27 13:24:33.908  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.908  5664  5710 I jxcore-log: 
09-27 13:24:33.908  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.908  5664  5710 I jxcore-log: 
09-27 13:24:33.908  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.908  5664  5710 I jxcore-log: 
09-27 13:24:33.908  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.908  5664  5710 I jxcore-log: 
09-27 13:24:33.909  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.909  5664  5710 I jxcore-log: 
09-27 13:24:33.911  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.911  5664  5710 I jxcore-log: 
09-27 13:24:33.911  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.911  5664  5710 I jxcore-log: 
09-27 13:24:33.911  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.911  5664  5710 I jxcore-log: 
09-27 13:24:33.912  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.912  5664  5710 I jxcore-log: 
09-27 13:24:33.912  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.912  5664  5710 I jxcore-log: 
09-27 13:24:33.912  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.912  5664  5710 I jxcore-log: 
09-27 13:24:33.912  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.912  5664  5710 I jxcore-log: 
09-27 13:24:33.912  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.912  5664  5710 I jxcore-log: 
09-27 13:24:33.913  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.913  5664  5710 I jxcore-log: 
09-27 13:24:33.913  5664  5710 I jxcore-log,: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.913  5664  5710 I jxcore-log: 
09-27 13:24:33.913  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.913  5664  5710 I jxcore-log: 
09-27 13:24:33.914  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.914  5664  5710 I jxcore-log: 
09-27 13:24:33.914  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.914  5664  5710 I jxcore-log: 
09-27 13:24:33.914  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.914  5664  5710 I jxcore-log: 
09-27 13:24:33.914  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.914  5664  5710 I jxcore-log: 
09-27 13:24:33.914  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.914  5664  5710 I jxcore-log: 
09-27 13:24:33.915  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 13:24:33.915  5664  5710 I jxcore-log: 
09-27 13:24:33.915  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.915  5664  5710 I jxcore-log: 
09-27 13:24:33.915  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 13:24:33.915  5664  5710 I jxcore-log: 
09-27 13:24:33.915  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.915  5664  5710 I jxcore-log: 
09-27 13:24:33.916  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.916  5664  5710 I jxcore-log: 
09-27 13:24:33.916  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.916  5664  5710 I jxcore-log: 
09-27 13:24:33.916  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.916  5664  5710 I jxcore-log: 
09-27 13:24:33.916  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.916  5664  5710 I jxcore-log: 
09-27 13:24:33.917  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 13:24:33.917  5664  5710 D io.jxcore.node.StartStopOperat,ionHandler: Operation timeout, state error: null
09-27 13:24:33.917  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.917  5664  5710 I jxcore-log: 
09-27 13:24:33.917  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.917  5664  5710 I jxcore-log: 
09-27 13:24:33.917  5664  5710 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 13:24:33.917  5664  5710 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-27 13:24:33.917  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 13:24:33.917  5664  5710 I jxcore-log: 
09-27 13:24:33.918  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.918  5664  5710 I jxcore-log: 
09-27 13:24:33.918  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.918  5664  5710 I jxcore-log: 
09-27 13:24:33.919  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 13:24:33.919  5664  5710 I jxcore-log: 
09-27 13:24:33.921  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-27 13:24:33.921  5664  5710 I jxcore-log: 
09-27 13:24:33.921  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - WARN testUtils: 'myNameCallback not set!'
09-27 13:24:33.921  5664  5710 I jxcore-log: 
09-27 13:24:33.921  5664  5710 I jxcore-log: 2016-09-27 17:24:33 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-27 13:24:33.921  5664  5710 I jxcore-log: 
09-27 13:24:33.928  5664  5664 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-27 13:24:35.917  5664  5710 I jxcore-log: 2016-09-27 17:24:35 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-27 13:24:35.917  5664  5710 I jxcore-log: 
,09-27 13:24:36.235  5664  5710 I jxcore-log: 2016-09-27 17:24:36 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-27 13:24:36.235  5664  5710 I jxcore-log: 
,09-27 13:24:36.247  5664  5710 I jxcore-log: 2016-09-27 17:24:36 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-27 13:24:36.247  5664  5710 I jxcore-log: 
,09-27 13:24:37.340  5664  5710 I jxcore-log: 2016-09-27 17:24:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-27 13:24:37.340  5664  5710 I jxcore-log: 
,09-27 13:24:37.486  5664  5710 I jxcore-log: 2016-09-27 17:24:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-27 13:24:37.486  5664  5710 I jxcore-log: 
,09-27 13:24:37.491  5664  5710 I jxcore-log: 2016-09-27 17:24:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-27 13:24:37.491  5664  5710 I jxcore-log: 
,09-27 13:24:37.496  5664  5710 I jxcore-log: 2016-09-27 17:24:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-27 13:24:37.496  5664  5710 I jxcore-log: 
,09-27 13:24:38.020  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-27 13:24:38.020  5664  5710 I jxcore-log: 
,09-27 13:24:38.069  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-27 13:24:38.069  5664  5710 I jxcore-log: 
,09-27 13:24:38.081  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-27 13:24:38.081  5664  5710 I jxcore-log: 
,09-27 13:24:38.092  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-27 13:24:38.092  5664  5710 I jxcore-log: 
,09-27 13:24:38.348  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-27 13:24:38.348  5664  5710 I jxcore-log: 
,09-27 13:24:38.466  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-27 13:24:38.466  5664  5710 I jxcore-log: 
,09-27 13:24:38.689  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-27 13:24:38.689  5664  5710 I jxcore-log: 
,09-27 13:24:38.698  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-27 13:24:38.698  5664  5710 I jxcore-log: 
,09-27 13:24:38.702  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-27 13:24:38.702  5664  5710 I jxcore-log: 
,09-27 13:24:38.708  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-27 13:24:38.708  5664  5710 I jxcore-log: 
,09-27 13:24:38.713  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-27 13:24:38.713  5664  5710 I jxcore-log: 
,09-27 13:24:38.740  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-27 13:24:38.740  5664  5710 I jxcore-log: 
,09-27 13:24:38.775  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-27 13:24:38.775  5664  5710 I jxcore-log: 
,09-27 13:24:38.781  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-27 13:24:38.781  5664  5710 I jxcore-log: 
,09-27 13:24:38.788  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-27 13:24:38.788  5664  5710 I jxcore-log: 
,09-27 13:24:38.803  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-27 13:24:38.803  5664  5710 I jxcore-log: 
,09-27 13:24:38.807  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-27 13:24:38.807  5664  5710 I jxcore-log: 
,09-27 13:24:38.814  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-27 13:24:38.814  5664  5710 I jxcore-log: 
,09-27 13:24:38.826  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-27 13:24:38.826  5664  5710 I jxcore-log: 
,09-27 13:24:38.847  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-27 13:24:38.847  5664  5710 I jxcore-log: 
,09-27 13:24:38.856  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-27 13:24:38.856  5664  5710 I jxcore-log: 
,09-27 13:24:38.866  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-27 13:24:38.866  5664  5710 I jxcore-log: 
,09-27 13:24:38.876  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-27 13:24:38.876  5664  5710 I jxcore-log: 
,09-27 13:24:38.887  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-27 13:24:38.887  5664  5710 I jxcore-log: 
,09-27 13:24:38.897  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-27 13:24:38.897  5664  5710 I jxcore-log: 
,09-27 13:24:38.902  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-27 13:24:38.902  5664  5710 I jxcore-log: 
,09-27 13:24:38.921  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-27 13:24:38.921  5664  5710 I jxcore-log: 
,09-27 13:24:38.929  5664  5710 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-27 13:24:38.930  5664  5710 I jxcore-log: 2016-09-27 17:24:38 - INFO testUtils: 'BLE multiple advertisement supported'
09-27 13:24:38.930  5664  5710 I jxcore-log: 
,09-27 13:24:39.182  5664  5710 I jxcore-log: 2016-09-27 17:24:39 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:24:39.182  5664  5710 I jxcore-log: 
,09-27 13:24:43.670   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:44.671   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:45.672   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:46.454   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:24:46.674   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:47.675   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:48.676   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 13:24:53.677   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:54.679   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:55.680   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:56.681   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:57.682   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:24:58.683   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 13:25:08.684   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:09.686   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:10.687   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:11.688   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:12.690   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:13.690   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 13:25:26.458   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:25:28.691   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:29.692   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:30.694   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:31.695   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:32.696   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:33.697   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 13:25:46.459   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:25:53.698   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:54.700   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:55.702   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:56.703   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:57.705   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:25:58.706   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 13:26:16.371   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:26:19.383   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:26:23.707   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 13:26:23.707   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 13:26:26.464   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:26:43.708   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:44.710   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:45.711   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:46.466   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:26:46.712   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:47.714   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:48.714   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 13:26:53.715   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:54.717   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:55.718   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:56.719   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:57.720   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:26:58.721   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 13:27:06.468   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:27:08.723   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:09.724   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:10.726   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:11.727   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:12.728   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:13.729   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 13:27:13.882   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:27:16.910   928  2999 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 13:27:28.731   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:29.732   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:30.733   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:31.735   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:32.736   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 13:27:33.518  5664  5710 I jxcore-log: 2016-09-27 17:27:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-27 13:27:33.518  5664  5710 I jxcore-log: 
,09-27 13:27:33.736   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 13:27:33.802  5664  5710 I jxcore-log: 2016-09-27 17:27:33 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:33.802  5664  5710 I jxcore-log: 
,09-27 13:27:33.814  5664  5710 I jxcore-log: 2016-09-27 17:27:33 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:33.814  5664  5710 I jxcore-log: 
,09-27 13:27:34.278  5664  5710 I jxcore-log: 2016-09-27 17:27:34 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:34.278  5664  5710 I jxcore-log: 
,09-27 13:27:34.288  5664  5710 I jxcore-log: 2016-09-27 17:27:34 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:34.288  5664  5710 I jxcore-log: 
,09-27 13:27:34.774  5664  5710 I jxcore-log: 2016-09-27 17:27:34 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:34.774  5664  5710 I jxcore-log: 
,09-27 13:27:34.782  5664  5710 I jxcore-log: 2016-09-27 17:27:34 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:34.782  5664  5710 I jxcore-log: 
,09-27 13:27:35.825  5664  5710 I jxcore-log: 2016-09-27 17:27:35 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:35.825  5664  5710 I jxcore-log: 
,09-27 13:27:35.837  5664  5710 I jxcore-log: 2016-09-27 17:27:35 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:35.837  5664  5710 I jxcore-log: 
,09-27 13:27:36.884  5664  5710 I jxcore-log: 2016-09-27 17:27:36 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:36.884  5664  5710 I jxcore-log: 
09-27 13:27:36.892  5664  5710 I jxcore-log: 2016-09-27 17:27:36 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:36.892  5664  5710 I jxcore-log: 
,09-27 13:27:37.929  5664  5710 I jxcore-log: 2016-09-27 17:27:37 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:37.929  5664  5710 I jxcore-log: 
,09-27 13:27:37.938  5664  5710 I jxcore-log: 2016-09-27 17:27:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:37.938  5664  5710 I jxcore-log: 
,09-27 13:27:38.977  5664  5710 I jxcore-log: 2016-09-27 17:27:38 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:38.977  5664  5710 I jxcore-log: 
,09-27 13:27:38.985  5664  5710 I jxcore-log: 2016-09-27 17:27:38 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:38.985  5664  5710 I jxcore-log: 
,09-27 13:27:40.022  5664  5710 I jxcore-log: 2016-09-27 17:27:40 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:40.022  5664  5710 I jxcore-log: 
,09-27 13:27:40.031  5664  5710 I jxcore-log: 2016-09-27 17:27:40 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:40.031  5664  5710 I jxcore-log: 
,09-27 13:27:41.072  5664  5710 I jxcore-log: 2016-09-27 17:27:41 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:41.072  5664  5710 I jxcore-log: 
,09-27 13:27:41.083  5664  5710 I jxcore-log: 2016-09-27 17:27:41 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:41.083  5664  5710 I jxcore-log: 
,09-27 13:27:42.151  5664  5710 I jxcore-log: 2016-09-27 17:27:42 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:42.151  5664  5710 I jxcore-log: 
,09-27 13:27:42.160  5664  5710 I jxcore-log: 2016-09-27 17:27:42 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:42.160  5664  5710 I jxcore-log: 
,09-27 13:27:43.197  5664  5710 I jxcore-log: 2016-09-27 17:27:43 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:43.197  5664  5710 I jxcore-log: 
,09-27 13:27:43.204  5664  5710 I jxcore-log: 2016-09-27 17:27:43 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:43.204  5664  5710 I jxcore-log: 
,09-27 13:27:43.954   928  5968 D NetlinkSocketObserver: NeighborEvent{elapsedMs=525064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 13:27:44.237  5664  5710 I jxcore-log: 2016-09-27 17:27:44 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:44.237  5664  5710 I jxcore-log: 
,09-27 13:27:44.244  5664  5710 I jxcore-log: 2016-09-27 17:27:44 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:44.244  5664  5710 I jxcore-log: 
,09-27 13:27:45.288  5664  5710 I jxcore-log: 2016-09-27 17:27:45 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:45.288  5664  5710 I jxcore-log: 
,09-27 13:27:45.295  5664  5710 I jxcore-log: 2016-09-27 17:27:45 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:45.295  5664  5710 I jxcore-log: 
,09-27 13:27:46.329  5664  5710 I jxcore-log: 2016-09-27 17:27:46 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:46.329  5664  5710 I jxcore-log: 
,09-27 13:27:46.337  5664  5710 I jxcore-log: 2016-09-27 17:27:46 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:46.337  5664  5710 I jxcore-log: 
,09-27 13:27:46.472   928  2997 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 13:27:47.371  5664  5710 I jxcore-log: 2016-09-27 17:27:47 - DEBUG CoordinatedClient: 'connected to the test server'
09-27 13:27:47.371  5664  5710 I jxcore-log: 
,09-27 13:27:47.381  5664  5710 I jxcore-log: 2016-09-27 17:27:47 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-27 13:27:47.381  5664  5710 I jxcore-log: 
,09-27 13:27:49.234   928  5968 D NetlinkSocketObserver: NeighborEvent{elapsedMs=530344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}

```
