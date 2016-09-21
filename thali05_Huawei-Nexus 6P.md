#### Test 861478347f75dc8_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 12:13:53.997   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-21 12:13:53.998   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-21 12:13:54.516  5377  5377 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 12:13:54.521  5377  5377 D AndroidRuntime: CheckJNI is OFF
09-21 12:13:54.549  5377  5377 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 12:13:54.584  5377  5377 I Radio-JNI: register_android_hardware_Radio DONE
09-21 12:13:54.601  5377  5377 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 12:13:54.607   925  3326 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 12:13:54.655   925  3326 I ActivityManager: Start proc 5386:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 12:13:54.659  5377  5377 D AndroidRuntime: Shutting down VM
,09-21 12:13:54.999   925   935 I WindowManager: Screenshot max retries 4 of Token{9202910 ActivityRecord{86989d3 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{9ee604b u0 Starting com.test.thalitest} drawState=2
,09-21 12:13:55.063  5386  5386 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 12:13:55.098  5386  5386 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 12:13:55.122  5386  5386 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9676-9695)
,09-21 12:13:55.122  5386  5386 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 12:13:55.142  5386  5386 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {253ca50}
,09-21 12:13:55.142  5386  5386 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 12:13:55.142  5386  5386 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 12:13:55.147  5386  5386 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 12:13:55.149  5386  5386 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 12:13:55.183  5386  5386 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 12:13:55.196  5386  5386 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 12:13:55.196  5386  5386 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 12:13:55.197  5386  5386 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 12:13:55.197  5386  5386 I Adreno  : Build Date                       : 12/06/15
09-21 12:13:55.197  5386  5386 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 12:13:55.197  5386  5386 I Adreno  : Local Branch                     : mybranch17112971
09-21 12:13:55.197  5386  5386 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 12:13:55.197  5386  5386 I Adreno  : Remote Branch                    : NONE
09-21 12:13:55.197  5386  5386 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 12:13:55.253   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c9296be:true
,09-21 12:13:55.281   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[29758]" dev="sockfs" ino=29758 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 12:13:55.281   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29758]" dev="sockfs" ino=29758 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 12:13:55.296  5386  5386 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 12:13:55.306  5386  5386 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 12:13:55.341   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31736]" dev="sockfs" ino=31736 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 12:13:55.341   404   404 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31736]" dev="sockfs" ino=31736 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 12:13:55.344  5386  5423 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 12:13:55.344  3326  3326 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29770]" dev="sockfs" ino=29770 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 12:13:55.344  3326  3326 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29770]" dev="sockfs" ino=29770 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 12:13:55.351  5386  5410 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 12:13:55.374  5386  5423 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 12:13:55.452   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +448ms (total +828ms)
,09-21 12:13:55.491  5386  5386 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5386
,09-21 12:13:55.572  5386  5386 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 12:13:55.696  5386  5425 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -577767120
,09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 12:13:55.700  5386  5425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc3941 added. We now have 1 listener(s)
,09-21 12:13:55.702  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-21 12:13:55.702  5386  5425 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 12:13:55.702  5386  5425 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 12:13:55.703  5386  5425 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 12:13:55.705  5386  5425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1815ed4 added. We now have 1 listener(s)
09-21 12:13:55.705  5386  5425 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 12:13:55.710   925  2916 D WifiService: New client listening to asynchronous messages
,09-21 12:13:55.711  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 12:13:55.711  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 12:13:55.711  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 12:13:55.711  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 12:13:55.711  5386  5425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 12:13:55.714  5386  5425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 12:13:55.715  5386  5425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 12:13:55.721  5386  5425 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 12:13:55.721  5386  5425 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 12:13:55.721  5386  5425 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 12:13:55.721  5386  5425 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 12:13:55.721  5386  5425 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 12:13:55.724  5386  5386 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 12:13:55.730  5386  5386 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 12:13:55.735  5386  5386 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 12:13:55.772   925  2915 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 12:13:56.003  5386  5432 W jxcore-log: Initializing JXcore engine
,09-21 12:13:56.003  5386  5432 W jxcore-log: JXcore engine is ready
,09-21 12:13:56.024  5432  5432 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12478 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 12:13:56.024  5432  5432 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13671]" dev="sockfs" ino=13671 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 12:13:56.024  5432  5432 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 12:13:56.024  5432  5432 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31714]" dev="sockfs" ino=31714 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 12:13:56.035  5386  5432 W jxcore-log: Starting JXcore engine
,09-21 12:13:56.093  5386  5432 W jxcore-log: Platform android
09-21 12:13:56.093  5386  5432 W jxcore-log: 
,09-21 12:13:56.093  5386  5432 W jxcore-log: Process ARCH arm
09-21 12:13:56.093  5386  5432 W jxcore-log: 
,09-21 12:13:56.194  5386  5432 I jxcore-log: JXcore Cordova bridge is ready!
09-21 12:13:56.194  5386  5432 I jxcore-log: 
,09-21 12:13:56.194  5386  5432 W jxcore-log: JXcore engine is started
,09-21 12:13:56.206  5386  5425 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 12:13:56.214  5386  5386 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)

```
