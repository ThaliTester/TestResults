#### Test 87966432114c2fe_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-05 05:49:37.774   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 05:49:37.775   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-05 05:49:38.241  5612  5612 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-05 05:49:38.247  5612  5612 D AndroidRuntime: CheckJNI is OFF
10-05 05:49:38.275  5612  5612 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-05 05:49:38.313  5612  5612 I Radio-JNI: register_android_hardware_Radio DONE
10-05 05:49:38.330  5612  5612 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-05 05:49:38.337   930  3115 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-05 05:49:38.384   930  3115 I ActivityManager: Start proc 5621:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-05 05:49:38.402  5612  5612 D AndroidRuntime: Shutting down VM
,10-05 05:49:38.731   930  3870 I WindowManager: Screenshot max retries 4 of Token{5681ea7 ActivityRecord{b5e0b66 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{139213e u0 Starting com.test.thalitest} drawState=2
,10-05 05:49:38.797  5621  5621 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-05 05:49:38.834  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-05 05:49:38.856  5621  5621 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 485-503)
,10-05 05:49:38.856  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-05 05:49:38.876  5621  5621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dee140}
,10-05 05:49:38.876  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-05 05:49:38.876  5621  5621 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-05 05:49:38.882  5621  5621 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-05 05:49:38.884  5621  5621 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-05 05:49:38.918  5621  5621 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-05 05:49:38.938  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-05 05:49:38.938  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-05 05:49:38.938  5621  5621 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-05 05:49:38.938  5621  5621 I Adreno  : Build Date                       : 12/06/15
10-05 05:49:38.938  5621  5621 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-05 05:49:38.938  5621  5621 I Adreno  : Local Branch                     : mybranch17112971
10-05 05:49:38.938  5621  5621 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-05 05:49:38.938  5621  5621 I Adreno  : Remote Branch                    : NONE
10-05 05:49:38.938  5621  5621 I Adreno  : Reconstruct Branch               : NOTHING
,10-05 05:49:38.979   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@deac16d:true
,10-05 05:49:39.010   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21209]" dev="sockfs" ino=21209 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 05:49:39.010   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[21209]" dev="sockfs" ino=21209 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 05:49:39.024  5621  5621 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-05 05:49:39.032  5621  5621 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-05 05:49:39.056  5621  5658 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-05 05:49:39.050   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31165]" dev="sockfs" ino=31165 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-05 05:49:39.050   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31165]" dev="sockfs" ino=31165 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 05:49:39.053  3849  3849 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14246]" dev="sockfs" ino=14246 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 05:49:39.053  3849  3849 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14246]" dev="sockfs" ino=14246 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 05:49:39.061  5621  5645 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-05 05:49:39.082  5621  5658 I OpenGLRenderer: Initialized EGL, version 1.4
,10-05 05:49:39.152   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +417ms (total +799ms)
,10-05 05:49:39.193  5621  5621 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5621
,10-05 05:49:39.255   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:49:39.277  5621  5621 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-05 05:49:39.413  5621  5660 D jxcore_app_log: JniHelper::setJavaVM(0xf55bc000), pthread_self() = -576194256
,10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-05 05:49:39.417  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4822371 added. We now have 1 listener(s)
,10-05 05:49:39.419  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-05 05:49:39.419  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 05:49:39.420  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 05:49:39.420  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-05 05:49:39.422  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73b32c4 added. We now have 1 listener(s)
10-05 05:49:39.422  5621  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:49:39.427   930  2963 D WifiService: New client listening to asynchronous messages
,10-05 05:49:39.433  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 05:49:39.433  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-05 05:49:39.434  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-05 05:49:39.434  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-05 05:49:39.434  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-05 05:49:39.436  5621  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:49:39.436  5621  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-05 05:49:39.440  5621  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:49:39.440  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:49:39.440  5621  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-05 05:49:39.441  5621  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:49:39.441  5621  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-05 05:49:39.444  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:39.447  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:39.456  5621  5621 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-05 05:49:39.764  5621  5668 W jxcore-log: Initializing JXcore engine
,10-05 05:49:39.764  5621  5668 W jxcore-log: JXcore engine is ready
,10-05 05:49:39.786  5668  5668 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12358 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-05 05:49:39.786  5668  5668 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14439]" dev="sockfs" ino=14439 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-05 05:49:39.786  5668  5668 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-05 05:49:39.786  5668  5668 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32322]" dev="sockfs" ino=32322 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-05 05:49:39.797  5621  5668 W jxcore-log: Starting JXcore engine
,10-05 05:49:39.856  5621  5668 W jxcore-log: Platform android
10-05 05:49:39.856  5621  5668 W jxcore-log: 
10-05 05:49:39.856  5621  5668 W jxcore-log: Process ARCH arm
10-05 05:49:39.856  5621  5668 W jxcore-log: 
,10-05 05:49:39.954  5621  5668 I jxcore-log: JXcore Cordova bridge is ready!
10-05 05:49:39.954  5621  5668 I jxcore-log: 
,10-05 05:49:39.954  5621  5668 W jxcore-log: JXcore engine is started
,10-05 05:49:39.966  5621  5660 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-05 05:49:39.974  5621  5621 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-05 05:49:40.615   930  2962 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 05:49:42.275   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:49:47.776   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:48.777   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:49.672  5621  5668 I jxcore-log: 2016-10-05 09:49:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-05 05:49:49.672  5621  5668 I jxcore-log: 
,10-05 05:49:49.674  5621  5668 I jxcore-log: 2016-10-05 09:49:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-05 05:49:49.674  5621  5668 I jxcore-log: 
,10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:49:49.678  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:49:49.679  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:49:49.681  5621  5668 I jxcore-log: 2016-10-05 09:49:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-05 05:49:49.681  5621  5668 I jxcore-log: 
,10-05 05:49:49.683  5621  5668 I jxcore-log: 2016-10-05 09:49:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-05 05:49:49.683  5621  5668 I jxcore-log: 
,10-05 05:49:49.778   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:49.931  5621  5668 I jxcore-log: 2016-10-05 09:49:49 - DEBUG UnitTest_app: 'Running unit tests'
10-05 05:49:49.931  5621  5668 I jxcore-log: 
,10-05 05:49:49.932  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 05:49:49.932  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71a5ce added. We now have 2 listener(s)
,10-05 05:49:49.933  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 05:49:49.933  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 05:49:49.933  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:49:49.933  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 05:49:49.933  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3c8cef added. We now have 2 listener(s)
,10-05 05:49:49.933  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:49:49.934  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 05:49:49.936  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:49:49.938  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:49:49.939  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:49.940  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:49:49.940  5621  5668 D executeNativeTests: Running unit tests
,10-05 05:49:49.946  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:49.952  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:49.977  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 05:49:49.977  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 added. We now have 3 listener(s)
,10-05 05:49:49.977  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 05:49:49.977  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:49:49.977  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:49:49.977  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:49:49.978  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a added. We now have 3 listener(s)
,10-05 05:49:49.978  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:49:49.978  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 05:49:49.979  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:49:49.982  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:49:49.983  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:49.983  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:49:49.984  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 05:49:49.984  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-05 05:49:49.984  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:49:49.984  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:49:49.985  5621  5668 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-05 05:49:49.985  5621  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-05 05:49:49.985  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 05:49:49.985  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:49:49.985  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:49:49.985  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:49:49.985  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:49:49.985  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:49:49.985  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:49:49.986  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:49:49.986  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:49.986  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:49:49.986  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:49:49.986  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 05:49:49.986  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 removed from the list
10-05 05:49:49.986  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:49.987  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a removed from the list
,10-05 05:49:49.992  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:49.999  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:49:50.000  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:49:50.000  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:49:50.001  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.001  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.001  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 05:49:50.001  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:49:50.001  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:50.001  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:50.002  5621  5668 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-05 05:49:50.002  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:49:50.002  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:49:50.002  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:49:50.003  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:49:50.003  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.003  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:49:50.003  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:49:50.003  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:49:50.003  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:50.003  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:50.003  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 05:49:50.003  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.003  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.003  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.003  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.003  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:49:50.003  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 05:49:50.003  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:50.003  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-05 05:49:50.006  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 05:49:50.007  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:49:50.007  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:49:50.007  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:49:50.007  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:49:50.007  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.007  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.007  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:49:50.007  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:49:50.007  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:50.007  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:50.007  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:49:50.007  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.007  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.007  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:50.007  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:50.008  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:49:50.008  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:49:50.008  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:50.008  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:50.008  5621  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 05:49:50.009  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:49:50.014  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:49:50.017  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:49:50.017  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:49:50.017  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Shoul,d affect listening to advertisements only
10-05 05:49:50.017  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 05:49:50.017  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 05:49:50.017  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:49:50.017  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 05:49:50.019  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 05:49:50.019  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 05:49:50.022  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:49:50.024  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:49:50.024  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 05:49:50.025  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:49:50.026  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 05:49:50.027  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-05 05:49:50.028  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-05 05:49:50.028  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 05:49:50.028  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 05:49:50.028  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:49:50.028  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 05:49:50.028  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:49:50.028  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:49:50.031  4590  4603 D BtGatt.GattService: registerClient() - UUID=4bec8c45-ef01-4b28-8dee-cfdfb2345c62
10-05 05:49:50.031  4590  4665 D BtGatt.GattService: onClientRegistered() - UUID=4bec8c45-ef01-4b28-8dee-cfdfb2345c62, clientIf=5
10-05 05:49:50.033  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 05:49:50.034  4590  4814 D BtGatt.GattService: start scan with filters
10-05 05:49:50.040  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 05:49:50.040  4590  4670 D BtGatt.ScanManager: handling starting scan
10-05 05:49:50.040  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 05:49:50.040  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:49:50.040  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 05:49:50.040  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:49:50.040  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:49:50.040  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 05:49:50.042  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:49:50.042  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:49:50.042  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:49:50.042  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:49:50.044  4590  4670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:49:50.046  5621  5668 I io.jxcore.node.ConnectionHelper: start: OK
10-05 05:49:50.051  4590  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:49:50.051  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:50.052  4590  4670 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 05:49:50.058  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 05:49:50.058  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:50.058  4590  4670 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:49:50.058  4590  4670 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 05:49:50.068  4590  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 05:49:50.068  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:50.074  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 05:49:50.074  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:49:50.544  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 05:49:50.544  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 05:49:50.544  5621  5621 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 05:49:50.779   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:51.353   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:49:51.780   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:52.781   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 05:49:55.050  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 05:49:55.050  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 05:49:55.051  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 05:49:55.051  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:49:55.051  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 05:49:55.051  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:49:55.051  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 05:49:55.051  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:49:55.051  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:49:55.051  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 05:49:55.052  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 05:49:55.052  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:49:55.053  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:49:55.054  4590  4604 D BtGatt.GattService: stopScan() - queue size =1
10-05 05:49:55.055  4590  4835 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 05:49:55.055  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:49:55.056  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:49:55.056  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:49:55.056  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-05 05:49:55.056  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 05:49:55.056  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-05 05:49:55.056  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:49:55.056  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 05:49:55.057  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:49:55.058  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 05:49:55.058  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 05:49:55.058  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-05 05:49:55.058  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 05:49:55.059  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:49:55.060  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:49:55.061  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:49:55.061  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:49:55.061  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:49:55.061  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:49:55.061  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:49:55.061  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:49:55.061  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:49:55.061  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 05:49:55.061  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:49:55.061  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:49:55.061  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:49:55.064  4590  4590 D BtGatt.ScanManager: awakened up at time 236711
,10-05 05:49:55.070  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:49:55.071  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:55.071  4590  4670 D BtGatt.ScanManager: stopping BLe Batch
,10-05 05:49:55.081  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 05:49:55.081  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:55.081  4590  4670 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 05:49:55.105  4590  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
10-05 05:49:55.105  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:49:55.106  4590  4665 D BtGatt.GattService: current time is 236753495420
,10-05 05:49:55.106  4590  4665 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -84, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -32, 42, -45, -103, -54, 90, 1, -128, -96, 48, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 71, -122, -77, 84, 69, -12, 1, -128, -90, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -85, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-05 05:49:55.108  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 05:49:55.109  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 05:49:55.109  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-05 05:49:55.109  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
10-05 05:49:55.109  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-05 05:49:55.110  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 05:49:55.110  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-05 05:49:55.563  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 05:49:57.391   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:49:57.782   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:58.784   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:49:59.785   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:00.064  5621  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-05 05:50:00.068  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:00.075  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:50:00.080  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:50:00.081  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:50:00.081  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:50:00.081  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-05 05:50:00.081  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-05 05:50:00.081  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:50:00.081  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 05:50:00.085  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 05:50:00.085  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 05:50:00.086  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:00.089  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:00.089  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 05:50:00.090  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:50:00.090  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 05:50:00.093  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 05:50:00.093  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 05:50:00.093  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:50:00.093  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-05 05:50:00.093  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:50:00.094  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:50:00.095  4590  4603 D BtGatt.GattService: registerClient() - UUID=f5daac1d-d6b8-4c9c-880d-08ad6139537a
10-05 05:50:00.096  4590  4665 D BtGatt.GattService: onClientRegistered() - UUID=f5daac1d-d6b8-4c9c-880d-08ad6139537a, clientIf=5
10-05 05:50:00.096  5621  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 05:50:00.097  4590  4604 D BtGatt.GattService: start scan with filters
10-05 05:50:00.099  4590  4670 D BtGatt.ScanManager: handling starting scan
,10-05 05:50:00.099  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-05 05:50:00.099  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 05:50:00.099  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:50:00.099  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 05:50:00.099  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:50:00.099  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:50:00.099  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 05:50:00.101  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:50:00.101  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:50:00.101  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:50:00.103  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:50:00.106  5621  5668 I io.jxcore.node.ConnectionHelper: start: OK
10-05 05:50:00.107  4590  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:50:00.107  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.107  4590  4670 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 05:50:00.108  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:00.108  5621  5668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 05:50:00.108  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:00.108  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 05:50:00.108  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:00.108  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-05 05:50:00.108  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:00.109  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 05:50:00.109  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:50:00.109  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:50:00.109  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 05:50:00.109  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 05:50:00.109  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:50:00.109  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:50:00.110  4590  4835 D BtGatt.GattService: stopScan() - queue size =1
10-05 05:50:00.110  4590  4834 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:50:00.111  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 05:50:00.111  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:50:00.111  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 05:50:00.112  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:00.112  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 05:50:00.112  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 05:50:00.113  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-05 05:50:00.113  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 05:50:00.113  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 05:50:00.113  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.113  4590  4670 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:50:00.113  4590  4670 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 05:50:00.113  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:50:00.115  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:00.115  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:50:00.115  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:00.115  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:50:00.115  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:50:00.115  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:00.115  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:00.115  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:00.115  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:00.115  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:00.115  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:00.116  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:00.116  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:00.116  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:00.117  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:00.117  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:00.117  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:00.118  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:00.118  5621  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 05:50:00.120  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:50:00.125  4590  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 05:50:00.125  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:00.126  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:50:00.128  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:00.128  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:50:00.128  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:50:00.128  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 05:50:00.129  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 05:50:00.129  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:50:00.129  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 05:50:00.130  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 05:50:00.131  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.131  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:00.132  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 05:50:00.132  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 05:50:00.136  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:00.136  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 05:50:00.137  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:50:00.137  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 05:50:00.138  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:50:00.138  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.138  4590  4670 D BtGatt.ScanManager: stopping BLe Batch
10-05 05:50:00.141  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 05:50:00.141  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 05:50:00.141  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:50:00.142  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-05 05:50:00.142  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:50:00.142  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:50:00.143  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 05:50:00.143  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.143  4590  4670 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 05:50:00.144  4590  4835 D BtGatt.GattService: registerClient() - UUID=fa235be4-8fa7-4625-aae6-bbd9a8d93555
10-05 05:50:00.145  4590  4665 D BtGatt.GattService: onClientRegistered() - UUID=fa235be4-8fa7-4625-aae6-bbd9a8d93555, clientIf=5
,10-05 05:50:00.147  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 05:50:00.147  4590  4834 D BtGatt.GattService: start scan with filters
10-05 05:50:00.148  4590  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 05:50:00.148  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:50:00.149  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 05:50:00.149  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 05:50:00.149  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:50:00.150  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-05 05:50:00.150  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:50:00.150  4590  4670 D BtGatt.ScanManager: handling starting scan
10-05 05:50:00.150  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:50:00.150  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 05:50:00.151  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:50:00.152  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:50:00.152  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 05:50:00.153  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:50:00.155  5621  5668 I io.jxcore.node.ConnectionHelper: start: OK
10-05 05:50:00.155  4590  4665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:50:00.155  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.155  4590  4670 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 05:50:00.159  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-05 05:50:00.159  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:00.159  4590  4670 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:50:00.159  4590  4670 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 05:50:00.167  4590  4665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 05:50:00.167  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:50:00.171  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 05:50:00.172  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:50:00.415   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:50:00.418   930  2964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-05 05:50:00.653  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 05:50:00.653  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:50:00.654  5621  5621 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 05:50:00.787   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:01.788   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:02.788   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 05:50:03.441   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-05 05:50:03.448   930  2964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-05 05:50:05.155  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:05.156  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:50:05.156  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 05:50:05.156  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:05.156  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 05:50:05.156  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:05.156  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 05:50:05.157  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:50:05.157  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:50:05.157  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-05 05:50:05.157  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 05:50:05.157  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:50:05.160  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:50:05.162  4590  4834 D BtGatt.GattService: stopScan() - queue size =1
,10-05 05:50:05.164  4590  4603 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 05:50:05.165  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:50:05.165  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:50:05.165  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:50:05.165  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:50:05.166  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-05 05:50:05.166  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 05:50:05.166  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:50:05.166  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 05:50:05.169  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:05.169  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 05:50:05.170  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-05 05:50:05.170  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 05:50:05.170  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 05:50:05.171  4590  4590 D BtGatt.ScanManager: awakened up at time 246819
10-05 05:50:05.174  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:50:05.176  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:50:05.176  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:50:05.176  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:05.177  4590  4665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:50:05.177  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:05.177  4590  4670 D BtGatt.ScanManager: stopping BLe Batch
,10-05 05:50:05.184  4590  4665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 05:50:05.184  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:05.184  4590  4670 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 05:50:05.201  4590  4665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
10-05 05:50:05.201  4590  4665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:50:05.201  4590  4665 D BtGatt.GattService: current time is 246849414425
,10-05 05:50:05.202  4590  4665 D BtGatt.GattService: Batch record : [-32, 42, -45, -103, -54, 90, 1, -128, -90, 43, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -80, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -85, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -77, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-05 05:50:05.202  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
10-05 05:50:05.202  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 05:50:05.203  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-05 05:50:05.203  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 05:50:05.203  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-05 05:50:05.203  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-05 05:50:05.203  4590  4665 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-05 05:50:05.677  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-05 05:50:05.677  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:50:05.677  5621  5621 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 05:50:06.468   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 05:50:10.177  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 05:50:10.177  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.177  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.178  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.178  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.178  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 05:50:10.178  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.178  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.178  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.179  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.179  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 05:50:10.179  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.180  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.181  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.183  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.184  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.184  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:10.184  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.185  5621  5668 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-05 05:50:10.187  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.187  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.187  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.188  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 05:50:10.188  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.188  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.188  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.188  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.188  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.188  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
,10-05 05:50:10.189  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.189  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.189  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.189  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.189  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:10.191  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.192  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 05:50:10.192  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.192  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.194  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 05:50:10.195  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.195  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.195  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.195  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.195  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.196  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.196  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:50:10.196  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.196  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.196  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.196  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.197  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.197  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.197  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.197  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.198  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.198  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 05:50:10.198  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.198  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.199  5621  5668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-05 05:50:10.199  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.199  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.200  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.200  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.200  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.200  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.200  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.200  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.200  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:10.200  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.200  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.200  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.200  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.200  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.200  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.202  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.202  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.202  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.202  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
,10-05 05:50:10.203  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-05 05:50:10.203  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.203  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.203  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.203  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.203  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.203  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.203  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.204  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.204  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.204  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
,10-05 05:50:10.204  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.204  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.204  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.204  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.204  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:10.206  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 05:50:10.206  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.206  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.206  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.207  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:50:10.207  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:50:10.207  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:50:10.207  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 05:50:10.207  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.208  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.208  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.208  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 05:50:10.208  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.208  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.208  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.208  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.208  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.208  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.208  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.208  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.208  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:10.208  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.208  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.211  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.211  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.211  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.211  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.212  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 05:50:10.212  5621  5668 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 05:50:10.212  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 05:50:10.216  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-05 05:50:10.216  5621  5668 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-05 05:50:10.216  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 05:50:10.216  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 05:50:10.216  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 05:50:10.216  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-05 05:50:10.216  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 05:50:10.217  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 05:50:10.218  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 05:50:10.218  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-05 05:50:10.218  5621  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 05:50:10.218  5621  5668 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-05 05:50:10.218  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 05:50:10.218  5621  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 05:50:10.219  5621  5668 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-05 05:50:10.219  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-05 05:50:10.219  5621  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 05:50:10.219  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-05 05:50:10.222  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-05 05:50:10.224  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-05 05:50:10.224  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-05 05:50:10.225  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-05 05:50:10.225  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-05 05:50:10.225  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-05 05:50:10.225  5621  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 05:50:10.225  5621  5668 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-05 05:50:10.225  5621  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
10-05 05:50:10.225  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-05 05:50:10.226  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-05 05:50:10.226  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-05 05:50:10.226  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.226  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.226  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.226  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.226  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.227  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.227  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.227  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,10-05 05:50:10.229  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.229  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.229  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.229  5621  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
,10-05 05:50:10.229  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.229  5621  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-05 05:50:10.229  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.229  5621  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
10-05 05:50:10.229  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.229  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.229  5621  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
10-05 05:50:10.229  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.229  5621  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-05 05:50:10.229  5621  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-05 05:50:10.229  5621  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,10-05 05:50:10.230  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.230  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.230  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.230  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.231  5621  5668 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-05 05:50:10.232  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.232  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.232  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.233  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.233  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.233  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.233  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:50:10.233  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
,10-05 05:50:10.233  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.233  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.233  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.233  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.233  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.233  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.233  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.234  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.235  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.235  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.235  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.235  5621  5668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-05 05:50:10.236  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.236  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:50:10.236  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.236  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.236  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.236  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.236  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.236  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.236  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.236  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.236  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.236  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.236  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.236  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.237  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:10.238  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.238  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.238  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.238  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.239  5621  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-05 05:50:10.239  5621  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-05 05:50:10.239  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 05:50:10.239  5621  5668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-05 05:50:10.239  5621  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 05:50:10.240  5621  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-05 05:50:10.240  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 05:50:10.240  5621  5668 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-05 05:50:10.240  5621  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 05:50:10.240  5621  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 05:50:10.240  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-05 05:50:10.240  5621  5668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-05 05:50:10.240  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:10.240  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:10.240  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:10.240  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.240  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.240  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.240  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.240  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.240  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.241  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.241  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.241  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.241  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.241  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.241  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:10.242  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:10.242  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:10.242  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.242  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.243  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:10.243  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.243  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:10.243  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:10.243  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:10.243  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:10.244  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:10.244  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:10.244  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:10.244  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:12.789   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:13.790   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:14.791   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:15.245  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:15.245  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.245  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 05:50:15.245  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:50:15.246  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.246  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:50:15.246  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
,10-05 05:50:15.246  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:15.246  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:50:15.247  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:15.247  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 05:50:15.247  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.247  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.247  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:50:15.247  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:15.247  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:15.248  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.248  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:15.248  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.248  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.249  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.249  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:15.253  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:15.254  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:15.254  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.254  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.261  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-05 05:50:15.262  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:50:15.264  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-05 05:50:15.266  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-05 05:50:15.266  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-05 05:50:15.267  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-05 05:50:15.267  5621  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-05 05:50:15.267  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-05 05:50:15.267  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-05 05:50:15.267  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 05:50:15.268  5621  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:15.268  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:15.268  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-05 05:50:15.268  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-05 05:50:15.269  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:15.269  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-05 05:50:15.269  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.269  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:50:15.269  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 05:50:15.269  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.270  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.272  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:15.272  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.272  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:50:15.272  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 05:50:15.272  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:15.272  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:50:15.272  5621  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-05 05:50:15.272  5621  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-05 05:50:15.272  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:15.273  5621  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-05 05:50:15.273  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 05:50:15.273  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:15.273  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.273  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.273  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 05:50:15.273  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:15.266  4834  4834 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32380]" dev="sockfs" ino=32380 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 05:50:15.273  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-05 05:50:15.274  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:15.274  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:15.274  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.274  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:15.274  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.274  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.274  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.274  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.266  4834  4834 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32380]" dev="sockfs" ino=32380 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-05 05:50:15.277  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 05:50:15.277  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:15.277  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.277  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.279  5621  5668 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-05 05:50:15.280  5621  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-05 05:50:15.280  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 05:50:15.280  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-05 05:50:15.280  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 05:50:15.281  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:15.281  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:15.281  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:15.281  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:15.281  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.281  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.281  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:15.281  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:15.282  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.282  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.282  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:15.282  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.282  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.282  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.282  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:15.284  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 05:50:15.284  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:15.284  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.285  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
,10-05 05:50:15.292  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 05:50:15.292  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:15.292  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:15.292  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:15.292  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.292  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.292  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:15.292  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
10-05 05:50:15.292  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.293  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.293  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:15.293  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.293  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.293  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:50:15.293  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:50:15.294  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 05:50:15.294  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:15.294  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.294  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.295  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:50:15.295  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:50:15.295  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:50:15.295  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:50:15.295  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.295  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.295  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:50:15.296  5621  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9913ef5 not in the list
,10-05 05:50:15.296  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:15.296  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.296  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:15.296  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.296  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.296  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:15.296  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:15.297  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:50:15.297  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:50:15.297  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:15.297  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84a48a not in the list
10-05 05:50:15.298  5621  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-05 05:50:15.298  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 05:50:15.298  5621  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-05 05:50:15.298  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 05:50:15.298  5621  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-05 05:50:15.298  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 05:50:15.300  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 05:50:15.300  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-05 05:50:15.302  5621  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-05 05:50:15.302  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 05:50:15.302  5621  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-05 05:50:15.302  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 05:50:15.302  5621  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-05 05:50:15.302  5621  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-05 05:50:15.303  5621  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-05 05:50:15.303  5621  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-05 05:50:15.303  5621  5668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-05 05:50:15.304  5621  5668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-05 05:50:15.304  5621  5668 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-05 05:50:15.304  5621  5668 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-05 05:50:15.305  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:15.305  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd8305c added. We now have 3 listener(s)
10-05 05:50:15.305  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:50:15.307  5621  5668 D BluetoothAdapter: enable(): BT is already enabled..!
,10-05 05:50:15.307   930   940 D WifiService: setWifiEnabled: true pid=5621, uid=10077
10-05 05:50:15.307   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:50:15.773  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 05:50:15.792   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:16.793   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:17.794   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 05:50:20.313  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:20.313  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f0cf65 added. We now have 4 listener(s)
10-05 05:50:20.313  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:50:20.326  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:50:20.326  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f0cf65 removed from the list
10-05 05:50:20.326  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 05:50:20.326  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:50:20.327  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:20.328  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:20.329  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7443a added. We now have 4 listener(s)
10-05 05:50:20.329  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:50:20.332  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:20.332  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7443a removed from the list
10-05 05:50:20.332  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:20.332  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:50:20.332  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:20.334  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:20.334  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14de8eb added. We now have 4 listener(s)
10-05 05:50:20.335  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:50:20.337   930  3779 D WifiService: setWifiEnabled: false pid=5621, uid=10077
,10-05 05:50:20.338   930  3779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:50:20.343   930  2962 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 05:50:20.343   930  2962 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-05 05:50:20.343   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 05:50:20.343   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:50:20.348  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:50:20.351  4590  4661 D BluetoothAdapterState: Current state: ON, message: 23
10-05 05:50:20.353  4590  4661 D BluetoothAdapterProperties: Setting state to 13
,10-05 05:50:20.353  4590  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-05 05:50:20.356  4590  4661 D BluetoothAdapterProperties: onBluetoothDisable()
10-05 05:50:20.357  4590  4661 I BluetoothAdapterState: Entering PendingCommandState
10-05 05:50:20.357  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:20.357  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:50:20.358  4590  4665 D BluetoothAdapterProperties: Scan Mode:20
10-05 05:50:20.358  4590  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-05 05:50:20.359  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.359  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.360  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 05:50:20.360  4590  4590 D HeadsetService: Received stop request...Stopping profile...
10-05 05:50:20.362  3120  3972 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:20.362   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:20.362  4590  4590 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:20.362   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:20.362  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.362  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.362  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.363  3782  3813 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:20.363  3120  3120 D HeadsetProfile: Bluetooth service disconnected
10-05 05:50:20.363   930   930 D BluetoothHeadset: Proxy object disconnected
,10-05 05:50:20.364   930  5378 D DhcpClient: Clearing IP address
10-05 05:50:20.364   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-05 05:50:20.365  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.367  4590  4590 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 05:50:20.367  4590  4590 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-05 05:50:20.368  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:20.368  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:20.368  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:20.368  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:20.369  4590  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 05:50:20.369  4590  4665 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 05:50:20.369  4590  4590 D A2dpService: Received stop request...Stopping profile...
10-05 05:50:20.369  4590  4817 D A2dpStateMachine: Exit Disconnected: -1
,10-05 05:50:20.370   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:20.373   930   930 D BluetoothA2dp: Proxy object disconnected
10-05 05:50:20.373  3120  3120 D BluetoothA2dp: Proxy object disconnected
10-05 05:50:20.373   930  5379 D DhcpClient: Receive thread stopped
10-05 05:50:20.373  4590  4590 D HidService: Received stop request...Stopping profile...
,10-05 05:50:20.374  4590  4590 D HidService: Stopping Bluetooth HidService
10-05 05:50:20.374  3568  5433 V NativeCrypto: Read error: ssl=0x7f9f78c100: I/O error during system call, Connection timed out
10-05 05:50:20.375  3120  3120 D BluetoothInputDevice: Proxy object disconnected
10-05 05:50:20.375  3120  3120 D HidProfile: Bluetooth service disconnected
10-05 05:50:20.376  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:20.376  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:50:20.377  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.377  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.377  3568  5433 V NativeCrypto: SSL shutdown failed: ssl=0x7f9f78c100: I/O error during system call, Broken pipe
10-05 05:50:20.379  4590  4590 D HealthService: Received stop request...Stopping profile...
,10-05 05:50:20.381  4590  4590 D PanService: Received stop request...Stopping profile...
10-05 05:50:20.382   930  3879 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-05 05:50:20.382  3120  3120 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 05:50:20.382  3120  3120 D PanProfile: Bluetooth service disconnected
10-05 05:50:20.382   930  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-05 05:50:20.383  4590  4590 D BluetoothMapService: Received stop request...Stopping profile...
10-05 05:50:20.383  4590  4590 D BluetoothMapService: stop()
10-05 05:50:20.384  4590  4590 D BluetoothMapAppObserver: deinitObservers()
10-05 05:50:20.384  4590  4590 D BluetoothMapAppObserver: removeReceiver()
10-05 05:50:20.385   930  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-05 05:50:20.385  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:20.385  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:50:20.385   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,10-05 05:50:20.385   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-05 05:50:20.386  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.386  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:20.386   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-05 05:50:20.387  4590  4590 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:20.387  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.387  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.387  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.387   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 05:50:20.387  4590  4590 D SapService: Received stop request...Stopping profile...
10-05 05:50:20.387  4590  4590 V SapService: stop()
10-05 05:50:20.387   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-05 05:50:20.387  3120  3120 D BluetoothMap: Proxy object disconnected
10-05 05:50:20.387  3120  3120 D MapProfile: Bluetooth service disconnected
,10-05 05:50:20.390  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:20.390  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:50:20.391   536   536 E Parcel  : Reading a NULL string not supported here.
10-05 05:50:20.391  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.391   930   930 D RttService: SCAN_AVAILABLE : 1
10-05 05:50:20.391  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:20.391   930  3072 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 05:50:20.393  4590  4590 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:20.393  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.393  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.394  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.394  4590  4590 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 05:50:20.394  4590  4590 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 05:50:20.394  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:20.394  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:20.394  4590  4590 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:20.394  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.394  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.394  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.394  4590  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 05:50:20.394  4590  4665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 05:50:20.395  4590  4793 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 05:50:20.395  4590  4793 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 05:50:20.395  4590  4590 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 05:50:20.395  4590  4793 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 05:50:20.395  4590  4665 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-05 05:50:20.395  4590  4793 W bt_l2cap: btif_in_execute_service_request: Unknown service
10-05 05:50:20.395  4590  4590 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-05 05:50:20.396  4590  4590 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:20.396  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.396  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.396  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.396  4590  4590 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 05:50:20.396  4590  4590 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 05:50:20.397  4590  4590 D BluetoothMapService: MAP Service closeService in
10-05 05:50:20.397  4590  4590 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 05:50:20.397  4590  4590 D ObexServerSockets0: shutdown(block = true)
10-05 05:50:20.398  4590  4590 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 05:50:20.398  4590  4836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-05 05:50:20.398  4590  4590 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 05:50:20.398  4590  4837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 05:50:20.398  4590  4590 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:20.398  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.398  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.398  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.399   930  2964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-05 05:50:20.399  4590  4812 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-05 05:50:20.399  4590  4590 D BluetoothMapService: cleanup()
,10-05 05:50:20.399  4590  4590 D BluetoothMapService: MAP Service closeService in
,10-05 05:50:20.400  3743  3897 W QCNEJ   : |CORE| network lost: 100
,10-05 05:50:20.401  3743  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-05 05:50:20.403  4590  4590 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:20.403  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.403  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.403  4590  4590 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:20.404  4590  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 05:50:20.404  4590  4661 D BluetoothAdapterProperties: Setting state to 15
10-05 05:50:20.404  4590  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 05:50:20.405  4590  4661 I BluetoothAdapterState: Entering BleOnState
10-05 05:50:20.405  4590  4590 I BtOppRfcommListener: stopping Accept Thread
10-05 05:50:20.405  4590  5317 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 05:50:20.406  4590  5317 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-05 05:50:20.406   930  2962 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-05 05:50:20.408  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.408  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:20.408  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.408  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:20.411  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:20.415  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.415  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:20.417  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.418  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:20.424   930   943 I ActivityManager: Start proc 5683:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-05 05:50:20.426   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 05:50:20.426  3120  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 05:50:20.427   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:20.427  3782  4108 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:20.427  3120  3132 D BluetoothPan: onBluetoothStateChange on: false
,10-05 05:50:20.429   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 05:50:20.429  3120  3134 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 05:50:20.430  3120  3972 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 05:50:20.431   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 05:50:20.431   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:20.431  3120  3132 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:20.431  3120  3134 D BluetoothMap: onBluetoothStateChange: up=false
10-05 05:50:20.431   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-05 05:50:20.432  4590  4661 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 05:50:20.432  4590  4661 D BluetoothAdapterProperties: Setting state to 16
10-05 05:50:20.432  4590  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 05:50:20.433  4590  4661 D BluetoothAdapterProperties: onBleDisable
10-05 05:50:20.433  4590  4661 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:20.433  4590  4662 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 05:50:20.433  4590  4665 D BluetoothAdapterProperties: Scan Mode:20
10-05 05:50:20.434  4590  4793 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 05:50:20.434  4590  4793 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-05 05:50:20.437  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.438  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.439  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.440  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.441  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.442  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.456   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:50:20.457   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-05 05:50:20.457   510   924 D TetherController: Setting IP forward enable = 0
10-05 05:50:20.458   930  2964 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-05 05:50:20.458   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:50:20.464   930  2962 D DhcpClient: doQuit
,10-05 05:50:20.464   930  2962 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 05:50:20.464   930  5378 D DhcpClient: onQuitting
10-05 05:50:20.465  3430  3430 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-05 05:50:20.465   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-05 05:50:20.470  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.470  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:20.471  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.471  5274  5274 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@78bca2c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-05 05:50:20.471  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:50:20.475  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.475  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:20.476  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:20.476  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:20.478  5043  5066 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 05:50:20.478  5043  5066 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 05:50:20.478  5043  5066 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 05:50:20.478  5043  5066 E SarControlService: no key has been found,reset the power
10-05 05:50:20.478  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 05:50:20.478  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 05:50:20.478  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.478  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:20.478  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:20.479  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:20.479  5068  5068 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 05:50:20.479  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:20.479  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:20.480  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 05:50:20.480  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 05:50:20.480  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-05 05:50:20.481  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:20.481  5068  5068 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 05:50:20.482  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:20.483  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000ea03000000000000ffffffff]
10-05 05:50:20.483  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:50:20.483  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:20.483  5068  5082 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-05 05:50:20.484  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:20.484  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 05:50:20.485  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:20.488  3568  5703 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-05 05:50:20.490  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000eb03000000000000ffffffff]
,10-05 05:50:20.490  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:50:20.490  5068  5082 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-05 05:50:20.491  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:20.492  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 05:50:20.493  3430  3430 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-05 05:50:20.494  5683  5683 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-05 05:50:20.504  3430  3430 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 05:50:20.508  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 05:50:20.513   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ca9b57:true
10-05 05:50:20.514  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 05:50:20.520  3568  5693 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-05 05:50:20.521   510   924 E Netd    : netlink response contains error (No such file or directory)
10-05 05:50:20.522   510   924 D TetherController: Setting IP forward enable = 0
10-05 05:50:20.523   930  2964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 05:50:20.523  3568  5693 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-05 05:50:20.526   930  3779 I ActivityManager: Start proc 5712:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-05 05:50:20.544  3568  5703 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-05 05:50:20.551  5683  5683 D LocalBluetoothProfileManager: Adding local MAP profile
,10-05 05:50:20.551  3430  3430 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 05:50:20.556  5683  5683 D BluetoothMap: Create BluetoothMap proxy object
,10-05 05:50:20.557  3568  5693 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,10-05 05:50:20.566  3430  3430 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 05:50:20.569  5683  5683 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-05 05:50:20.587  5712  5712 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-05 05:50:20.595  5683  5683 D DockEventReceiver: finishStartingService: stopping service
,10-05 05:50:20.598   930   941 I ActivityManager: Killing 5406:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-05 05:50:20.644  4590  4665 I bt_hci  : shut_down
,10-05 05:50:20.648  4590  4671 D bt_hwcfg: hw_epilog_process
,10-05 05:50:20.649  4590  4671 I bt_vendor: low_power_mode_cb
,10-05 05:50:20.651  4590  4671 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 05:50:20.651  4590  4671 I bt_vendor: epilog_cb
10-05 05:50:20.651  4590  4671 I bt_hci  : epilog_finished_callback
,10-05 05:50:20.653  4590  4665 I bt_hci_h4: hal_close
10-05 05:50:20.654  4590  4665 I bt_userial_vendor: device fd = 54 close
,10-05 05:50:20.673  5018  5018 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 05:50:20.673   930  2962 D wifi    : In wifi stop Hal
10-05 05:50:20.673   930  2962 D wifi    : halHandle = 0x7f8cf88900, mVM = 0x7fa960d140, mCls = 0x100a02
10-05 05:50:20.674   930  3429 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 05:50:20.674   930  3429 D WifiHAL : Got a signal to exit!!!
10-05 05:50:20.674   930  3429 I WifiHAL : Exit wifi_event_loop
10-05 05:50:20.674   930  2962 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-05 05:50:20.674   930  2962 E WifiHAL : Event processing terminated
10-05 05:50:20.674   930  2962 D wifi    : In wifi cleaned up handler
10-05 05:50:20.674   930  2962 I WifiHAL : Internal cleanup completed
,10-05 05:50:20.676  4093  4211 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 05:50:20.676  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.678  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.680  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:20.699   930  3429 D wifi    : set interface wlan0 flags (DOWN)
,10-05 05:50:20.700   930  2962 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 05:50:20.758  4590  4662 D bt_stack_manager: event_shut_down_stack finished.
,10-05 05:50:20.759  4590  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 05:50:20.761  4590  4590 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 05:50:20.761  4590  4661 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-05 05:50:20.761  4590  4590 D BtGatt.GattService: Received stop request...Stopping profile...
,10-05 05:50:20.761  4590  4590 D BtGatt.GattService: stop()
10-05 05:50:20.761  4590  4590 D BtGatt.AdvertiseManager: advertise clients cleared
10-05 05:50:20.763  4590  4590 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:20.763  4590  4590 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:20.764  4590  4590 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:20.764  4590  4590 V BluetoothAdapterState: isBleTurningOff()=true
10-05 05:50:20.764  4590  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-05 05:50:20.764  4590  4661 D BluetoothAdapterProperties: Setting state to 10
10-05 05:50:20.764  4590  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 05:50:20.765  4590  4661 I BluetoothAdapterState: Entering OffState
,10-05 05:50:20.765   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-05 05:50:20.772  4590  4590 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-05 05:50:20.772  4590  4590 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 05:50:20.772  4590  4590 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-05 05:50:20.773  4590  4662 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 05:50:20.782  4590  4662 D bt_stack_manager: event_clean_up_stack finished.
,10-05 05:50:20.793  4590  4590 I art     : System.exit called, status: 0
,10-05 05:50:20.793  4590  4590 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 05:50:20.824   930  3779 I ActivityManager: Process com.android.bluetooth (pid 4590) has died
,10-05 05:50:20.835  5712  5712 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 05:50:20.835  5712  5712 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.835  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.k.d(PG:583)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.836  5712  5712 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:50:20.836  5712  5712 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:50:20.840  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 05:50:20.854   930   940 I ActivityManager: Start proc 5748:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,10-05 05:50:20.877  5683  5683 D DockEventReceiver: finishStartingService: stopping service
10-05 05:50:20.878   930  3601 I ActivityManager: Killing 5419:com.android.chrome/u0a39 (adj 15): empty #17
10-05 05:50:20.902   930   947 D Tethering: InitialState.processMessage what=4
10-05 05:50:20.905   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 05:50:20.942  5748  5748 D AdapterServiceConfig: Adding HeadsetService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding A2dpService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding HidService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding HealthService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding PanService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding GattService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding BluetoothMapService
10-05 05:50:20.943  5748  5748 D AdapterServiceConfig: Adding SapService
,10-05 05:50:20.945   930  3849 I ActivityManager: Killing 5438:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-05 05:50:20.973  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 05:50:20.989  3871  3871 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 05:50:20.992  3871  3871 D SystemUpdateService: onCreate
,10-05 05:50:20.996  3871  3871 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 05:50:21.008  3871  3871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 05:50:21.014  3871  5403 I iu.UploadsManager: num queued entries: 0
,10-05 05:50:21.015  3871  5403 I iu.UploadsManager: num updated entries: 0
10-05 05:50:21.015  3871  5403 I iu.SyncManager: NEXT; no task
,10-05 05:50:21.020  3871  3871 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 05:50:21.022  3871  3871 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 05:50:21.023  3871  5761 I SystemUpdateService: active receiver: enabled
,10-05 05:50:21.030  3871  5761 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 05:50:21.033  3871  5761 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 05:50:21.033  3871  5761 I SystemUpdateService: now status is 0 (complete)
10-05 05:50:21.033  3871  5761 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 05:50:21.033  3871  5761 I SystemUpdateService: file has been verified
10-05 05:50:21.033  3871  5761 I SystemUpdateService: OTA package size = 21989297
,10-05 05:50:21.038   930  3779 I ActivityManager: Start proc 5763:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-05 05:50:21.046  3871  5761 I SystemUpdateService: showing system update notification
,10-05 05:50:21.067  3871  3871 D SystemUpdateService: onDestroy
,10-05 05:50:21.081  5763  5763 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-05 05:50:21.084  5763  5763 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:50:21.090  5763  5763 D SprintDMHelper: simOperator: 
10-05 05:50:21.090  5763  5763 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 05:50:21.104   930  3847 I ActivityManager: Start proc 5775:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-05 05:50:21.104   930  3847 I ActivityManager: Killing 5274:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-05 05:50:21.210  5018  5789 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 05:50:21.219   930  3188 I ActivityManager: Start proc 5790:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-05 05:50:21.221   930  3870 I ActivityManager: Killing 4675:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-05 05:50:21.273  5790  5790 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-05 05:50:21.427  5712  5737 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-05 05:50:21.454   930  3837 I ActivityManager: Killing 5157:com.google.android.youtube/u0a75 (adj 15): empty #17
,10-05 05:50:21.483   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6ec6a4:true
,10-05 05:50:21.506   930   941 I ActivityManager: Start proc 5803:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-05 05:50:21.540  5803  5803 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-05 05:50:21.548   930  3600 I ActivityManager: Killing 5494:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-05 05:50:25.362   930   940 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,10-05 05:50:25.362   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:50:25.374   510   924 D SoftapController: Softap fwReload - Ok
,10-05 05:50:25.381   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:25.382   510   924 D CommandListener: Trying to bring down wlan0
10-05 05:50:25.383   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 05:50:25.387   930  2962 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 05:50:25.958   930  2962 D wifi    : set interface wlan0 flags (UP)
,10-05 05:50:25.959   930  2962 I WifiHAL : Initializing wifi
10-05 05:50:25.959   930  2962 I WifiHAL : Creating socket
,10-05 05:50:25.963   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-05 05:50:25.963   930  2962 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-05 05:50:25.963   930  2962 D wifi    : Did set static halHandle = 0x7f8cf88900
10-05 05:50:25.963   930  2962 D wifi    : halHandle = 0x7f8cf88900, mVM = 0x7fa960d140, mCls = 0x19b2
10-05 05:50:25.963   930  2962 D wifi    : array field set
,10-05 05:50:25.963   930  2962 I WifiNative-HAL: interface[0] = wlan0
,10-05 05:50:25.966   930  5824 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547825944832
,10-05 05:50:25.966   930  5824 D wifi    : waitForHalEvents called, vm = 0x7fa960d140, obj = 0x19b2, env = 0x7f8fb70c80
,10-05 05:50:26.030  5825  5825 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 05:50:26.054  5825  5825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 05:50:26.061  5825  5825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 05:50:26.061  5825  5825 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 05:50:26.068   930  2962 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 05:50:26.073  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:26.076  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:26.076  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:26.076  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:26.076  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:26.079  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:26.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:26.079  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:26.079  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:26.085   930  2962 D WifiConfigStore: Loading config and enabling all networks 
10-05 05:50:26.086  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:26.086  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:26.086  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:26.086  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:26.088  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:26.089  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:26.094   930  2962 D WifiConfigStore: loaded 0 passpoint configs
,10-05 05:50:26.095   930  2962 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-05 05:50:26.095   930  2962 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-05 05:50:26.096   930  2962 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-05 05:50:26.096   930  2962 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 05:50:26.096   930  2962 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 05:50:26.097   930  2962 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 05:50:26.097   930  2962 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 05:50:26.099   930  2962 D WifiNative-HAL: Setting external_sim to 1
,10-05 05:50:26.099   930  2962 D wifi    : setting dfs flag to true, 0x7f904b9080
,10-05 05:50:26.099  5018  5018 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 05:50:26.099   930  2962 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 05:50:26.099   930  2962 D wifi    : setting scan oui 0x7f904b9080
10-05 05:50:26.099   930  2962 D WifiHAL : Sending mac address OUI
,10-05 05:50:26.102   930  2962 E native  : do suspend false
,10-05 05:50:26.109   930  2962 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-05 05:50:26.109   930   930 D RttService: SCAN_AVAILABLE : 3
10-05 05:50:26.109   930  3072 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 05:50:26.113   510   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-05 05:50:26.114   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:26.117   930  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
10-05 05:50:26.117   930  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 05:50:26.124   930  2961 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 05:50:26.128   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267776 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-05 05:50:26.128   930  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 05:50:29.279  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:50:29.285  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:50:29.290  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:50:29.295  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:50:29.351   930  2962 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 05:50:29.352   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-05 05:50:29.352   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:50:29.365   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 05:50:29.398   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 05:50:29.401  5825  5825 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 05:50:29.855  5825  5825 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 05:50:29.887  5825  5825 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 05:50:29.889  5825  5825 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 05:50:29.901   930  2962 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 05:50:29.902   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-05 05:50:29.902   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 05:50:29.920   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:50:29.935   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:29.940   930  2962 D WifiStateMachine: Start Dhcp Watchdog 2
,10-05 05:50:29.946   930  5831 D DhcpClient: Receive thread started
,10-05 05:50:29.950   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-05 05:50:29.950   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 05:50:29.950   930  2964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-05 05:50:30.031   930  2962 E native  : do suspend false
,10-05 05:50:30.046   930  5830 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 05:50:30.060   930  5831 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,10-05 05:50:30.061   930  5830 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,10-05 05:50:30.063   930  5830 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 05:50:30.084   930  5831 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 05:50:30.085   930  5830 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 05:50:30.088   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:30.092   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 05:50:30.097   930  5830 D DhcpClient: Scheduling renewal in 86399s
,10-05 05:50:30.105   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 05:50:30.107   930  2962 D WifiConfigStore: No blacklist allowed without epno enabled
,10-05 05:50:30.107   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-05 05:50:30.109   930  2964 D ConnectivityService: Adding iface wlan0 to network 101
10-05 05:50:30.118   930  2962 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 05:50:30.156   930  2964 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 05:50:30.156   930  2964 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
10-05 05:50:30.158   930  2964 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-05 05:50:30.163   930  2964 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-05 05:50:30.165   930  2964 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-05 05:50:30.173   930  2964 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 05:50:30.177   930  2964 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-05 05:50:30.178   930  2964 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-05 05:50:30.178   930  2964 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-05 05:50:30.178   930  2964 D ConnectivityService:    accepting network in place of null
10-05 05:50:30.178   930  2962 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 05:50:30.178   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 05:50:30.178   930  2964 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 05:50:30.200   930  5829 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271847, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 05:50:30.201   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:50:30.221   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:50:30.224   930  2964 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-05 05:50:30.224   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 05:50:30.224  3743  3897 W QCNEJ   : |CORE| network available: 101
10-05 05:50:30.225   930  2964 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-05 05:50:30.226   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-05 05:50:30.229  3743  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 05:50:30.231  3743  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 05:50:30.231  3743  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-05 05:50:30.231  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:30.231  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:50:30.231  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:30.231  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:30.234  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:30.234  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:50:30.234  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.234  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:50:30.237  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:50:30.237  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:50:30.237  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.237  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:50:30.243  5043  5066 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 05:50:30.243  5043  5066 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 05:50:30.243  5043  5066 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 05:50:30.243  5043  5066 E SarControlService: no key has been found,reset the power
10-05 05:50:30.244  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 05:50:30.244  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 05:50:30.244  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-05 05:50:30.244  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:30.244  5068  5068 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 05:50:30.245  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 05:50:30.245  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 05:50:30.245  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 05:50:30.246  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:30.246  5068  5068 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 05:50:30.248  3871  3871 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 05:50:30.251  3871  3871 D SystemUpdateService: onCreate
10-05 05:50:30.252  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000ec03000000000000ffffffff]
10-05 05:50:30.252  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-05 05:50:30.252  5068  5082 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-05 05:50:30.252  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:30.253  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 05:50:30.256  3871  3871 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 05:50:30.257  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000ed03000000000000ffffffff]
10-05 05:50:30.257  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:50:30.257  5068  5082 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-05 05:50:30.258  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:30.258  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 05:50:30.267  3871  3871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 05:50:30.272  3871  5403 I iu.UploadsManager: num queued entries: 0
,10-05 05:50:30.272   930  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-05 05:50:30.273  3871  5403 I iu.UploadsManager: num updated entries: 0
10-05 05:50:30.273  3871  5403 I iu.SyncManager: NEXT; no task
,10-05 05:50:30.278  3871  3871 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 05:50:30.280  3871  3871 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 05:50:30.281  5763  5763 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:50:30.285  5763  5763 D SprintDMHelper: simOperator: 
10-05 05:50:30.285  5763  5763 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 05:50:30.293  3871  5841 I SystemUpdateService: active receiver: enabled
,10-05 05:50:30.317  3871  5841 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 05:50:30.322   930  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 09:50:30 GMT], X-Android-Received-Millis=[1475661030321], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475661030296]}
,10-05 05:50:30.322   930  2964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 05:50:30.322   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-05 05:50:30.323   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-05 05:50:30.324   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-05 05:50:30.324  3871  5841 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-05 05:50:30.324  3871  5841 I SystemUpdateService: now status is 0 (complete)
10-05 05:50:30.324  3871  5841 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 05:50:30.324  3871  5841 I SystemUpdateService: file has been verified
10-05 05:50:30.324  3871  5841 I SystemUpdateService: OTA package size = 21989297
,10-05 05:50:30.330  3871  5841 I SystemUpdateService: showing system update notification
,10-05 05:50:30.338  3871  3871 D SystemUpdateService: onDestroy
,10-05 05:50:30.371   930   941 D WifiService: setWifiEnabled: false pid=5621, uid=10077
10-05 05:50:30.371   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:50:30.372   930  2962 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 05:50:30.372   930  2962 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-05 05:50:30.372   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 05:50:30.373   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:50:30.383   930  5830 D DhcpClient: Clearing IP address
,10-05 05:50:30.383   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 05:50:30.384   510   924 D CommandListener: Setting iface cfg
,10-05 05:50:30.386   930  5831 D DhcpClient: Receive thread stopped
10-05 05:50:30.389  3568  5852 V NativeCrypto: Read error: ssl=0x7f9eaec000: I/O error during system call, Connection timed out
10-05 05:50:30.390  3568  5852 V NativeCrypto: SSL shutdown failed: ssl=0x7f9eaec000: I/O error during system call, Broken pipe
,10-05 05:50:30.392  5018  5846 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-05 05:50:30.393   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 05:50:30.393   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-05 05:50:30.396   536   536 E Parcel  : Reading a NULL string not supported here.
,10-05 05:50:30.398   930   930 D RttService: SCAN_AVAILABLE : 1
,10-05 05:50:30.399   930  3072 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-05 05:50:30.399   930  2964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-05 05:50:30.400  3743  3897 W QCNEJ   : |CORE| network lost: 101
10-05 05:50:30.401  3743  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-05 05:50:30.402   930  2962 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-05 05:50:30.406   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
10-05 05:50:30.409  ,5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
10-05 05:50:30.409  5018  5846 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-05 05:50:30.409  5018  5846 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 05:50:30.423   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:50:30.442   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:50:30.442   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-05 05:50:30.443   930  2964 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-05 05:50:30.443   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:50:30.445   930   947 D Tethering: MasterInitialState.processMessage what=3
10-05 05:50:30.446   930  2962 D DhcpClient: doQuit
10-05 05:50:30.446   930  2962 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 05:50:30.446   930  5830 D DhcpClient: onQuitting
10-05 05:50:30.448  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:30.448  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:30.448  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.448  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:30.449  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:30.449  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:30.449  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.449  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:30.449  5825  5825 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 05:50:30.450  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:30.451  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:30.451  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.451  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:30.452  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:5,0:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:30.452  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:30.452  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:30.452  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:30.455  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:30.455  5043  5066 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 05:50:30.455  5043  5066 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 05:50:30.455  5043  5066 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 05:50:30.456  5043  5066 E SarControlService: no key has been found,reset the power
10-05 05:50:30.456  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-05 05:50:30.456  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 05:50:30.456  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 05:50:30.457  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:30.457  5068  5068 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 05:50:30.459  3871  3871 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 05:50:30.460  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 05:50:30.460  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 05:50:30.460  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 05:50:30.460  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:50:30.460  5068  5068 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 05:50:30.463  3871  3871 D SystemUpdateService: onCreate
10-05 05:50:30.464  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000ee03000000000000ffffffff]
10-05 05:50:30.464  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:50:30.464  5068  5082 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-05 05:50:30.464  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:30.465  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 05:50:30.466  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000ef03000000000000ffffffff]
10-05 05:50:30.466  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:50:30.466  5068  5082 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-05 05:50:30.466  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-05 05:50:30.466  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:50:30.467  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 05:50:30.468  3871  3871 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 05:50:30.473  5825  5825 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 05:50:30.476  3871  5860 I SystemUpdateService: active receiver: enabled
,10-05 05:50:30.477  3871  3871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 05:50:30.484  3871  3871 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-05 05:50:30.486  3871  3871 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 05:50:30.488  5763  5763 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:50:30.493  5763  5763 D SprintDMHelper: simOperator: 
,10-05 05:50:30.493  5763  5763 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 05:50:30.500  3871  5403 I iu.UploadsManager: num queued entries: 0
,10-05 05:50:30.502  3871  5860 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 05:50:30.504  3871  5403 I iu.UploadsManager: num updated entries: 0
,10-05 05:50:30.507  5018  5863 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 05:50:30.508  3871  5860 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 05:50:30.511  3871  5860 I SystemUpdateService: now status is 0 (complete)
10-05 05:50:30.511  3871  5860 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 05:50:30.511  3871  5860 I SystemUpdateService: file has been verified
,10-05 05:50:30.515  3871  5860 I SystemUpdateService: OTA package size = 21989297
,10-05 05:50:30.516  3871  5403 I iu.SyncManager: NEXT; no task
,10-05 05:50:30.520   510   924 E Netd    : netlink response contains error (No such file or directory)
,10-05 05:50:30.521   930  2964 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-05 05:50:30.524  3871  5860 I SystemUpdateService: showing system update notification
,10-05 05:50:30.525  5825  5825 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 05:50:30.533  3871  3871 D SystemUpdateService: onDestroy
,10-05 05:50:30.539  5825  5825 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 05:50:30.641   930  2962 D wifi    : In wifi stop Hal
,10-05 05:50:30.642   930  2962 D wifi    : halHandle = 0x7f8cf88900, mVM = 0x7fa960d140, mCls = 0x19b2
10-05 05:50:30.642   930  5824 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 05:50:30.642   930  5824 D WifiHAL : Got a signal to exit!!!
10-05 05:50:30.642   930  5824 I WifiHAL : Exit wifi_event_loop
10-05 05:50:30.643   930  2962 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-05 05:50:30.643   930  2962 E WifiHAL : Event processing terminated
10-05 05:50:30.643   930  2962 D wifi    : In wifi cleaned up handler
10-05 05:50:30.644   930  2962 I WifiHAL : Internal cleanup completed
10-05 05:50:30.646  4093  4211 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 05:50:30.647  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:30.647  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:30.648  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:30.648  5018  5018 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 05:50:30.675   930  5824 D wifi    : set interface wlan0 flags (DOWN)
,10-05 05:50:30.676   930  2962 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 05:50:30.882   930   947 D Tethering: InitialState.processMessage what=4
,10-05 05:50:30.888   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 05:50:31.225   930  2964 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-05 05:50:32.795   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:33.796   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:34.797   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:35.407   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aab9ee8:true
,10-05 05:50:35.408  5748  5748 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 05:50:35.412  5748  5748 I bt_bluedroid: init
,10-05 05:50:35.412  5748  5866 I BluetoothAdapterState: Entering OffState
,10-05 05:50:35.415  5748  5867 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 05:50:35.416  5748  5867 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 05:50:35.416  5748  5867 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 05:50:35.416  5748  5867 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-05 05:50:35.417  5748  5748 I bt_bluedroid: get_profile_interface socket
,10-05 05:50:35.420  5748  5870 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 05:50:35.420  5748  5748 I bt_bluedroid: get_profile_interface sdp
10-05 05:50:35.422  5748  5870 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 05:50:35.428  5748  5759 I bt_bluedroid: config_hci_snoop_log
,10-05 05:50:35.429   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 05:50:35.434  5748  5866 D BluetoothAdapterState: Current state: OFF, message: 0
10-05 05:50:35.434  5748  5866 D BluetoothAdapterProperties: Setting state to 14
10-05 05:50:35.435  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 05:50:35.437  5748  5866 D BluetoothBondStateMachine: make
,10-05 05:50:35.439  5748  5871 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 05:50:35.442  5748  5866 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:35.444  5748  5748 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 05:50:35.447  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:35.448  5748  5748 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 05:50:35.449  5748  5748 D BtGatt.GattService: Received start request. Starting profile...
10-05 05:50:35.449  5748  5748 D BtGatt.GattService: start()
10-05 05:50:35.449  5748  5748 I bt_bluedroid: get_profile_interface gatt
,10-05 05:50:35.451  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:35.451  5748  5748 D BtGatt.AdvertiseManager: advertise manager created
,10-05 05:50:35.458  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,10-05 05:50:35.459  5748  5748 V BluetoothAdapterState: isTurningOn()=false
,10-05 05:50:35.459  5748  5748 V BluetoothAdapterState: isBleTurningOn()=true
,10-05 05:50:35.459  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:35.459  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-05 05:50:35.461  5748  5866 I bt_bluedroid: bt_bluedroid
10-05 05:50:35.461  5748  5867 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-05 05:50:35.462  5748  5867 I bt_hci  : start_up
,10-05 05:50:35.469  5748  5867 I bt_vendor: alloc value 0xf422c871
,10-05 05:50:35.469  5748  5867 I bt_vendor: init
10-05 05:50:35.469  5748  5867 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,10-05 05:50:35.469  5748  5867 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 05:50:35.579  5748  5867 D bt_hci  : start_up starting async portion
,10-05 05:50:35.580  5748  5874 I bt_hci  : event_finish_startup
10-05 05:50:35.580  5748  5874 I bt_hci_h4: hal_open
,10-05 05:50:35.580  5748  5874 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 05:50:35.576  5875  5875 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-05 05:50:35.583  5748  5874 I bt_userial_vendor: device fd = 54 open
,10-05 05:50:35.598  5748  5874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 05:50:35.601  5748  5874 D bt_hwcfg: Chipset BCM4358A3
,10-05 05:50:35.601  5748  5874 D bt_hwcfg: Target name = [BCM4358A3]
10-05 05:50:35.601  5748  5874 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 05:50:35.798   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:35.988  5748  5874 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 05:50:35.988  5748  5874 D bt_hwcfg: Settlement delay -- 100 ms
10-05 05:50:35.988  5748  5874 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 05:50:36.122  5748  5874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 05:50:36.122  5748  5874 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-05 05:50:36.124  5748  5874 I bt_hwcfg: vendor lib fwcfg completed
10-05 05:50:36.124  5748  5874 I bt_vendor: firmware callback
10-05 05:50:36.124  5748  5874 I bt_hci  : firmware_config_callback
,10-05 05:50:36.134  5748  5877 I bt_btu  : btu_task pending for preload complete event
,10-05 05:50:36.134  5748  5877 I bt_btu_task: Bluetooth chip preload is complete
,10-05 05:50:36.134  5748  5877 I bt_btu  : btu_task received preload complete event
,10-05 05:50:36.141  5748  5877 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 05:50:36.141  5748  5877 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-05 05:50:36.141  5748  5877 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_A2D
,10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 05:50:36.142  5748  5877 I         : BTE_InitTraceLevels -- TRC_GAP
10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_PAN
,10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_SDP
10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_GATT
,10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 05:50:36.143  5748  5877 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 05:50:36.227  5748  5877 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41aa549
,10-05 05:50:36.227  5748  5877 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41aa549 
,10-05 05:50:36.246  5748  5870 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 05:50:36.247  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-05 05:50:36.248  5748  5870 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-05 05:50:36.250  5748  5870 D BluetoothAdapterProperties: Name is: Nexus 6P
10-05 05:50:36.252  5748  5870 D BluetoothAdapterProperties: Scan Mode:20
10-05 05:50:36.252  5748  5870 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-05 05:50:36.253  5748  5870 D bt_hci  : do_postload posting postload work item
10-05 05:50:36.253  5748  5874 I bt_hci  : event_postload
10-05 05:50:36.253  5748  5874 I bt_vendor: sco_config_cb
10-05 05:50:36.253  5748  5874 I bt_hci  : sco_config_callback postload finished.
,10-05 05:50:36.257  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:36.260  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:36.263  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:36.264  5748  5874 I bt_vendor: low_power_mode_cb
,10-05 05:50:36.264  5748  5870 D bt_bte_conf: Device ID record 1 : primary
10-05 05:50:36.264  5748  5870 D bt_bte_conf:   vendorId            = 000f
,10-05 05:50:36.264  5748  5870 D bt_bte_conf:   vendorIdSource      = 0001
10-05 05:50:36.264  5748  5870 D bt_bte_conf:   product             = 1200
10-05 05:50:36.264  5748  5870 D bt_bte_conf:   version             = 1436
10-05 05:50:36.265  5748  5870 D bt_bte_conf:   clientExecutableURL = 
10-05 05:50:36.265  5748  5870 D bt_bte_conf:   serviceDescription  = 
10-05 05:50:36.265  5748  5870 D bt_bte_conf:   documentationURL    = 
10-05 05:50:36.265  5748  5870 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 05:50:36.265  5748  5867 D bt_stack_manager: event_start_up_stack finished
10-05 05:50:36.266  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 05:50:36.267  5748  5866 D BluetoothAdapterProperties: Setting state to 15
,10-05 05:50:36.267  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 05:50:36.268  5748  5866 I BluetoothAdapterState: Entering BleOnState
,10-05 05:50:36.271  5748  5866 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 05:50:36.271  5748  5866 D BluetoothAdapterProperties: Setting state to 11
,10-05 05:50:36.271  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 05:50:36.276  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:36.278  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:36.280  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:36.280  5748  5748 D HeadsetService: Received start request. Starting profile...
10-05 05:50:36.281  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:36.283  5748  5748 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-05 05:50:36.283  5748  5748 D HeadsetStateMachine: make
,10-05 05:50:36.290  5748  5866 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:36.292  5748  5748 D HeadsetStateMachine: max_hf_connections = 1
,10-05 05:50:36.292  5748  5748 I bt_bluedroid: get_profile_interface handsfree
10-05 05:50:36.292  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 05:50:36.293  5748  5870 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-05 05:50:36.296  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:36.296  5748  5748 D A2dpService: Received start request. Starting profile...
,10-05 05:50:36.297  5748  5748 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-05 05:50:36.297  5748  5748 I bt_bluedroid: get_profile_interface avrcp
,10-05 05:50:36.302  5748  5748 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 05:50:36.302  5748  5748 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 05:50:36.302  5748  5748 D A2dpStateMachine: make
10-05 05:50:36.303  5748  5748 I bt_bluedroid: get_profile_interface a2dp
,10-05 05:50:36.304  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 05:50:36.305  5748  5885 D A2dpStateMachine: Enter Disconnected: -2
,10-05 05:50:36.306  5748  5748 I BluetoothHidServiceJni: classInitNative: succeeds
10-05 05:50:36.307  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:36.308  5748  5748 D HidService: Received start request. Starting profile...
10-05 05:50:36.308  5683  5683 D BluetoothInputDevice: Proxy object connected
,10-05 05:50:36.308  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 05:50:36.308  5748  5748 I bt_bluedroid: get_profile_interface hidhost
10-05 05:50:36.308  5748  5748 D HidService: setHidService(): set to: null
,10-05 05:50:36.308  5748  5870 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf418b56d
10-05 05:50:36.308  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-05 05:50:36.309  5748  5748 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 05:50:36.309  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:36.310  5683  5683 D HidProfile: Bluetooth service connected
10-05 05:50:36.310  5748  5748 D HealthService: Received start request. Starting profile...
,10-05 05:50:36.312  5748  5748 I bt_bluedroid: get_profile_interface health
,10-05 05:50:36.312  5748  5748 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-05 05:50:36.313  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:36.314  5683  5683 D BluetoothPan: BluetoothPAN Proxy object connected
,10-05 05:50:36.314  5748  5748 D PanService: Received start request. Starting profile...
10-05 05:50:36.314  5748  5748 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 05:50:36.314  5748  5748 I bt_bluedroid: get_profile_interface pan
10-05 05:50:36.315  5683  5683 D PanProfile: Bluetooth service connected
10-05 05:50:36.315  5748  5870 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-05 05:50:36.317  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:36.318  5683  5683 D BluetoothMap: Proxy object connected
,10-05 05:50:36.318  5683  5683 D MapProfile: Bluetooth service connected
10-05 05:50:36.319  5683  5683 D BluetoothMap: getConnectedDevices()
10-05 05:50:36.319  5748  5748 D BluetoothMapService: Received start request. Starting profile...
10-05 05:50:36.319  5748  5748 D BluetoothMapService: start()
10-05 05:50:36.319  5683  5683 D BluetoothMap: Bluetooth is Not enabled
,10-05 05:50:36.321  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 05:50:36.322  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 05:50:36.322  5748  5748 D BluetoothMapAppObserver: createReceiver()
,10-05 05:50:36.323  5748  5748 D BluetoothMapAppObserver: initObservers()
,10-05 05:50:36.323  5748  5748 D BluetoothMapAppObserver: getEnabledAccountItems()
10-05 05:50:36.328  5748  5748 V SapService: SapBinder()
10-05 05:50:36.328  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:36.330  5748  5748 D SapService: Received start request. Starting profile...
,10-05 05:50:36.330  5748  5748 V SapService: start()
,10-05 05:50:36.332  5748  5748 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:36.332  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.332  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.332  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.332  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.333  5748  5883 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.333  5748  5748 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.334  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.335  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 05:50:36.335  5748  5748 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:36.335  5748  5748 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:36.336  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:36.336  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:36.336  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 05:50:36.336  5748  5866 D BluetoothAdapterProperties: ScanMode =  20
10-05 05:50:36.336  5748  5866 D BluetoothAdapterProperties: State =  11
10-05 05:50:36.336  5748  5866 D BluetoothAdapterProperties: Setting state to 12
10-05 05:50:36.336  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 05:50:36.337  3120  3132 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 05:50:36.337  5748  5870 D BluetoothAdapterProperties: Scan Mode:21
10-05 05:50:36.337  5748  5866 I BluetoothAdapterState: Entering OnState
10-05 05:50:36.337  5748  5870 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 05:50:36.338  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 05:50:36.340   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 05:50:36.340  5683  5697 D BluetoothMap: onBluetoothStateChange: up=true
,10-05 05:50:36.341  3120  3120 D BluetoothA2dp: Proxy object connected
10-05 05:50:36.341  3782  4108 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:36.342  3120  3972 D BluetoothPan: onBluetoothStateChange on: true
10-05 05:50:36.343  3120  3120 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 05:50:36.343  3120  3120 D PanProfile: Bluetooth service connected
,10-05 05:50:36.343   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:36.344  3120  3134 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:36.344  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:36.345  3120  3972 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 05:50:36.346  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:36.346   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-05 05:50:36.346  3120  3120 D BluetoothInputDevice: Proxy object connected
10-05 05:50:36.346  3120  3120 D HidProfile: Bluetooth service connected
10-05 05:50:36.347   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:36.347   930   930 D BluetoothA2dp: Proxy object connected
10-05 05:50:36.347  5683  5696 D BluetoothPan: onBluetoothStateChange on: true
10-05 05:50:36.347  5683  5697 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 05:50:36.348  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 05:50:36.348  3120  3134 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:36.349  3120  3972 D BluetoothMap: onBluetoothStateChange: up=true
10-05 05:50:36.349  5748  5748 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:36.350  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:36.351  3120  3120 D BluetoothMap: Proxy object connected
10-05 05:50:36.351  3120  3120 D MapProfile: Bluetooth service connected
10-05 05:50:36.351  5683  5696 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-05 05:50:36.351  3120  3120 D BluetoothMap: getConnectedDevices()
10-05 05:50:36.351  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:36.352   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 05:50:36.353  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:36.355  5683  5683 D LocalBluetoothProfileManager: Adding local A2DP profile
10-05 05:50:36.356  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:36.357  5748  5748 D ObexServerSockets: Succeed to create listening sockets 
10-05 05:50:36.357  5748  5748 D ObexServerSockets0: startAccept()
10-05 05:50:36.358  5748  5748 D ObexServerSockets0: prepareForNewConnect()
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:36.358  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:36.359  5683  5683 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-05 05:50:36.360  5748  5748 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 05:50:36.360  5748  5748 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 05:50:36.361  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:36.361  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-05 05:50:36.363  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:36.363  5748  5748 D BluetoothMapService: onReceive
10-05 05:50:36.363  5748  5894 D ObexServerSockets0: Accepting socket connection...
,10-05 05:50:36.363  5748  5895 D ObexServerSockets0: Accepting socket connection...
10-05 05:50:36.363  5748  5748 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 05:50:36.363  5748  5748 D BluetoothMapService: STATE_ON
10-05 05:50:36.364  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:36.365  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:36.365  5748  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:36.366  5748  5896 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 05:50:36.366  5748  5896 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-05 05:50:36.370  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 05:50:36.373  5683  5683 D BluetoothA2dp: Proxy object connected
,10-05 05:50:36.376  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 05:50:36.379  5683  5683 D DockEventReceiver: finishStartingService: stopping service
,10-05 05:50:36.384  5683  5683 D BluetoothPbap: Proxy object connected
10-05 05:50:36.385  5683  5683 D PbapServerProfile: Bluetooth service connected
10-05 05:50:36.386  3120  3120 D BluetoothPbap: Proxy object connected
10-05 05:50:36.386  3120  3120 D PbapServerProfile: Bluetooth service connected
,10-05 05:50:36.389  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 05:50:36.389  5748  5748 D ObexServerSockets0: prepareForNewConnect()
,10-05 05:50:36.390  5748  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 05:50:36.405  5748  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 05:50:36.406  5748  5904 I BtOppRfcommListener: Accept thread started.
,10-05 05:50:36.443  3120  3132 D BluetoothHeadset: Proxy object connected
,10-05 05:50:36.443  3120  3120 D HeadsetProfile: Bluetooth service connected
10-05 05:50:36.443   930   930 D BluetoothHeadset: Proxy object connected
10-05 05:50:36.443   930   930 D BluetoothHeadset: Proxy object connected
10-05 05:50:36.444   930   947 D BluetoothHeadset: Proxy object connected
10-05 05:50:36.444  3782  3982 D BluetoothHeadset: Proxy object connected
10-05 05:50:36.444   930   930 D BluetoothHeadset: Proxy object connected
,10-05 05:50:36.447   930   947 D BluetoothHeadset: Proxy object connected
,10-05 05:50:36.449  3120  3134 D BluetoothHeadset: Proxy object connected
,10-05 05:50:36.449  3120  3120 D HeadsetProfile: Bluetooth service connected
,10-05 05:50:36.462  5683  5697 D BluetoothHeadset: Proxy object connected
,10-05 05:50:36.463  5683  5683 D HeadsetProfile: Bluetooth service connected
,10-05 05:50:36.799   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:37.800   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 05:50:38.185   930  2964 D ConnectivityService: handlePromptUnvalidated 101
,10-05 05:50:40.384  5748  5866 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 05:50:40.385  5748  5866 D BluetoothAdapterProperties: Setting state to 13
,10-05 05:50:40.385  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-05 05:50:40.386  5748  5866 D BluetoothAdapterProperties: onBluetoothDisable()
,10-05 05:50:40.388  5748  5866 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:40.393  5748  5748 D BluetoothMapService: onReceive
,10-05 05:50:40.393  5748  5748 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-05 05:50:40.393  5748  5748 D BluetoothMapService: STATE_TURNING_OFF
,10-05 05:50:40.394  5748  5748 D BluetoothMapService: MAP Service closeService in
10-05 05:50:40.394  5748  5748 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 05:50:40.394  5748  5748 D ObexServerSockets0: shutdown(block = true)
10-05 05:50:40.395  5748  5748 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 05:50:40.395  5748  5894 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-05 05:50:40.396  5748  5748 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-05 05:50:40.396  5748  5879 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 05:50:40.396  5748  5895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 05:50:40.398  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:40.398  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:40.399  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.399  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:40.401  5748  5870 D BluetoothAdapterProperties: Scan Mode:20
,10-05 05:50:40.401  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 05:50:40.403  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 05:50:40.403  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.403  5748  5748 I BtOppRfcommListener: stopping Accept Thread
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:40.403  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:40.404  5748  5904 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 05:50:40.404  5748  5904 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 05:50:40.406  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.407  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:40.411  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:40.412  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:40.412  5748  5748 D HeadsetService: Received stop request...Stopping profile...
,10-05 05:50:40.413  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 05:50:40.413  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:50:40.416  3120  3972 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:40.416  5683  5683 D DockEventReceiver: finishStartingService: stopping service
10-05 05:50:40.417   930   930 D BluetoothHeadset: Proxy object disconnected
,10-05 05:50:40.417  5748  5748 D A2dpService: Received stop request...Stopping profile...
,10-05 05:50:40.417   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:40.417  5748  5885 D A2dpStateMachine: Exit Disconnected: -1
10-05 05:50:40.417  5683  5696 D BluetoothHeadset: Proxy object disconnected
10-05 05:50:40.418  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.418  3782  3818 D BluetoothHeadset: Proxy object disconnected
,10-05 05:50:40.418   930   930 D BluetoothHeadset: Proxy object disconnected
,10-05 05:50:40.419   930   930 D BluetoothA2dp: Proxy object disconnected
,10-05 05:50:40.419  5683  5683 D HeadsetProfile: Bluetooth service disconnected
10-05 05:50:40.420  5683  5683 D BluetoothA2dp: Proxy object disconnected
10-05 05:50:40.421  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.422  5748  5748 D HidService: Received stop request...Stopping profile...
10-05 05:50:40.422  5748  5748 D HidService: Stopping Bluetooth HidService
10-05 05:50:40.423  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:40.424  5748  5748 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:40.424  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.424  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.424  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.427  3120  3120 D HeadsetProfile: Bluetooth service disconnected
10-05 05:50:40.427  3120  3120 D BluetoothA2dp: Proxy object disconnected
10-05 05:50:40.427  3120  3120 D BluetoothInputDevice: Proxy object disconnected
10-05 05:50:40.427  3120  3120 D HidProfile: Bluetooth service disconnected
10-05 05:50:40.425  5683  5683 D BluetoothInputDevice: Proxy object disconnected
10-05 05:50:40.428  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 05:50:40.428  5683  5683 D HidProfile: Bluetooth service disconnected
10-05 05:50:40.430  5748  5748 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 05:50:40.430  5748  5748 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-05 05:50:40.430  5748  5748 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:40.430  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.431  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.431  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.431  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.431  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.431  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.432  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,10-05 05:50:40.432  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 05:50:40.433  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.433  5748  5870 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 05:50:40.433  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.433  5748  5877 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 05:50:40.433  5748  5877 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 05:50:40.433  5748  5877 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-05 05:50:40.433  5748  5877 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-05 05:50:40.435  5748  5748 D HealthService: Received stop request...Stopping profile...
,10-05 05:50:40.437  5748  5748 D PanService: Received stop request...Stopping profile...
10-05 05:50:40.438  3120  3120 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 05:50:40.438  3120  3120 D PanProfile: Bluetooth service disconnected
10-05 05:50:40.439  5748  5748 D BluetoothMapService: Received stop request...Stopping profile...
10-05 05:50:40.439  5748  5748 D BluetoothMapService: stop()
10-05 05:50:40.439  5748  5748 D BluetoothMapAppObserver: deinitObservers()
10-05 05:50:40.439  5748  5748 D BluetoothMapAppObserver: removeReceiver()
10-05 05:50:40.439  5683  5683 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 05:50:40.440  5683  5683 D PanProfile: Bluetooth service disconnected
10-05 05:50:40.441  3120  3120 D BluetoothMap: Proxy object disconnected
10-05 05:50:40.441  5683  5683 D BluetoothMap: Proxy object disconnected
10-05 05:50:40.441  3120  3120 D MapProfile: Bluetooth service disconnected
10-05 05:50:40.441  5748  5748 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:40.441  5683  5683 D MapProfile: Bluetooth service disconnected
10-05 05:50:40.441  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.441  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.441  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.441  5748  5748 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 05:50:40.441  5748  5748 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 05:50:40.442  5748  5870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 05:50:40.443  5748  5748 D SapService: Received stop request...Stopping profile...
10-05 05:50:40.443  5748  5748 V SapService: stop()
,10-05 05:50:40.446  3120  3120 D BluetoothPbap: Proxy object disconnected
10-05 05:50:40.446  3120  3120 D PbapServerProfile: Bluetooth service disconnected
,10-05 05:50:40.446  5748  5748 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:40.446  5748  5748 V BluetoothAdapterState: isTurningOn()=false
,10-05 05:50:40.446  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.446  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 05:50:40.447  5748  5748 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 05:50:40.447  5748  5870 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-05 05:50:40.448  5748  5748 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-05 05:50:40.448  5748  5748 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:40.448  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.448  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.448  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.448  5748  5748 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-05 05:50:40.449  5748  5748 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 05:50:40.450  5748  5748 D BluetoothMapService: MAP Service closeService in
10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isTurningOff()=true
10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.451  5748  5748 D BluetoothMapService: cleanup()
,10-05 05:50:40.451  5748  5748 D BluetoothMapService: MAP Service closeService in
10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isTurningOff()=true
,10-05 05:50:40.451  5748  5748 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:40.452  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:40.452  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:40.452  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 05:50:40.452  5748  5866 D BluetoothAdapterProperties: Setting state to 15
10-05 05:50:40.452  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 05:50:40.452  5748  5866 I BluetoothAdapterState: Entering BleOnState
10-05 05:50:40.453  3120  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 05:50:40.454  5683  5683 D BluetoothPbap: Proxy object disconnected
10-05 05:50:40.454  5683  5683 D PbapServerProfile: Bluetooth service disconnected
10-05 05:50:40.454   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:40.454  5683  5696 D BluetoothMap: onBluetoothStateChange: up=false
10-05 05:50:40.455  3782  3813 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:40.455  3120  3132 D BluetoothPan: onBluetoothStateChange on: false
10-05 05:50:40.457   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 05:50:40.457  3120  3134 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 05:50:40.457  5683  5697 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 05:50:40.458  3120  3972 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 05:50:40.458   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 05:50:40.458   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:40.459  5683  5696 D BluetoothPan: onBluetoothStateChange on: false
10-05 05:50:40.459  5683  5697 D BluetoothPbap: onBluetoothStateChange: up=false
,10-05 05:50:40.460  5683  5696 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:40.460  3120  3132 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 05:50:40.460  3120  3134 D BluetoothMap: onBluetoothStateChange: up=false
10-05 05:50:40.460  5683  5697 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-05 05:50:40.461  5748  5866 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 05:50:40.461  5748  5866 D BluetoothAdapterProperties: Setting state to 16
10-05 05:50:40.461  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 05:50:40.462  5748  5866 D BluetoothAdapterProperties: onBleDisable
10-05 05:50:40.463  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.464  5748  5866 I BluetoothAdapterState: Entering PendingCommandState
10-05 05:50:40.464  5748  5867 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 05:50:40.465  5748  5870 D BluetoothAdapterProperties: Scan Mode:20
10-05 05:50:40.465  5748  5877 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 05:50:40.466  5748  5877 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 05:50:40.466  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 05:50:40.467  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.469  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.471  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.473  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:40.475  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 05:50:40.475  5683  5683 D DockEventReceiver: finishStartingService: stopping service
10-05 05:50:40.475  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:40.677  5748  5870 I bt_hci  : shut_down
,10-05 05:50:40.682  5748  5874 D bt_hwcfg: hw_epilog_process
,10-05 05:50:40.684  5748  5874 I bt_vendor: low_power_mode_cb
,10-05 05:50:40.686  5748  5874 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 05:50:40.686  5748  5874 I bt_vendor: epilog_cb
10-05 05:50:40.686  5748  5874 I bt_hci  : epilog_finished_callback
,10-05 05:50:40.690  5748  5870 I bt_hci_h4: hal_close
,10-05 05:50:40.690  5748  5870 I bt_userial_vendor: device fd = 54 close
,10-05 05:50:40.804  5748  5867 D bt_stack_manager: event_shut_down_stack finished.
,10-05 05:50:40.805  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 05:50:40.810  5748  5866 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-05 05:50:40.811  5748  5748 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 05:50:40.812  5748  5748 D BtGatt.GattService: Received stop request...Stopping profile...
,10-05 05:50:40.812  5748  5748 D BtGatt.GattService: stop()
10-05 05:50:40.812  5748  5748 D BtGatt.AdvertiseManager: advertise clients cleared
,10-05 05:50:40.816  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,10-05 05:50:40.816  5748  5748 V BluetoothAdapterState: isTurningOn()=false
,10-05 05:50:40.816  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:40.816  5748  5748 V BluetoothAdapterState: isBleTurningOff()=true
,10-05 05:50:40.817  5748  5866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-05 05:50:40.817  5748  5866 D BluetoothAdapterProperties: Setting state to 10
,10-05 05:50:40.817  5748  5866 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 05:50:40.818  5748  5866 I BluetoothAdapterState: Entering OffState
10-05 05:50:40.820   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-05 05:50:40.846  5748  5748 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-05 05:50:40.847  5748  5748 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 05:50:40.847  5748  5748 I BluetoothServiceJni: cleanupNative: return from cleanup
10-05 05:50:40.847  5748  5867 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 05:50:40.856  5748  5748 I art     : System.exit called, status: 0
,10-05 05:50:40.856  5748  5748 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 05:50:40.887   930  3837 I ActivityManager: Process com.android.bluetooth (pid 5748) has died
,10-05 05:50:45.381  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:45.382  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:45.387  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:45.387  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14de8eb removed from the list
,10-05 05:50:45.388  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:45.388  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:45.388  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:45.390  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:45.390  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a3fce1 added. We now have 4 listener(s)
10-05 05:50:45.391  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:50:45.394  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:45.394  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a3fce1 removed from the list
10-05 05:50:45.395  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:45.395  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:50:45.395  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:45.398  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 05:50:45.398  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e56a06 added. We now have 4 listener(s)
10-05 05:50:45.398  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:50:50.409  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:50.448   930   947 I ActivityManager: Start proc 5912:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-05 05:50:50.531  5912  5912 D AdapterServiceConfig: Adding HeadsetService
,10-05 05:50:50.532  5912  5912 D AdapterServiceConfig: Adding A2dpService
10-05 05:50:50.532  5912  5912 D AdapterServiceConfig: Adding HidService
10-05 05:50:50.532  5912  5912 D AdapterServiceConfig: Adding HealthService
10-05 05:50:50.532  5912  5912 D AdapterServiceConfig: Adding PanService
10-05 05:50:50.532  5912  5912 D AdapterServiceConfig: Adding GattService
,10-05 05:50:50.533  5912  5912 D AdapterServiceConfig: Adding BluetoothMapService
,10-05 05:50:50.543  5912  5912 D AdapterServiceConfig: Adding SapService
,10-05 05:50:50.556   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1549ec1:true
,10-05 05:50:50.556  5912  5912 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 05:50:50.559  5912  5912 I bt_bluedroid: init
,10-05 05:50:50.559  5912  5924 I BluetoothAdapterState: Entering OffState
,10-05 05:50:50.561  5912  5925 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 05:50:50.561  5912  5925 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 05:50:50.562  5912  5925 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 05:50:50.562  5912  5925 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-05 05:50:50.562  5912  5912 I bt_bluedroid: get_profile_interface socket
,10-05 05:50:50.564  5912  5912 I bt_bluedroid: get_profile_interface sdp
,10-05 05:50:50.564  5912  5928 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-05 05:50:50.566  5912  5928 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 05:50:50.572  5912  5923 I bt_bluedroid: config_hci_snoop_log
,10-05 05:50:50.573   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 05:50:50.578  5912  5924 D BluetoothAdapterState: Current state: OFF, message: 0
10-05 05:50:50.578  5912  5924 D BluetoothAdapterProperties: Setting state to 14
10-05 05:50:50.578  5912  5924 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 05:50:50.580  5912  5924 D BluetoothBondStateMachine: make
,10-05 05:50:50.581  5912  5929 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 05:50:50.584  5912  5924 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:50.586  5912  5912 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 05:50:50.588  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:50.588  5912  5912 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 05:50:50.590  5912  5912 D BtGatt.GattService: Received start request. Starting profile...
10-05 05:50:50.590  5912  5912 D BtGatt.GattService: start()
10-05 05:50:50.591  5912  5912 I bt_bluedroid: get_profile_interface gatt
10-05 05:50:50.592  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:50.592  5912  5912 D BtGatt.AdvertiseManager: advertise manager created
,10-05 05:50:50.598  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:50.598  5912  5912 V BluetoothAdapterState: isTurningOn()=false
10-05 05:50:50.598  5912  5912 V BluetoothAdapterState: isBleTurningOn()=true
10-05 05:50:50.598  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:50.598  5912  5924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-05 05:50:50.600  5912  5924 I bt_bluedroid: bt_bluedroid
,10-05 05:50:50.600  5912  5925 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-05 05:50:50.600  5912  5925 I bt_hci  : start_up
,10-05 05:50:50.606  5912  5925 I bt_vendor: alloc value 0xf427f871
,10-05 05:50:50.606  5912  5925 I bt_vendor: init
10-05 05:50:50.606  5912  5925 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 05:50:50.606  5912  5925 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 05:50:50.715  5912  5925 D bt_hci  : start_up starting async portion
10-05 05:50:50.715  5912  5932 I bt_hci  : event_finish_startup
10-05 05:50:50.716  5912  5932 I bt_hci_h4: hal_open
10-05 05:50:50.716  5912  5932 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 05:50:50.713  5933  5933 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 05:50:50.718  5912  5932 I bt_userial_vendor: device fd = 54 open
,10-05 05:50:50.734  5912  5932 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 05:50:50.737  5912  5932 D bt_hwcfg: Chipset BCM4358A3
10-05 05:50:50.737  5912  5932 D bt_hwcfg: Target name = [BCM4358A3]
,10-05 05:50:50.737  5912  5932 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 05:50:51.241  5912  5932 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 05:50:51.242  5912  5932 D bt_hwcfg: Settlement delay -- 100 ms
10-05 05:50:51.242  5912  5932 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 05:50:51.377  5912  5932 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 05:50:51.377  5912  5932 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-05 05:50:51.379  5912  5932 I bt_hwcfg: vendor lib fwcfg completed
10-05 05:50:51.379  5912  5932 I bt_vendor: firmware callback
10-05 05:50:51.379  5912  5932 I bt_hci  : firmware_config_callback
,10-05 05:50:51.389  5912  5935 I bt_btu  : btu_task pending for preload complete event
,10-05 05:50:51.389  5912  5935 I bt_btu_task: Bluetooth chip preload is complete
10-05 05:50:51.389  5912  5935 I bt_btu  : btu_task received preload complete event
,10-05 05:50:51.395  5912  5935 I         : BTE_InitTraceLevels -- TRC_HCI
10-05 05:50:51.395  5912  5935 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 05:50:51.395  5912  5935 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_A2D
,10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_BNEP
10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_GAP
,10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 05:50:51.396  5912  5935 I         : BTE_InitTraceLevels -- TRC_SDP
,10-05 05:50:51.397  5912  5935 I         : BTE_InitTraceLevels -- TRC_GATT
10-05 05:50:51.397  5912  5935 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 05:50:51.397  5912  5935 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-05 05:50:51.397  5912  5935 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 05:50:51.493  5912  5935 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41fd549
,10-05 05:50:51.493  5912  5935 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41fd549 
,10-05 05:50:51.512  5912  5928 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 05:50:51.514  5912  5928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-05 05:50:51.515  5912  5928 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-05 05:50:51.518  5912  5928 D BluetoothAdapterProperties: Name is: Nexus 6P
10-05 05:50:51.521  5912  5928 D BluetoothAdapterProperties: Scan Mode:20
10-05 05:50:51.521  5912  5928 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 05:50:51.522  5912  5928 D bt_hci  : do_postload posting postload work item
10-05 05:50:51.522  5912  5932 I bt_hci  : event_postload
10-05 05:50:51.522  5912  5932 I bt_vendor: sco_config_cb
10-05 05:50:51.522  5912  5932 I bt_hci  : sco_config_callback postload finished.
,10-05 05:50:51.527  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:51.527  5912  5928 D bt_bte_conf: Device ID record 1 : primary
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   vendorId            = 000f
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   vendorIdSource      = 0001
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   product             = 1200
,10-05 05:50:51.528  5912  5928 D bt_bte_conf:   version             = 1436
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   clientExecutableURL = 
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   serviceDescription  = 
10-05 05:50:51.528  5912  5928 D bt_bte_conf:   documentationURL    = 
10-05 05:50:51.528  5912  5928 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 05:50:51.529  5912  5925 D bt_stack_manager: event_start_up_stack finished
10-05 05:50:51.530  5912  5924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 05:50:51.530  5912  5924 D BluetoothAdapterProperties: Setting state to 15
10-05 05:50:51.531  5912  5924 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 05:50:51.532  5912  5924 I BluetoothAdapterState: Entering BleOnState
10-05 05:50:51.533  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:51.536  5912  5924 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 05:50:51.536  5912  5924 D BluetoothAdapterProperties: Setting state to 11
10-05 05:50:51.536  5912  5924 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 05:50:51.537  5912  5932 I bt_vendor: low_power_mode_cb
,10-05 05:50:51.544  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:51.545  5912  5912 D HeadsetService: Received start request. Starting profile...
10-05 05:50:51.547  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:50:51.548  5912  5912 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 05:50:51.548  5912  5912 D HeadsetStateMachine: make
10-05 05:50:51.550  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:51.561  5912  5924 I BluetoothAdapterState: Entering PendingCommandState
,10-05 05:50:51.562  5912  5912 D HeadsetStateMachine: max_hf_connections = 1
10-05 05:50:51.562  5912  5912 I bt_bluedroid: get_profile_interface handsfree
10-05 05:50:51.562  5912  5928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 05:50:51.566  5912  5928 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-05 05:50:51.569  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 05:50:51.571  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:51.572  5912  5912 D A2dpService: Received start request. Starting profile...
10-05 05:50:51.573  5912  5912 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-05 05:50:51.573  5912  5912 I bt_bluedroid: get_profile_interface avrcp
,10-05 05:50:51.580  5912  5912 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 05:50:51.580  5912  5912 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 05:50:51.580  5912  5912 D A2dpStateMachine: make
10-05 05:50:51.582  5912  5912 I bt_bluedroid: get_profile_interface a2dp
,10-05 05:50:51.582  5912  5928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 05:50:51.584  5912  5943 D A2dpStateMachine: Enter Disconnected: -2
10-05 05:50:51.584  5912  5912 I BluetoothHidServiceJni: classInitNative: succeeds
,10-05 05:50:51.585  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:51.586  5912  5912 D HidService: Received start request. Starting profile...
10-05 05:50:51.586  5912  5912 I bt_bluedroid: get_profile_interface hidhost
,10-05 05:50:51.586  5912  5912 D HidService: setHidService(): set to: null
10-05 05:50:51.586  5912  5928 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41de56d
10-05 05:50:51.586  5912  5928 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-05 05:50:51.587  5912  5912 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 05:50:51.587  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:51.588  5912  5912 D HealthService: Received start request. Starting profile...
10-05 05:50:51.589  5912  5912 I bt_bluedroid: get_profile_interface health
10-05 05:50:51.590  5912  5912 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-05 05:50:51.591  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:51.591  5912  5912 D PanService: Received start request. Starting profile...
,10-05 05:50:51.592  5912  5912 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 05:50:51.592  5912  5912 I bt_bluedroid: get_profile_interface pan
10-05 05:50:51.592  5912  5928 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-05 05:50:51.595  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
10-05 05:50:51.596  5912  5912 D BluetoothMapService: Received start request. Starting profile...
10-05 05:50:51.596  5912  5912 D BluetoothMapService: start()
10-05 05:50:51.599  5912  5912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-05 05:50:51.600  5912  5912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 05:50:51.600  5912  5912 D BluetoothMapAppObserver: createReceiver()
10-05 05:50:51.601  5912  5912 D BluetoothMapAppObserver: initObservers()
10-05 05:50:51.601  5912  5912 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 05:50:51.609  5912  5912 V SapService: SapBinder()
10-05 05:50:51.609  5912  5912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:50:51.610  5912  5912 D SapService: Received start request. Starting profile...
10-05 05:50:51.610  5912  5912 V SapService: start()
,10-05 05:50:51.612  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.612  5912  5912 V BluetoothAdapterState: isTurningOn()=true
,10-05 05:50:51.612  5912  5941 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 05:50:51.612  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:51.612  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOff()=false
,10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.613  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
10-05 05:50:51.614  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.615  5912  5912 V BluetoothAdapterState: isTurningOff()=false
10-05 05:50:51.615  5912  5912 V BluetoothAdapterState: isTurningOn()=true
10-05 05:50:51.615  5912  5912 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 05:50:51.616  5912  5912 V BluetoothAdapterState: isBleTurningOff()=false
10-05 05:50:51.616  5912  5924 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 05:50:51.616  5912  5924 D BluetoothAdapterProperties: ScanMode =  20
10-05 05:50:51.616  5912  5924 D BluetoothAdapterProperties: State =  11
10-05 05:50:51.616  5912  5924 D BluetoothAdapterProperties: Setting state to 12
10-05 05:50:51.616  5912  5924 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 05:50:51.617  5912  5924 I BluetoothAdapterState: Entering OnState
10-05 05:50:51.617  3120  3134 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 05:50:51.620  5912  5928 D BluetoothAdapterProperties: Scan Mode:21
10-05 05:50:51.620   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 05:50:51.620  5912  5928 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 05:50:51.620  5683  5697 D BluetoothMap: onBluetoothStateChange: up=true
10-05 05:50:51.621  3120  3120 D BluetoothA2dp: Proxy object connected
10-05 05:50:51.622  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 05:50:51.622  3782  3813 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:51.623  3120  3972 D BluetoothPan: onBluetoothStateChange on: true
,10-05 05:50:51.624  5683  5683 D BluetoothMap: Proxy object connected
10-05 05:50:51.624  5683  5683 D MapProfile: Bluetooth service connected
10-05 05:50:51.624  5683  5683 D BluetoothMap: getConnectedDevices()
10-05 05:50:51.624   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:51.625  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:51.626  3120  3120 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 05:50:51.626  3120  3120 D PanProfile: Bluetooth service connected
10-05 05:50:51.626  3120  3132 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 05:50:51.628  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:50:51.629  5683  5697 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 05:50:51.629  5912  5912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 05:50:51.629  5912  5912 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 05:50:51.631  5912  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 05:50:51.631  3120  3972 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:51.631  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:50:51.633   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-05 05:50:51.633  5912  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:51.634   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:51.634   930   930 D BluetoothA2dp: Proxy object connected
10-05 05:50:51.634  5683  5696 D BluetoothPan: onBluetoothStateChange on: true
10-05 05:50:51.634  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 05:50:51.636  5912  5912 D ObexServerSockets: Succeed to create listening sockets 
10-05 05:50:51.636  5912  5912 D ObexServerSockets0: startAccept()
10-05 05:50:51.636  5912  5912 D ObexServerSockets0: prepareForNewConnect()
10-05 05:50:51.636  5683  5697 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 05:50:51.638  5912  5912 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 05:50:51.638  5912  5912 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 05:50:51.638  5683  5696 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:51.639  3120  3134 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 05:50:51.639  5912  5949 D ObexServerSockets0: Accepting socket connection...
10-05 05:50:51.639  5912  5950 D ObexServerSockets0: Accepting socket connection...
10-05 05:50:51.639  3120  3132 D BluetoothMap: onBluetoothStateChange: up=true
10-05 05:50:51.640  3120  3120 D BluetoothInputDevice: Proxy object connected
10-05 05:50:51.640  3120  3120 D HidProfile: Bluetooth service connected
10-05 05:50:51.641  5683  5683 D BluetoothA2dp: Proxy object connected
10-05 05:50:51.641  3120  3120 D BluetoothMap: Proxy object connected
10-05 05:50:51.641  5683  5697 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 05:50:51.641  3120  3120 D MapProfile: Bluetooth service connected
10-05 05:50:51.641  3120  3120 D BluetoothMap: getConnectedDevices()
10-05 05:50:51.644   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 05:50:51.645  5912  5912 D BluetoothMapService: onReceive
10-05 05:50:51.645  5912  5912 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 05:50:51.645  5912  5912 D BluetoothMapService: STATE_ON
,10-05 05:50:51.646  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 05:50:51.647  5683  5683 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 05:50:51.647  5683  5683 D PanProfile: Bluetooth service connected
10-05 05:50:51.647  5683  5683 D BluetoothInputDevice: Proxy object connected
10-05 05:50:51.647  5683  5683 D HidProfile: Bluetooth service connected
10-05 05:50:51.648  5912  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 05:50:51.648  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:51.651  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:50:51.652  5912  5953 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 05:50:51.652  5912  5953 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-05 05:50:51.654  5683  5683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 05:50:51.661  3568  3568 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 05:50:51.662  5683  5683 D DockEventReceiver: finishStartingService: stopping service
,10-05 05:50:51.668  5912  5912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 05:50:51.668  3120  3120 D BluetoothPbap: Proxy object connected
10-05 05:50:51.668  5912  5912 D ObexServerSockets0: prepareForNewConnect()
10-05 05:50:51.668  3120  3120 D PbapServerProfile: Bluetooth service connected
10-05 05:50:51.669  5683  5683 D BluetoothPbap: Proxy object connected
10-05 05:50:51.669  5683  5683 D PbapServerProfile: Bluetooth service connected
,10-05 05:50:51.677  5912  5957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 05:50:51.689  5912  5961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 05:50:51.690  5912  5961 I BtOppRfcommListener: Accept thread started.
,10-05 05:50:51.721  3120  3132 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.722  3120  3120 D HeadsetProfile: Bluetooth service connected
10-05 05:50:51.722   930   930 D BluetoothHeadset: Proxy object connected
,10-05 05:50:51.722   930   930 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.722  5683  5697 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.722  3782  3982 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.722  3782  4108 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.723   930   930 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.723  5683  5683 D HeadsetProfile: Bluetooth service connected
,10-05 05:50:51.725   930   947 D BluetoothHeadset: Proxy object connected
,10-05 05:50:51.734   930   947 D BluetoothHeadset: Proxy object connected
,10-05 05:50:51.739  5683  5948 D BluetoothHeadset: Proxy object connected
,10-05 05:50:51.739  3120  3134 D BluetoothHeadset: Proxy object connected
10-05 05:50:51.740  5683  5683 D HeadsetProfile: Bluetooth service connected
10-05 05:50:51.740  3120  3120 D HeadsetProfile: Bluetooth service connected
,10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:50:55.425  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:50:55.430  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:50:55.430  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:50:55.431  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e56a06 removed from the list
10-05 05:50:55.431  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:50:55.431  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:50:55.431  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:50:55.433  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:50:55.433  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a028c7 added. We now have 4 listener(s)
10-05 05:50:55.433  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:50:55.437   930  3849 D WifiService: setWifiEnabled: false pid=5621, uid=10077
10-05 05:50:55.438   930  3849 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:50:57.801   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:58.803   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:50:59.804   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:51:00.447  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:00.448   930  3601 D WifiService: setWifiEnabled: true pid=5621, uid=10077
10-05 05:51:00.449   930  3601 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 05:51:00.459   510   924 D SoftapController: Softap fwReload - Ok
,10-05 05:51:00.464   510   924 D CommandListener: Setting iface cfg
,10-05 05:51:00.465   510   924 D CommandListener: Trying to bring down wlan0
10-05 05:51:00.466   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-05 05:51:00.470   930  2962 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 05:51:00.806   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:51:01.136   930  2962 D wifi    : set interface wlan0 flags (UP)
10-05 05:51:01.136   930  2962 I WifiHAL : Initializing wifi
,10-05 05:51:01.136   930  2962 I WifiHAL : Creating socket
,10-05 05:51:01.144   930  2962 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-05 05:51:01.144   930  2962 D wifi    : Did set static halHandle = 0x7f8cf88900
10-05 05:51:01.144   930  2962 D wifi    : halHandle = 0x7f8cf88900, mVM = 0x7fa960d140, mCls = 0x201572
,10-05 05:51:01.144   930  2962 D wifi    : array field set
10-05 05:51:01.145   930  2962 I WifiNative-HAL: interface[0] = wlan0
10-05 05:51:01.147   930  5966 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547825944832
10-05 05:51:01.147   930  5966 D wifi    : waitForHalEvents called, vm = 0x7fa960d140, obj = 0x201572, env = 0x7f9392fc00
,10-05 05:51:01.148   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-05 05:51:01.208  5967  5967 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 05:51:01.229  5967  5967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 05:51:01.253   930  2962 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 05:51:01.257  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:51:01.262  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:51:01.285  5967  5967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 05:51:01.285  5967  5967 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 05:51:01.304   930  2962 D WifiConfigStore: Loading config and enabling all networks 
,10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:51:01.306  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 05:51:01.308  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 05:51:01.311  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 05:51:01.313  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 05:51:01.319   930  2962 D WifiConfigStore: loaded 0 passpoint configs
10-05 05:51:01.320   930  2962 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 05:51:01.320   930  2962 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-05 05:51:01.321   930  2962 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-05 05:51:01.322   930  2962 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 05:51:01.322   930  2962 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 05:51:01.322   930  2962 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 05:51:01.322   930  2962 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 05:51:01.325   930  2962 D WifiNative-HAL: Setting external_sim to 1
,10-05 05:51:01.325  5018  5018 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 05:51:01.325   930  2962 D wifi    : setting dfs flag to true, 0x7f8fb3e0a0
10-05 05:51:01.325   930  2962 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 05:51:01.325   930  2962 D wifi    : setting scan oui 0x7f8fb3e0a0
10-05 05:51:01.326   930  2962 D WifiHAL : Sending mac address OUI
,10-05 05:51:01.330   930  2962 E native  : do suspend false
,10-05 05:51:01.340   930  2962 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-05 05:51:01.340   930   930 D RttService: SCAN_AVAILABLE : 3
10-05 05:51:01.340   510   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 05:51:01.341   930  3072 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 05:51:01.341   510   924 D CommandListener: Setting iface cfg
,10-05 05:51:01.346   930  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-05 05:51:01.346   930  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 05:51:01.356   930  2961 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 05:51:01.362   930  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 05:51:01.362   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303010 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,10-05 05:51:01.807   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 05:51:02.808   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-05 05:51:04.535  5967  5967 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:51:04.541  5967  5967 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:51:04.548  5967  5967 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:51:04.551  5967  5967 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:51:04.553  5967  5967 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 05:51:04.599   930  2962 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 05:51:04.600   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 05:51:04.600   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:51:04.611   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 05:51:04.642   930  2962 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 05:51:04.644  5967  5967 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 05:51:05.062  5967  5967 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 05:51:05.094  5967  5967 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 05:51:05.095  5967  5967 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 05:51:05.103   930  2962 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-05 05:51:05.104   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:51:05.104   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 05:51:05.125   930  2962 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 05:51:05.142   510   924 D CommandListener: Setting iface cfg
,10-05 05:51:05.147   930  2962 D WifiStateMachine: Start Dhcp Watchdog 3
,10-05 05:51:05.152   930  5972 D DhcpClient: Receive thread started
,10-05 05:51:05.157   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 05:51:05.157   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 05:51:05.157   930  2964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-05 05:51:05.237   930  2962 E native  : do suspend false
,10-05 05:51:05.250   930  5971 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 05:51:05.303   930  5972 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-05 05:51:05.304   930  5971 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-05 05:51:05.306   930  5971 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 05:51:05.339   930  5972 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 05:51:05.340   930  5971 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 05:51:05.343   510   924 D CommandListener: Setting iface cfg
10-05 05:51:05.347   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 05:51:05.352   930  5971 D DhcpClient: Scheduling renewal in 86399s
,10-05 05:51:05.365   930  2962 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-05 05:51:05.366   930  2962 D WifiConfigStore: No blacklist allowed without epno enabled
10-05 05:51:05.367   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-05 05:51:05.368   930  2964 D ConnectivityService: Adding iface wlan0 to network 102
10-05 05:51:05.373   930  2962 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 05:51:05.415   930  2964 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 05:51:05.415   930  2964 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-05 05:51:05.422   930  2964 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-05 05:51:05.423   930  2964 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-05 05:51:05.425   930  2964 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-05 05:51:05.435   930  2964 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 05:51:05.438   930  2964 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-05 05:51:05.439   930  2964 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-05 05:51:05.439   930  2964 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-05 05:51:05.439   930  2962 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 05:51:05.439   930  2962 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 05:51:05.439   930  2964 D ConnectivityService:    accepting network in place of null
,10-05 05:51:05.440   930  2964 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 05:51:05.452   930  5970 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307099, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 05:51:05.463   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:05.463  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:05.466  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:51:05.467  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:05.467  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a028c7 removed from the list
10-05 05:51:05.467  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:05.467  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:51:05.467  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:51:05.470  5621  5979 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,10-05 05:51:05.470  5621  5979 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-05 05:51:05.484   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 05:51:05.488   930  2964 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-05 05:51:05.488   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 05:51:05.488  3743  3897 W QCNEJ   : |CORE| network available: 102
,10-05 05:51:05.489   930  2964 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-05 05:51:05.489   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-05 05:51:05.491  3743  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-05 05:51:05.492  3743  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 05:51:05.493  3743  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:05.499  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:05.501  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:51:05.501  5043  5066 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 05:51:05.502  5043  5066 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 05:51:05.502  5043  5066 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 05:51:05.502  5043  5066 E SarControlService: no key has been found,reset the power
10-05 05:51:05.502  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 05:51:05.502  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 05:51:05.502  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 05:51:05.503  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:51:05.503  5068  5068 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 05:51:05.504  5043  5080 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 05:51:05.504  5043  5080 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 05:51:05.505  5043  5080 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 05:51:05.505  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:05.505  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 05:51:05.505  5068  5068 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 05:51:05.507  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:51:05.507  3871  3871 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 05:51:05.510  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000f003000000000000ffffffff]
10-05 05:51:05.510  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:51:05.510  5068  5082 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-05 05:51:05.510  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:51:05.510  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 05:51:05.513  3871  3871 D SystemUpdateService: onCreate
10-05 05:51:05.517  3871  3871 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-05 05:51:05.518  5068  5082 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b38c872 HexData = [00000000f103000000000000ffffffff]
,10-05 05:51:05.519  5068  5082 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 05:51:05.519  5068  5082 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-05 05:51:05.519  5068  5068 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 05:51:05.520  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 05:51:05.525   930  5969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-05 05:51:05.527  3871  3871 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 05:51:05.534  3871  5983 I SystemUpdateService: active receiver: enabled
,10-05 05:51:05.535  3871  5403 I iu.UploadsManager: num queued entries: 0
,10-05 05:51:05.535  3871  5403 I iu.UploadsManager: num updated entries: 0
,10-05 05:51:05.538  3871  3871 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 05:51:05.539  3871  3871 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 05:51:05.541  5763  5763 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 05:51:05.544  5763  5763 D SprintDMHelper: simOperator: 
10-05 05:51:05.544  5763  5763 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 05:51:05.555  3871  5403 I iu.SyncManager: NEXT; no task
,10-05 05:51:05.564  3871  5983 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 05:51:05.573   930  5969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 09:51:05 GMT], X-Android-Received-Millis=[1475661065573], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475661065548]}
,10-05 05:51:05.574   930  2964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-05 05:51:05.574   930  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-05 05:51:05.574   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 05:51:05.576   930  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 05:51:05.578  3871  5983 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-05 05:51:05.578  3871  5983 I SystemUpdateService: now status is 0 (complete)
,10-05 05:51:05.578  3871  5983 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 05:51:05.578  3871  5983 I SystemUpdateService: file has been verified
10-05 05:51:05.578  3871  5983 I SystemUpdateService: OTA package size = 21989297
,10-05 05:51:05.585  3871  5983 I SystemUpdateService: showing system update notification
,10-05 05:51:05.594  3871  3871 D SystemUpdateService: onDestroy
,10-05 05:51:05.644  5018  5987 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 05:51:08.502  5621  5979 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,10-05 05:51:08.502  5621  5996 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-05 05:51:08.503  5621  5996 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-05 05:51:08.503  5621  5979 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-05 05:51:08.504  5621  5979 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 05:51:08.504  5621  5996 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 05:51:08.506  5621  5979 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 05:51:08.506  5621  5996 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 05:51:08.507  5621  5979 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-05 05:51:08.511  5621  5999 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.511  5621  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:08.511  5621  5998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.511  5621  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:08.513  5621  5996 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,10-05 05:51:08.513  5621  6000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.513  5621  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:08.514  5621  6001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.514  5621  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:08.514  5621  6000 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.514  5621  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:08.514  5621  6000 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:08.514  5621  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:08.514  5621  6000 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:08.514  5621  6001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.514  5621  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:08.515  5621  6000 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,10-05 05:51:08.515  5621  6001 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.515  5621  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:08.515  5621  6001 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 05:51:08.517  5621  5998 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: OutgoingSocketThread/Sender): Socket closed
10-05 05:51:08.517  5621  5998 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.517  5621  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-05 05:51:08.517  5621  5998 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 05:51:08.517  5621  5998 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 05:51:08.517  5621  5998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.517  5621  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 05:51:08.519  5621  5999 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 159, thread name: IncomingSocketThread/Sender): Socket closed
10-05 05:51:08.519  5621  5999 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 159, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.519  5621  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-05 05:51:08.520  5621  5999 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 05:51:08.520  5621  5999 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 05:51:08.520  5621  5999 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:08.520  5621  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-05 05:51:11.482  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-05 05:51:11.483  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-05 05:51:11.490  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3d68296 Bundle[{}]
,10-05 05:51:11.491  5621  5668 I io.jxcore.node.LifeCycleMonitor: start: OK
10-05 05:51:11.492  5621  5668 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-05 05:51:11.492  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-05 05:51:11.493  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-05 05:51:11.493  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-05 05:51:11.495  5621  5668 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-05 05:51:11.501  5621  5668 I System.out: Running OutgoingSocketThread
,10-05 05:51:11.503  5621  6002 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,10-05 05:51:11.503  5621  6002 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-05 05:51:13.444   930  2964 D ConnectivityService: handlePromptUnvalidated 102
,10-05 05:51:14.513  5621  6003 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,10-05 05:51:14.513  5621  6003 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-05 05:51:14.514  5621  6003 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 05:51:14.514  5621  6002 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,10-05 05:51:14.514  5621  6002 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-05 05:51:14.514  5621  6002 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 05:51:14.515  5621  6003 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 05:51:14.515  5621  6002 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 05:51:14.517  5621  6003 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-05 05:51:14.517  5621  6002 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
10-05 05:51:14.520  5621  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.520  5621  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 05:51:14.525  5621  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.525  5621  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:14.528  5621  6008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.528  5621  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-05 05:51:14.529  5621  6007 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.529  5621  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 05:51:14.529  5621  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:14.530  5621  6006 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 171, thread name: OutgoingSocketThread/Sender): Socket closed
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:14.530  5621  6006 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 171, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.530  5621  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 05:51:14.530  5621  6008 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:14.530  5621  6008 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:14.530  5621  6006 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,10-05 05:51:14.530  5621  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:14.530  5621  6008 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:14.530  5621  6005 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 05:51:14.530  5621  6006 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 05:51:14.531  5621  6005 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:14.531  5621  6008 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-05 05:51:14.531  5621  6007 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:14.531  5621  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.531  5621  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 05:51:14.531  5621  6007 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:14.531  5621  6005 I io.jxcore.node.IncomingSocketThread: The sending thread is done
,10-05 05:51:14.531  5621  6008 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.531  5621  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 05:51:14.531  5621  6007 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-05 05:51:14.531  5621  6005 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
10-05 05:51:14.531  5621  6007 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
10-05 05:51:14.531  5621  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 05:51:14.531  5621  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 05:51:14.531  5621  6007 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 05:51:14.531  5621  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-05 05:51:16.364   930  2962 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-05 05:51:17.514  5621  5668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
10-05 05:51:17.515  5621  5668 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-05 05:51:17.515  5621  5668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 183)
,10-05 05:51:17.521  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 05:51:17.522  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b882ef4 added. We now have 3 listener(s)
10-05 05:51:17.525  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.525  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 05:51:17.525  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.525  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.525  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c02861d added. We now have 4 listener(s)
10-05 05:51:17.526  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.526  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 05:51:17.531  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:17.535  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:17.538  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:51:17.538  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:51:17.538  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 05:51:17.538  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dec8a63 added. We now have 4 listener(s)
,10-05 05:51:17.540  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.541  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.541  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.541  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.541  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b734660 added. We now have 5 listener(s)
10-05 05:51:17.541  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.541  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 05:51:17.541  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.541  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:51:17.541  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.541  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.542  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:51:17.542  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.542  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.542  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 05:51:17.542  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b882ef4 removed from the list
10-05 05:51:17.542  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.542  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c02861d removed from the list
10-05 05:51:17.546  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:51:17.546  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:17.546  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:51:17.547  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.547  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.548  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.548  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.548  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.548  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c02861d not in the list
10-05 05:51:17.548  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.548  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.549  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 05:51:17.549  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.549  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.549  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b734660 removed from the list
10-05 05:51:17.550  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.550  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.550  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.550  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.550  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.550  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dec8a63 removed from the list
10-05 05:51:17.551  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.551  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc66719 added. We now have 3 listener(s)
10-05 05:51:17.553  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.553  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.553  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 05:51:17.553  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.553  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@739b3de added. We now have 4 listener(s)
10-05 05:51:17.553  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.554  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 05:51:17.558  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:17.562  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:17.564  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.564  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 05:51:17.564  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.564  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f36688c added. We now have 4 listener(s)
,10-05 05:51:17.566  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.566  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.566  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.566  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.566  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64d5bd5 added. We now have 5 listener(s)
10-05 05:51:17.566  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:51:17.566  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.567  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 05:51:17.567  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 05:51:17.567  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:51:17.567  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 05:51:17.567  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:51:17.570  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 05:51:17.570  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 05:51:17.571  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 05:51:17.573  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 05:51:17.574  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:51:17.574  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 05:51:17.577  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 05:51:17.578  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-05 05:51:17.578  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:51:17.578  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 05:51:17.578  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:51:17.578  5621  5668 D BluetoothAdapter: STATE_ON
,10-05 05:51:17.582  5912  5939 D BtGatt.GattService: registerClient() - UUID=76f14a43-fb59-409a-9e55-bc00ac72ec41
,10-05 05:51:17.583  5912  5928 D BtGatt.GattService: onClientRegistered() - UUID=76f14a43-fb59-409a-9e55-bc00ac72ec41, clientIf=5
,10-05 05:51:17.583  5621  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 05:51:17.584  5912  5952 D BtGatt.GattService: start scan with filters
10-05 05:51:17.587  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 05:51:17.588  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 05:51:17.588  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.588  5912  5931 D BtGatt.ScanManager: handling starting scan
10-05 05:51:17.588  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 05:51:17.588  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:51:17.588  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:51:17.588  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 05:51:17.590  5912  5931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24f893b
,10-05 05:51:17.591  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:51:17.591  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:51:17.591  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 05:51:17.592  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:51:17.595  5621  5668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 05:51:17.595  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 05:51:17.595  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 05:51:17.595  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.595  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 05:51:17.595  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.595  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 05:51:17.595  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:51:17.595  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:51:17.595  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-05 05:51:17.596  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 05:51:17.596  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:51:17.596  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:51:17.597  5912  5928 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:51:17.597  5912  5939 D BtGatt.GattService: stopScan() - queue size =1
10-05 05:51:17.597  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.597  5912  5952 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 05:51:17.598  5912  5931 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 05:51:17.598  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:51:17.598  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:51:17.598  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:51:17.598  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.599  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 05:51:17.599  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 05:51:17.599  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:51:17.599  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-05 05:51:17.600  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.601  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 05:51:17.601  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 05:51:17.601  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 05:51:17.601  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-05 05:51:17.601  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:51:17.602  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:51:17.603  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:51:17.603  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.604  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:51:17.604  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.604  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 05:51:17.604  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 05:51:17.604  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.604  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.605  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.605  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 05:51:17.605  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.605  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.605  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc66719 removed from the list
10-05 05:51:17.605  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.605  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@739b3de removed from the list
10-05 05:51:17.605  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:17.605  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.605  5912  5931 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:51:17.605  5912  5931 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 05:51:17.606  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 05:51:17.606  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.607  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.607  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.607  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.607  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@739b3de not in the list
10-05 05:51:17.607  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.607  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:51:17.608  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.608  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.608  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.608  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64d5bd5 removed from the list
10-05 05:51:17.608  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 05:51:17.608  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.608  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.608  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.608  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.608  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f36688c removed from the list
10-05 05:51:17.609  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 05:51:17.609  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f14e051 added. We now have 3 listener(s)
10-05 05:51:17.611  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.611  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.611  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.611  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.611  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e260b6 added. We now have 4 listener(s)
10-05 05:51:17.611  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 05:51:17.612  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 05:51:17.614  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:51:17.618  5912  5928 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 05:51:17.618  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:17.618  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:17.620  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 05:51:17.620  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:51:17.620  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.620  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0f3d24 added. We now have 4 listener(s)
10-05 05:51:17.622  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.622  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.622  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.622  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 05:51:17.622  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6308d added. We now have 5 listener(s)
10-05 05:51:17.622  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.622  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.623  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.623  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.623  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 05:51:17.623  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 05:51:17.623  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:51:17.623  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 05:51:17.623  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 05:51:17.623  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:51:17.627  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.627  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 05:51:17.627  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 05:51:17.632  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 05:51:17.632  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:51:17.632  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.632  5912  5931 D BtGatt.ScanManager: stopping BLe Batch
,10-05 05:51:17.633  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:51:17.633  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 05:51:17.636  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 05:51:17.636  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-05 05:51:17.636  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:51:17.636  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 05:51:17.636  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:51:17.637  5621  5668 D BluetoothAdapter: STATE_ON
,10-05 05:51:17.638  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 05:51:17.638  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.639  5912  5931 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 05:51:17.641  5912  5923 D BtGatt.GattService: registerClient() - UUID=0f36fdd5-0382-464c-9118-593956ce06fd
10-05 05:51:17.641  5912  5928 D BtGatt.GattService: onClientRegistered() - UUID=0f36fdd5-0382-464c-9118-593956ce06fd, clientIf=5
,10-05 05:51:17.641  5621  5731 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 05:51:17.643  5912  5952 D BtGatt.GattService: start scan with filters
,10-05 05:51:17.644  5912  5928 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 05:51:17.644  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.645  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 05:51:17.645  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-05 05:51:17.645  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.645  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 05:51:17.645  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:51:17.645  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:51:17.645  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 05:51:17.646  5912  5931 D BtGatt.ScanManager: handling starting scan
,10-05 05:51:17.647  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 05:51:17.647  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:51:17.647  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:51:17.648  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:51:17.651  5912  5928 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:51:17.651  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.651  5912  5931 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 05:51:17.652  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.652  5621  5668 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-05 05:51:17.652  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:51:17.652  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.652  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 05:51:17.652  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.652  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.652  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 05:51:17.652  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.653  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.653  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f14e051 removed from the list
10-05 05:51:17.653  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.653  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e260b6 removed from the list
10-05 05:51:17.653  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:17.653  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:51:17.653  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.654  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 05:51:17.654  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.654  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:51:17.656  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e260b6 not in the list
10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:51:17.656  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:51:17.656  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 05:51:17.656  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:51:17.656  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 05:51:17.656  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.657  5912  5931 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:51:17.657  5912  5931 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 05:51:17.657  5621  5668 D BluetoothAdapter: STATE_ON
,10-05 05:51:17.658  5912  5952 D BtGatt.GattService: stopScan() - queue size =1
,10-05 05:51:17.659  5912  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:51:17.659  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 05:51:17.659  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:51:17.659  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 05:51:17.660  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.660  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-05 05:51:17.661  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 05:51:17.661  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 05:51:17.661  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 05:51:17.661  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.662  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.662  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.662  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.662  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:51:17.662  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6308d removed from the list
10-05 05:51:17.662  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.662  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 05:51:17.662  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.662  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.662  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.662  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.662  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.662  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0f3d24 removed from the list
10-05 05:51:17.663  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.663  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3224889 added. We now have 3 listener(s)
10-05 05:51:17.664  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.664  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.664  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.664  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 05:51:17.664  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa8d08e added. We now have 4 listener(s)
10-05 05:51:17.665  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.665  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 05:51:17.665  5912  5928 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 05:51:17.665  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.667  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:51:17.670  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 05:51:17.671  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:17.672  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:17.674  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.674  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 05:51:17.674  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.674  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66b0cbc added. We now have 4 listener(s)
10-05 05:51:17.676  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.676  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.676  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 05:51:17.676  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.676  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edde445 added. We now have 5 listener(s)
10-05 05:51:17.676  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.676  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.676  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 05:51:17.676  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.676  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 05:51:17.676  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 05:51:17.676  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 05:51:17.676  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:51:17.677  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.677  5912  5931 D BtGatt.ScanManager: stopping BLe Batch
10-05 05:51:17.678  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.679  5621  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 05:51:17.679  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 05:51:17.682  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 05:51:17.682  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.682  5912  5931 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 05:51:17.682  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 05:51:17.683  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 05:51:17.683  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 05:51:17.687  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 05:51:17.687  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 05:51:17.687  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 05:51:17.687  5912  5928 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 05:51:17.688  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.688  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 05:51:17.688  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 05:51:17.688  5621  5668 D BluetoothAdapter: STATE_ON
10-05 05:51:17.690  5912  5951 D BtGatt.GattService: registerClient() - UUID=b6377341-3304-4415-94f6-2470acf61686
10-05 05:51:17.690  5912  5928 D BtGatt.GattService: onClientRegistered() - UUID=b6377341-3304-4415-94f6-2470acf61686, clientIf=5
,10-05 05:51:17.690  5621  5731 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 05:51:17.691  5912  5952 D BtGatt.GattService: start scan with filters
10-05 05:51:17.693  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-05 05:51:17.693  5912  5931 D BtGatt.ScanManager: handling starting scan
10-05 05:51:17.693  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 05:51:17.693  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.693  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 05:51:17.693  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 05:51:17.693  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 05:51:17.693  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 05:51:17.695  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:51:17.695  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 05:51:17.695  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 05:51:17.696  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 05:51:17.697  5912  5928 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 05:51:17.697  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.698  5912  5931 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 05:51:17.700  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:51:17.700  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.700  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:51:17.700  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.700  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.700  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 05:51:17.700  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 05:51:17.700  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.700  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3224889 removed from the list
10-05 05:51:17.700  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.700  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa8d08e removed from the list
10-05 05:51:17.700  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:17.700  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:51:17.701  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.701  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 05:51:17.701  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.701  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.702  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa8d08e not in the list
10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 05:51:17.702  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 05:51:17.702  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 05:51:17.702  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 05:51:17.702  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 05:51:17.702  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.703  5912  5931 D BtGatt.ScanManager: Starting BLE batch scan
10-05 05:51:17.703  5912  5931 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 05:51:17.703  5621  5668 D BluetoothAdapter: STATE_ON
,10-05 05:51:17.704  5912  5951 D BtGatt.GattService: stopScan() - queue size =1
10-05 05:51:17.704  5912  5952 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 05:51:17.705  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 05:51:17.705  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 05:51:17.705  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 05:51:17.706  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.706  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 05:51:17.706  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 05:51:17.706  5621  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 05:51:17.706  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 05:51:17.706  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.707  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.707  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.707  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.707  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:51:17.707  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edde445 removed from the list
10-05 05:51:17.707  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.707  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 05:51:17.707  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.707  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 05:51:17.707  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.708  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.708  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.708  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66b0cbc removed from the list
10-,05 05:51:17.708  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.708  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd7fc1 added. We now have 3 listener(s)
10-05 05:51:17.710  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.710  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.710  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 05:51:17.710  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.710  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7226366 added. We now have 4 listener(s)
10-05 05:51:17.711  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.711  5912  5928 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 05:51:17.711  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.711  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 05:51:17.714  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 05:51:17.717  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 05:51:17.717  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 05:51:17.721  5621  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 05:51:17.722  5912  5928 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 05:51:17.722  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 05:51:17.723  5912  5931 D BtGatt.ScanManager: stopping BLe Batch
,10-05 05:51:17.723  5621  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 05:51:17.723  5621  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 05:51:17.723  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 05:51:17.723  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34e3754 added. We now have 4 listener(s)
10-05 05:51:17.724  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 05:51:17.724  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 05:51:17.724  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 05:51:17.725  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 05:51:17.725  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2156fd added. We now have 5 listener(s)
10-05 05:51:17.725  5621  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 05:51:17.725  5621  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 05:51:17.725  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.725  5621  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 05:51:17.725  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.725  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.725  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 05:51:17.725  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.725  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.725  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd7fc1 removed from the list
10-05 05:51:17.725  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:51:17.725  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7226366 removed from the list
10-05 05:51:17.726  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.728  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 05:51:17.728  5621  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-05 05:51:17.728  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.728  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.728  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.729  5912  5928 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 05:51:17.729  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:51:17.729  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.729  5912  5931 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 05:51:17.729  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.729  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 05:51:17.729  5621  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7226366 not in the list
10-05 05:51:17.729  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.729  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 05:51:17.730  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 05:51:17.730  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 05:51:17.730  5621  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 05:51:17.730  5621  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2156fd removed from the list
10-05 05:51:17.731  5621  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 05:51:17.731  5621  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 05:51:17.731  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 05:51:17.731  5621  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 05:51:17.731  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 05:51:17.731  5621  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34e3754 removed from the list
10-05 05:51:17.731  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-05 05:51:17.731  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-05 05:51:17.732  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-05 05:51:17.732  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:17.732  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-05 05:51:17.732  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:17.734  5912  5928 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 05:51:17.734  5912  5928 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 05:51:18.104  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 05:51:18.164  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 05:51:18.209  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 05:51:19.884  5621  6009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 05:51:19.884  5621  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:20.718  5621  6009 W !!      : call onHalfStreamCopied
,10-05 05:51:20.718  5621  6009 I testCopyDataAndClose: closing input stream
,10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 05:51:21.494  5621  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 05:51:23.293   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 05:51:25.270  5621  6011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:25.270  5621  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:26.315   930  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 05:51:27.270  5621  5668 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 194. Connection data: Peer properties: [null null].
10-05 05:51:27.270  5621  5668 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:27.270  5621  5668 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 194, name: My test thread name)
,10-05 05:51:27.323  5621  6011 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-05 05:51:27.323  5621  6011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:27.323  5621  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,10-05 05:51:27.428  5621  6012 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 05:51:27.428  5621  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:27.808   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 05:51:27.809   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:29.110  5621  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:29.111  5621  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:29.111  5621  6012 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:29.111  5621  6012 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-05 05:51:29.111  5621  6012 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 05:51:29.111  5621  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 05:51:32.863  5621  6013 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 198, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.863  5621  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 198, thread name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 05:51:32.864  5621  6013 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 05:51:32.865  5621  6013 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 198, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.865  5621  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-05 05:51:32.866  5621  5668 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 05:51:32.869  5621  6014 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.869  5621  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 05:51:32.869  5621  6014 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 202, thread name: My test thread name): Test exception.
,10-05 05:51:32.870  5621  6014 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 202, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.870  5621  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 05:51:32.870  5621  6014 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-05 05:51:32.870  5621  6014 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: My test thread name). Connection data: Peer properties: [null null].
10-05 05:51:32.870  5621  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 05:51:32.875  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
10-05 05:51:32.875  5621  5668 I jxcore-log: 
10-05 05:51:32.875  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-05 05:51:32.875  5621  5668 I jxcore-log: 
,10-05 05:51:32.876  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Number of failed tests:  2'
10-05 05:51:32.876  5621  5668 I jxcore-log: 
10-05 05:51:32.876  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-05 05:51:32.876  5621  5668 I jxcore-log: 
10-05 05:51:32.876  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Total duration:  102896'
10-05 05:51:32.876  5621  5668 I jxcore-log: 
10-05 05:51:32.877  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Failures: 
10-05 05:51:32.877  5621  5668 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-05 05:51:32.877  5621  5668 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
10-05 05:51:32.877  5621  5668 I jxcore-log:      but: was ""
10-05 05:51:32.877  5621  5668 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-05 05:51:32.877  5621  5668 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
10-05 05:51:32.877  5621  5668 I jxcore-log:      but: was ""
10-05 05:51:32.877  5621  5668 I jxcore-log: '
10-05 05:51:32.877  5621  5668 I jxcore-log: 
10-05 05:51:32.878  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-05 05:51:32.878  5621  5668 I jxcore-log: 
10-05 05:51:32.879  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-05 05:51:32.879  5621  5668 I jxcore-log: 
,10-05 05:51:32.882  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.882  5621  5668 I jxcore-log: 
10-05 05:51:32.883  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.883  5621  5668 I jxcore-log: 
10-05 05:51:32.883  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.883  5621  5668 I jxcore-log: 
10-05 05:51:32.883  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.883  5621  5668 I jxcore-log: 
,10-05 05:51:32.884  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 05:51:32.884  5621  5668 I jxcore-log: 
,10-05 05:51:32.884  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.884  5621  5668 I jxcore-log: 
10-05 05:51:32.884  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.884  5621  5668 I jxcore-log: 
,10-05 05:51:32.885  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.885  5621  5668 I jxcore-log: 
10-05 05:51:32.885  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 05:51:32.885  5621  5668 I jxcore-log: 
10-05 05:51:32.885  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.885  5621  5668 I jxcore-log: 
,10-05 05:51:32.885  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.885  5621  5668 I jxcore-log: 
10-05 05:51:32.885  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.885  5621  5668 I jxcore-log: 
10-05 05:51:32.886  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.886  5621  5668 I jxcore-log: 
10-05 05:51:32.886  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.886  5621  5668 I jxcore-log: 
,10-05 05:51:32.886  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.886  5621  5668 I jxcore-log: 
10-05 05:51:32.887  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.887  5621  5668 I jxcore-log: 
10-05 05:51:32.887  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.887  5621  5668 I jxcore-log: 
,10-05 05:51:32.887  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.887  5621  5668 I jxcore-log: 
10-05 05:51:32.887  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.887  5621  5668 I jxcore-log: 
10-05 05:51:32.887  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.887  5621  5668 I jxcore-log: 
10-05 05:51:32.888  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.888  5621  5668 I jxcore-log: 
10-05 05:51:32.888  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.888  5621  5668 I jxcore-log: 
10-05 05:51:32.889  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.889  5621  5668 I jxcore-log: 
,10-05 05:51:32.890  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.890  5621  5668 I jxcore-log: 
10-05 05:51:32.890  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.890  5621  5668 I jxcore-log: 
10-05 05:51:32.890  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.890  5621  5668 I jxcore-log: 
10-05 05:51:32.891  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.891  5621  5668 I jxcore-log: 
10-05 05:51:32.891  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.891  5621  5668 I jxcore-log: 
10-05 05:51:32.891  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.891  5621  5668 I jxcore-log: 
,10-05 05:51:32.891  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.891  5621  5668 I jxcore-log: 
10-05 05:51:32.891  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.891  5621  5668 I jxcore-log: 
10-05 05:51:32.892  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.892  5621  5668 I jxcore-log: 
10-05 05:51:32.892  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.892  5621  5668 I jxcore-log: 
10-05 05:51:32.892  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.892  5621  5668 I jxcore-log: 
10-05 05:51:32.892  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.892  5621  5668 I jxcore-log: 
10-05 05:51:32.893  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.893  5621  5668 I jxcore-log: 
10-05 05:51:32.893  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.893  5621  5668 I jxcore-log: 
,10-05 05:51:32.893  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.893  5621  5668 I jxcore-log: 
10-05 05:51:32.893  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 05:51:32.893  5621  5668 I jxcore-log: 
10-05 05:51:32.893  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.893  5621  5668 I jxcore-log: 
10-05 05:51:32.894  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 05:51:32.894  5621  5668 I jxcore-log: 
10-05 05:51:32.894  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.894  5621  5668 I jxcore-log: 
10-05 05:51:32.894  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.894  5621  5668 I jxcore-log: 
,10-05 05:51:32.894  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.894  5621  5668 I jxcore-log: 
10-05 05:51:32.895  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.895  5621  5668 I jxcore-log: 
10-05 05:51:32.895  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.895  5621  5668 I jxcore-log: 
10-05 05:51:32.895  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 05:51:32.895  5621  5668 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-05 05:51:32.895  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.895  5621  5668 I jxcore-log: 
,10-05 05:51:32.895  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.895  5621  5668 I jxcore-log: 
10-05 05:51:32.896  5621  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 05:51:32.896  5621  5668 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-05 05:51:32.896  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 05:51:32.896  5621  5668 I jxcore-log: 
10-05 05:51:32.896  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.896  5621  5668 I jxcore-log: 
,10-05 05:51:32.896  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.896  5621  5668 I jxcore-log: 
10-05 05:51:32.896  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 05:51:32.896  5621  5668 I jxcore-log: 
10-05 05:51:32.901  5621  5621 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-05 05:51:32.902  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-05 05:51:32.902  5621  5668 I jxcore-log: 
10-05 05:51:32.902  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - WARN testUtils: 'myNameCallback not set!'
10-05 05:51:32.902  5621  5668 I jxcore-log: 
10-05 05:51:32.903  5621  5668 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-05 05:51:32.904  5621  5668 I jxcore-log: 2016-10-05 09:51:32 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-05 05:51:32.904  5621  5668 I jxcore-log: 
,10-05 05:51:33.363  5621  5668 I jxcore-log: 2016-10-05 09:51:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-05 05:51:33.363  5621  5668 I jxcore-log: 
,10-05 05:51:33.745  5621  5668 I jxcore-log: 2016-10-05 09:51:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-05 05:51:33.745  5621  5668 I jxcore-log: 
,10-05 05:51:33.761  5621  5668 I jxcore-log: 2016-10-05 09:51:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-05 05:51:33.761  5621  5668 I jxcore-log: 
,10-05 05:51:34.865  5621  5668 I jxcore-log: 2016-10-05 09:51:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-05 05:51:34.865  5621  5668 I jxcore-log: 
,10-05 05:51:35.030  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-05 05:51:35.030  5621  5668 I jxcore-log: 
,10-05 05:51:35.034  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-05 05:51:35.034  5621  5668 I jxcore-log: 
,10-05 05:51:35.039  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-05 05:51:35.039  5621  5668 I jxcore-log: 
,10-05 05:51:35.580  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-05 05:51:35.580  5621  5668 I jxcore-log: 
,10-05 05:51:35.632  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-05 05:51:35.632  5621  5668 I jxcore-log: 
,10-05 05:51:35.644  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-05 05:51:35.644  5621  5668 I jxcore-log: 
,10-05 05:51:35.648  5621  5668 I jxcore-log: 2016-10-05 09:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-05 05:51:35.648  5621  5668 I jxcore-log: 
,10-05 05:51:36.057  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-05 05:51:36.057  5621  5668 I jxcore-log: 
,10-05 05:51:36.181  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-05 05:51:36.181  5621  5668 I jxcore-log: 
,10-05 05:51:36.409  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-05 05:51:36.409  5621  5668 I jxcore-log: 
,10-05 05:51:36.420  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-05 05:51:36.420  5621  5668 I jxcore-log: 
,10-05 05:51:36.424  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-05 05:51:36.424  5621  5668 I jxcore-log: 
,10-05 05:51:36.429  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-05 05:51:36.429  5621  5668 I jxcore-log: 
,10-05 05:51:36.435  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-05 05:51:36.435  5621  5668 I jxcore-log: 
,10-05 05:51:36.464  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-05 05:51:36.464  5621  5668 I jxcore-log: 
,10-05 05:51:36.501  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-05 05:51:36.501  5621  5668 I jxcore-log: 
,10-05 05:51:36.508  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-05 05:51:36.508  5621  5668 I jxcore-log: 
,10-05 05:51:36.515  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-05 05:51:36.515  5621  5668 I jxcore-log: 
,10-05 05:51:36.529  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-05 05:51:36.529  5621  5668 I jxcore-log: 
,10-05 05:51:36.532  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-05 05:51:36.532  5621  5668 I jxcore-log: 
,10-05 05:51:36.538  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-05 05:51:36.538  5621  5668 I jxcore-log: 
,10-05 05:51:36.542  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-05 05:51:36.542  5621  5668 I jxcore-log: 
,10-05 05:51:36.554  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-05 05:51:36.554  5621  5668 I jxcore-log: 
,10-05 05:51:36.573  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-05 05:51:36.573  5621  5668 I jxcore-log: 
,10-05 05:51:36.583  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-05 05:51:36.583  5621  5668 I jxcore-log: 
,10-05 05:51:36.594  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-05 05:51:36.594  5621  5668 I jxcore-log: 
,10-05 05:51:36.603  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-05 05:51:36.603  5621  5668 I jxcore-log: 
,10-05 05:51:36.615  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-05 05:51:36.615  5621  5668 I jxcore-log: 
,10-05 05:51:36.624  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-05 05:51:36.624  5621  5668 I jxcore-log: 
,10-05 05:51:36.629  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-05 05:51:36.629  5621  5668 I jxcore-log: 
,10-05 05:51:36.650  5621  5668 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-05 05:51:36.651  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - INFO testUtils: 'BLE multiple advertisement supported'
10-05 05:51:36.651  5621  5668 I jxcore-log: 
,10-05 05:51:36.688  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - DEBUG ServerClient: 'connecting to '85.14.110.168:3000''
10-05 05:51:36.688  5621  5668 I jxcore-log: 
,10-05 05:51:36.702  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - DEBUG ServerClient: 'connected to '85.14.110.168:3000''
10-05 05:51:36.702  5621  5668 I jxcore-log: 
,10-05 05:51:36.702  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - DEBUG CoordinatedClient: 'connected to the test server'
10-05 05:51:36.702  5621  5668 I jxcore-log: 
,10-05 05:51:36.770  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-05 05:51:36.770  5621  5668 I jxcore-log: 
,10-05 05:51:36.772  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - DEBUG CoordinatedClient: 'test client failed'
10-05 05:51:36.772  5621  5668 I jxcore-log: 
,10-05 05:51:36.779  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:152:20
10-05 05:51:36.779  5621  5668 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-05 05:51:36.779  5621  5668 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-05 05:51:36.779  5621  5668 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-05 05:51:36.779  5621  5668 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-05 05:51:36.779  5621  5668 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-05 05:51:36.779  5621  5668 I jxcore-log: 
,10-05 05:51:36.780  5621  5668 I jxcore-log: 2016-10-05 09:51:36 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-05 05:51:36.780  5621  5668 I jxcore-log: 
,10-05 05:51:37.324  6015  6015 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-05 05:51:37.329  6015  6015 D AndroidRuntime: CheckJNI is OFF
,10-05 05:51:37.353  6015  6015 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-05 05:51:37.384  6015  6015 I Radio-JNI: register_android_hardware_Radio DONE
,10-05 05:51:37.400  6015  6015 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-05 05:51:37.413   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-05 05:51:37.414   930   943 I ActivityManager: Killing 5621:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-05 05:51:37.524   930  3879 I WindowState: WIN DEATH: Window{c4bdfdd u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-05 05:51:37.524   930  2963 D WifiService: Client connection lost with reason: 4
10-05 05:51:37.524   930  3601 D GraphicsStats: Buffer count: 2
,10-05 05:51:37.546   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-05 05:51:37.547   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-05 05:51:37.548   930   943 E ActivityManager: Failure starting process com.test.thalitest
10-05 05:51:37.548   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-05 05:51:37.548   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:37.548   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:37.548   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 05:51:37.548   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-05 05:51:37.549   930   943 I ActivityManager:   Force finishing activity ActivityRecord{b5e0b66 u0 com.test.thalitest/.MainActivity t2}
10-05 05:51:37.549   930   955 I art     : Starting a blocking GC Explicit
,10-05 05:51:37.559   930  3847 W ActivityManager: Spurious death for ProcessRecord{7e505b1 0:com.test.thalitest/u0a77}, curProc for 5621: null
,10-05 05:51:37.563   930   948 W WindowManager: Attempted to add application window with unknown token Token{5681ea7 ActivityRecord{b5e0b66 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-05 05:51:37.564   930   948 W WindowManager: Token{5681ea7 ActivityRecord{b5e0b66 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{5681ea7 ActivityRecord{b5e0b66 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-05 05:51:37.564   930   948 W WindowManager: view not successfully added to wm, removing view
10-05 05:51:37.564   930   948 W WindowManager: Exception when adding starting window
10-05 05:51:37.564   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{fa3e270 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-05 05:51:37.564   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-05 05:51:37.564   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-05 05:51:37.564   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-05 05:51:37.564   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-05 05:51:37.564   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-05 05:51:37.564   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:37.564   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:37.564   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 05:51:37.564   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-05 05:51:37.630   930   955 I art     : Explicit concurrent mark sweep GC freed 55524(3MB) AllocSpace objects, 16(560KB) LOS objects, 33% free, 28MB/43MB, paused 1.530ms total 80.654ms
,10-05 05:51:37.650   930   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-05 05:51:37.652  6015  6015 I art     : System.exit called, status: 0
,10-05 05:51:37.652  6015  6015 I AndroidRuntime: VM exiting with result code 0.
,10-05 05:51:37.668   930   955 I ActivityManager: Start proc 6025:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-05 05:51:37.669   930   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
10-05 05:51:37.674   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-05 05:51:37.679  5912  5912 D BluetoothMapAppObserver: onReceive
,10-05 05:51:37.679  5912  5912 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-05 05:51:37.680  3653  3653 I Keyboard.Facilitator: resetDictionaries() : en_US
10-05 05:51:37.684  4093  4180 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-05 05:51:37.693   930  2928 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-05 05:51:37.728  3653  6036 I Keyboard.Facilitator.DecoderInitializer: run()
,10-05 05:51:37.730  3387  6039 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-05 05:51:37.734  3653  6036 I Decoder : createOrResetDecoder
,10-05 05:51:37.739  3782  3782 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-05 05:51:37.747   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-05 05:51:37.756    28    28 W kworker/2:1: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 05:51:37.760    28    28 W kworker/2:1: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 05:51:37.775  3814  3934 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-05 05:51:37.779  3568  3568 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-05 05:51:37.780  3568  3568 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
10-05 05:51:37.781  3568  3568 E AndroidRuntime: FATAL EXCEPTION: main
10-05 05:51:37.781  3568  3568 E AndroidRuntime: Process: com.google.process.gapps, PID: 3568
10-05 05:51:37.781  3568  3568 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-05 05:51:37.781  3568  3568 E AndroidRuntime: 	... 8 more
,10-05 05:51:37.776    28    28 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 05:51:37.800   930   940 I ActivityManager: Start proc 6044:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-05 05:51:37.800  3814  3934 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-05 05:51:37.800  3814  3934 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3814
10-05 05:51:37.800  3814  3934 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:37.800  3814  3934 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 05:51:37.802  3387  3410 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjFB79BA900) - 
,10-05 05:51:37.809   930  3115 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:37.812   930  6056 E DropBoxManagerService: Can't write: system_app_crash
10-05 05:51:37.812   930  6056 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 05:51:37.812   930  6056 E DropBoxManagerService: 	... 5 more
,10-05 05:51:37.815  3814  3934 I Process : Sending signal. PID: 3814 SIG: 9
,10-05 05:51:37.815   930  6057 E DropBoxManagerService: Can't write: system_app_crash
10-05 05:51:37.815   930  6057 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 05:51:37.815   930  6057 E DropBoxManagerService: 	... 5 more
10-05 05:51:37.815  3568  3568 I Process : Sending signal. PID: 3568 SIG: 9
,10-05 05:51:37.841   930  2963 D WifiService: Client connection lost with reason: 4
,10-05 05:51:37.842  3387  6039 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-05 05:51:37.843  3387  6039 I Process : Sending signal. PID: 3387 SIG: 9
10-05 05:51:37.845   930  3870 I ActivityManager: Process com.google.process.gapps (pid 3568) has died
10-05 05:51:37.846   930  3870 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
10-05 05:51:37.846   930  3870 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
,10-05 05:51:37.846   930  3870 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
10-05 05:51:37.846   930  3870 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,10-05 05:51:37.867   930  3879 I ActivityManager: Start proc 6060:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,10-05 05:51:37.923   930  3600 D GraphicsStats: Buffer count: 1
,10-05 05:51:37.923   930  3849 I WindowState: WIN DEATH: Window{9ee6e9b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-05 05:51:37.928   930   941 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3814) has died
,10-05 05:51:37.929   930   941 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-05 05:51:37.930   930   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 05:51:37.937   930  3879 I ActivityManager: Process android.process.acore (pid 3387) has died
10-05 05:51:37.938   930  3879 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-05 05:51:37.951   930   943 I ActivityManager: Start proc 6073:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:37.998  6073  6073 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:51:37.998  6073  6073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 05:51:37.999  6073  6073 D AndroidRuntime: Shutting down VM
,10-05 05:51:38.005  6073  6073 E AndroidRuntime: FATAL EXCEPTION: main
10-05 05:51:38.005  6073  6073 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6073
10-05 05:51:38.005  6073  6073 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 05:51:38.005  6073  6073 E AndroidRuntime: 	... 10 more
,10-05 05:51:38.008   930  3601 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:38.008   930  6086 E DropBoxManagerService: Can't write: system_app_crash
10-05 05:51:38.008   930  6086 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 05:51:38.008   930  6086 E DropBoxManagerService: 	... 5 more
10-05 05:51:38.009  6073  6073 I Process : Sending signal. PID: 6073 SIG: 9
,10-05 05:51:38.019   930  3870 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6073) has died
,10-05 05:51:38.020   930  3870 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 05:51:38.035   930   943 I ActivityManager: Start proc 6087:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:38.084  6087  6087 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:51:38.084  6087  6087 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 05:51:38.084  6087  6087 D AndroidRuntime: Shutting down VM
,10-05 05:51:38.091  6087  6087 E AndroidRuntime: FATAL EXCEPTION: main
10-05 05:51:38.091  6087  6087 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6087
10-05 05:51:38.091  6087  6087 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 05:51:38.091  6087  6087 E AndroidRuntime: 	... 10 more
,10-05 05:51:38.094   930  3779 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:38.094   930  6099 E DropBoxManagerService: Can't write: system_app_crash
10-05 05:51:38.094   930  6099 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 05:51:38.094   930  6099 E DropBoxManagerService: 	... 5 more
10-05 05:51:38.095  6087  6087 I Process : Sending signal. PID: 6087 SIG: 9
,10-05 05:51:38.106   930   941 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6087) has died
,10-05 05:51:38.107   930   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 05:51:38.122   930   943 I ActivityManager: Start proc 6100:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 05:51:38.150   382   484 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
