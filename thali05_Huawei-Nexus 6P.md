#### Test 861725253aa3a32_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 10:25:02.681   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 10:25:02.681   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 10:25:03.204  5477  5477 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 10:25:03.209  5477  5477 D AndroidRuntime: CheckJNI is OFF
09-23 10:25:03.242  5477  5477 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 10:25:03.277  5477  5477 I Radio-JNI: register_android_hardware_Radio DONE
09-23 10:25:03.294  5477  5477 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 10:25:03.299   927  3481 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 10:25:03.340   927  3481 I ActivityManager: Start proc 5486:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 10:25:03.356  5477  5477 D AndroidRuntime: Shutting down VM
,09-23 10:25:03.684   927  3203 I WindowManager: Screenshot max retries 4 of Token{61facd ActivityRecord{87ec864 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{58bffc u0 Starting com.test.thalitest} drawState=2
,09-23 10:25:03.750  5486  5486 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 10:25:03.785  5486  5486 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 10:25:03.808  5486  5486 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 1026-1045)
,09-23 10:25:03.809  5486  5486 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 10:25:03.829  5486  5486 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b325f0d}
09-23 10:25:03.830  5486  5486 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 10:25:03.830  5486  5486 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 10:25:03.835  5486  5486 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 10:25:03.837  5486  5486 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 10:25:03.871  5486  5486 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 10:25:03.885  5486  5486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 10:25:03.886  5486  5486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 10:25:03.886  5486  5486 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 10:25:03.886  5486  5486 I Adreno  : Build Date                       : 12/06/15
09-23 10:25:03.886  5486  5486 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 10:25:03.886  5486  5486 I Adreno  : Local Branch                     : mybranch17112971
09-23 10:25:03.886  5486  5486 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 10:25:03.886  5486  5486 I Adreno  : Remote Branch                    : NONE
09-23 10:25:03.886  5486  5486 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 10:25:03.938   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8571294:true
,09-23 10:25:03.964   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21179]" dev="sockfs" ino=21179 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 10:25:03.964   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[21179]" dev="sockfs" ino=21179 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 10:25:03.977  5486  5486 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 10:25:03.986  5486  5486 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 10:25:04.007   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31658]" dev="sockfs" ino=31658 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 10:25:04.007   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31658]" dev="sockfs" ino=31658 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 10:25:04.010  5486  5523 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 10:25:04.010  3203  3203 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21191]" dev="sockfs" ino=21191 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 10:25:04.010  3203  3203 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[21191]" dev="sockfs" ino=21191 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 10:25:04.018  5486  5510 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 10:25:04.041  5486  5523 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 10:25:04.118   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +429ms (total +803ms)
,09-23 10:25:04.166  5486  5486 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5486
,09-23 10:25:04.271  5486  5486 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 10:25:04.421  5486  5525 D jxcore_app_log: JniHelper::setJavaVM(0xf51fc000), pthread_self() = -579602128
,09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 10:25:04.425  5486  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@519ada added. We now have 1 listener(s)
,09-23 10:25:04.428  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 10:25:04.429  5486  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 10:25:04.429  5486  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 10:25:04.429  5486  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 10:25:04.432  5486  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae0bc01 added. We now have 1 listener(s)
09-23 10:25:04.432  5486  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 10:25:04.436   927  3022 D WifiService: New client listening to asynchronous messages
,09-23 10:25:04.436  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 10:25:04.436  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 10:25:04.436  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 10:25:04.436  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-23 10:25:04.437  5486  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 10:25:04.438  5486  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:25:04.438  5486  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 10:25:04.442  5486  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:25:04.443  5486  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 10:25:04.443  5486  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-23 10:25:04.443  5486  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:25:04.443  5486  5525 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 10:25:04.446  5486  5486 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:25:04.449  5486  5486 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:25:04.476  5486  5486 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 10:25:04.777  5486  5533 W jxcore-log: Initializing JXcore engine
09-23 10:25:04.778  5486  5533 W jxcore-log: JXcore engine is ready
,09-23 10:25:04.800  5533  5533 W Thread-58: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11634 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 10:25:04.800  5533  5533 W Thread-58: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16539]" dev="sockfs" ino=16539 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 10:25:04.800  5533  5533 W Thread-58: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 10:25:04.800  5533  5533 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30407]" dev="sockfs" ino=30407 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 10:25:04.811  5486  5533 W jxcore-log: Starting JXcore engine
,09-23 10:25:04.867  5486  5533 W jxcore-log: Platform android
09-23 10:25:04.867  5486  5533 W jxcore-log: 
,09-23 10:25:04.867  5486  5533 W jxcore-log: Process ARCH arm
09-23 10:25:04.867  5486  5533 W jxcore-log: 
,09-23 10:25:04.901   927  3021 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 10:25:04.963  5486  5533 I jxcore-log: JXcore Cordova bridge is ready!
09-23 10:25:04.963  5486  5533 I jxcore-log: 
,09-23 10:25:04.963  5486  5533 W jxcore-log: JXcore engine is started
,09-23 10:25:04.973  5486  5525 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 10:25:04.979  5486  5486 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)

```
