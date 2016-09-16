#### Test 8450065413b5ede_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-16 12:26:16.816   614   614 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:26:17.292  5381  5381 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 12:26:17.298  5381  5381 D AndroidRuntime: CheckJNI is OFF
09-16 12:26:17.323  5381  5381 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 12:26:17.355  5381  5381 I Radio-JNI: register_android_hardware_Radio DONE
09-16 12:26:17.370  5381  5381 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-16 12:26:17.373   929  3481 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 12:26:17.422   929  3481 I ActivityManager: Start proc 5390:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 12:26:17.442  5381  5381 D AndroidRuntime: Shutting down VM
09-16 12:26:17.761   929  3411 I WindowManager: Screenshot max retries 4 of Token{6e265c3 ActivityRecord{b1ecd72 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{a7698ca u0 Starting com.test.thalitest} drawState=2
09-16 12:26:17.817   614   614 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
09-16 12:26:17.828   929  2958 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 12:26:17.836  5390  5390 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-16 12:26:17.867  5390  5390 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-16 12:26:17.891  5390  5390 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 4740-4761)
09-16 12:26:17.892  5390  5390 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 12:26:17.912  5390  5390 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {674ad5f}
09-16 12:26:17.913  5390  5390 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 12:26:17.913  5390  5390 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-16 12:26:17.916  5390  5390 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-16 12:26:17.917  5390  5390 E SysUtils: ApplicationContext is null in ApplicationStatus
09-16 12:26:17.956  5390  5390 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-16 12:26:17.964  5390  5390 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 12:26:17.964  5390  5390 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 12:26:17.964  5390  5390 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 12:26:17.964  5390  5390 I Adreno  : Build Date                       : 12/06/15
09-16 12:26:17.964  5390  5390 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 12:26:17.964  5390  5390 I Adreno  : Local Branch                     : mybranch17112971
09-16 12:26:17.964  5390  5390 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 12:26:17.964  5390  5390 I Adreno  : Remote Branch                    : NONE
09-16 12:26:17.964  5390  5390 I Adreno  : Reconstruct Branch               : NOTHING
09-16 12:26:18.019   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c478a0f:true
09-16 12:26:18.050   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28839]" dev="sockfs" ino=28839 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.050   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[28839]" dev="sockfs" ino=28839 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.059  5390  5390 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 12:26:18.069  5390  5390 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
09-16 12:26:18.110   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31195]" dev="sockfs" ino=31195 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.113  5390  5427 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 12:26:18.110   406   406 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31195]" dev="sockfs" ino=31195 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.117  3423  3423 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28844]" dev="sockfs" ino=28844 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.117  3423  3423 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28844]" dev="sockfs" ino=28844 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:18.122  5390  5414 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-16 12:26:18.157  5390  5427 I OpenGLRenderer: Initialized EGL, version 1.4
09-16 12:26:18.250   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +486ms (total +854ms)
09-16 12:26:18.292  5390  5390 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5390
09-16 12:26:18.394  5390  5390 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 12:26:18.554  5390  5429 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -580912848
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 12:26:18.566  5390  5429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5739d04 added. We now have 1 listener(s)
09-16 12:26:18.568  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-16 12:26:18.569  5390  5429 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 12:26:18.569  5390  5429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 12:26:18.569  5390  5429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 12:26:18.571  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 12:26:18.572  5390  5429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40f8570 added. We now have 1 listener(s)
09-16 12:26:18.572  5390  5429 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 12:26:18.577   929  2957 D WifiService: New client listening to asynchronous messages
09-16 12:26:18.578  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 12:26:18.578  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 12:26:18.578  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 12:26:18.578  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 12:26:18.578  5390  5429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-16 12:26:18.581  5390  5429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:18.581  5390  5429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-16 12:26:18.586  5390  5429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:18.586  5390  5429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:18.586  5390  5429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 12:26:18.586  5390  5429 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:26:18.587  5390  5429 I io.jxcore.node.LifeCycleMonitor: start: OK
09-16 12:26:18.588  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:18.592  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:18.795  5390  5390 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-16 12:26:19.165  5390  5399 I art     : Background sticky concurrent mark sweep GC freed 79533(7MB) AllocSpace objects, 18(1676KB) LOS objects, 26% free, 23MB/32MB, paused 1.770ms total 273.069ms
,09-16 12:26:20.431  5390  5436 W jxcore-log: Initializing JXcore engine
09-16 12:26:20.431  5390  5436 W jxcore-log: JXcore engine is ready
,09-16 12:26:20.483  5436  5436 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-16 12:26:20.483  5436  5436 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12666]" dev="sockfs" ino=12666 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-16 12:26:20.483  5436  5436 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 12:26:20.483  5436  5436 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31806]" dev="sockfs" ino=31806 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 12:26:20.501  5390  5436 W jxcore-log: Starting JXcore engine
,09-16 12:26:20.562  5390  5436 W jxcore-log: Platform android
09-16 12:26:20.562  5390  5436 W jxcore-log: 
,09-16 12:26:20.562  5390  5436 W jxcore-log: Process ARCH arm
09-16 12:26:20.562  5390  5436 W jxcore-log: 
,09-16 12:26:20.676  5390  5436 I jxcore-log: JXcore Cordova bridge is ready!
09-16 12:26:20.676  5390  5436 I jxcore-log: 
09-16 12:26:20.676  5390  5436 W jxcore-log: JXcore engine is started
,09-16 12:26:20.685  5390  5429 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 12:26:20.692  5390  5390 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 12:26:23.883   929  2958 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 12:26:27.818   614   614 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:26:28.819   614   614 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:26:29.820   614   614 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:26:30.138  5390  5436 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 12:26:30.138  5390  5436 I jxcore-log: 
,09-16 12:26:30.141  5390  5436 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 12:26:30.141  5390  5436 I jxcore-log: 
,09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.146  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 12:26:30.147  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 12:26:30.149  5390  5436 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 12:26:30.149  5390  5436 I jxcore-log: 
,09-16 12:26:30.150  5390  5436 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 12:26:30.150  5390  5436 I jxcore-log: 
,09-16 12:26:30.396  5390  5436 D ExecuteNativeTests: Running unit tests
,09-16 12:26:30.435  5390  5436 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 12:26:30.435  5390  5436 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 added. We now have 2 listener(s)
09-16 12:26:30.436  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 12:26:30.436  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 12:26:30.436  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 12:26:30.436  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 12:26:30.436  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 added. We now have 2 listener(s)
,09-16 12:26:30.436  5390  5436 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 12:26:30.437  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 12:26:30.439  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.442  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.444  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.444  5390  5436 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:26:30.445  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 12:26:30.446  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:26:30.446  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 12:26:30.447  5390  5436 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 12:26:30.447  5390  5436 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 12:26:30.447  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 12:26:30.447  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 12:26:30.447  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 12:26:30.447  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.448  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 12:26:30.448  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.448  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.448  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.448  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.448  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 12:26:30.448  5390  5436 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 removed from the list
09-16 12:26:30.448  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.448  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 removed from the list
09-16 12:26:30.451  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.457  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.458  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.458  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.458  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.458  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.459  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.459  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 12:26:30.459  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.459  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.460  5390  5436 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 12:26:30.460  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.460  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.460  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 12:26:30.460  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.460  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.460  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.460  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.460  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.461  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.461  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 12:26:30.461  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.461  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.461  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.461  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.461  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.461  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.461  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.461  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.463  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 12:26:30.463  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 12:26:30.463  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 12:26:30.463  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 12:26:30.464  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 12:26:30.464  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.464  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.464  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.464  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.464  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:26:30.464  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.465  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.465  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.465  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.465  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.465  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.465  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.465  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.465  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.465  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 12:26:30.465  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.465  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.465  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.466  5390  5436 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 12:26:30.466  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.469  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.469  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 12:26:30.469  5390  5436 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:26:30.470  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 12:26:30.470  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 12:26:30.470  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 12:26:30.470  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.470  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.472  5390  5436 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.472  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 12:26:30.474  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.476  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 12:26:30.476  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.477  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 12:26:30.477  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 12:26:30.478  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 12:26:30.479  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-16 12:26:30.479  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 12:26:30.479  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 12:26:30.480  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 12:26:30.480  5390  5436 D BluetoothAdapter: STATE_ON
,09-16 12:26:30.482  4430  4656 D BtGatt.GattService: registerClient() - UUID=8d672ff0-885f-4753-8e66-6df9b147f22c
,09-16 12:26:30.483  4430  4501 D BtGatt.GattService: onClientRegistered() - UUID=8d672ff0-885f-4753-8e66-6df9b147f22c, clientIf=5
,09-16 12:26:30.484  5390  5400 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 12:26:30.485  4430  4444 D BtGatt.GattService: start scan with filters
,09-16 12:26:30.490  4430  4507 D BtGatt.ScanManager: handling starting scan
09-16 12:26:30.490  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 12:26:30.490  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 12:26:30.490  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 12:26:30.490  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 12:26:30.491  4430  4507 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd592d6
,09-16 12:26:30.492  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 12:26:30.492  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 12:26:30.492  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:26:30.493  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 12:26:30.494  5390  5436 I io.jxcore.node.ConnectionHelper: start: OK
09-16 12:26:30.495  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.495  5390  5436 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 12:26:30.495  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.495  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 12:26:30.495  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.495  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:26:30.495  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 12:26:30.495  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 12:26:30.495  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 12:26:30.495  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 12:26:30.496  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 12:26:30.496  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 12:26:30.497  5390  5436 D BluetoothAdapter: STATE_ON
,09-16 12:26:30.498  4430  4501 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 12:26:30.498  4430  4683 D BtGatt.GattService: stopScan() - queue size =1
,09-16 12:26:30.498  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.498  4430  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 12:26:30.498  4430  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 12:26:30.499  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.499  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 12:26:30.499  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 12:26:30.499  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 12:26:30.499  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 12:26:30.502  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 12:26:30.502  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 12:26:30.502  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.502  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.502  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 12:26:30.502  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.502  4430  4507 D BtGatt.ScanManager: Starting BLE batch scan
09-16 12:26:30.502  4430  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 12:26:30.502  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 12:26:30.503  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.503  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.503  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.503  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.503  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.503  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.503  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.503  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.503  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:26:30.503  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.503  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.503  5390  5436 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 12:26:30.505  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.505  5390  5390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 12:26:30.507  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 12:26:30.508  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.508  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 12:26:30.508  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 12:26:30.508  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.509  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.511  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.511  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.511  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.513  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 12:26:30.513  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.513  4430  4501 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 12:26:30.513  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.513  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.513  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.514  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.514  5390  5436 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:26:30.514  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 12:26:30.514  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 12:26:30.514  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.515  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 12:26:30.515  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.515  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.516  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.516  5390  5436 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 12:26:30.518  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:30.519  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 12:26:30.519  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.519  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 12:26:30.519  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 12:26:30.519  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 12:26:30.520  5390  5436 D BluetoothAdapter: STATE_ON
,09-16 12:26:30.523  4430  4442 D BtGatt.GattService: registerClient() - UUID=742dc7a0-f6b5-4271-93f9-84b20dd42ec6
,09-16 12:26:30.523  4430  4501 D BtGatt.GattService: onClientRegistered() - UUID=742dc7a0-f6b5-4271-93f9-84b20dd42ec6, clientIf=5
,09-16 12:26:30.524  5390  5401 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 12:26:30.524  4430  4444 D BtGatt.GattService: start scan with filters
,09-16 12:26:30.527  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 12:26:30.527  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.527  4430  4507 D BtGatt.ScanManager: stopping BLe Batch
09-16 12:26:30.528  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 12:26:30.528  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 12:26:30.528  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 12:26:30.528  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 12:26:30.531  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 12:26:30.531  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 12:26:30.531  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:26:30.531  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 12:26:30.532  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 12:26:30.532  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:26:30.532  4430  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 12:26:30.532  5390  5436 I io.jxcore.node.ConnectionHelper: start: OK
09-16 12:26:30.533  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 12:26:30.533  5390  5436 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 12:26:30.533  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.533  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 12:26:30.533  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.533  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:26:30.533  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 12:26:30.533  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 12:26:30.533  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 12:26:30.533  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 12:26:30.533  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 12:26:30.533  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 12:26:30.535  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.535  4430  4501 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 12:26:30.535  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:26:30.535  4430  4683 D BtGatt.GattService: stopScan() - queue size =0
09-16 12:26:30.536  4430  4656 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 12:26:30.536  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 12:26:30.536  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.536  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 12:26:30.536  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.536  4430  4507 D BtGatt.ScanManager: handling starting scan
09-16 12:26:30.537  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.538  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.538  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.538  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.538  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.538  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.538  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.538  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.538  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:26:30.538  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.538  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.538  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 12:26:30.541  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 12:26:30.541  5390  5390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 12:26:30.542  4430  4501 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 12:26:30.542  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.542  4430  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 12:26:30.544  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 12:26:30.546  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 12:26:30.546  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 12:26:30.546  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.547  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 12:26:30.547  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.547  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.547  4430  4507 D BtGatt.ScanManager: Starting BLE batch scan
09-16 12:26:30.547  4430  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 12:26:30.549  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.549  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 12:26:30.549  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.551  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.552  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 12:26:30.552  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.554  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.554  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.555  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.555  4430  4501 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 12:26:30.555  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.555  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.555  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.555  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.556  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.556  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.556  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 12:26:30.556  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.556  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.556  5390  5436 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 12:26:30.557  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 12:26:30.560  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 12:26:30.560  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.560  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 12:26:30.562  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.562  5390  5436 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 12:26:30.563  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 12:26:30.563  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 12:26:30.563  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 12:26:30.563  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.563  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.564  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:30.565  5390  5436 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.566  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 12:26:30.566  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.566  4430  4507 D BtGatt.ScanManager: stopping BLe Batch
09-16 12:26:30.567  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:30.568  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 12:26:30.568  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 12:26:30.568  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 12:26:30.569  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.570  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 12:26:30.570  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 12:26:30.571  4430  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 12:26:30.572  4430  4684 D BtGatt.GattService: registerClient() - UUID=5f15cb3a-aabd-4090-9648-e869f976af72
09-16 12:26:30.572  4430  4501 D BtGatt.GattService: onClientRegistered() - UUID=5f15cb3a-aabd-4090-9648-e869f976af72, clientIf=5
09-16 12:26:30.572  5390  5400 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 12:26:30.573  4430  4656 D BtGatt.GattService: start scan with filters
,09-16 12:26:30.575  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 12:26:30.575  4430  4501 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 12:26:30.575  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 12:26:30.575  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.575  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 12:26:30.575  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 12:26:30.576  4430  4507 D BtGatt.ScanManager: handling starting scan
09-16 12:26:30.577  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:26:30.577  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 12:26:30.577  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 12:26:30.578  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 12:26:30.579  5390  5436 I io.jxcore.node.ConnectionHelper: start: OK
09-16 12:26:30.579  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.579  5390  5436 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-16 12:26:30.579  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.579  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 12:26:30.579  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.579  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:26:30.579  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 12:26:30.579  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 12:26:30.579  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 12:26:30.579  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 12:26:30.580  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 12:26:30.580  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 12:26:30.580  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.580  4430  4444 D BtGatt.GattService: stopScan() - queue size =1
,09-16 12:26:30.581  4430  4656 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 12:26:30.581  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.581  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 12:26:30.581  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 12:26:30.581  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 12:26:30.581  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 12:26:30.581  4430  4501 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 12:26:30.581  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.581  4430  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 12:26:30.582  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.582  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.582  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 12:26:30.582  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.582  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 12:26:30.583  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.583  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.583  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 12:26:30.583  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:26:30.583  5390  5436 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 12:26:30.583  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.583  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.583  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.583  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.583  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 12:26:30.583  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.583  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.583  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.583  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.584  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.585  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.585  5390  5390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 12:26:30.586  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 12:26:30.586  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.586  4430  4507 D BtGatt.ScanManager: Starting BLE batch scan
09-16 12:26:30.586  4430  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 12:26:30.589  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 12:26:30.589  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 12:26:30.589  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 12:26:30.590  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 12:26:30.592  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.594  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.594  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.594  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.595  4430  4501 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 12:26:30.595  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.597  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.597  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.597  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.599  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.599  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.599  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.599  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 12:26:30.599  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.600  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.600  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.600  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 12:26:30.601  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.601  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.601  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.601  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.601  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.601  5390  5436 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-16 12:26:30.602  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.602  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.602  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.602  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.602  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.602  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.602  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.602  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.602  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.602  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.602  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.602  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.602  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.602  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.603  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.603  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.603  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.604  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.604  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.604  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.604  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.604  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.605  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 12:26:30.605  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 12:26:30.605  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.605  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.605  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.605  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.605  4430  4501 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 12:26:30.605  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.605  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.605  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.605  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.605  4430  4507 D BtGatt.ScanManager: stopping BLe Batch
09-16 12:26:30.605  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.605  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.605  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.605  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.605  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.605  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.606  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.607  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.607  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.607  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.607  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.607  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.607  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.607  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.608  5390  5436 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 12:26:30.608  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.608  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.608  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.608  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.608  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.608  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.608  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.608  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.608  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.608  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 12:26:30.608  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.609  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.609  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.609  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.610  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.610  4430  4501 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 12:26:30.610  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.610  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.610  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.611  4430  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 12:26:30.611  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.611  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.611  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.611  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.611  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.612  5390  5436 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.612  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.612  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.612  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.612  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.612  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.612  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.612  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.612  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.612  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.612  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.612  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.613  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.613  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.613  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.614  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.614  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.614  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.615  5390  5436 D BluetoothAdapter: STATE_ON
,09-16 12:26:30.615  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.615  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.615  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.615  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.615  4430  4501 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 12:26:30.615  4430  4501 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 12:26:30.615  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 12:26:30.615  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:26:30.615  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 12:26:30.615  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 12:26:30.616  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 12:26:30.616  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 12:26:30.616  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.616  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.616  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.616  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.616  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.616  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.616  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.616  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.616  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.616  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.616  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.620  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.621  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.621  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.622  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.622  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.622  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.623  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.623  5390  5436 D BluetoothLeScanner: could not find callback wrapper
,09-16 12:26:30.623  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.624  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.625  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.627  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 12:26:30.627  5390  5436 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 12:26:30.627  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 12:26:30.632  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 12:26:30.632  5390  5436 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 12:26:30.632  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 12:26:30.633  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 12:26:30.634  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 12:26:30.634  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 12:26:30.634  5390  5436 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 12:26:30.634  5390  5436 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 12:26:30.634  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 12:26:30.635  5390  5436 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 12:26:30.635  5390  5436 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 12:26:30.635  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 12:26:30.635  5390  5436 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 12:26:30.635  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-16 12:26:30.638  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-16 12:26:30.638  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 12:26:30.639  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-16 12:26:30.639  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 12:26:30.639  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 12:26:30.639  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 12:26:30.639  5390  5436 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 12:26:30.640  5390  5436 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 12:26:30.640  5390  5437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-16 12:26:30.640  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.640  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 12:26:30.640  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.641  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.641  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.641  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.641  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-16 12:26:30.642  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.642  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.642  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.642  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.642  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:26:30.642  5390  5437 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 12:26:30.642  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.642  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.642  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.643  5390  5438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-16 12:26:30.644  5390  5438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
,09-16 12:26:30.644  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.644  5390  5438 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-16 12:26:30.644  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.644  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.644  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.644  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.644  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.644  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.645  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.645  5390  5436 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 12:26:30.646  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.646  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.646  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.646  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 12:26:30.646  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.646  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.646  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.646  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.646  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.646  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.646  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:26:30.646  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.646  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.646  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.643  4444  4444 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:30.647  4444  4444 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:30.647  5390  5437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-16 12:26:30.647  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.647  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.648  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.648  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.648  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.648  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 12:26:30.648  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.648  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.649  5390  5436 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 12:26:30.649  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.649  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.649  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.649  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.649  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.649  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.649  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.650  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.650  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.650  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.650  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.650  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.650  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.650  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.651  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.651  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.651  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.651  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.652  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.652  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.652  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.652  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.652  5390  5436 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 12:26:30.652  5390  5436 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 12:26:30.652  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 12:26:30.652  5390  5436 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 12:26:30.652  5390  5436 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 12:26:30.653  5390  5436 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 12:26:30.653  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 12:26:30.653  5390  5436 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-16 12:26:30.653  5390  5436 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 12:26:30.653  5390  5436 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 12:26:30.653  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 12:26:30.653  5390  5436 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 12:26:30.653  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.653  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.653  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.653  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.653  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.653  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.654  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.654  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.654  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.654  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.654  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.654  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.654  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.654  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.655  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.655  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.655  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 12:26:30.655  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.656  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.656  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.656  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.656  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.656  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.656  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.656  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.656  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.656  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 12:26:30.656  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.656  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.657  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.657  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.657  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.657  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.657  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 12:26:30.657  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.657  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.657  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.657  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.657  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.657  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.657  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 12:26:30.657  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.657  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.658  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.658  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.658  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.658  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.658  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.658  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.658  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.658  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.659  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 12:26:30.659  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.659  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.659  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.660  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.660  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.660  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.660  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.661  5390  5436 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-16 12:26:30.661  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.662  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 12:26:30.662  5390  5436 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 12:26:30.662  5390  5436 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 12:26:30.663  5390  5390 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 12:26:30.663  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 12:26:30.663  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.663  5390  5436 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 12:26:30.663  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.663  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.664  5390  5390 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 12:26:30.664  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 12:26:30.664  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 12:26:30.664  5390  5439 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 12:26:30.664  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 12:26:30.664  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 12:26:30.664  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.665  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.665  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.665  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.665  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 12:26:30.665  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:26:30.665  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.663  4683  4683 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31228]" dev="sockfs" ino=31228 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 12:26:30.666  5390  5436 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.666  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.666  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.666  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.666  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 12:26:30.666  5390  5439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 12:26:30.666  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 12:26:30.666  5390  5439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 12:26:30.666  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.666  5390  5439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 12:26:30.666  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.666  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.666  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.666  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.666  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.666  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.666  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.666  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.667  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.667  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 12:26:30.663  4683  4683 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31228]" dev="sockfs" ino=31228 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 12:26:30.669  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.669  5390  5390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 12:26:30.672  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 12:26:30.672  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 12:26:30.672  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 12:26:30.672  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 12:26:30.672  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.674  5390  5390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 12:26:30.674  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.674  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 12:26:30.676  5390  5390 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 12:26:30.677  5390  5390 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 12:26:30.677  5390  5390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.679  5390  5390 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 12:26:30.679  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 12:26:30.679  5390  5390 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 12:26:30.679  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.680  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 12:26:30.680  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.680  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 12:26:30.680  5390  5436 D BluetoothAdapter: STATE_ON
,09-16 12:26:30.680  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.680  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.681  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.681  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.682  5390  5436 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 12:26:30.682  5390  5436 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 12:26:30.682  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 12:26:30.682  5390  5436 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 12:26:30.682  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.682  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.682  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.682  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.682  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.682  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.682  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.682  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.682  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.682  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.682  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.682  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.682  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.682  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 12:26:30.683  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.684  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.684  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 12:26:30.684  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.684  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.684  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.684  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.684  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.687  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.687  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.687  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.687  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.687  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.687  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.687  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.688  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.688  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.688  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 12:26:30.688  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.688  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.688  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.688  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.689  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.689  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.689  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.689  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.689  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.689  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.689  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.689  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
09-16 12:26:30.690  5390  5436 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 12:26:30.690  5390  5436 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 12:26:30.690  5390  5436 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 12:26:30.690  5390  5436 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 12:26:30.690  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.690  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.690  5390  5436 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@723b8e6 not in the list
09-16 12:26:30.690  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.690  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.690  5390  5436 D io.jxcore.node.ConnectivityMonitor: stop
09-16 12:26:30.690  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.691  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.691  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 12:26:30.691  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 12:26:30.692  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 12:26:30.692  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 12:26:30.692  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 12:26:30.693  5390  5436 D BluetoothAdapter: STATE_ON
09-16 12:26:30.693  5390  5436 D BluetoothLeScanner: could not find callback wrapper
09-16 12:26:30.693  5390  5436 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 12:26:30.693  5390  5436 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 12:26:30.693  5390  5436 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46ffe27 not in the list
,09-16 12:26:30.694  5390  5436 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 12:26:30.694  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 12:26:30.694  5390  5436 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 12:26:30.694  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 12:26:30.694  5390  5436 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 12:26:30.694  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 12:26:30.696  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-16 12:26:30.696  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-16 12:26:30.697  5390  5436 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 12:26:30.697  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 12:26:30.697  5390  5436 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 12:26:30.697  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 12:26:30.697  5390  5436 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 12:26:30.697  5390  5436 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 12:26:30.698  5390  5436 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 12:26:30.698  5390  5436 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-16 12:26:30.701  5390  5436 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 12:26:30.701  5390  5436 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 12:26:30.701  5390  5436 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-16 12:26:30.701  5390  5436 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 12:26:30.702  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 12:26:30.702  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1d2ca5 added. We now have 2 listener(s)
09-16 12:26:30.702  5390  5436 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:26:30.704  5390  5436 D BluetoothAdapter: enable(): BT is already enabled..!
09-16 12:26:30.704   929  3481 D WifiService: setWifiEnabled: true pid=5390, uid=10077
09-16 12:26:30.704   929  3481 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 12:26:30.705  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 12:26:30.705  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba4787a added. We now have 3 listener(s)
09-16 12:26:30.705  5390  5436 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:26:30.710  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 12:26:30.710  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a18a82b added. We now have 4 listener(s)
09-16 12:26:30.710  5390  5436 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:26:30.711  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 12:26:30.711  5390  5436 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfee488 added. We now have 5 listener(s)
09-16 12:26:30.711  5390  5436 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 12:26:30.713   929  3423 D WifiService: setWifiEnabled: false pid=5390, uid=10077
09-16 12:26:30.713   929  3423 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 12:26:30.715   929  2956 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-16 12:26:30.715   929  2956 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 12:26:30.715   929  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 12:26:30.715   929  2956 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 12:26:30.719  4430  4490 D BluetoothAdapterState: Current state: ON, message: 23
09-16 12:26:30.719  4430  4490 D BluetoothAdapterProperties: Setting state to 13
09-16 12:26:30.719  4430  4490 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 12:26:30.719  4430  4490 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 12:26:30.720  4430  4490 I BluetoothAdapterState: Entering PendingCommandState
,09-16 12:26:30.721  4430  4430 D BluetoothMapService: onReceive
,09-16 12:26:30.722  4430  4430 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 12:26:30.722  4430  4430 D BluetoothMapService: STATE_TURNING_OFF
09-16 12:26:30.722  4430  4430 D BluetoothMapService: MAP Service closeService in
09-16 12:26:30.722  4430  4430 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 12:26:30.722  4430  4430 D ObexServerSockets0: shutdown(block = true)
09-16 12:26:30.722  4430  4690 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-16 12:26:30.723  4430  4430 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 12:26:30.723  4430  4430 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 12:26:30.723  4430  4652 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 12:26:30.723  4430  4691 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 12:26:30.725  4430  4430 I BtOppRfcommListener: stopping Accept Thread
09-16 12:26:30.725  4430  5098 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 12:26:30.725  5390  5436 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 12:26:30.726  4430  5098 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-16 12:26:30.729   929  5143 D DhcpClient: Clearing IP address
09-16 12:26:30.729   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-16 12:26:30.734  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.735  5390  5436 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.736  5390  5436 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.736  5390  5436 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 12:26:30.736  5390  5436 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 12:26:30.736   509   922 D CommandListener: Setting iface cfg
,09-16 12:26:30.738   929  5144 D DhcpClient: Receive thread stopped
09-16 12:26:30.739   929   942 I ActivityManager: Start proc 5442:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-16 12:26:30.740  4430  4501 D BluetoothAdapterProperties: Scan Mode:20
09-16 12:26:30.740  4430  4490 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 12:26:30.741  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.743  3601  5196 V NativeCrypto: Read error: ssl=0x7f7ffd7180: I/O error during system call, Connection timed out
09-16 12:26:30.746  3601  5196 V NativeCrypto: SSL shutdown failed: ssl=0x7f7ffd7180: I/O error during system call, Broken pipe
09-16 12:26:30.746  4430  4430 D HeadsetService: Received stop request...Stopping profile...
09-16 12:26:30.747  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.748   929   929 D BluetoothHeadset: Proxy object disconnected
09-16 12:26:30.748   929   929 D BluetoothHeadset: Proxy object disconnected
,09-16 12:26:30.748   929   929 D BluetoothHeadset: Proxy object disconnected
09-16 12:26:30.749  3498  3516 D BluetoothHeadset: Proxy object disconnected
,09-16 12:26:30.750   929  2958 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 12:26:30.750   929  2958 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-16 12:26:30.750  3110  3122 D BluetoothHeadset: Proxy object disconnected
,09-16 12:26:30.750  3110  3110 D HeadsetProfile: Bluetooth service disconnected
09-16 12:26:30.751  4430  4430 D A2dpService: Received stop request...Stopping profile...
09-16 12:26:30.751  4430  4668 D A2dpStateMachine: Exit Disconnected: -1
09-16 12:26:30.753   612   612 E Parcel  : Reading a NULL string not supported here.
09-16 12:26:30.754   929   929 D BluetoothA2dp: Proxy object disconnected
09-16 12:26:30.754  5390  5399 I art     : Background partial concurrent mark sweep GC freed 90171(6MB) AllocSpace objects, 18(3MB) LOS objects, 39% free, 22MB/38MB, paused 7.460ms total 57.063ms
09-16 12:26:30.754  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.755  3110  3110 D BluetoothA2dp: Proxy object disconnected
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 12:26:30.755  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.755  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.755  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 12:26:30.756   929   929 D RttService: SCAN_AVAILABLE : 1
09-16 12:26:30.757  4430  4430 D HidService: Received stop request...Stopping profile...
09-16 12:26:30.757   929  3063 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 12:26:30.757  4430  4430 D HidService: Stopping Bluetooth HidService
09-16 12:26:30.757  3110  3110 D BluetoothInputDevice: Proxy object disconnected
09-16 12:26:30.758  3110  3110 D HidProfile: Bluetooth service disconnected
09-16 12:26:30.758  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.758  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.758  4430  4430 D HealthService: Received stop request...Stopping profile...
,09-16 12:26:30.758  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.758  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 12:26:30.759  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.759  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.759  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.759  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.759   929  2958 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-16 12:26:30.759  4430  4430 D PanService: Received stop request...Stopping profile...
09-16 12:26:30.760  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.760  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 12:26:30.761  3474  3633 W QCNEJ   : |CORE| network lost: 100
09-16 12:26:30.761  3474  3633 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 12:26:30.762  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.762  4430  4430 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 12:26:30.762  4430  4430 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 12:26:30.762  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.762  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.762  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.763  4430  4430 D BluetoothMapService: Received stop request...Stopping profile...
09-16 12:26:30.763  4430  4430 D BluetoothMapService: stop()
09-16 12:26:30.763  4430  4430 D BluetoothMapAppObserver: deinitObservers()
09-16 12:26:30.763  4430  4430 D BluetoothMapAppObserver: removeReceiver()
09-16 12:26:30.763  4430  4501 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 12:26:30.763  4430  4501 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 12:26:30.767  4430  4430 D SapService: Received stop request...Stopping profile...
09-16 12:26:30.769  4430  4430 V SapService: stop()
09-16 12:26:30.770  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.770  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.770  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.770  4430  4652 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-16 12:26:30.770  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.771  4430  4501 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 12:26:30.771  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.771  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.771  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.771  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.771  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.772  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.772  4430  4638 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 12:26:30.772  4430  4638 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 12:26:30.772  4430  4638 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 12:26:30.772  4430  4638 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 12:26:30.772  4430  4430 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 12:26:30.772  4430  4430 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 12:26:30.772  4430  4501 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 12:26:30.772  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.772  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.772  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.772  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.772  4430  4430 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 12:26:30.772  4430  4501 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 12:26:30.773   929  2956 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 12:26:30.773  4430  4430 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 12:26:30.773  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.773  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.773  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.773  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.774  4430  4430 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 12:26:30.774  4430  4430 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 12:26:30.775  4430  4430 D BluetoothMapService: MAP Service closeService in
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.775  4430  4430 D BluetoothMapService: cleanup()
09-16 12:26:30.775  4430  4430 D BluetoothMapService: MAP Service closeService in
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isTurningOff()=true
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:30.775  4430  4430 V BluetoothAdapterState: isBleTurningOff()=false
09-16 12:26:30.776  4430  4490 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 12:26:30.776  4430  4490 D BluetoothAdapterProperties: Setting state to 15
09-16 12:26:30.776  4430  4490 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 12:26:30.776  4430  4490 I BluetoothAdapterState: Entering BleOnState
09-16 12:26:30.776   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 12:26:30.776   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 12:26:30.776  3110  3121 D BluetoothPan: onBluetoothStateChange on: false
09-16 12:26:30.777  3110  3122 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 12:26:30.778  3110  3414 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 12:26:30.779  3110  3121 D BluetoothMap: onBluetoothStateChange: up=false
09-16 12:26:30.780  3110  3122 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 12:26:30.781   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 12:26:30.781  3498  3520 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 12:26:30.781  3110  3414 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 12:26:30.782   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 12:26:30.783  4430  4490 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 12:26:30.783  4430  4490 D BluetoothAdapterProperties: Setting state to 16
09-16 12:26:30.783  4430  4490 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 12:26:30.783  4430  4490 D BluetoothAdapterProperties: onBleDisable
09-16 12:26:30.783  4430  4490 I BluetoothAdapterState: Entering PendingCommandState
09-16 12:26:30.783  4430  4494 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 12:26:30.785  4430  4638 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 12:26:30.785  4430  4638 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 12:26:30.786  4430  4501 D BluetoothAdapterProperties: Scan Mode:20
09-16 12:26:30.791  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.791  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:26:30.791   929  2956 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 12:26:30.794  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.794  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 12:26:30.797   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 12:26:30.797  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.799  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.807  5442  5442 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-16 12:26:30.820   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 12:26:30.821   509   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 12:26:30.821  5442  5442 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 12:26:30.821   929  2958 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-16 12:26:30.821   509   922 D TetherController: Setting IP forward enable = 0
09-16 12:26:30.821   929  2958 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 12:26:30.822   614   614 I ServiceManager: Waiting for service AtCmdFwd...
09-16 12:26:30.824   929   946 D Tethering: MasterInitialState.processMessage what=3
09-16 12:26:30.825  4214  4214 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@288e03b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-16 12:26:30.826   929  2956 D DhcpClient: doQuit
09-16 12:26:30.826   929  2956 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 12:26:30.826  3636  3636 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 12:26:30.827   929  5143 D DhcpClient: onQuitting
09-16 12:26:30.830  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 12:26:30.831  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.832  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:26:30.832  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.832  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 12:26:30.835  4851  4866 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 12:26:30.835  4851  4866 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 12:26:30.835  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.835  4851  4866 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:30.835  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:26:30.835  4851  4866 E SarControlService: no key has been found,reset the power
,09-16 12:26:30.835  4851  4890 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-16 12:26:30.835  4851  4890 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 12:26:30.836  4851  4890 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 12:26:30.836  4880  4880 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 12:26:30.836  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:30.836  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 12:26:30.836  4880  4880 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 12:26:30.838  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 12:26:30.839  4851  4890 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 12:26:30.839  4851  4890 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 12:26:30.839  4851  4890 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 12:26:30.840  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:30.840  4880  4880 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 12:26:30.840  4880  4880 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 12:26:30.843  4880  4894 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@614d9b9 HexData = [00000000ea03000000000000ffffffff]
09-16 12:26:30.843  4880  4894 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 12:26:30.843  4880  4894 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 12:26:30.843  4880  4880 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 12:26:30.843  4851  4862 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 12:26:30.846  4880  4894 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@614d9b9 HexData = [00000000eb03000000000000ffffffff]
,09-16 12:26:30.846  4880  4894 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-16 12:26:30.846  4880  4894 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-16 12:26:30.846   929  3187 I ActivityManager: Start proc 5470:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 12:26:30.847  4880  4880 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 12:26:30.848  4851  4863 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 12:26:30.849  3636  3636 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-16 12:26:30.853   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@edbd960:true
09-16 12:26:30.854  3636  3636 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 12:26:30.869  5442  5442 D LocalBluetoothProfileManager: Adding local MAP profile
,09-16 12:26:30.875  5442  5442 D BluetoothMap: Create BluetoothMap proxy object
,09-16 12:26:30.876   509   922 E Netd    : netlink response contains error (No such file or directory)
,09-16 12:26:30.877   509   922 D TetherController: Setting IP forward enable = 0
,09-16 12:26:30.877   929  2958 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-16 12:26:30.888  5442  5442 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 12:26:30.889  3636  3636 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 12:26:30.896  5470  5470 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 12:26:30.907  5442  5442 D DockEventReceiver: finishStartingService: stopping service
09-16 12:26:30.907  3636  3636 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 12:26:30.910   929  3539 I ActivityManager: Killing 4832:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-16 12:26:30.997  4430  4501 I bt_hci  : shut_down
,09-16 12:26:30.999  4430  4508 D bt_hwcfg: hw_epilog_process
09-16 12:26:31.000  4430  4508 I bt_vendor: low_power_mode_cb
,09-16 12:26:31.002  4430  4508 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 12:26:31.002  4430  4508 I bt_vendor: epilog_cb
09-16 12:26:31.002  4430  4508 I bt_hci  : epilog_finished_callback
09-16 12:26:31.004  4430  4501 I bt_hci_h4: hal_close
09-16 12:26:31.005  4430  4501 I bt_userial_vendor: device fd = 54 close
,09-16 12:26:31.010  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 12:26:31.010   929  2956 D wifi    : In wifi stop Hal
09-16 12:26:31.010   929  2956 D wifi    : halHandle = 0x7f65177560, mVM = 0x7f8178d140, mCls = 0x100b5e
09-16 12:26:31.011   929  3632 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 12:26:31.011   929  3632 D WifiHAL : Got a signal to exit!!!
,09-16 12:26:31.011   929  3632 I WifiHAL : Exit wifi_event_loop
09-16 12:26:31.011   929  2956 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-16 12:26:31.011   929  2956 E WifiHAL : Event processing terminated
09-16 12:26:31.012   929  2956 D wifi    : In wifi cleaned up handler
09-16 12:26:31.012   929  2956 I WifiHAL : Internal cleanup completed
09-16 12:26:31.013  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:31.015  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:31.016  3449  4013 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 12:26:31.036   929  3632 D wifi    : set interface wlan0 flags (DOWN)
,09-16 12:26:31.036   929  2956 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 12:26:31.096  5470  5470 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-16 12:26:31.096  5470  5470 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.096  5470  5470 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.096  5470  5470 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.096  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.101  5470  5470 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.101  5470  5470 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.101  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.102  5470  5470 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.102  5470  5470 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 12:26:31.102  5470  5470 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 12:26:31.109  5442  5442 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 12:26:31.113  4430  4494 D bt_stack_manager: event_shut_down_stack finished.
09-16 12:26:31.113  4430  4490 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-16 12:26:31.115  4430  4490 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-16 12:26:31.115  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 12:26:31.115  4430  4430 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 12:26:31.116  4430  4430 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 12:26:31.116  4430  4430 D BtGatt.GattService: stop()
09-16 12:26:31.116  4430  4430 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 12:26:31.118  4430  4430 V BluetoothAdapterState: isTurningOff()=false
09-16 12:26:31.118  4430  4430 V BluetoothAdapterState: isTurningOn()=false
09-16 12:26:31.118  4430  4430 V BluetoothAdapterState: isBleTurningOn()=false
09-16 12:26:31.118  4430  4430 V BluetoothAdapterState: isBleTurningOff()=true
09-16 12:26:31.119  4430  4490 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 12:26:31.119  4430  4490 D BluetoothAdapterProperties: Setting state to 10
09-16 12:26:31.119  4430  4490 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 12:26:31.119  4430  4490 I BluetoothAdapterState: Entering OffState
09-16 12:26:31.121   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-16 12:26:31.132  4430  4430 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 12:26:31.132  4430  4430 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 12:26:31.132  4430  4430 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 12:26:31.133  4430  4494 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-16 12:26:31.140  3856  3856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-16 12:26:31.147  4430  4494 D bt_stack_manager: event_clean_up_stack finished.
09-16 12:26:31.158  5442  5442 D DockEventReceiver: finishStartingService: stopping service
09-16 12:26:31.160  4430  4430 I art     : System.exit called, status: 0
09-16 12:26:31.160  4430  4430 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-16 12:26:31.168  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 12:26:31.169  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-16 12:26:31.171  5168  5168 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 12:26:31.175  5168  5168 D SprintDMHelper: simOperator: 
09-16 12:26:31.175  5168  5168 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 12:26:31.179  5390  5390 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 12:26:31.186  4274  5508 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 12:26:31.189   929  3515 I ActivityManager: Killing 4214:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-16 12:26:31.203  3856  5166 I iu.UploadsManager: num queued entries: 0
,09-16 12:26:31.204  3856  5166 I iu.UploadsManager: num updated entries: 0
09-16 12:26:31.204  3856  5166 I iu.SyncManager: NEXT; no task
,09-16 12:26:31.232   929  3515 I ActivityManager: Start proc 5509:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 12:26:31.235   929  3423 I ActivityManager: Process com.android.bluetooth (pid 4430) has died
,09-16 12:26:31.239   929   946 D Tethering: InitialState.processMessage what=4
,09-16 12:26:31.242   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 12:26:31.262  5509  5509 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 12:26:31.270   929  3539 I ActivityManager: Killing 4528:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-16 12:26:31.398  5470  5494 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 12:26:31.410   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d75b6c1:true
,09-16 12:26:31.823   614   614 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 12:26:32.823   614   614 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 12:26:33.738   929   939 D WifiService: setWifiEnabled: true pid=5390, uid=10077
,09-16 12:26:33.738   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 12:26:33.745   509   922 D SoftapController: Softap fwReload - Ok
,09-16 12:26:33.750   509   922 D CommandListener: Setting iface cfg
,09-16 12:26:33.750   509   922 D CommandListener: Trying to bring down wlan0
,09-16 12:26:33.752   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-16 12:26:33.757   929  2956 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 12:26:34.356   929  2956 D wifi    : set interface wlan0 flags (UP)
,09-16 12:26:34.359   929  2956 I WifiHAL : Initializing wifi
09-16 12:26:34.359   929  2956 I WifiHAL : Creating socket
,09-16 12:26:34.366   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 12:26:34.366   929  2956 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 12:26:34.367   929  2956 D wifi    : Did set static halHandle = 0x7f65177560
09-16 12:26:34.367   929  2956 D wifi    : halHandle = 0x7f65177560, mVM = 0x7f8178d140, mCls = 0x1836
09-16 12:26:34.368   929  2956 D wifi    : array field set
09-16 12:26:34.368   929  2956 I WifiNative-HAL: interface[0] = wlan0
09-16 12:26:34.371   929  5526 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547156882784
,09-16 12:26:34.371   929  5526 D wifi    : waitForHalEvents called, vm = 0x7f8178d140, obj = 0x1836, env = 0x7f6515afc0
,09-16 12:26:34.447  5527  5527 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 12:26:34.468  5527  5527 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 12:26:34.472   929  2956 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 12:26:34.480  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:34.481  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 12:26:34.490  5527  5527 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 12:26:34.490  5527  5527 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 12:26:34.505   929  2956 D WifiConfigStore: Loading config and enabling all networks 
,09-16 12:26:34.505  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:34.505  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 12:26:34.505  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:34.505  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 12:26:34.506  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 12:26:34.507  5390  5390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 12:26:34.507  5390  5390 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 12:26:34.507  5390  5390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 12:26:34.519   929  2956 D WifiConfigStore: loaded 0 passpoint configs
,09-16 12:26:34.519   929  2956 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 12:26:34.520   929  2956 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 12:26:34.521   929  2956 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 12:26:34.522   929  2956 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 12:26:34.522   929  2956 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 12:26:34.523   929  2956 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 12:26:34.523   929  2956 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 12:26:34.527   929  2956 D WifiNative-HAL: Setting external_sim to 1
,09-16 12:26:34.527   929  2956 D wifi    : setting dfs flag to true, 0x7f6616e680
09-16 12:26:34.528   929  2956 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 12:26:34.528   929  2956 D wifi    : setting scan oui 0x7f6616e680
09-16 12:26:34.528   929  2956 D WifiHAL : Sending mac address OUI
,09-16 12:26:34.528  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 12:26:34.532   929  2956 E native  : do suspend false
,09-16 12:26:34.540   929  2956 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 12:26:34.540   929   929 D RttService: SCAN_AVAILABLE : 3
,09-16 12:26:34.540   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 12:26:34.540   929  3063 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 12:26:34.541   509   922 D CommandListener: Setting iface cfg
,09-16 12:26:34.545   929  2955 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-16 12:26:34.545   929  2955 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 12:26:34.554   929  2955 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 12:26:34.558   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=261428 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-16 12:26:34.558   929  2955 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 12:26:34.816   929  2956 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 14, 15 -> obsolete

```
