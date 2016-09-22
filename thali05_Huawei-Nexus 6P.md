#### Test 8617437951c5913_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 10:54:50.390   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:54:51.391   541   541 I ServiceManager: Waiting for service AtCmdFwd...
09-22 10:54:51.475  5479  5479 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 10:54:51.480  5479  5479 D AndroidRuntime: CheckJNI is OFF
09-22 10:54:51.486   929  5245 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-22 10:54:51.508  5479  5479 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 10:54:51.541  5479  5479 I Radio-JNI: register_android_hardware_Radio DONE
09-22 10:54:51.556  5479  5479 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 10:54:51.559   929  3151 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 10:54:51.607   929  3151 I ActivityManager: Start proc 5488:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 10:54:51.619  5479  5479 D AndroidRuntime: Shutting down VM
09-22 10:54:51.650   929   940 I ActivityManager: Killing 4881:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-22 10:54:51.990   929   940 I WindowManager: Screenshot max retries 4 of Token{34612f7 ActivityRecord{104def6 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{154d6ce u0 Starting com.test.thalitest} drawState=4
,09-22 10:54:52.053  5488  5488 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 10:54:52.086  5488  5488 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 10:54:52.108  5488  5488 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 6841-6859)
,09-22 10:54:52.108  5488  5488 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 10:54:52.127  5488  5488 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28e1580}
,09-22 10:54:52.127  5488  5488 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 10:54:52.127  5488  5488 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 10:54:52.132  5488  5488 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 10:54:52.134  5488  5488 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 10:54:52.166  5488  5488 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 10:54:52.180  5488  5488 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 10:54:52.180  5488  5488 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 10:54:52.180  5488  5488 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 10:54:52.180  5488  5488 I Adreno  : Build Date                       : 12/06/15
09-22 10:54:52.180  5488  5488 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 10:54:52.180  5488  5488 I Adreno  : Local Branch                     : mybranch17112971
09-22 10:54:52.180  5488  5488 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 10:54:52.180  5488  5488 I Adreno  : Remote Branch                    : NONE
09-22 10:54:52.180  5488  5488 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 10:54:52.228   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@132ea3d:true
,09-22 10:54:52.264   953   953 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16347]" dev="sockfs" ino=16347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 10:54:52.264   953   953 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16347]" dev="sockfs" ino=16347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 10:54:52.276  5488  5488 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 10:54:52.284  5488  5488 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 10:54:52.304   953   953 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30120]" dev="sockfs" ino=30120 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 10:54:52.304   953   953 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30120]" dev="sockfs" ino=30120 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 10:54:52.308  5488  5525 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 10:54:52.310   939   939 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16351]" dev="sockfs" ino=16351 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 10:54:52.310   939   939 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16351]" dev="sockfs" ino=16351 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 10:54:52.315  5488  5512 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 10:54:52.347  5488  5525 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 10:54:52.392   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:54:52.411   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +419ms (total +838ms)
,09-22 10:54:52.435  5488  5488 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5488
,09-22 10:54:52.520  5488  5488 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 10:54:52.645  5488  5528 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -580122320
,09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 10:54:52.649  5488  5528 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250cab1 added. We now have 1 listener(s)
,09-22 10:54:52.651  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-22 10:54:52.652  5488  5528 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:54:52.652  5488  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 10:54:52.652  5488  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 10:54:52.654  5488  5528 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a7304 added. We now have 1 listener(s)
09-22 10:54:52.654  5488  5528 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:54:52.658   929  3032 D WifiService: New client listening to asynchronous messages
,09-22 10:54:52.658  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:54:52.658  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 10:54:52.659  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 10:54:52.659  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 10:54:52.659  5488  5528 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 10:54:52.660  5488  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:54:52.660  5488  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 10:54:52.664  5488  5528 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:54:52.665  5488  5528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:54:52.665  5488  5528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 10:54:52.665  5488  5528 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:54:52.665  5488  5528 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 10:54:52.669  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:54:52.676  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:54:52.683  5488  5488 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 10:54:52.951  5488  5534 W jxcore-log: Initializing JXcore engine
09-22 10:54:52.951  5488  5534 W jxcore-log: JXcore engine is ready
,09-22 10:54:52.974  5534  5534 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11604 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 10:54:52.974  5534  5534 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14408]" dev="sockfs" ino=14408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 10:54:52.974  5534  5534 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-22 10:54:52.974  5534  5534 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30100]" dev="sockfs" ino=30100 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 10:54:52.983  5488  5534 W jxcore-log: Starting JXcore engine
,09-22 10:54:53.033  5488  5534 W jxcore-log: Platform android
09-22 10:54:53.033  5488  5534 W jxcore-log: 
09-22 10:54:53.034  5488  5534 W jxcore-log: Process ARCH arm
09-22 10:54:53.034  5488  5534 W jxcore-log: 
,09-22 10:54:53.128  5488  5534 I jxcore-log: JXcore Cordova bridge is ready!
09-22 10:54:53.128  5488  5534 I jxcore-log: 
,09-22 10:54:53.128  5488  5534 W jxcore-log: JXcore engine is started
,09-22 10:54:53.132  5488  5528 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 10:54:53.135  5488  5488 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 10:54:53.393   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:54:54.394   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:54:55.394   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 10:54:59.646  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 10:54:59.646  5488  5534 I jxcore-log: 
,09-22 10:54:59.648  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 10:54:59.648  5488  5534 I jxcore-log: 
,09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:54:59.651  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 10:54:59.653  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 10:54:59.655  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 10:54:59.655  5488  5534 I jxcore-log: 
,09-22 10:54:59.657  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 10:54:59.657  5488  5534 I jxcore-log: 
,09-22 10:55:00.008  5488  5534 D executeNativeTests: Running unit tests
,09-22 10:55:00.044  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 10:55:00.044  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d added. We now have 2 listener(s)
09-22 10:55:00.045  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:00.045  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:00.045  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:00.045  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 10:55:00.045  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 added. We now have 2 listener(s)
09-22 10:55:00.045  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:00.046  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:55:00.047  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.049  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 10:55:00.050  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.051  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:00.052  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 10:55:00.052  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 10:55:00.052  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 10:55:00.053  5488  5534 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 10:55:00.053  5488  5534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 10:55:00.053  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-22 10:55:00.053  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-22 10:55:00.053  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 10:55:00.053  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.053  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.053  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.053  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.053  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 10:55:00.053  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.054  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:00.054  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d removed from the list
09-22 10:55:00.054  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.054  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 removed from the list
09-22 10:55:00.059  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.059  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.059  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.060  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.060  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.063  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.064  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.064  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.064  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.065  5488  5534 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 10:55:00.065  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 10:55:00.065  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.065  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.065  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.065  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 10:55:00.065  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.065  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.065  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.065  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.067  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.067  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.067  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.067  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.067  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 10:55:00.067  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.068  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.068  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.068  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 10:55:00.068  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-22 10:55:00.071  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 10:55:00.072  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.072  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.072  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.072  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.072  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.072  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.072  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.072  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.072  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.072  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.072  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.072  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:00.072  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.072  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.073  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 10:55:00.073  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.073  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.073  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
,09-22 10:55:00.073  5488  5534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 10:55:00.074  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.076  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:55:00.077  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.077  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:00.077  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:00.077  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:00.077  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 10:55:00.077  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.077  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:00.079  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.079  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 10:55:00.079  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 10:55:00.080  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.082  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 10:55:00.083  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 10:55:00.083  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 10:55:00.084  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-22 10:55:00.085  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 10:55:00.085  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 10:55:00.085  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:00.085  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 10:55:00.086  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.088  4455  4470 D BtGatt.GattService: registerClient() - UUID=2bc292b4-3395-4e04-8432-3c5c7b996642
09-22 10:55:00.088  4455  4517 D BtGatt.GattService: onClientRegistered() - UUID=2bc292b4-3395-4e04-8432-3c5c7b996642, clientIf=5
09-22 10:55:00.089  5488  5499 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 10:55:00.090  4455  4469 D BtGatt.GattService: start scan with filters
09-22 10:55:00.094  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 10:55:00.094  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:00.094  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 10:55:00.094  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 10:55:00.094  4455  4520 D BtGatt.ScanManager: handling starting scan
09-22 10:55:00.095  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.095  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:00.096  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.096  4455  4520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:00.096  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 10:55:00.097  5488  5534 I io.jxcore.node.ConnectionHelper: start: OK
09-22 10:55:00.098  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.098  5488  5534 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 10:55:00.098  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.099  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 10:55:00.099  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.099  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:00.099  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 10:55:00.099  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:00.099  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:00.099  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:00.099  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:00.099  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:00.100  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.100  4455  4470 D BtGatt.GattService: stopScan() - queue size =1
09-22 10:55:00.100  4455  4469 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:00.100  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:00.100  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:00.100  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:00.100  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 10:55:00.100  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:00.101  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.101  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:00.101  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:00.101  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 10:55:00.102  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.102  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.103  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.103  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.103  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.103  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.103  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.103  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.103  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.103  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.103  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.103  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.103  5488  5534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 10:55:00.103  4455  4517 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 10:55:00.103  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.104  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.104  4455  4520 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.106  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:55:00.109  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.109  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:00.109  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:00.109  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:00.109  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 10:55:00.109  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.109  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:00.109  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:00.109  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.110  4455  4520 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:00.110  4455  4520 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 10:55:00.110  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.111  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.116  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 10:55:00.116  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 10:55:00.119  4455  4517 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:00.119  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.119  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 10:55:00.120  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 10:55:00.120  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 10:55:00.123  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 10:55:00.123  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:00.123  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 10:55:00.123  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.124  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:00.124  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.126  4455  4469 D BtGatt.GattService: registerClient() - UUID=065c0e66-4ddc-4c6b-bc6c-495cafc9e0ad
09-22 10:55:00.126  4455  4517 D BtGatt.GattService: onClientRegistered() - UUID=065c0e66-4ddc-4c6b-bc6c-495cafc9e0ad, clientIf=5
09-22 10:55:00.127  5488  5499 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 10:55:00.127  4455  4470 D BtGatt.GattService: start scan with filters
09-22 10:55:00.130  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 10:55:00.130  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:00.130  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 10:55:00.130  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 10:55:00.130  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 10:55:00.130  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.130  4455  4520 D BtGatt.ScanManager: stopping BLe Batch
09-22 10:55:00.131  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.131  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:00.131  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.131  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 10:55:00.132  5488  5534 I io.jxcore.node.ConnectionHelper: start: OK
09-22 10:55:00.133  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.133  5488  5534 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 10:55:00.133  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.133  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 10:55:00.133  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.133  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:00.133  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 10:55:00.133  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-22 10:55:00.133  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:00.133  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:00.133  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:00.134  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:00.134  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.134  4455  4653 D BtGatt.GattService: stopScan() - queue size =0
09-22 10:55:00.134  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 10:55:00.135  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.135  4455  4469 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:00.135  4455  4520 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 10:55:00.135  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:00.135  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:00.135  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:00.135  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 10:55:00.135  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:00.136  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.136  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:00.136  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:00.136  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 10:55:00.137  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.137  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.137  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.137  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.137  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.137  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.137  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.137  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.137  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.137  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.137  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.137  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.138  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.138  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.139  4455  4517 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 10:55:00.139  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.139  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.139  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.139  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.139  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.139  5488  5534 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 10:55:00.140  4455  4520 D BtGatt.ScanManager: handling starting scan
09-22 10:55:00.140  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.142  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:55:00.145  4455  4517 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 10:55:00.145  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.145  4455  4520 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 10:55:00.146  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.146  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:00.146  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:00.146  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:00.147  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 10:55:00.147  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.147  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:00.148  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.149  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:00.149  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.149  4455  4520 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:00.149  4455  4520 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 10:55:00.150  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 10:55:00.150  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 10:55:00.150  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.156  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 10:55:00.156  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 10:55:00.156  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 10:55:00.157  4455  4517 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:00.157  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.158  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 10:55:00.158  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:00.158  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 10:55:00.159  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.160  4455  4469 D BtGatt.GattService: registerClient() - UUID=17d582f6-efb3-4dd1-aa6b-0a17329f5652
09-22 10:55:00.161  4455  4517 D BtGatt.GattService: onClientRegistered() - UUID=17d582f6-efb3-4dd1-aa6b-0a17329f5652, clientIf=5
09-22 10:55:00.161  5488  5499 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 10:55:00.161  4455  4470 D BtGatt.GattService: start scan with filters
09-22 10:55:00.162  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:00.162  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.163  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 10:55:00.163  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:00.163  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 10:55:00.163  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 10:55:00.165  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.165  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:00.165  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:00.166  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 10:55:00.167  5488  5534 I io.jxcore.node.ConnectionHelper: start: OK
09-22 10:55:00.167  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.167  5488  5534 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 10:55:00.167  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.167  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 10:55:00.167  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.167  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:00.167  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 10:55:00.167  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:00.167  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:00.167  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:00.167  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:00.167  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:00.167  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:00.168  4455  4653 D BtGatt.GattService: stopScan() - queue size =0
09-22 10:55:00.169  4455  4470 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:00.169  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 10:55:00.169  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.169  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:00.169  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:00.169  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:00.169  4455  4520 D BtGatt.ScanManager: stopping BLe Batch
09-22 10:55:00.170  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 10:55:00.170  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:00.170  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.170  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:00.170  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:00.170  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 10:55:00.170  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.173  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.173  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.173  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.173  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.173  5488  5534 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 10:55:00.173  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.173  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.173  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.173  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.173  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:00.173  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.173  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.173  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
,09-22 10:55:00.173  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.173  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.174  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.174  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 10:55:00.174  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.174  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.174  4455  4520 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 10:55:00.175  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.175  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.175  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.175  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.175  5488  5534 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-22 10:55:00.176  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.176  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.176  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.176  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.176  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.176  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.176  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.176  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.176  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.176  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.176  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.176  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.176  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.176  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.177  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.177  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.177  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.177  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.177  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 10:55:00.177  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.177  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.177  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.177  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.177  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.177  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.177  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.177  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.177  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.177  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.177  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.178  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.178  4455  4517 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 10:55:00.178  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.178  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.178  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.178  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.178  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.178  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.178  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.178  5488  5534 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 10:55:00.178  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.178  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.178  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.179  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.179  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.179  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.179  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.179  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.179  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.179  4455  4520 D BtGatt.ScanManager: handling starting scan
09-22 10:55:00.179  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.179  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.179  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.179  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.179  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.180  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.180  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.180  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.180  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.183  4455  4517 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 10:55:00.180  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 10:55:00.183  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.183  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.183  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.183  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.184  4455  4520 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 10:55:00.184  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.184  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.184  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.184  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.184  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.184  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.184  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.184  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.184  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.184  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.184  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.184  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.184  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.184  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.184  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.185  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 10:55:00.185  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 10:55:00.185  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 10:55:00.185  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 10:55:00.185  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 10:55:00.185  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 10:55:00.185  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.185  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.185  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.185  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.185  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.185  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.185  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.185  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.185  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.185  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.185  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.185  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.185  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.185  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.186  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.186  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.186  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.186  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.186  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 10:55:00.186  5488  5534 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 10:55:00.186  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 10:55:00.187  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 10:55:00.187  5488  5534 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 10:55:00.187  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 10:55:00.187  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 10:55:00.187  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 10:55:00.187  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 10:55:00.187  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 10:55:00.188  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 10:55:00.188  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 10:55:00.188  5488  5534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 10:55:00.189  5488  5534 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 10:55:00.189  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 10:55:00.189  5488  5534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 10:55:00.189  5488  5534 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-22 10:55:00.189  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 10:55:00.189  5488  5534 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 10:55:00.189  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 10:55:00.190  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 10:55:00.191  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:00.191  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.191  4455  4520 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:00.191  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 10:55:00.191  4455  4520 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 10:55:00.191  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-22 10:55:00.191  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 10:55:00.191  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 10:55:00.191  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 10:55:00.191  5488  5534 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 10:55:00.191  5488  5534 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-22 10:55:00.192  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.192  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.192  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.192  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.192  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.192  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.192  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 10:55:00.193  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.193  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.193  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.193  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.193  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.193  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.193  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.193  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.194  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.194  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.194  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.194  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.194  5488  5534 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 10:55:00.194  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.194  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.194  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.194  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.194  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.194  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.194  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.194  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.194  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.194  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.194  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.194  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.195  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.195  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.195  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.195  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.195  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.195  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.195  5488  5534 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-22 10:55:00.195  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.195  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.195  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.196  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.196  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.196  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.196  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.196  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.196  5488  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-22 10:55:00.196  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.196  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.196  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.196  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.196  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.196  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.196  5488  5535 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 10:55:00.196  5488  5535 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-22 10:55:00.198  4455  4517 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:00.198  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.198  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.198  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.198  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.198  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.198  5488  5534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 10:55:00.198  5488  5534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 10:55:00.198  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 10:55:00.198  5488  5534 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 10:55:00.198  5488  5534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 10:55:00.198  5488  5534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 10:55:00.199  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 10:55:00.199  5488  5534 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 10:55:00.199  5488  5534 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 10:55:00.199  5488  5534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 10:55:00.199  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 10:55:00.199  5488  5534 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 10:55:00.199  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.199  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.199  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.199  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.199  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.199  ,5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.199  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.199  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.199  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.199  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.199  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.199  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.199  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.199  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.200  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.200  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.200  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.200  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.200  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.200  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.200  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.200  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.200  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.200  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.200  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.200  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.200  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.200  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.200  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.201  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.201  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.201  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.201  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.201  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.201  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.201  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.201  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.201  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.201  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.201  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.201  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.202  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.202  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.202  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.202  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.202  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:00.202  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.203  5488  5534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 10:55:00.203  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.203  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-22 10:55:00.203  5488  5534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 10:55:00.203  5488  5534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 10:55:00.204  5488  5488 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 10:55:00.204  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.204  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:00.204  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.204  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.205  5488  5488 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 10:55:00.205  5488  5537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:00.205  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.205  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.206  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.205  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.206  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.206  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.206  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:00.206  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.206  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.206  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:00.206  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.206  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.206  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.206  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.206  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.206  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.206  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.206  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.206  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.207  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.207  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.204  4469  4469 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31464]" dev="sockfs" ino=31464 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 10:55:00.207  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.207  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.207  4455  4517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 10:55:00.207  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.207  5488  5534 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 10:55:00.207  4455  4520 D BtGatt.ScanManager: stopping BLe Batch
09-22 10:55:00.207  5488  5534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 10:55:00.207  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 10:55:00.207  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 10:55:00.207  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.207  5488  5537 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 10:55:00.204  4469  4469 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31464]" dev="sockfs" ino=31464 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 10:55:00.208  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.208  5488  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 10:55:00.208  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.208  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.208  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.208  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.208  5488  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 10:55:00.208  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.208  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.208  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.208  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.208  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.208  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.208  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.208  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.208  5488  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 10:55:00.209  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.209  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.209  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.209  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.211  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.211  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.212  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.212  4455  4517 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 10:55:00.212  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.212  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.212  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.212  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.212  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.212  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.212  4455  4520 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 10:55:00.212  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.212  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.212  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.212  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.212  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.212  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.212  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.212  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.212  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.212  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.213  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:00.213  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:00.213  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:00.213  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:00.213  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.213  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.213  5488  5534 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03a27d not in the list
09-22 10:55:00.213  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.213  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.213  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:00.213  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.213  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.213  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:00.213  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:00.216  4455  4517 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 10:55:00.216  4455  4517 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:00.216  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:00.216  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:00.216  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:00.216  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc7572 not in the list
09-22 10:55:00.217  5488  5534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 10:55:00.217  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 10:55:00.217  5488  5534 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 10:55:00.217  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 10:55:00.217  5488  5534 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 10:55:00.217  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 10:55:00.218  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 10:55:00.218  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-22 10:55:00.219  5488  5534 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 10:55:00.219  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 10:55:00.219  5488  5534 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 10:55:00.219  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 10:55:00.219  5488  5534 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-22 10:55:00.219  5488  5534 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-22 10:55:00.219  5488  5534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-22 10:55:00.219  5488  5534 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 10:55:00.220  5488  5534 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 10:55:00.220  5488  5534 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 10:55:00.220  5488  5534 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 10:55:00.220  5488  5534 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 10:55:00.220  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:00.220  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@113c704 added. We now have 2 listener(s)
09-22 10:55:00.220  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:00.221  5488  5534 D BluetoothAdapter: enable(): BT is already enabled..!
09-22 10:55:00.221   929  3151 D WifiService: setWifiEnabled: true pid=5488, uid=10077
09-22 10:55:00.221   929  3151 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 10:55:00.221  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:00.222  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2724ed added. We now have 3 listener(s)
09-22 10:55:00.222  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:00.224  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:00.224  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3391f22 added. We now have 4 listener(s)
09-22 10:55:00.224  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:00.224  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:00.224  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1acdb3 added. We now have 5 listener(s)
09-22 10:55:00.224  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:00.225   929  3597 D WifiService: setWifiEnabled: false pid=5488, uid=10077
09-22 10:55:00.225   929  3597 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 10:55:00.227   929  3019 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-22 10:55:00.227   929  3019 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-22 10:55:00.227   929  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 10:55:00.228   929  3019 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 10:55:00.229  4455  4513 D BluetoothAdapterState: Current state: ON, message: 23
09-22 10:55:00.229  4455  4513 D BluetoothAdapterProperties: Setting state to 13
09-22 10:55:00.229  4455  4513 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 10:55:00.229  4455  4513 D BluetoothAdapterProperties: onBluetoothDisable()
09-22 10:55:00.230  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:00.230  4455  4513 I BluetoothAdapterState: Entering PendingCommandState
09-22 10:55:00.231  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.231  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:55:00.232  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.232  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.232  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:00.232  4455  4517 D BluetoothAdapterProperties: Scan Mode:20
09-22 10:55:00.233  4455  4513 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 10:55:00.234  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.235  4455  4455 D HeadsetService: Received stop request...Stopping profile...
09-22 10:55:00.236  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.237   929  5246 D DhcpClient: Clearing IP address
09-22 10:55:00.237   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-22 10:55:00.238  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 10:55:00.238  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 10:55:00.239  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.239  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 10:55:00.240  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.242   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:00.242  3168  3706 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:00.242  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.242  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.242  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.242  3569  3596 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:00.242  3168  3168 D HeadsetProfile: Bluetooth service disconnected
09-22 10:55:00.242   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:00.242   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:00.244   509   923 D CommandListener: Setting iface cfg
09-22 10:55:00.245  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:00.246  4455  4455 D A2dpService: Received stop request...Stopping profile...
,09-22 10:55:00.246  4455  4669 D A2dpStateMachine: Exit Disconnected: -1
09-22 10:55:00.247   929  5247 D DhcpClient: Receive thread stopped
09-22 10:55:00.248   929   929 D BluetoothA2dp: Proxy object disconnected
09-22 10:55:00.248  3168  3168 D BluetoothA2dp: Proxy object disconnected
09-22 10:55:00.249  3631  5300 V NativeCrypto: Read error: ssl=0x7f693a4000: I/O error during system call, Connection timed out
09-22 10:55:00.250  3631  5300 V NativeCrypto: SSL shutdown failed: ssl=0x7f693a4000: I/O error during system call, Broken pipe
09-22 10:55:00.250  4455  4455 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 10:55:00.250  4455  4455 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 10:55:00.250  4455  4517 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 10:55:00.251  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 10:55:00.251  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:00.251  4455  4455 D HidService: Received stop request...Stopping profile...
09-22 10:55:00.251  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:00.251  4455  4455 D HidService: Stopping Bluetooth HidService
09-22 10:55:00.251  4455  4517 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 10:55:00.253  3168  3168 D BluetoothInputDevice: Proxy object disconnected
09-22 10:55:00.253  3168  3168 D HidProfile: Bluetooth service disconnected
09-22 10:55:00.255   929  4667 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 10:55:00.255   929  5244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 10:55:00.257   929  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 10:55:00.257   929  3038 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-22 10:55:00.257   539   539 E Parcel  : Reading a NULL string not supported here.
09-22 10:55:00.258   929  5244 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-22 10:55:00.260   929   929 D RttService: SCAN_AVAILABLE : 1
09-22 10:55:00.260   929  3095 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 10:55:00.261   929  3038 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-22 10:55:00.262  4455  4455 D HealthService: Received stop request...Stopping profile...
,09-22 10:55:00.262  3523  3688 W QCNEJ   : |CORE| network lost: 100
,09-22 10:55:00.263  3523  3688 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 10:55:00.264  4455  4455 D PanService: Received stop request...Stopping profile...
09-22 10:55:00.266  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.266  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.266  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.266  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.267  4455  4455 D BluetoothMapService: Received stop request...Stopping profile...
09-22 10:55:00.267  4455  4455 D BluetoothMapService: stop()
09-22 10:55:00.267  4455  4455 D BluetoothMapAppObserver: deinitObservers()
09-22 10:55:00.267  4455  4455 D BluetoothMapAppObserver: removeReceiver()
09-22 10:55:00.269  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:00.269  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:00.271  4455  4517 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 10:55:00.271  4455  4648 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 10:55:00.271  4455  4648 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 10:55:00.271  4455  4455 D SapService: Received stop request...Stopping profile...
09-22 10:55:00.271  4455  4648 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-22 10:55:00.271  4455  4648 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 10:55:00.271  4455  4455 V SapService: stop()
09-22 10:55:00.271   929  3019 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-22 10:55:00.272  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.272  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.272  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.272  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.273  4455  4455 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 10:55:00.273  4455  4455 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 10:55:00.273  4455  4517 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 10:55:00.273  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.273  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.273  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 10:55:00.273  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.273  4455  4455 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 10:55:00.273  4455  4517 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 10:55:00.274  4455  4455 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 10:55:00.275  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.275  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.275  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 10:55:00.275  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.276  4455  4455 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 10:55:00.276  4455  4455 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 10:55:00.277  4455  4455 D BluetoothMapService: MAP Service closeService in
09-22 10:55:00.277  4455  4455 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 10:55:00.277  4455  4455 D ObexServerSockets0: shutdown(block = true)
09-22 10:55:00.277  4455  4675 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 10:55:00.277  4455  4455 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 10:55:00.277  4455  4455 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 10:55:00.277  4455  4676 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 10:55:00.277  4455  4651 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.278  4455  4455 D BluetoothMapService: cleanup()
09-22 10:55:00.278  4455  4455 D BluetoothMapService: MAP Service closeService in
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.278  4455  4455 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:00.279  4455  4513 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 10:55:00.279  4455  4513 D BluetoothAdapterProperties: Setting state to 15
09-22 10:55:00.279  4455  4513 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-22 10:55:00.279  4455  4513 I BluetoothAdapterState: Entering BleOnState
,09-22 10:55:00.281  4455  4455 I BtOppRfcommListener: stopping Accept Thread
,09-22 10:55:00.282  4455  5178 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 10:55:00.282  4455  5178 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 10:55:00.283   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 10:55:00.283  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:00.284  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:00.284  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.284  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:00.285  3168  3168 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 10:55:00.285  3168  3168 D PanProfile: Bluetooth service disconnected
09-22 10:55:00.285  3168  3168 D BluetoothMap: Proxy object disconnected
09-22 10:55:00.285  3168  3168 D MapProfile: Bluetooth service disconnected
09-22 10:55:00.286  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:00.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:00.287  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.287  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:00.288   929  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 10:55:00.293   929   942 I ActivityManager: Start proc 5548:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 10:55:00.294  3168  3706 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 10:55:00.295  3168  3447 D BluetoothPan: onBluetoothStateChange on: false
09-22 10:55:00.295   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 10:55:00.295  3569  3596 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:00.296  3168  3180 D BluetoothMap: onBluetoothStateChange: up=false
09-22 10:55:00.297   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:00.297  3168  3179 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 10:55:00.298   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-22 10:55:00.298   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:00.298  3168  3706 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 10:55:00.299  3168  3447 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 10:55:00.300  4455  4513 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 10:55:00.300  4455  4513 D BluetoothAdapterProperties: Setting state to 16
09-22 10:55:00.300  4455  4513 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 10:55:00.301  4455  4513 D BluetoothAdapterProperties: onBleDisable
,09-22 10:55:00.301  4455  4513 I BluetoothAdapterState: Entering PendingCommandState
09-22 10:55:00.301  4455  4514 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 10:55:00.302  4455  4517 D BluetoothAdapterProperties: Scan Mode:20
09-22 10:55:00.302  4455  4648 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 10:55:00.302  4455  4648 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:00.303  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:00.305  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.306  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.307  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:00.313   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 10:55:00.314   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-22 10:55:00.314   509   923 D TetherController: Setting IP forward enable = 0
,09-22 10:55:00.315   929  3038 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-22 10:55:00.315   929  3038 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-22 10:55:00.316   929  3019 D DhcpClient: doQuit
,09-22 10:55:00.317   929  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 10:55:00.317   929  5246 D DhcpClient: onQuitting
09-22 10:55:00.318   929   946 D Tethering: MasterInitialState.processMessage what=3
09-22 10:55:00.320  3653  3653 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 10:55:00.321  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:00.321  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:00.322  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.322  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:00.324  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:00.324  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:00.325  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:00.325  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:00.327  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.327  5151  5151 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bac426c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-22 10:55:00.329  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:00.331  4865  4880 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-22 10:55:00.331  4865  4880 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 10:55:00.331  4865  4880 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 10:55:00.331  4865  4880 E SarControlService: no key has been found,reset the power
09-22 10:55:00.331  4865  4906 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 10:55:00.331  4865  4906 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 10:55:00.331  4865  4906 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 10:55:00.332  4894  4894 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 10:55:00.332  4894  4894 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 10:55:00.334  4865  4906 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 10:55:00.334  4865  4906 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 10:55:00.334  4865  4906 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 10:55:00.335  4894  4894 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 10:55:00.335  4894  4894 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 10:55:00.338  4894  4908 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b2552b2 HexData = [00000000ea03000000000000ffffffff]
09-22 10:55:00.339  4894  4908 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-22 10:55:00.339  4894  4908 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 10:55:00.339  4894  4894 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 10:55:00.339  4865  4876 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-22 10:55:00.346  4894  4908 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b2552b2 HexData = [00000000eb03000000000000ffffffff]
,09-22 10:55:00.346  4894  4908 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 10:55:00.346  4894  4908 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-22 10:55:00.347  4894  4894 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-22 10:55:00.347  4865  4877 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-22 10:55:00.348  3653  3653 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 10:55:00.353  3653  3653 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-22 10:55:00.355  5548  5548 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-22 10:55:00.366  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 10:55:00.372  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 10:55:00.372   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aa5018e:true
09-22 10:55:00.374   509   923 E Netd    : netlink response contains error (No such file or directory)
,09-22 10:55:00.374   509   923 D TetherController: Setting IP forward enable = 0
,09-22 10:55:00.375   929  3038 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-22 10:55:00.381  3653  3653 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 10:55:00.386   929  3548 I ActivityManager: Start proc 5572:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-22 10:55:00.392  5548  5548 D LocalBluetoothProfileManager: Adding local MAP profile
,09-22 10:55:00.392  3653  3653 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-22 10:55:00.395  5548  5548 D BluetoothMap: Create BluetoothMap proxy object
,09-22 10:55:00.402  5548  5548 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 10:55:00.408  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-22 10:55:00.418   929  3548 I ActivityManager: Killing 4820:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 10:55:00.433  5572  5572 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-22 10:55:00.498   929  3019 D wifi    : In wifi stop Hal
,09-22 10:55:00.498  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 10:55:00.498   929  3019 D wifi    : halHandle = 0x7f681212a0, mVM = 0x7f8410d140, mCls = 0x100b56
09-22 10:55:00.498   929  3651 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 10:55:00.498   929  3651 D WifiHAL : Got a signal to exit!!!
,09-22 10:55:00.498   929  3651 I WifiHAL : Exit wifi_event_loop
09-22 10:55:00.500   929  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 10:55:00.500   929  3019 E WifiHAL : Event processing terminated
09-22 10:55:00.500   929  3019 D wifi    : In wifi cleaned up handler
,09-22 10:55:00.500   929  3019 I WifiHAL : Internal cleanup completed
09-22 10:55:00.500  3493  4039 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 10:55:00.501  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:00.502  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:00.510  4455  4517 I bt_hci  : shut_down
,09-22 10:55:00.514  4455  4521 D bt_hwcfg: hw_epilog_process
,09-22 10:55:00.514  4455  4521 I bt_vendor: low_power_mode_cb
,09-22 10:55:00.517  4455  4521 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 10:55:00.517  4455  4521 I bt_vendor: epilog_cb
09-22 10:55:00.517  4455  4521 I bt_hci  : epilog_finished_callback
09-22 10:55:00.517   929  3651 D wifi    : set interface wlan0 flags (DOWN)
,09-22 10:55:00.518   929  3019 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 10:55:00.520  4455  4517 I bt_hci_h4: hal_close
09-22 10:55:00.520  4455  4517 I bt_userial_vendor: device fd = 54 close
,09-22 10:55:00.611  5572  5572 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.611  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.612  5572  5572 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 10:55:00.612  5572  5572 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 10:55:00.624  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 10:55:00.631  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 10:55:00.634  4455  4514 D bt_stack_manager: event_shut_down_stack finished.
09-22 10:55:00.635  4455  4513 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 10:55:00.636  4455  4513 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 10:55:00.637  4455  4455 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 10:55:00.637  4455  4455 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 10:55:00.637  4455  4455 D BtGatt.GattService: stop()
09-22 10:55:00.638  4455  4455 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 10:55:00.639  4455  4455 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:00.640  4455  4455 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:00.640  4455  4455 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:00.640  4455  4455 V BluetoothAdapterState: isBleTurningOff()=true
09-22 10:55:00.640  5548  5548 D DockEventReceiver: finishStartingService: stopping service
09-22 10:55:00.640  4455  4513 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 10:55:00.640  4455  4513 D BluetoothAdapterProperties: Setting state to 10
09-22 10:55:00.640  4455  4513 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 10:55:00.640  4455  4513 I BluetoothAdapterState: Entering OffState
09-22 10:55:00.643   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-22 10:55:00.648  3944  3944 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-22 10:55:00.651  4455  4455 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 10:55:00.651  4455  4455 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 10:55:00.651  4455  4455 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 10:55:00.653  4455  4514 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-22 10:55:00.657  3944  3944 D SystemUpdateService: onCreate
09-22 10:55:00.661  3944  3944 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-22 10:55:00.665  4455  4514 D bt_stack_manager: event_clean_up_stack finished.
09-22 10:55:00.669  3944  3944 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-22 10:55:00.674  3944  5271 I iu.UploadsManager: num queued entries: 0
09-22 10:55:00.674  3944  5271 I iu.UploadsManager: num updated entries: 0
09-22 10:55:00.675  3944  5271 I iu.SyncManager: NEXT; no task
09-22 10:55:00.679  4455  4455 I art     : System.exit called, status: 0
09-22 10:55:00.679  4455  4455 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-22 10:55:00.704  3944  3944 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-22 10:55:00.706  3944  3944 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-22 10:55:00.707  5488  5488 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-22 10:55:00.707  5274  5274 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-22 10:55:00.711  5274  5274 D SprintDMHelper: simOperator: 
09-22 10:55:00.711  5274  5274 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 10:55:00.721   929   946 D Tethering: InitialState.processMessage what=4
,09-22 10:55:00.721  3944  5604 I SystemUpdateService: active receiver: enabled
,09-22 10:55:00.723   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 10:55:00.728  4314  5606 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 10:55:00.739   929  3151 I ActivityManager: Start proc 5607:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-22 10:55:00.743   929  3152 I ActivityManager: Process com.android.bluetooth (pid 4455) has died
,09-22 10:55:00.742  3944  5604 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 10:55:00.753  3944  5604 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 10:55:00.756  3944  5604 I SystemUpdateService: now status is 0 (complete)
,09-22 10:55:00.756  3944  5604 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 10:55:00.757  3944  5604 I SystemUpdateService: file has been verified
09-22 10:55:00.757  3944  5604 I SystemUpdateService: OTA package size = 21989297
,09-22 10:55:00.772  5607  5607 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 10:55:00.779   929  3597 I ActivityManager: Killing 5151:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-22 10:55:00.794  3944  5604 I SystemUpdateService: showing system update notification
,09-22 10:55:00.856  3944  3944 D SystemUpdateService: onDestroy
,09-22 10:55:00.857   929   940 I ActivityManager: Killing 4527:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 10:55:00.972  5572  5593 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 10:55:00.984   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e78333:true
,09-22 10:55:03.234   929  3151 D WifiService: setWifiEnabled: true pid=5488, uid=10077
,09-22 10:55:03.234   929  3151 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 10:55:03.241   509   923 D SoftapController: Softap fwReload - Ok
,09-22 10:55:03.246   509   923 D CommandListener: Setting iface cfg
,09-22 10:55:03.247   509   923 D CommandListener: Trying to bring down wlan0
09-22 10:55:03.248   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 10:55:03.253   929  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 10:55:03.845   929  3019 D wifi    : set interface wlan0 flags (UP)
,09-22 10:55:03.848   929  3019 I WifiHAL : Initializing wifi
,09-22 10:55:03.851   929  3019 I WifiHAL : Creating socket
,09-22 10:55:03.852   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 10:55:03.859   929  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 10:55:03.859   929  3019 D wifi    : Did set static halHandle = 0x7f681212a0
09-22 10:55:03.859   929  3019 D wifi    : halHandle = 0x7f681212a0, mVM = 0x7f8410d140, mCls = 0x195e
09-22 10:55:03.859   929  3019 D wifi    : array field set
09-22 10:55:03.859   929  3019 I WifiNative-HAL: interface[0] = wlan0
09-22 10:55:03.861   929  5625 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547206861472
09-22 10:55:03.861   929  5625 D wifi    : waitForHalEvents called, vm = 0x7f8410d140, obj = 0x195e, env = 0x7f67af5b80
,09-22 10:55:03.948  5626  5626 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 10:55:03.966   929  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 10:55:03.968  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:03.971  5626  5626 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 10:55:03.972  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:03.996  5626  5626 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 10:55:03.996  5626  5626 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 10:55:04.010   929  3019 D WifiConfigStore: Loading config and enabling all networks 
,09-22 10:55:04.011  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:04.011  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:04.011  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:04.012  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:04.013  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:04.013  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:04.013  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:04.013  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:04.022   929  3019 D WifiConfigStore: loaded 0 passpoint configs
,09-22 10:55:04.023   929  3019 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 10:55:04.023   929  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 10:55:04.024   929  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 10:55:04.026   929  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 10:55:04.026   929  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 10:55:04.026   929  3019 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 10:55:04.026   929  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 10:55:04.030   929  3019 D WifiNative-HAL: Setting external_sim to 1
,09-22 10:55:04.030  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 10:55:04.031   929  3019 D wifi    : setting dfs flag to true, 0x7f6aed8fc0
09-22 10:55:04.031   929  3019 D WifiStateMachine: Setting OUI to DA-A1-19
,09-22 10:55:04.031   929  3019 D wifi    : setting scan oui 0x7f6aed8fc0
09-22 10:55:04.031   929  3019 D WifiHAL : Sending mac address OUI
,09-22 10:55:04.035   929  3019 E native  : do suspend false
,09-22 10:55:04.042   929  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-22 10:55:04.042   929   929 D RttService: SCAN_AVAILABLE : 3
09-22 10:55:04.042   929  3095 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-22 10:55:04.042   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 10:55:04.043   509   923 D CommandListener: Setting iface cfg
,09-22 10:55:04.047   929  3014 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-22 10:55:04.048   929  3014 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 10:55:04.056   929  3014 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 10:55:04.061   929  3014 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 10:55:04.061   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178811 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-22 10:55:06.122   929  3019 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 10, 11 -> obsolete
,09-22 10:55:06.241   929  3151 D WifiService: setWifiEnabled: false pid=5488, uid=10077
,09-22 10:55:06.241   929  3151 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 10:55:06.249   929   929 D RttService: SCAN_AVAILABLE : 1
,09-22 10:55:06.249   929  3095 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 10:55:06.261   929  3019 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 10:55:06.263   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 10:55:06.267   929  3019 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 10:55:06.269  5626  5626 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 10:55:06.278  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:06.278  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:06.278  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 10:55:06.278  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:06.281  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:06.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:06.281  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:06.281  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:06.286  5626  5626 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 10:55:06.312  5626  5626 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 10:55:06.315  5626  5626 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 10:55:06.418   929  3019 D wifi    : In wifi stop Hal
,09-22 10:55:06.418   929  3019 D wifi    : halHandle = 0x7f681212a0, mVM = 0x7f8410d140, mCls = 0x195e
09-22 10:55:06.419   929  5625 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 10:55:06.419   929  5625 D WifiHAL : Got a signal to exit!!!
09-22 10:55:06.419   929  5625 I WifiHAL : Exit wifi_event_loop
,09-22 10:55:06.420   929  3019 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-22 10:55:06.420   929  3019 E WifiHAL : Event processing terminated
09-22 10:55:06.421   929  3019 D wifi    : In wifi cleaned up handler
09-22 10:55:06.421   929  3019 I WifiHAL : Internal cleanup completed
,09-22 10:55:06.423  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 10:55:06.431  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:06.433  3493  4039 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 10:55:06.434  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:06.464   929  5625 D wifi    : set interface wlan0 flags (DOWN)
,09-22 10:55:06.465   929  3019 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 10:55:06.670   929   946 D Tethering: InitialState.processMessage what=4
,09-22 10:55:06.676   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 10:55:09.284   929   946 I ActivityManager: Start proc 5632:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 10:55:09.388  5632  5632 D AdapterServiceConfig: Adding HeadsetService
,09-22 10:55:09.389  5632  5632 D AdapterServiceConfig: Adding A2dpService
,09-22 10:55:09.389  5632  5632 D AdapterServiceConfig: Adding HidService
09-22 10:55:09.389  5632  5632 D AdapterServiceConfig: Adding HealthService
,09-22 10:55:09.389  5632  5632 D AdapterServiceConfig: Adding PanService
09-22 10:55:09.390  5632  5632 D AdapterServiceConfig: Adding GattService
09-22 10:55:09.390  5632  5632 D AdapterServiceConfig: Adding BluetoothMapService
,09-22 10:55:09.390  5632  5632 D AdapterServiceConfig: Adding SapService
,09-22 10:55:09.403   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53b0a7f:true
,09-22 10:55:09.404  5632  5632 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 10:55:09.407  5632  5632 I bt_bluedroid: init
,09-22 10:55:09.407  5632  5644 I BluetoothAdapterState: Entering OffState
,09-22 10:55:09.410  5632  5645 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 10:55:09.410  5632  5645 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 10:55:09.410  5632  5645 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 10:55:09.410  5632  5645 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 10:55:09.411  5632  5632 I bt_bluedroid: get_profile_interface socket
,09-22 10:55:09.413  5632  5648 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 10:55:09.413  5632  5632 I bt_bluedroid: get_profile_interface sdp
,09-22 10:55:09.416  5632  5648 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 10:55:09.421  5632  5643 I bt_bluedroid: config_hci_snoop_log
,09-22 10:55:09.422   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 10:55:09.427  5632  5644 D BluetoothAdapterState: Current state: OFF, message: 0
09-22 10:55:09.427  5632  5644 D BluetoothAdapterProperties: Setting state to 14
09-22 10:55:09.427  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 10:55:09.430  5632  5644 D BluetoothBondStateMachine: make
,09-22 10:55:09.432  5632  5649 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 10:55:09.434  5632  5644 I BluetoothAdapterState: Entering PendingCommandState
,09-22 10:55:09.436  5632  5632 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 10:55:09.438  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:09.438  5632  5632 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 10:55:09.439  5632  5632 D BtGatt.GattService: Received start request. Starting profile...
09-22 10:55:09.439  5632  5632 D BtGatt.GattService: start()
09-22 10:55:09.439  5632  5632 I bt_bluedroid: get_profile_interface gatt
,09-22 10:55:09.440  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:09.440  5632  5632 D BtGatt.AdvertiseManager: advertise manager created
,09-22 10:55:09.445  5632  5632 V BluetoothAdapterState: isTurningOff()=false
,09-22 10:55:09.445  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:09.445  5632  5632 V BluetoothAdapterState: isBleTurningOn()=true
09-22 10:55:09.445  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:09.446  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 10:55:09.447  5632  5644 I bt_bluedroid: bt_bluedroid
09-22 10:55:09.447  5632  5645 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 10:55:09.447  5632  5645 I bt_hci  : start_up
,09-22 10:55:09.453  5632  5645 I bt_vendor: alloc value 0xf3f93871
,09-22 10:55:09.453  5632  5645 I bt_vendor: init
09-22 10:55:09.453  5632  5645 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 10:55:09.453  5632  5645 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 10:55:09.562  5632  5645 D bt_hci  : start_up starting async portion
,09-22 10:55:09.563  5632  5652 I bt_hci  : event_finish_startup
09-22 10:55:09.563  5632  5652 I bt_hci_h4: hal_open
,09-22 10:55:09.563  5632  5652 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-22 10:55:09.560  5653  5653 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 10:55:09.567  5632  5652 I bt_userial_vendor: device fd = 54 open
,09-22 10:55:09.581  5632  5652 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 10:55:09.584  5632  5652 D bt_hwcfg: Chipset BCM4358A3
,09-22 10:55:09.584  5632  5652 D bt_hwcfg: Target name = [BCM4358A3]
09-22 10:55:09.585  5632  5652 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 10:55:09.987  5632  5652 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 10:55:09.987  5632  5652 D bt_hwcfg: Settlement delay -- 100 ms
09-22 10:55:09.988  5632  5652 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 10:55:10.123  5632  5652 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 10:55:10.123  5632  5652 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-22 10:55:10.125  5632  5652 I bt_hwcfg: vendor lib fwcfg completed
,09-22 10:55:10.125  5632  5652 I bt_vendor: firmware callback
09-22 10:55:10.125  5632  5652 I bt_hci  : firmware_config_callback
,09-22 10:55:10.136  5632  5655 I bt_btu  : btu_task pending for preload complete event
,09-22 10:55:10.136  5632  5655 I bt_btu_task: Bluetooth chip preload is complete
09-22 10:55:10.137  5632  5655 I bt_btu  : btu_task received preload complete event
,09-22 10:55:10.142  5632  5655 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 10:55:10.143  5632  5655 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 10:55:10.144  5632  5655 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 10:55:10.230  5632  5655 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f11549
09-22 10:55:10.230  5632  5655 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f11549 
09-22 10:55:10.243  5632  5648 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-22 10:55:10.244  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 10:55:10.245  5632  5648 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 10:55:10.247  5632  5648 D BluetoothAdapterProperties: Name is: Nexus 6P
09-22 10:55:10.251  5632  5648 D BluetoothAdapterProperties: Scan Mode:20
09-22 10:55:10.251  5632  5648 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 10:55:10.252  5632  5648 D bt_hci  : do_postload posting postload work item
09-22 10:55:10.252  5632  5652 I bt_hci  : event_postload
09-22 10:55:10.252  5632  5652 I bt_vendor: sco_config_cb
09-22 10:55:10.252  5632  5652 I bt_hci  : sco_config_callback postload finished.
09-22 10:55:10.256  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:10.262  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:10.262  5632  5648 D bt_bte_conf: Device ID record 1 : primary
09-22 10:55:10.263  5632  5652 I bt_vendor: low_power_mode_cb
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   vendorId            = 000f
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   vendorIdSource      = 0001
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   product             = 1200
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   version             = 1436
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   clientExecutableURL = 
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   serviceDescription  = 
09-22 10:55:10.263  5632  5648 D bt_bte_conf:   documentationURL    = 
09-22 10:55:10.263  5632  5648 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 10:55:10.264  5632  5645 D bt_stack_manager: event_start_up_stack finished
09-22 10:55:10.265  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 10:55:10.265  5632  5644 D BluetoothAdapterProperties: Setting state to 15
09-22 10:55:10.265  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 10:55:10.267  5632  5644 I BluetoothAdapterState: Entering BleOnState
09-22 10:55:10.272  5632  5644 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-22 10:55:10.272  5632  5644 D BluetoothAdapterProperties: Setting state to 11
09-22 10:55:10.272  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-22 10:55:10.280  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:10.281  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:10.281  5632  5632 D HeadsetService: Received start request. Starting profile...
09-22 10:55:10.283  5632  5632 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 10:55:10.284  5632  5632 D HeadsetStateMachine: make
09-22 10:55:10.285  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:10.294  5632  5632 D HeadsetStateMachine: max_hf_connections = 1
09-22 10:55:10.294  5632  5632 I bt_bluedroid: get_profile_interface handsfree
09-22 10:55:10.294  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 10:55:10.294  5632  5648 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-22 10:55:10.295  5632  5644 I BluetoothAdapterState: Entering PendingCommandState
09-22 10:55:10.297  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:10.298  5632  5632 D A2dpService: Received start request. Starting profile...
09-22 10:55:10.298  5632  5632 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 10:55:10.299  5632  5632 I bt_bluedroid: get_profile_interface avrcp
09-22 10:55:10.304  5632  5632 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 10:55:10.304  5632  5632 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 10:55:10.304  5632  5632 D A2dpStateMachine: make
09-22 10:55:10.305  5632  5632 I bt_bluedroid: get_profile_interface a2dp
09-22 10:55:10.306  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-22 10:55:10.307  5632  5664 D A2dpStateMachine: Enter Disconnected: -2
,09-22 10:55:10.309  5632  5632 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 10:55:10.310  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:10.310  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 10:55:10.312  5548  5548 D BluetoothInputDevice: Proxy object connected
,09-22 10:55:10.313  5632  5632 D HidService: Received start request. Starting profile...
09-22 10:55:10.313  5548  5548 D HidProfile: Bluetooth service connected
09-22 10:55:10.313  5632  5632 I bt_bluedroid: get_profile_interface hidhost
09-22 10:55:10.313  5632  5632 D HidService: setHidService(): set to: null
09-22 10:55:10.313  5632  5648 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ef256d
09-22 10:55:10.313  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 10:55:10.313  5632  5632 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-22 10:55:10.314  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:10.315  5632  5632 D HealthService: Received start request. Starting profile...
,09-22 10:55:10.317  5632  5632 I bt_bluedroid: get_profile_interface health
09-22 10:55:10.317  5632  5632 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 10:55:10.318  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:10.319  5548  5548 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 10:55:10.319  5632  5632 D PanService: Received start request. Starting profile...
,09-22 10:55:10.320  5632  5632 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 10:55:10.320  5632  5632 I bt_bluedroid: get_profile_interface pan
09-22 10:55:10.320  5548  5548 D PanProfile: Bluetooth service connected
09-22 10:55:10.320  5632  5648 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-22 10:55:10.323  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:10.325  5548  5548 D BluetoothMap: Proxy object connected
,09-22 10:55:10.325  5632  5632 D BluetoothMapService: Received start request. Starting profile...
09-22 10:55:10.326  5632  5632 D BluetoothMapService: start()
09-22 10:55:10.328  5632  5632 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-22 10:55:10.329  5632  5632 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 10:55:10.329  5632  5632 D BluetoothMapAppObserver: createReceiver()
09-22 10:55:10.331  5632  5632 D BluetoothMapAppObserver: initObservers()
09-22 10:55:10.331  5632  5632 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 10:55:10.338  5632  5632 V SapService: SapBinder()
09-22 10:55:10.338  5632  5632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:10.339  5632  5632 D SapService: Received start request. Starting profile...
09-22 10:55:10.339  5632  5632 V SapService: start()
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:10.341  5632  5662 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:10.341  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 10:55:10.342  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:10.343  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.343  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.343  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 10:55:10.343  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:10.344  5632  5632 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:10.344  5632  5632 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:10.344  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:10.344  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:10.344  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 10:55:10.344  5632  5644 D BluetoothAdapterProperties: ScanMode =  20
09-22 10:55:10.344  5632  5644 D BluetoothAdapterProperties: State =  11
09-22 10:55:10.345  5632  5644 D BluetoothAdapterProperties: Setting state to 12
09-22 10:55:10.345  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 10:55:10.345  5632  5644 I BluetoothAdapterState: Entering OnState
,09-22 10:55:10.346  5548  5561 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 10:55:10.347  5632  5648 D BluetoothAdapterProperties: Scan Mode:21
09-22 10:55:10.347  5632  5648 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 10:55:10.347  5548  5560 D BluetoothPan: onBluetoothStateChange on: true
09-22 10:55:10.348  3168  3447 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 10:55:10.350  3168  3168 D BluetoothInputDevice: Proxy object connected
,09-22 10:55:10.350  5548  5561 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 10:55:10.350  3168  3168 D HidProfile: Bluetooth service connected
09-22 10:55:10.350  3168  3706 D BluetoothPan: onBluetoothStateChange on: true
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:10.351  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:10.352   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:10.352  3168  3168 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 10:55:10.352  3168  3168 D PanProfile: Bluetooth service connected
09-22 10:55:10.352  3569  3596 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:10.353  3168  3447 D BluetoothMap: onBluetoothStateChange: up=true
09-22 10:55:10.353  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:10.354   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:10.354  3168  3168 D BluetoothMap: Proxy object connected
,09-22 10:55:10.354  3168  3168 D MapProfile: Bluetooth service connected
,09-22 10:55:10.354  3168  3168 D BluetoothMap: getConnectedDevices()
09-22 10:55:10.354  3168  3706 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 10:55:10.325  5548  5548 D MapProfile: Bluetooth service connected
,09-22 10:55:10.355  5548  5548 D BluetoothMap: getConnectedDevices()
09-22 10:55:10.356  5548  5560 D BluetoothMap: onBluetoothStateChange: up=true
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:10.356  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:10.356   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 10:55:10.357  5632  5632 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 10:55:10.357   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:10.357  3168  3180 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 10:55:10.357  5632  5632 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 10:55:10.359  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:10.359  3168  3447 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:10.359  5632  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:10.361   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 10:55:10.363  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:10.364  5548  5548 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 10:55:10.364  5632  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 10:55:10.365  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:10.366  5632  5632 D ObexServerSockets: Succeed to create listening sockets 
09-22 10:55:10.366  5632  5632 D ObexServerSockets0: startAccept()
09-22 10:55:10.366  5632  5632 D ObexServerSockets0: prepareForNewConnect()
,09-22 10:55:10.369  5632  5632 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 10:55:10.369  5632  5632 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 10:55:10.369  5548  5548 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-22 10:55:10.369  5632  5670 D ObexServerSockets0: Accepting socket connection...
,09-22 10:55:10.371  5632  5671 D ObexServerSockets0: Accepting socket connection...
09-22 10:55:10.372   929   929 D BluetoothA2dp: Proxy object connected
09-22 10:55:10.372  5632  5632 D BluetoothMapService: onReceive
09-22 10:55:10.373  5632  5632 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 10:55:10.373  5632  5632 D BluetoothMapService: STATE_ON
09-22 10:55:10.376  5632  5672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 10:55:10.378  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 10:55:10.378  5632  5672 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 10:55:10.378  5632  5672 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 10:55:10.380  5548  5548 D BluetoothA2dp: Proxy object connected
09-22 10:55:10.380  3168  3168 D BluetoothA2dp: Proxy object connected
,09-22 10:55:10.384  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 10:55:10.386  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-22 10:55:10.391  3168  3168 D BluetoothPbap: Proxy object connected
,09-22 10:55:10.391  3168  3168 D PbapServerProfile: Bluetooth service connected
,09-22 10:55:10.393  5548  5548 D BluetoothPbap: Proxy object connected
,09-22 10:55:10.394  5548  5548 D PbapServerProfile: Bluetooth service connected
,09-22 10:55:10.398  5632  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:10.398  5632  5632 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 10:55:10.399  5632  5632 D ObexServerSockets0: prepareForNewConnect()
,09-22 10:55:10.415  5632  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 10:55:10.417  5632  5680 I BtOppRfcommListener: Accept thread started.
,09-22 10:55:10.453   929   929 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.453  3168  3706 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.453  3168  3168 D HeadsetProfile: Bluetooth service connected
09-22 10:55:10.454  3569  3804 D BluetoothHeadset: Proxy object connected
09-22 10:55:10.454   929   929 D BluetoothHeadset: Proxy object connected
09-22 10:55:10.454   929   929 D BluetoothHeadset: Proxy object connected
09-22 10:55:10.454   929   946 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.458   929   946 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.459  3168  3180 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.459  3168  3168 D HeadsetProfile: Bluetooth service connected
,09-22 10:55:10.473  5548  5560 D BluetoothHeadset: Proxy object connected
,09-22 10:55:10.474  5548  5548 D HeadsetProfile: Bluetooth service connected
,09-22 10:55:12.260  5632  5644 D BluetoothAdapterState: Current state: ON, message: 23
,09-22 10:55:12.260  5632  5644 D BluetoothAdapterProperties: Setting state to 13
09-22 10:55:12.260  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 10:55:12.261  5632  5644 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 10:55:12.265  5632  5632 D BluetoothMapService: onReceive
09-22 10:55:12.265  5632  5632 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 10:55:12.266  5632  5632 D BluetoothMapService: STATE_TURNING_OFF
09-22 10:55:12.266  5632  5632 D BluetoothMapService: MAP Service closeService in
,09-22 10:55:12.266  5632  5632 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 10:55:12.267  5632  5632 D ObexServerSockets0: shutdown(block = true)
,09-22 10:55:12.267  5632  5644 I BluetoothAdapterState: Entering PendingCommandState
09-22 10:55:12.268  5632  5632 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 10:55:12.269  5632  5632 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 10:55:12.270  5632  5671 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 10:55:12.271  5632  5670 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-22 10:55:12.273  5632  5657 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-22 10:55:12.277  5632  5648 D BluetoothAdapterProperties: Scan Mode:20
,09-22 10:55:12.277  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 10:55:12.279  5632  5632 I BtOppRfcommListener: stopping Accept Thread
09-22 10:55:12.279  5632  5680 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 10:55:12.280  5632  5680 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 10:55:12.280  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 10:55:12.281  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:12.281  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:12.283  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:12.283  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:12.286  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:12.286  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:12.289  5488  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 10:55:12.289  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:12.290  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 10:55:12.291  5632  5632 D HeadsetService: Received stop request...Stopping profile...
09-22 10:55:12.291  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:12.293  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:12.294   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:12.294  3168  3706 D BluetoothHeadset: Proxy object disconnected
,09-22 10:55:12.295  5548  5560 D BluetoothHeadset: Proxy object disconnected
,09-22 10:55:12.295  3569  3595 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:12.296   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:12.296   929   929 D BluetoothHeadset: Proxy object disconnected
09-22 10:55:12.297  3168  3168 D BluetoothPbap: Proxy object disconnected
,09-22 10:55:12.297  3168  3168 D PbapServerProfile: Bluetooth service disconnected
,09-22 10:55:12.297  5632  5632 D A2dpService: Received stop request...Stopping profile...
09-22 10:55:12.297  3168  3168 D HeadsetProfile: Bluetooth service disconnected
09-22 10:55:12.297  5632  5664 D A2dpStateMachine: Exit Disconnected: -1
09-22 10:55:12.298  5548  5548 D DockEventReceiver: finishStartingService: stopping service
09-22 10:55:12.301  3168  3168 D BluetoothA2dp: Proxy object disconnected
09-22 10:55:12.301   929   929 D BluetoothA2dp: Proxy object disconnected
09-22 10:55:12.302  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.302  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.302  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.302  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.304  5548  5548 D BluetoothPbap: Proxy object disconnected
09-22 10:55:12.304  5548  5548 D PbapServerProfile: Bluetooth service disconnected
09-22 10:55:12.304  5548  5548 D HeadsetProfile: Bluetooth service disconnected
,09-22 10:55:12.304  5632  5632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 10:55:12.304  5632  5632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-22 10:55:12.304  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 10:55:12.304  5548  5548 D BluetoothA2dp: Proxy object disconnected
09-22 10:55:12.304  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:12.304  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:12.304  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:12.305  5632  5648 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-22 10:55:12.306  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.306  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.306  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.306  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.307  5632  5632 D HidService: Received stop request...Stopping profile...
09-22 10:55:12.307  5632  5632 D HidService: Stopping Bluetooth HidService
09-22 10:55:12.307  3168  3168 D BluetoothInputDevice: Proxy object disconnected
09-22 10:55:12.307  3168  3168 D HidProfile: Bluetooth service disconnected
09-22 10:55:12.307  5548  5548 D BluetoothInputDevice: Proxy object disconnected
09-22 10:55:12.307  5548  5548 D HidProfile: Bluetooth service disconnected
09-22 10:55:12.310  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 10:55:12.310  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:12.310  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 10:55:12.310  5632  5632 D HealthService: Received stop request...Stopping profile...
09-22 10:55:12.311  5632  5655 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 10:55:12.311  5632  5655 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 10:55:12.311  5632  5655 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 10:55:12.311  5632  5655 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 10:55:12.312  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.312  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.312  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.312  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.312  5632  5632 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 10:55:12.312  5632  5632 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 10:55:12.312  5632  5648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 10:55:12.313  5632  5632 D PanService: Received stop request...Stopping profile...
09-22 10:55:12.314  3168  3168 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 10:55:12.314  3168  3168 D PanProfile: Bluetooth service disconnected
09-22 10:55:12.314  5632  5632 D BluetoothMapService: Received stop request...Stopping profile...
09-22 10:55:12.314  5632  5632 D BluetoothMapService: stop()
09-22 10:55:12.314  5548  5548 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 10:55:12.315  5548  5548 D PanProfile: Bluetooth service disconnected
09-22 10:55:12.315  5632  5632 D BluetoothMapAppObserver: deinitObservers()
09-22 10:55:12.315  5632  5632 D BluetoothMapAppObserver: removeReceiver()
09-22 10:55:12.316  5548  5548 D BluetoothMap: Proxy object disconnected
09-22 10:55:12.316  5548  5548 D MapProfile: Bluetooth service disconnected
09-22 10:55:12.319  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.319  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.319  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.319  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.319  5632  5632 D SapService: Received stop request...Stopping profile...
09-22 10:55:12.319  5632  5632 V SapService: stop()
09-22 10:55:12.320  3168  3168 D BluetoothMap: Proxy object disconnected
09-22 10:55:12.320  3168  3168 D MapProfile: Bluetooth service disconnected
09-22 10:55:12.322  5632  5632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 10:55:12.323  5632  5648 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 10:55:12.323  5632  5632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-22 10:55:12.323  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.323  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.323  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.323  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.323  5632  5632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 10:55:12.323  5632  5632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 10:55:12.324  5632  5632 D BluetoothMapService: MAP Service closeService in
09-22 10:55:12.324  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.324  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.324  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.324  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.325  5632  5632 D BluetoothMapService: cleanup()
09-22 10:55:12.325  5632  5632 D BluetoothMapService: MAP Service closeService in
09-22 10:55:12.325  5632  5632 V BluetoothAdapterState: isTurningOff()=true
09-22 10:55:12.325  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.325  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.325  5632  5632 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:12.325  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 10:55:12.326  5632  5644 D BluetoothAdapterProperties: Setting state to 15
09-22 10:55:12.326  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 10:55:12.326  5632  5644 I BluetoothAdapterState: Entering BleOnState
09-22 10:55:12.326  5548  5561 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 10:55:12.327  5548  5560 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 10:55:12.327  5548  5561 D BluetoothPan: onBluetoothStateChange on: false
09-22 10:55:12.328  3168  3179 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 10:55:12.328  5548  5560 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 10:55:12.329  5548  5561 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 10:55:12.330  3168  3706 D BluetoothPan: onBluetoothStateChange on: false
09-22 10:55:12.330   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:12.330  3569  3844 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:12.330  3168  3180 D BluetoothMap: onBluetoothStateChange: up=false
09-22 10:55:12.331   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:12.331  3168  3447 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 10:55:12.336  5548  5560 D BluetoothMap: onBluetoothStateChange: up=false
09-22 10:55:12.336   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 10:55:12.336   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 10:55:12.336  3168  3179 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 10:55:12.337  3168  3706 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 10:55:12.338  5632  5644 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 10:55:12.338  5632  5644 D BluetoothAdapterProperties: Setting state to 16
09-22 10:55:12.338  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-22 10:55:12.339  5632  5644 D BluetoothAdapterProperties: onBleDisable
09-22 10:55:12.339  5632  5644 I BluetoothAdapterState: Entering PendingCommandState
,09-22 10:55:12.339  5632  5645 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 10:55:12.341  5632  5655 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 10:55:12.341  5632  5655 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 10:55:12.343  5632  5648 D BluetoothAdapterProperties: Scan Mode:20
,09-22 10:55:12.345  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:12.346  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:12.347  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 10:55:12.347  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:12.351  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:12.354  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 10:55:12.354  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-22 10:55:12.549  5632  5648 I bt_hci  : shut_down
,09-22 10:55:12.553  5632  5652 D bt_hwcfg: hw_epilog_process
,09-22 10:55:12.553  5632  5652 I bt_vendor: low_power_mode_cb
,09-22 10:55:12.556  5632  5652 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 10:55:12.556  5632  5652 I bt_vendor: epilog_cb
09-22 10:55:12.556  5632  5652 I bt_hci  : epilog_finished_callback
,09-22 10:55:12.557  5632  5648 I bt_hci_h4: hal_close
09-22 10:55:12.558  5632  5648 I bt_userial_vendor: device fd = 54 close
,09-22 10:55:12.674  5632  5645 D bt_stack_manager: event_shut_down_stack finished.
,09-22 10:55:12.675  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 10:55:12.678  5632  5644 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-22 10:55:12.679  5632  5632 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 10:55:12.680  5632  5632 D BtGatt.GattService: Received stop request...Stopping profile...
,09-22 10:55:12.680  5632  5632 D BtGatt.GattService: stop()
09-22 10:55:12.680  5632  5632 D BtGatt.AdvertiseManager: advertise clients cleared
,09-22 10:55:12.684  5632  5632 V BluetoothAdapterState: isTurningOff()=false
,09-22 10:55:12.684  5632  5632 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:12.684  5632  5632 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:12.684  5632  5632 V BluetoothAdapterState: isBleTurningOff()=true
09-22 10:55:12.685  5632  5644 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-22 10:55:12.685  5632  5644 D BluetoothAdapterProperties: Setting state to 10
09-22 10:55:12.685  5632  5644 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 10:55:12.688  5632  5644 I BluetoothAdapterState: Entering OffState
,09-22 10:55:12.688   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 10:55:12.704  5632  5632 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-22 10:55:12.705  5632  5632 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-22 10:55:12.705  5632  5632 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 10:55:12.707  5632  5645 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 10:55:12.714  5632  5632 I art     : System.exit called, status: 0
,09-22 10:55:12.715  5632  5632 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 10:55:12.742   929   940 I ActivityManager: Process com.android.bluetooth (pid 5632) has died
,09-22 10:55:15.257  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 10:55:15.258  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:15.395   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:55:16.396   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:55:17.397   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:55:18.266  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:18.266  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4de22e9 added. We now have 6 listener(s)
,09-22 10:55:18.266  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:18.272  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 10:55:18.272  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a6e0b6e added. We now have 7 listener(s)
,09-22 10:55:18.272  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:18.273  5488  5534 I System.out: IsBluetoothEnabled
,09-22 10:55:18.282  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:18.314   929   946 I ActivityManager: Start proc 5688:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 10:55:18.398   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:55:18.401  5688  5688 D AdapterServiceConfig: Adding HeadsetService
,09-22 10:55:18.401  5688  5688 D AdapterServiceConfig: Adding A2dpService
09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding HidService
09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding HealthService
09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding PanService
09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding GattService
,09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding BluetoothMapService
09-22 10:55:18.402  5688  5688 D AdapterServiceConfig: Adding SapService
,09-22 10:55:18.414   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acf330c:true
,09-22 10:55:18.415  5688  5688 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 10:55:18.418  5688  5688 I bt_bluedroid: init
09-22 10:55:18.418  5688  5700 I BluetoothAdapterState: Entering OffState
,09-22 10:55:18.420  5688  5701 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 10:55:18.420  5688  5701 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 10:55:18.420  5688  5701 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 10:55:18.420  5688  5701 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-22 10:55:18.421  5688  5688 I bt_bluedroid: get_profile_interface socket
,09-22 10:55:18.422  5688  5704 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 10:55:18.423  5688  5688 I bt_bluedroid: get_profile_interface sdp
,09-22 10:55:18.424  5688  5704 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 10:55:18.427  5688  5699 I bt_bluedroid: config_hci_snoop_log
,09-22 10:55:18.429   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 10:55:18.432  5688  5700 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 10:55:18.433  5688  5700 D BluetoothAdapterProperties: Setting state to 14
09-22 10:55:18.433  5688  5700 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-22 10:55:18.435  5688  5700 D BluetoothBondStateMachine: make
,09-22 10:55:18.436  5688  5705 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 10:55:18.439  5688  5700 I BluetoothAdapterState: Entering PendingCommandState
,09-22 10:55:18.440  5688  5688 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 10:55:18.442  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:18.443  5688  5688 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 10:55:18.443  5688  5688 D BtGatt.GattService: Received start request. Starting profile...
09-22 10:55:18.444  5688  5688 D BtGatt.GattService: start()
09-22 10:55:18.444  5688  5688 I bt_bluedroid: get_profile_interface gatt
,09-22 10:55:18.445  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:18.445  5688  5688 D BtGatt.AdvertiseManager: advertise manager created
,09-22 10:55:18.450  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:18.450  5688  5688 V BluetoothAdapterState: isTurningOn()=false
09-22 10:55:18.450  5688  5688 V BluetoothAdapterState: isBleTurningOn()=true
09-22 10:55:18.450  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:18.451  5688  5700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-22 10:55:18.452  5688  5700 I bt_bluedroid: bt_bluedroid
09-22 10:55:18.452  5688  5701 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 10:55:18.452  5688  5701 I bt_hci  : start_up
,09-22 10:55:18.458  5688  5701 I bt_vendor: alloc value 0xf3f93871
09-22 10:55:18.458  5688  5701 I bt_vendor: init
09-22 10:55:18.458  5688  5701 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 10:55:18.458  5688  5701 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 10:55:18.570  5688  5701 D bt_hci  : start_up starting async portion
,09-22 10:55:18.570  5688  5708 I bt_hci  : event_finish_startup
09-22 10:55:18.570  5688  5708 I bt_hci_h4: hal_open
,09-22 10:55:18.571  5688  5708 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-22 10:55:18.570  5709  5709 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 10:55:18.575  5688  5708 I bt_userial_vendor: device fd = 54 open
,09-22 10:55:18.589  5688  5708 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 10:55:18.592  5688  5708 D bt_hwcfg: Chipset BCM4358A3
,09-22 10:55:18.592  5688  5708 D bt_hwcfg: Target name = [BCM4358A3]
09-22 10:55:18.593  5688  5708 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 10:55:18.990  5688  5708 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-22 10:55:18.990  5688  5708 D bt_hwcfg: Settlement delay -- 100 ms
09-22 10:55:18.990  5688  5708 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 10:55:19.124  5688  5708 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 10:55:19.124  5688  5708 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-22 10:55:19.126  5688  5708 I bt_hwcfg: vendor lib fwcfg completed
,09-22 10:55:19.126  5688  5708 I bt_vendor: firmware callback
,09-22 10:55:19.126  5688  5708 I bt_hci  : firmware_config_callback
,09-22 10:55:19.136  5688  5711 I bt_btu  : btu_task pending for preload complete event
,09-22 10:55:19.136  5688  5711 I bt_btu_task: Bluetooth chip preload is complete
09-22 10:55:19.136  5688  5711 I bt_btu  : btu_task received preload complete event
,09-22 10:55:19.145  5688  5711 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 10:55:19.146  5688  5711 I         : BTE_InitTraceLevels -- TRC_PAN
,09-22 10:55:19.147  5688  5711 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 10:55:19.147  5688  5711 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 10:55:19.147  5688  5711 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 10:55:19.147  5688  5711 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 10:55:19.147  5688  5711 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 10:55:19.229  5688  5711 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f11549
,09-22 10:55:19.229  5688  5711 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f11549 
,09-22 10:55:19.246  5688  5704 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 10:55:19.247  5688  5704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 10:55:19.247  5688  5704 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 10:55:19.249  5688  5704 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 10:55:19.253  5688  5704 D BluetoothAdapterProperties: Scan Mode:20
,09-22 10:55:19.253  5688  5704 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 10:55:19.254  5688  5704 D bt_hci  : do_postload posting postload work item
09-22 10:55:19.254  5688  5708 I bt_hci  : event_postload
09-22 10:55:19.254  5688  5708 I bt_vendor: sco_config_cb
09-22 10:55:19.254  5688  5708 I bt_hci  : sco_config_callback postload finished.
,09-22 10:55:19.257  5688  5704 D bt_bte_conf: Device ID record 1 : primary
09-22 10:55:19.257  5688  5704 D bt_bte_conf:   vendorId            = 000f
09-22 10:55:19.257  5688  5704 D bt_bte_conf:   vendorIdSource      = 0001
09-22 10:55:19.257  5688  5704 D bt_bte_conf:   product             = 1200
09-22 10:55:19.257  5688  5704 D bt_bte_conf:   version             = 1436
09-22 10:55:19.257  5688  5704 D bt_bte_conf:   clientExecutableURL = 
,09-22 10:55:19.257  5688  5704 D bt_bte_conf:   serviceDescription  = 
09-22 10:55:19.258  5688  5704 D bt_bte_conf:   documentationURL    = 
09-22 10:55:19.258  5688  5704 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 10:55:19.258  5688  5701 D bt_stack_manager: event_start_up_stack finished
09-22 10:55:19.259  5688  5700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 10:55:19.259  5688  5700 D BluetoothAdapterProperties: Setting state to 15
09-22 10:55:19.259  5688  5700 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 10:55:19.260  5688  5700 I BluetoothAdapterState: Entering BleOnState
09-22 10:55:19.260  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:19.262  5688  5708 I bt_vendor: low_power_mode_cb
,09-22 10:55:19.266  5688  5700 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 10:55:19.266  5688  5700 D BluetoothAdapterProperties: Setting state to 11
09-22 10:55:19.266  5688  5700 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 10:55:19.271  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.272  5688  5688 D HeadsetService: Received start request. Starting profile...
09-22 10:55:19.274  5688  5688 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 10:55:19.275  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:19.276  5688  5688 D HeadsetStateMachine: make
,09-22 10:55:19.284  5688  5700 I BluetoothAdapterState: Entering PendingCommandState
,09-22 10:55:19.286  5688  5688 D HeadsetStateMachine: max_hf_connections = 1
,09-22 10:55:19.286  5688  5688 I bt_bluedroid: get_profile_interface handsfree
09-22 10:55:19.287  5688  5704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 10:55:19.287  5688  5704 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-22 10:55:19.290  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.290  5688  5688 D A2dpService: Received start request. Starting profile...
,09-22 10:55:19.291  5688  5688 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 10:55:19.291  5688  5688 I bt_bluedroid: get_profile_interface avrcp
,09-22 10:55:19.297  5688  5688 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 10:55:19.297  5688  5688 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 10:55:19.297  5688  5688 D A2dpStateMachine: make
09-22 10:55:19.298  5688  5688 I bt_bluedroid: get_profile_interface a2dp
09-22 10:55:19.299  5688  5704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 10:55:19.301  5688  5719 D A2dpStateMachine: Enter Disconnected: -2
09-22 10:55:19.301  5688  5688 I BluetoothHidServiceJni: classInitNative: succeeds
,09-22 10:55:19.302  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.303  5688  5688 D HidService: Received start request. Starting profile...
09-22 10:55:19.303  5688  5688 I bt_bluedroid: get_profile_interface hidhost
09-22 10:55:19.303  5688  5688 D HidService: setHidService(): set to: null
09-22 10:55:19.303  5688  5704 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ef256d
,09-22 10:55:19.304  5688  5704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 10:55:19.304  5688  5688 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-22 10:55:19.305  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
09-22 10:55:19.306  5688  5688 D HealthService: Received start request. Starting profile...
,09-22 10:55:19.307  5688  5688 I bt_bluedroid: get_profile_interface health
,09-22 10:55:19.308  5688  5688 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 10:55:19.309  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.309  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 10:55:19.311  5688  5688 D PanService: Received start request. Starting profile...
09-22 10:55:19.311  5688  5688 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 10:55:19.311  5688  5688 I bt_bluedroid: get_profile_interface pan
,09-22 10:55:19.312  5688  5704 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 10:55:19.314  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.314  5688  5688 D BluetoothMapService: Received start request. Starting profile...
,09-22 10:55:19.314  5688  5688 D BluetoothMapService: start()
,09-22 10:55:19.317  5688  5688 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 10:55:19.318  5688  5688 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 10:55:19.318  5688  5688 D BluetoothMapAppObserver: createReceiver()
09-22 10:55:19.319  5688  5688 D BluetoothMapAppObserver: initObservers()
09-22 10:55:19.319  5688  5688 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 10:55:19.325  5688  5688 V SapService: SapBinder()
,09-22 10:55:19.325  5688  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:19.325  5688  5688 D SapService: Received start request. Starting profile...
09-22 10:55:19.325  5688  5688 V SapService: start()
,09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isTurningOff()=false
,09-22 10:55:19.329  5688  5717 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:19.329  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isTurningOn()=true
,09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.330  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.331  5688  5688 V BluetoothAdapterState: isTurningOn()=true
,09-22 10:55:19.332  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.332  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
09-22 10:55:19.332  5688  5688 V BluetoothAdapterState: isTurningOff()=false
09-22 10:55:19.333  5688  5688 V BluetoothAdapterState: isTurningOn()=true
09-22 10:55:19.333  5688  5688 V BluetoothAdapterState: isBleTurningOn()=false
09-22 10:55:19.333  5688  5688 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 10:55:19.333  5688  5700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-22 10:55:19.333  5688  5700 D BluetoothAdapterProperties: ScanMode =  20
09-22 10:55:19.333  5688  5700 D BluetoothAdapterProperties: State =  11
,09-22 10:55:19.334  5688  5700 D BluetoothAdapterProperties: Setting state to 12
09-22 10:55:19.334  5688  5700 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 10:55:19.334  5688  5700 I BluetoothAdapterState: Entering OnState
09-22 10:55:19.335  5548  5561 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 10:55:19.336  5688  5704 D BluetoothAdapterProperties: Scan Mode:21
09-22 10:55:19.337  5688  5704 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 10:55:19.337  5548  5560 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 10:55:19.337  5548  5561 D BluetoothPan: onBluetoothStateChange on: true
09-22 10:55:19.339  3168  3706 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:19.341  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:19.341  5548  5561 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 10:55:19.342  5548  5548 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 10:55:19.342  5548  5548 D PanProfile: Bluetooth service connected
09-22 10:55:19.342  3168  3168 D BluetoothInputDevice: Proxy object connected
09-22 10:55:19.342  3168  3168 D HidProfile: Bluetooth service connected
09-22 10:55:19.343  5688  5688 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 10:55:19.343  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:19.344  5548  5560 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 10:55:19.344  5688  5688 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 10:55:19.345  5688  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:19.345  3168  3447 D BluetoothPan: onBluetoothStateChange on: true
09-22 10:55:19.346  5688  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:19.347   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:19.347  3168  3168 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 10:55:19.347  3168  3168 D PanProfile: Bluetooth service connected
09-22 10:55:19.347  3569  3844 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:19.347  3168  3706 D BluetoothMap: onBluetoothStateChange: up=true
09-22 10:55:19.347  5688  5688 D ObexServerSockets: Succeed to create listening sockets 
09-22 10:55:19.348  5688  5688 D ObexServerSockets0: startAccept()
09-22 10:55:19.348  5688  5688 D ObexServerSockets0: prepareForNewConnect()
09-22 10:55:19.349   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:19.349  3168  3180 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 10:55:19.349  5688  5688 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 10:55:19.350  5688  5688 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-22 10:55:19.350  5688  5726 D ObexServerSockets0: Accepting socket connection...
,09-22 10:55:19.350  5688  5727 D ObexServerSockets0: Accepting socket connection...
09-22 10:55:19.351  5548  5548 D BluetoothInputDevice: Proxy object connected
09-22 10:55:19.351  5548  5548 D HidProfile: Bluetooth service connected
09-22 10:55:19.352  3168  3168 D BluetoothA2dp: Proxy object connected
09-22 10:55:19.352  5548  5560 D BluetoothMap: onBluetoothStateChange: up=true
09-22 10:55:19.353  3168  3168 D BluetoothMap: Proxy object connected
09-22 10:55:19.353  3168  3168 D MapProfile: Bluetooth service connected
09-22 10:55:19.353  3168  3168 D BluetoothMap: getConnectedDevices()
09-22 10:55:19.354   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 10:55:19.354   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:19.354   929   929 D BluetoothA2dp: Proxy object connected
09-22 10:55:19.354  3168  3180 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 10:55:19.356  3168  3447 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 10:55:19.357   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 10:55:19.357  5688  5688 D BluetoothMapService: onReceive
,09-22 10:55:19.358  5688  5688 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 10:55:19.358  5688  5688 D BluetoothMapService: STATE_ON
09-22 10:55:19.359  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:19.359  5548  5548 D BluetoothA2dp: Proxy object connected
09-22 10:55:19.361  5688  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 10:55:19.361  5548  5548 D BluetoothMap: Proxy object connected
09-22 10:55:19.361  5548  5548 D MapProfile: Bluetooth service connected
09-22 10:55:19.361  5548  5548 D BluetoothMap: getConnectedDevices()
09-22 10:55:19.362  5688  5729 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 10:55:19.363  5688  5729 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 10:55:19.366  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 10:55:19.373  3631  3631 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 10:55:19.374  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-22 10:55:19.380  5548  5548 D BluetoothPbap: Proxy object connected
,09-22 10:55:19.380  3168  3168 D BluetoothPbap: Proxy object connected
09-22 10:55:19.380  3168  3168 D PbapServerProfile: Bluetooth service connected
09-22 10:55:19.380  5548  5548 D PbapServerProfile: Bluetooth service connected
,09-22 10:55:19.385  5688  5688 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 10:55:19.385  5688  5688 D ObexServerSockets0: prepareForNewConnect()
,09-22 10:55:19.388  5688  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 10:55:19.398   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 10:55:19.400  5688  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 10:55:19.401  5688  5737 I BtOppRfcommListener: Accept thread started.
,09-22 10:55:19.439   929   929 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.440  3168  3179 D BluetoothHeadset: Proxy object connected
09-22 10:55:19.440  3168  3168 D HeadsetProfile: Bluetooth service connected
09-22 10:55:19.440  5548  5725 D BluetoothHeadset: Proxy object connected
09-22 10:55:19.440  3569  3596 D BluetoothHeadset: Proxy object connected
09-22 10:55:19.441   929   929 D BluetoothHeadset: Proxy object connected
09-22 10:55:19.441   929   929 D BluetoothHeadset: Proxy object connected
09-22 10:55:19.442  5548  5548 D HeadsetProfile: Bluetooth service connected
,09-22 10:55:19.447   929   946 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.448  3569  3804 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.449   929   946 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.454   929   946 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.457  3168  3706 D BluetoothHeadset: Proxy object connected
,09-22 10:55:19.457  3168  3168 D HeadsetProfile: Bluetooth service connected
,09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:20.299  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:20.304  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:20.307  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:20.307  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6a920f added. We now have 8 listener(s)
09-22 10:55:20.308  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:20.313   929  3548 D WifiService: setWifiEnabled: false pid=5488, uid=10077
09-22 10:55:20.313   929  3548 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 10:55:20.321  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:20.321   929   940 D WifiService: setWifiEnabled: true pid=5488, uid=10077
,09-22 10:55:20.321   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 10:55:20.328   509   923 D SoftapController: Softap fwReload - Ok
,09-22 10:55:20.331   509   923 D CommandListener: Setting iface cfg
,09-22 10:55:20.331   509   923 D CommandListener: Trying to bring down wlan0
09-22 10:55:20.332   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-22 10:55:20.335   929  3019 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 10:55:20.399   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 10:55:20.944   929  3019 D wifi    : set interface wlan0 flags (UP)
,09-22 10:55:20.948   929  3019 I WifiHAL : Initializing wifi
09-22 10:55:20.949   929  3019 I WifiHAL : Creating socket
09-22 10:55:20.951   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 10:55:20.955   929  3019 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 10:55:20.956   929  3019 D wifi    : Did set static halHandle = 0x7f681212a0
,09-22 10:55:20.956   929  3019 D wifi    : halHandle = 0x7f681212a0, mVM = 0x7f8410d140, mCls = 0x2019a6
09-22 10:55:20.956   929  3019 D wifi    : array field set
09-22 10:55:20.956   929  3019 I WifiNative-HAL: interface[0] = wlan0
09-22 10:55:20.958   929  5742 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547206861472
,09-22 10:55:20.958   929  5742 D wifi    : waitForHalEvents called, vm = 0x7f8410d140, obj = 0x2019a6, env = 0x7f683d1e40
,09-22 10:55:21.016  5743  5743 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 10:55:21.036  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 10:55:21.046  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 10:55:21.046  5743  5743 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 10:55:21.059   929  3019 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 10:55:21.070   929  3019 D WifiConfigStore: Loading config and enabling all networks 
,09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:21.073  5488  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:21.076  5488  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:21.077  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:21.081   929  3019 D WifiConfigStore: loaded 0 passpoint configs
,09-22 10:55:21.082   929  3019 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 10:55:21.082   929  3019 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 10:55:21.083   929  3019 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 10:55:21.084   929  3019 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-22 10:55:21.084   929  3019 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 10:55:21.084   929  3019 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 10:55:21.084   929  3019 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 10:55:21.088   929  3019 D WifiNative-HAL: Setting external_sim to 1
09-22 10:55:21.088  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 10:55:21.089   929  3019 D wifi    : setting dfs flag to true, 0x7f6b7fe1c0
,09-22 10:55:21.089   929  3019 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 10:55:21.090   929  3019 D wifi    : setting scan oui 0x7f6b7fe1c0
09-22 10:55:21.090   929  3019 D WifiHAL : Sending mac address OUI
,09-22 10:55:21.094   929  3019 E native  : do suspend false
,09-22 10:55:21.102   929   929 D RttService: SCAN_AVAILABLE : 3
09-22 10:55:21.102   929  3019 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-22 10:55:21.102   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 10:55:21.102   929  3095 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-22 10:55:21.103   509   923 D CommandListener: Setting iface cfg
,09-22 10:55:21.107   929  3014 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-22 10:55:21.107   929  3014 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 10:55:21.117   929  3014 D WifiNative-HAL: p2pGetDeviceAddress
09-22 10:55:21.117   929  3014 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 10:55:21.122   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=195873 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:21.343  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:21.349  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:21.356  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 10:55:21.357  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-22 10:55:21.362  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4c8f8d6 Bundle[{}]
,09-22 10:55:21.363  5488  5534 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 10:55:21.363  5488  5534 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-22 10:55:21.364  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-22 10:55:21.365  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-22 10:55:21.366  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-22 10:55:21.367  5488  5534 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-22 10:55:21.375  5488  5534 I System.out: Running OutgoingSocketThread
,09-22 10:55:21.377  5488  5745 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-22 10:55:21.378  5488  5745 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48501
09-22 10:55:21.378  5488  5745 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 10:55:22.378  5488  5534 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-22 10:55:22.378  5488  5534 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-22 10:55:22.386  5488  5534 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-22 10:55:22.387  5488  5534 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-22 10:55:22.387  5488  5534 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-22 10:55:22.395  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 10:55:22.395  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57af29c added. We now have 2 listener(s)
,09-22 10:55:22.398  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.398  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.398  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 10:55:22.399  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.399  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed04a5 added. We now have 9 listener(s)
,09-22 10:55:22.399  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:22.401  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 10:55:22.406  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:22.412  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:22.415  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:22.415  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 10:55:22.416  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 10:55:22.416  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@748402b added. We now have 3 listener(s)
09-22 10:55:22.418  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.418  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.418  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 10:55:22.418  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.418  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.419  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9929c88 added. We now have 10 listener(s)
09-22 10:55:22.420  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:22.420  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:22.420  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 10:55:22.420  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:22.421  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.421  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.421  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 10:55:22.421  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.421  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57af29c removed from the list
09-22 10:55:22.421  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.421  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed04a5 removed from the list
09-22 10:55:22.421  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:22.421  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:22.422  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.423  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.423  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.425  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.425  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 10:55:22.425  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.425  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bed04a5 not in the list
09-22 10:55:22.425  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.425  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.427  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.427  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.427  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.427  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9929c88 removed from the list
,09-22 10:55:22.427  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.427  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.428  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.428  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 10:55:22.428  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@748402b removed from the list
09-22 10:55:22.429  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.429  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e4621 added. We now have 2 listener(s)
09-22 10:55:22.431  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 10:55:22.431  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.431  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.432  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.432  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1381a46 added. We now have 9 listener(s)
09-22 10:55:22.432  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:22.433  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 10:55:22.437  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:22.440  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:22.443  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:22.443  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 10:55:22.443  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.443  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8f934 added. We now have 3 listener(s)
09-22 10:55:22.445  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.445  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.445  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.445  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.445  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.445  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b28235d added. We now have 10 listener(s)
09-22 10:55:22.446  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 10:55:22.446  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:22.446  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:22.446  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 10:55:22.446  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:22.446  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:22.447  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:22.451  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 10:55:22.451  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 10:55:22.455  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 10:55:22.456  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 10:55:22.456  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 10:55:22.459  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 10:55:22.459  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:22.459  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 10:55:22.460  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:22.463  5688  5716 D BtGatt.GattService: registerClient() - UUID=1148d0d4-c385-4277-a57d-14e96644141d
09-22 10:55:22.463  5688  5704 D BtGatt.GattService: onClientRegistered() - UUID=1148d0d4-c385-4277-a57d-14e96644141d, clientIf=5
,09-22 10:55:22.464  5488  5499 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 10:55:22.465  5688  5699 D BtGatt.GattService: start scan with filters
,09-22 10:55:22.468  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 10:55:22.468  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:22.468  5688  5707 D BtGatt.ScanManager: handling starting scan
09-22 10:55:22.468  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-22 10:55:22.468  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 10:55:22.470  5688  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fec4e7b
,09-22 10:55:22.471  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 10:55:22.471  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:22.472  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:22.473  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 10:55:22.475  5488  5534 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 10:55:22.475  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:22.476  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 10:55:22.476  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.476  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:22.476  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 10:55:22.476  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:22.476  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:22.476  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:22.476  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:22.476  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:22.477  5688  5704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 10:55:22.477  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:22.477  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.478  5688  5707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 10:55:22.478  5688  5699 D BtGatt.GattService: stopScan() - queue size =1
09-22 10:55:22.479  5688  5724 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:22.480  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:22.480  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:22.480  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:22.480  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 10:55:22.480  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:22.481  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.481  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:22.481  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:22.481  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 10:55:22.482  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.483  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.483  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.483  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.484  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:22.484  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.484  5688  5707 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:22.484  5688  5707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 10:55:22.486  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:22.486  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:22.486  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:22.486  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.486  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.486  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.486  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.486  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e4621 removed from the list
09-22 10:55:22.486  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.486  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1381a46 removed from the list
09-22 10:55:22.486  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:22.486  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.487  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.487  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:22.489  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.489  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.489  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.489  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1381a46 not in the list
09-22 10:55:22.489  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 10:55:22.489  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.490  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.490  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.490  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.490  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b28235d removed from the list
09-22 10:55:22.490  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.490  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.491  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.491  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.491  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8f934 removed from the list
,09-22 10:55:22.491  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.491  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c89859 added. We now have 2 listener(s)
09-22 10:55:22.492  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.493  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.493  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.493  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.493  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caa2c1e added. We now have 9 listener(s)
09-22 10:55:22.493  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.493  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:55:22.495  5688  5704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:22.495  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.496  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:22.500  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:22.500  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:22.500  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.502  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 10:55:22.502  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:22.503  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.503  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e3acc added. We now have 3 listener(s)
,09-22 10:55:22.504  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.504  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.504  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.504  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.504  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.504  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e616115 added. We now have 10 listener(s)
09-22 10:55:22.504  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.504  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:22.505  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:22.505  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:22.505  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 10:55:22.505  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.505  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:22.505  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:22.508  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 10:55:22.508  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.508  5688  5707 D BtGatt.ScanManager: stopping BLe Batch
,09-22 10:55:22.509  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 10:55:22.509  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 10:55:22.513  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 10:55:22.513  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.513  5688  5707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 10:55:22.513  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 10:55:22.514  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 10:55:22.514  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 10:55:22.518  5688  5704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 10:55:22.518  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.518  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 10:55:22.518  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:22.518  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 10:55:22.519  5488  5534 D BluetoothAdapter: STATE_ON
,09-22 10:55:22.521  5688  5724 D BtGatt.GattService: registerClient() - UUID=66faeb30-ed82-43e8-949a-05e9b397ce93
,09-22 10:55:22.521  5688  5704 D BtGatt.GattService: onClientRegistered() - UUID=66faeb30-ed82-43e8-949a-05e9b397ce93, clientIf=5
09-22 10:55:22.521  5488  5498 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 10:55:22.522  5688  5716 D BtGatt.GattService: start scan with filters
,09-22 10:55:22.524  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 10:55:22.524  5688  5707 D BtGatt.ScanManager: handling starting scan
09-22 10:55:22.524  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:22.524  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 10:55:22.524  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 10:55:22.526  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 10:55:22.526  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:22.526  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:22.527  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 10:55:22.530  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:22.530  5488  5534 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-22 10:55:22.530  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:22.530  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:22.530  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:22.530  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.530  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 10:55:22.530  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:22.530  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.530  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c89859 removed from the list
09-22 10:55:22.531  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.531  5688  5704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 10:55:22.531  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caa2c1e removed from the list
09-22 10:55:22.531  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.531  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:22.531  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.531  5688  5707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 10:55:22.531  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.531  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 10:55:22.531  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.531  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.532  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.532  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.532  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.532  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caa2c1e not in the list
09-22 10:55:22.532  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:22.533  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:22.533  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:22.533  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:22.533  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:22.533  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:22.534  5688  5699 D BtGatt.GattService: stopScan() - queue size =1
09-22 10:55:22.534  5688  5698 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:22.535  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:22.535  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:22.535  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:22.535  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 10:55:22.535  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:22.536  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.536  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:22.536  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:22.536  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 10:55:22.536  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:22.536  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.536  5688  5707 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:22.536  5688  5707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 10:55:22.537  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:22.537  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.538  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.538  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.538  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.538  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e616115 removed from the list
09-22 10:55:22.538  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.538  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.538  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.538  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.538  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.538  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.538  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e3acc removed from the list
,09-22 10:55:22.538  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.538  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@683f991 added. We now have 2 listener(s)
09-22 10:55:22.540  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.540  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.540  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.540  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.540  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361a0f6 added. We now have 9 listener(s)
09-22 10:55:22.540  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.540  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:55:22.542  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:22.544  5688  5704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:22.544  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:22.545  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 10:55:22.546  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:22.547  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:22.547  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.547  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9671764 added. We now have 3 listener(s)
09-22 10:55:22.548  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.548  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.548  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.548  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.548  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.548  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d9dcd added. We now have 10 listener(s)
09-22 10:55:22.548  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.548  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 10:55:22.548  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 10:55:22.548  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 10:55:22.548  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:22.548  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:22.548  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 10:55:22.548  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.549  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 10:55:22.553  5488  5534 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 10:55:22.553  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 10:55:22.554  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 10:55:22.555  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.555  5688  5707 D BtGatt.ScanManager: stopping BLe Batch
,09-22 10:55:22.558  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 10:55:22.559  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 10:55:22.559  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 10:55:22.560  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 10:55:22.560  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.560  5688  5707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 10:55:22.563  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 10:55:22.563  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 10:55:22.563  5488  5534 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 10:55:22.563  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:22.564  5688  5704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 10:55:22.564  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.565  5688  5699 D BtGatt.GattService: registerClient() - UUID=47ba7e04-00a9-450a-be6f-19ced970f08a
09-22 10:55:22.566  5688  5704 D BtGatt.GattService: onClientRegistered() - UUID=47ba7e04-00a9-450a-be6f-19ced970f08a, clientIf=5
,09-22 10:55:22.566  5488  5499 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 10:55:22.566  5688  5698 D BtGatt.GattService: start scan with filters
,09-22 10:55:22.568  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 10:55:22.568  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 10:55:22.568  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 10:55:22.568  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 10:55:22.568  5688  5707 D BtGatt.ScanManager: handling starting scan
,09-22 10:55:22.570  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 10:55:22.570  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 10:55:22.570  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 10:55:22.571  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 10:55:22.574  5688  5704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 10:55:22.574  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.574  5688  5707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 10:55:22.575  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 10:55:22.575  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 10:55:22.575  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:22.575  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.575  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.575  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 10:55:22.575  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 10:55:22.575  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@683f991 removed from the list
09-22 10:55:22.575  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.575  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361a0f6 removed from the list
09-22 10:55:22.575  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
09-22 10:55:22.575  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 10:55:22.576  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.576  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 10:55:22.576  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.576  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.577  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.577  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.577  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.577  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361a0f6 not in the list
,09-22 10:55:22.577  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 10:55:22.577  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 10:55:22.577  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 10:55:22.578  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 10:55:22.578  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 10:55:22.578  5488  5534 D BluetoothAdapter: STATE_ON
09-22 10:55:22.578  5688  5699 D BtGatt.GattService: stopScan() - queue size =1
09-22 10:55:22.578  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 10:55:22.579  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.579  5688  5707 D BtGatt.ScanManager: Starting BLE batch scan
09-22 10:55:22.579  5688  5707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 10:55:22.579  5688  5698 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 10:55:22.579  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 10:55:22.579  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 10:55:22.579  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 10:55:22.579  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 10:55:22.579  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 10:55:22.580  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.580  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 10:55:22.580  5488  5534 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 10:55:22.580  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 10:55:22.581  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:22.582  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.582  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.582  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.582  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.582  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d9dcd removed from the list
,09-22 10:55:22.582  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.582  5488  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 10:55:22.582  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.582  5488  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 10:55:22.582  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.582  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 10:55:22.582  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9671764 removed from the list
09-22 10:55:22.583  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.583  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb349c9 added. We now have 2 listener(s)
09-22 10:55:22.584  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.584  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.584  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.584  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 10:55:22.584  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647d8ce added. We now have 9 listener(s)
09-22 10:55:22.584  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.585  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 10:55:22.586  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 10:55:22.587  5688  5704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 10:55:22.587  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 10:55:22.590  5488  5534 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 10:55:22.591  5488  5534 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 10:55:22.592  5488  5534 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 10:55:22.592  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 10:55:22.592  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 10:55:22.592  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.592  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1beefc added. We now have 3 listener(s)
09-22 10:55:22.593  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.593  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 10:55:22.593  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 10:55:22.593  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 10:55:22.593  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 10:55:22.593  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79db985 added. We now have 10 listener(s)
09-22 10:55:22.593  5488  5534 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 10:55:22.593  5488  5534 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 10:55:22.593  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:22.594  5488  5534 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 10:55:22.594  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.594  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.594  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 10:55:22.594  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.594  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb349c9 removed from the list
09-22 10:55:22.594  5488  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 10:55:22.594  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.594  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647d8ce removed from the list
09-22 10:55:22.594  5488  5534 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 10:55:22.594  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.594  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.594  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.597  5688  5704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 10:55:22.597  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.598  5688  5707 D BtGatt.ScanManager: stopping BLe Batch
09-22 10:55:22.598  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 10:55:22.598  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.598  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.598  5488  5534 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647d8ce not in the list
09-22 10:55:22.598  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.598  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 10:55:22.599  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 10:55:22.599  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 10:55:22.599  5488  5534 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 10:55:22.599  5488  5534 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79db985 removed from the list
09-22 10:55:22.599  5488  5534 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 10:55:22.599  5488  5534 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 10:55:22.600  5488  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 10:55:22.600  5488  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 10:55:22.600  5488  5534 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1beefc removed from the list
09-22 10:55:22.600  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 10:55:22.600  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 10:55:22.601  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-22 10:55:22.601  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 10:55:22.601  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-22 10:55:22.601  5488  5534 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 10:55:22.602  5688  5704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 10:55:22.602  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 10:55:22.602  5688  5707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 10:55:22.606  5488  5746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,09-22 10:55:22.606  5488  5746 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-22 10:55:22.606  5488  5746 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-22 10:55:22.607  5688  5704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 10:55:22.607  5688  5704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 10:55:22.608  5488  5747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
,09-22 10:55:22.608  5488  5747 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-22 10:55:22.608  5488  5747 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 10:55:22.610  5488  5534 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-22 10:55:22.610  5488  5534 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-22 10:55:22.610  5488  5534 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 10:55:22.610  5488  5534 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 10:55:22.610  5488  5534 D com.test.thalitest.ThaliTestRunner: Total duration: 22566 ms
09-22 10:55:22.611  5488  5534 I jxcore-log: *Native tests were executed*
09-22 10:55:22.611  5488  5534 I jxcore-log: 
09-22 10:55:22.612  5488  5534 I jxcore-log: Total number of executed tests:  80
09-22 10:55:22.612  5488  5534 I jxcore-log: 
09-22 10:55:22.612  5488  5534 I jxcore-log: Number of passed tests:  80
09-22 10:55:22.612  5488  5534 I jxcore-log: 
09-22 10:55:22.612  5488  5534 I jxcore-log: Number of failed tests:  0
09-22 10:55:22.612  5488  5534 I jxcore-log: 
09-22 10:55:22.612  5488  5534 I jxcore-log: Number of ignored tests:  0
09-22 10:55:22.612  5488  5534 I jxcore-log: 
,09-22 10:55:22.612  5488  5534 I jxcore-log: Total duration:  22566
09-22 10:55:22.612  5488  5534 I jxcore-log: 
,09-22 10:55:22.613  5488  5534 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 10:55:22.613  5488  5534 I jxcore-log: 
09-22 10:55:22.615  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.615  5488  5534 I jxcore-log: 
09-22 10:55:22.618  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.618  5488  5534 I jxcore-log: 
,09-22 10:55:22.619  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.619  5488  5534 I jxcore-log: 
09-22 10:55:22.620  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.620  5488  5534 I jxcore-log: 
09-22 10:55:22.621  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.621  5488  5534 I jxcore-log: 
09-22 10:55:22.623  5488  5488 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 10:55:22.623  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.623  5488  5534 I jxcore-log: 
09-22 10:55:22.625  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 10:55:22.625  5488  5534 I jxcore-log: 
09-22 10:55:22.627  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.627  5488  5534 I jxcore-log: 
09-22 10:55:22.628  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.628  5488  5534 I jxcore-log: 
09-22 10:55:22.628  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.628  5488  5534 I jxcore-log: 
09-22 10:55:22.629  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.629  5488  5534 I jxcore-log: 
09-22 10:55:22.630  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 10:55:22.630  5488  5534 I jxcore-log: 
09-22 10:55:22.631  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.631  5488  5534 I jxcore-log: 
09-22 10:55:22.632  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.632  5488  5534 I jxcore-log: 
09-22 10:55:22.633  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.633  5488  5534 I jxcore-log: 
09-22 10:55:22.634  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.634  5488  5534 I jxcore-log: 
09-22 10:55:22.634  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.634  5488  5534 I jxcore-log: 
09-22 10:55:22.635  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.635  5488  5534 I jxcore-log: 
09-22 10:55:22.636  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.636  5488  5534 I jxcore-log: 
,09-22 10:55:22.636  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.636  5488  5534 I jxcore-log: 
09-22 10:55:22.637  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.637  5488  5534 I jxcore-log: 
,09-22 10:55:22.638  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 10:55:22.638  5488  5534 I jxcore-log: 
,09-22 10:55:22.638  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.638  5488  5534 I jxcore-log: 
09-22 10:55:22.639  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.639  5488  5534 I jxcore-log: 
,09-22 10:55:22.640  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.640  5488  5534 I jxcore-log: 
,09-22 10:55:22.640  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.640  5488  5534 I jxcore-log: 
09-22 10:55:22.641  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.641  5488  5534 I jxcore-log: 
,09-22 10:55:22.642  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.642  5488  5534 I jxcore-log: 
09-22 10:55:22.642  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 10:55:22.642  5488  5534 I jxcore-log: 
,09-22 10:55:22.984  5488  5488 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 10:55:22.988  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 10:55:22.988  5488  5534 I jxcore-log: 
,09-22 10:55:23.039  5488  5488 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 10:55:23.043  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 10:55:23.043  5488  5534 I jxcore-log: 
,09-22 10:55:23.083  5488  5488 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 10:55:23.087  5488  5534 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 10:55:23.087  5488  5534 I jxcore-log: 
,09-22 10:55:23.128  5748  5748 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 10:55:23.133  5748  5748 D AndroidRuntime: CheckJNI is OFF
,09-22 10:55:23.162  5748  5748 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 10:55:23.196  5748  5748 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 10:55:23.214  5748  5748 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 10:55:23.223   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-22 10:55:23.224   929   942 I ActivityManager: Killing 5488:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 10:55:23.310   929  3151 I WindowState: WIN DEATH: Window{497dcad u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 10:55:23.310   929  3443 D GraphicsStats: Buffer count: 2
09-22 10:55:23.311   929  3032 D WifiService: Client connection lost with reason: 4
,09-22 10:55:23.360   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-22 10:55:23.361   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 10:55:23.361   929   954 I art     : Starting a blocking GC Explicit
09-22 10:55:23.362   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-22 10:55:23.362   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 10:55:23.362   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:23.362   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:23.362   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:55:23.362   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 10:55:23.362   929   942 I ActivityManager:   Force finishing activity ActivityRecord{104def6 u0 com.test.thalitest/.MainActivity t2}
,09-22 10:55:23.370   929  4667 W ActivityManager: Spurious death for ProcessRecord{747a439 0:com.test.thalitest/u0a77}, curProc for 5488: null
,09-22 10:55:23.375   929   947 W WindowManager: Attempted to add application window with unknown token Token{34612f7 ActivityRecord{104def6 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
09-22 10:55:23.375   929   947 W WindowManager: Token{34612f7 ActivityRecord{104def6 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{34612f7 ActivityRecord{104def6 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 10:55:23.375   929   947 W WindowManager: view not successfully added to wm, removing view
09-22 10:55:23.376   929   947 W WindowManager: Exception when adding starting window
09-22 10:55:23.376   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{1f1318 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 10:55:23.376   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 10:55:23.376   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 10:55:23.376   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 10:55:23.376   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 10:55:23.376   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 10:55:23.376   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:23.376   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:23.376   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:55:23.376   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 10:55:23.438   929   954 I art     : Explicit concurrent mark sweep GC freed 24103(1524KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.595ms total 76.411ms
,09-22 10:55:23.456   929   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 10:55:23.459  5748  5748 I art     : System.exit called, status: 0
,09-22 10:55:23.459  5748  5748 I AndroidRuntime: VM exiting with result code 0.
,09-22 10:55:23.463   929   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 10:55:23.471   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-22 10:55:23.478  3450  3450 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-22 10:55:23.480  5688  5688 D BluetoothMapAppObserver: onReceive
09-22 10:55:23.480  5688  5688 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-22 10:55:23.486  3493  3992 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-22 10:55:23.489   929  2996 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-22 10:55:23.508  3450  5759 I Keyboard.Facilitator.DecoderInitializer: run()
09-22 10:55:23.514  3416  5760 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-22 10:55:23.518  3450  5759 I Decoder : createOrResetDecoder
,09-22 10:55:23.538  3569  3569 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-22 10:55:23.546   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-22 10:55:23.547    27    27 W kworker/2:1: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 10:55:23.550    27    27 W kworker/2:1: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 10:55:23.548  3631  3631 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-22 10:55:23.548  3631  3631 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-22 10:55:23.570    27    27 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 10:55:23.578  3944  5765 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-22 10:55:23.579  3944  5765 D AccountUtils: Clearing selected account for com.test.thalitest
,09-22 10:55:23.597  3631  3631 I ConfigService: onCreate
,09-22 10:55:23.599  3631  5768 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-22 10:55:23.599  3631  5768 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-22 10:55:23.603  3631  5768 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-22 10:55:23.598  3416  3449 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj72E354952) - 
09-22 10:55:23.605  3631  5768 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-22 10:55:23.613  3450  5759 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-22 10:55:23.632  3944  5765 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-22 10:55:23.654  3944  5765 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:23.654  3944  5765 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:23.654  3944  5765 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 10:55:23.655  3944  5765 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-22 10:55:23.661  3416  3449 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-22 10:55:23.661  3416  3449 E AndroidRuntime: Process: android.process.acore, PID: 3416
09-22 10:55:23.661  3416  3449 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 10:55:23.661  3416  3449 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 10:55:23.688  3416  3449 I Process : Sending signal. PID: 3416 SIG: 9
,09-22 10:55:23.728  3944  5773 I GMPM-SVC: App measurement is starting up
,09-22 10:55:23.732  3944  5773 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-22 10:55:23.733  3944  5773 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-22 10:55:23.945   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
