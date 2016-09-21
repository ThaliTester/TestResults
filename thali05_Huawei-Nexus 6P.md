#### Test 86171191c184704_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 11:20:43.891   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-21 11:20:43.891   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-21 11:20:44.415  5350  5350 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 11:20:44.421  5350  5350 D AndroidRuntime: CheckJNI is OFF
09-21 11:20:44.446  5350  5350 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 11:20:44.478  5350  5350 I Radio-JNI: register_android_hardware_Radio DONE
09-21 11:20:44.494  5350  5350 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 11:20:44.501   934  3440 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 11:20:44.549   934  3440 I ActivityManager: Start proc 5359:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 11:20:44.565  5350  5350 D AndroidRuntime: Shutting down VM
,09-21 11:20:44.883   934  3463 I WindowManager: Screenshot max retries 4 of Token{c1a61f5 ActivityRecord{ad9332c u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7acbbc4 u0 Starting com.test.thalitest} drawState=2
,09-21 11:20:44.947  5359  5359 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 11:20:44.980  5359  5359 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 11:20:45.006  5359  5359 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 272-291)
,09-21 11:20:45.006  5359  5359 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 11:20:45.025  5359  5359 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {743d49b}
09-21 11:20:45.026  5359  5359 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 11:20:45.026  5359  5359 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 11:20:45.032  5359  5359 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 11:20:45.033  5359  5359 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 11:20:45.067  5359  5359 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 11:20:45.081  5359  5359 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 11:20:45.081  5359  5359 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 11:20:45.081  5359  5359 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 11:20:45.081  5359  5359 I Adreno  : Build Date                       : 12/06/15
09-21 11:20:45.081  5359  5359 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 11:20:45.081  5359  5359 I Adreno  : Local Branch                     : mybranch17112971
09-21 11:20:45.081  5359  5359 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 11:20:45.081  5359  5359 I Adreno  : Remote Branch                    : NONE
09-21 11:20:45.081  5359  5359 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 11:20:45.141   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82803eb:true
,09-21 11:20:45.186   713   713 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13881]" dev="sockfs" ino=13881 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:20:45.186   713   713 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13881]" dev="sockfs" ino=13881 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:20:45.206  5359  5359 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 11:20:45.217  5359  5359 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 11:20:45.247  5359  5396 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 11:20:45.246   713   713 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32341]" dev="sockfs" ino=32341 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 11:20:45.246   713   713 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32341]" dev="sockfs" ino=32341 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:20:45.250  3060  3060 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28992]" dev="sockfs" ino=28992 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 11:20:45.250  3060  3060 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28992]" dev="sockfs" ino=28992 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 11:20:45.254  5359  5383 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 11:20:45.282  5359  5396 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 11:20:45.359   934   952 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +473ms (total +826ms)
,09-21 11:20:45.389  5359  5359 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5359
,09-21 11:20:45.459   934  2853 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 11:20:45.490  5359  5359 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 11:20:45.752  5359  5398 D jxcore_app_log: JniHelper::setJavaVM(0xf51fc000), pthread_self() = -581437136
,09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 11:20:45.758  5359  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6340b10 added. We now have 1 listener(s)
,09-21 11:20:45.762  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-21 11:20:45.763  5359  5398 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:20:45.764  5359  5398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:20:45.765  5359  5398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-21 11:20:45.770  5359  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bfba2f added. We now have 1 listener(s)
09-21 11:20:45.770  5359  5398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:20:45.784   934  2860 D WifiService: New client listening to asynchronous messages
,09-21 11:20:45.785  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:20:45.785  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-21 11:20:45.785  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-21 11:20:45.785  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 11:20:45.786  5359  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 11:20:45.788  5359  5398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:20:45.788  5359  5398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 11:20:45.792  5359  5398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:20:45.792  5359  5398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:20:45.792  5359  5398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 11:20:45.792  5359  5398 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:20:45.793  5359  5398 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 11:20:45.795  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:20:45.798  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:20:45.817  5359  5359 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 11:20:46.607  5359  5359 I Choreographer: Skipped 44 frames!  The application may be doing too much work on its main thread.
,09-21 11:20:46.789  5359  5405 W jxcore-log: Initializing JXcore engine
09-21 11:20:46.789  5359  5405 W jxcore-log: JXcore engine is ready
,09-21 11:20:46.813  5405  5405 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12548 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 11:20:46.813  5405  5405 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13403]" dev="sockfs" ino=13403 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 11:20:46.813  5405  5405 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 11:20:46.813  5405  5405 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32312]" dev="sockfs" ino=32312 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 11:20:46.822  5359  5405 W jxcore-log: Starting JXcore engine
,09-21 11:20:46.882  5359  5405 W jxcore-log: Platform android
09-21 11:20:46.882  5359  5405 W jxcore-log: 
09-21 11:20:46.883  5359  5405 W jxcore-log: Process ARCH arm
09-21 11:20:46.883  5359  5405 W jxcore-log: 
,09-21 11:20:46.986  5359  5405 I jxcore-log: JXcore Cordova bridge is ready!
09-21 11:20:46.986  5359  5405 I jxcore-log: 
09-21 11:20:46.986  5359  5405 W jxcore-log: JXcore engine is started
,09-21 11:20:46.998  5359  5398 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 11:20:47.003  5359  5359 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 11:20:53.892   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:20:54.524   934  5102 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-21 11:20:54.894   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:20:55.895   537   537 I ServiceManager: Waiting for service AtCmdFwd...

```
