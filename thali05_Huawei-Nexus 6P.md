#### Test 8326889373d8814_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 10:45:03.606   931  5191 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182878, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 10:45:04.082  5448  5448 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 10:45:04.087  5448  5448 D AndroidRuntime: CheckJNI is OFF
09-23 10:45:04.115  5448  5448 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 10:45:04.149  5448  5448 I Radio-JNI: register_android_hardware_Radio DONE
09-23 10:45:04.164  5448  5448 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 10:45:04.168   931  3162 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 10:45:04.215   931  3162 I ActivityManager: Start proc 5457:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 10:45:04.234  5448  5448 D AndroidRuntime: Shutting down VM
,09-23 10:45:04.562   931  3395 I WindowManager: Screenshot max retries 4 of Token{7c3664a ActivityRecord{2eeefb5 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{afa606d u0 Starting com.test.thalitest} drawState=4
,09-23 10:45:04.644  5457  5457 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 10:45:04.682  5457  5457 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 10:45:04.750  5457  5457 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 3958-4022)
09-23 10:45:04.750  5457  5457 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 10:45:04.783  5457  5457 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f6ae522}
,09-23 10:45:04.783  5457  5457 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 10:45:04.784  5457  5457 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 10:45:04.789  5457  5457 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 10:45:04.790  5457  5457 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 10:45:04.837  5457  5457 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 10:45:04.855  5457  5457 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 10:45:04.855  5457  5457 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 10:45:04.855  5457  5457 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 10:45:04.855  5457  5457 I Adreno  : Build Date                       : 12/06/15
09-23 10:45:04.855  5457  5457 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 10:45:04.855  5457  5457 I Adreno  : Local Branch                     : mybranch17112971
09-23 10:45:04.855  5457  5457 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 10:45:04.855  5457  5457 I Adreno  : Remote Branch                    : NONE
09-23 10:45:04.855  5457  5457 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 10:45:04.901   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3e5e08:true
,09-23 10:45:04.932   761   761 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25286]" dev="sockfs" ino=25286 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:04.932   761   761 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25286]" dev="sockfs" ino=25286 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:04.945  5457  5457 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 10:45:04.954  5457  5457 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 10:45:04.976   410   410 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33082]" dev="sockfs" ino=33082 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:04.976   410   410 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33082]" dev="sockfs" ino=33082 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:04.978  5457  5494 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 10:45:04.979  3589  3589 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28012]" dev="sockfs" ino=28012 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:04.979  3589  3589 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28012]" dev="sockfs" ino=28012 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:04.984  5457  5481 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 10:45:05.005  5457  5494 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 10:45:05.071   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +506ms (total +882ms)
,09-23 10:45:05.113  5457  5457 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5457
,09-23 10:45:05.194  5457  5457 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 10:45:05.320  5457  5496 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -562300624
,09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 10:45:05.324  5457  5496 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5390748 added. We now have 1 listener(s)
,09-23 10:45:05.327  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 10:45:05.327  5457  5496 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:05.328  5457  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 10:45:05.328  5457  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 10:45:05.330  5457  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d72dc7 added. We now have 1 listener(s)
09-23 10:45:05.330  5457  5496 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 10:45:05.334   931  2982 D WifiService: New client listening to asynchronous messages
,09-23 10:45:05.335  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 10:45:05.335  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 10:45:05.335  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-23 10:45:05.335  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 10:45:05.335  5457  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 10:45:05.337  5457  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:05.337  5457  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 10:45:05.341  5457  5496 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:05.341  5457  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 10:45:05.341  5457  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 10:45:05.341  5457  5496 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:45:05.342  5457  5496 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 10:45:05.465  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:05.470  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:05.474  5457  5457 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 10:45:05.634  5457  5503 W jxcore-log: Initializing JXcore engine
,09-23 10:45:05.634  5457  5503 W jxcore-log: JXcore engine is ready
,09-23 10:45:05.656  5503  5503 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12533 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 10:45:05.656  5503  5503 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15384]" dev="sockfs" ino=15384 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 10:45:05.656  5503  5503 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-23 10:45:05.656  5503  5503 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33063]" dev="sockfs" ino=33063 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 10:45:05.665  5457  5503 W jxcore-log: Starting JXcore engine
,09-23 10:45:05.676  5457  5466 I art     : Background sticky concurrent mark sweep GC freed 81393(8MB) AllocSpace objects, 18(1604KB) LOS objects, 22% free, 25MB/32MB, paused 993us total 102.393ms
,09-23 10:45:05.724  5457  5503 W jxcore-log: Platform android
09-23 10:45:05.724  5457  5503 W jxcore-log: 
,09-23 10:45:05.724  5457  5503 W jxcore-log: Process ARCH arm
09-23 10:45:05.724  5457  5503 W jxcore-log: 
,09-23 10:45:05.822  5457  5503 I jxcore-log: JXcore Cordova bridge is ready!
09-23 10:45:05.822  5457  5503 I jxcore-log: 
,09-23 10:45:05.822  5457  5503 W jxcore-log: JXcore engine is started
,09-23 10:45:05.830  5457  5496 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 10:45:05.833  5457  5457 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 10:45:10.112   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 10:45:11.113   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 10:45:12.114   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 10:45:12.328  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 10:45:12.328  5457  5503 I jxcore-log: 
,09-23 10:45:12.330  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 10:45:12.330  5457  5503 I jxcore-log: 
,09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:12.333  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:45:12.335  5457  5503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:45:12.336  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 10:45:12.336  5457  5503 I jxcore-log: 
,09-23 10:45:12.337  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 10:45:12.337  5457  5503 I jxcore-log: 
,09-23 10:45:12.690  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 10:45:12.690  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e4cb94 added. We now have 2 listener(s)
,09-23 10:45:12.691  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 10:45:12.691  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 10:45:12.691  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:45:12.691  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 10:45:12.691  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9f63d added. We now have 2 listener(s)
,09-23 10:45:12.691  5457  5503 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 10:45:12.692  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 10:45:12.693  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:12.696  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:45:12.700  5457  5503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:45:12.701  5457  5503 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 10:45:12.701  5457  5503 D ExecuteNativeTests: Running unit tests
09-23 10:45:12.702  5457  5503 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 10:45:12.702   931  3422 D WifiService: setWifiEnabled: true pid=5457, uid=10077
09-23 10:45:12.702   931  3422 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:12.708  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:12.713  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:13.115   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 10:45:14.116   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 10:45:15.117   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 10:45:22.613   931  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 10:45:22.707  5457  5503 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 10:45:22.774  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 10:45:22.774  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93651c7 added. We now have 3 listener(s)
09-23 10:45:22.775  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:22.775  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 10:45:22.775  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:45:22.776  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 10:45:22.776  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff5a3f4 added. We now have 3 listener(s)
09-23 10:45:22.776  5457  5503 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 10:45:22.777  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:45:22.780  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:22.785  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:45:22.786  5457  5503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:45:22.786  5457  5503 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 10:45:22.790  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-23 10:45:22.791  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 10:45:22.791  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 10:45:22.791  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:22.792  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:22.793  5457  5503 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 10:45:22.793  5457  5503 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 10:45:22.793  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 10:45:22.793  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:22.793  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:22.793  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:22.793  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-23 10:45:22.794  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:22.794  5457  5503 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 10:45:22.795  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-23 10:45:22.797  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-23 10:45:22.797  5457  5503 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 10:45:22.800  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:22.801  5457  5503 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-23 10:45:22.801  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-23 10:45:22.801  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 10:45:22.801  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:22.801  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 10:45:22.801  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:22.802  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:22.802  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 10:45:22.803  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 10:45:22.803  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:22.803  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:22.803  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 10:45:22.803  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:22.803  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:45:22.803  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:22.806  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 10:45:22.806  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 10:45:22.807  5457  5505 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 10:45:22.811  5457  5505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 10:45:22.806  4711  4711 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32097]" dev="sockfs" ino=32097 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:22.806  4711  4711 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32097]" dev="sockfs" ino=32097 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:22.812  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:22.815  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 10:45:22.816  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 10:45:22.820  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 10:45:22.820  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 10:45:22.821  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-23 10:45:22.822  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:22.822  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 10:45:22.822  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 10:45:22.823  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:22.826  4487  4711 D BtGatt.GattService: registerClient() - UUID=b30e2c85-08b9-4e6d-b2c5-cd3d32a66137
,09-23 10:45:22.827  4487  4549 D BtGatt.GattService: onClientRegistered() - UUID=b30e2c85-08b9-4e6d-b2c5-cd3d32a66137, clientIf=5
09-23 10:45:22.828  5457  5468 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 10:45:22.830  4487  4552 D BtGatt.AdvertiseManager: message : 0
,09-23 10:45:22.833  4487  4552 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 10:45:22.847  4487  4549 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:22.855  4487  4549 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:22.856  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 10:45:22.857  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 10:45:22.858  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 10:45:22.859  5457  5503 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 10:45:22.859  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:22.860  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 10:45:22.860  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-23 10:45:22.860  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 10:45:22.860  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 10:45:22.860  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 10:45:22.864  5457  5457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 10:45:22.864  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:23.364  5457  5503 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 10:45:23.364  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 10:45:23.364  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-23 10:45:23.364  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 10:45:23.365  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 10:45:23.366  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 10:45:23.366  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 10:45:23.367  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 10:45:23.367  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 10:45:23.367  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 10:45:23.368  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 10:45:23.368  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 10:45:23.368  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 10:45:23.368  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 10:45:23.368  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 10:45:23.369  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 10:45:23.369  5457  5503 D io.jxcore.node.,ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 10:45:23.369  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 10:45:23.369  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 10:45:23.369  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 10:45:23.370  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 10:45:23.370  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 10:45:23.370  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:23.370  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 10:45:23.371  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:45:23.371  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 10:45:23.371  5457  5505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 10:45:23.371  5457  5505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:23.371  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:45:23.372  5457  5505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 10:45:23.372  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:45:23.372  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 10:45:23.372  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:23.372  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:23.373  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 10:45:23.376  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:23.376  5457  5503 D BluetoothLeScanner: could not find callback wrapper
09-23 10:45:23.376  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:23.377  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 10:45:23.378  4487  4552 D BtGatt.AdvertiseManager: message : 1
09-23 10:45:23.379  4487  4552 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 10:45:23.390  4487  4549 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 10:45:23.391  4487  4549 D BtGatt.GattService: Client app is not null!
,09-23 10:45:23.392  4487  4502 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 10:45:23.393  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 10:45:23.393  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:23.393  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 10:45:23.393  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-23 10:45:23.393  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 10:45:23.395  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:45:23.395  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 10:45:23.396  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:45:23.397  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 10:45:23.399  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 10:45:23.399  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:45:23.399  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:23.400  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 10:45:23.400  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:23.400  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:23.400  5457  5503 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 10:45:23.400  5457  5503 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 10:45:23.400  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-23 10:45:23.400  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-23 10:45:23.401  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:23.401  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 10:45:23.401  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:23.401  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:23.402  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 10:45:23.402  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 10:45:23.403  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:23.403  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:23.403  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 10:45:23.403  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:23.403  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:45:23.403  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:23.404  5457  5508 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:23.406  4719  4719 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32102]" dev="sockfs" ino=32102 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:23.406  4719  4719 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32102]" dev="sockfs" ino=32102 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:23.409  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 10:45:23.409  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 10:45:23.409  5457  5508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 10:45:23.413  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:23.414  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:45:23.414  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 10:45:23.417  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 10:45:23.417  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:23.417  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-23 10:45:23.417  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:23.418  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 10:45:23.418  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 10:45:23.419  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:23.422  4487  4500 D BtGatt.GattService: registerClient() - UUID=e3699b5c-dfd5-4854-b81c-d5fd75e72974
09-23 10:45:23.422  4487  4549 D BtGatt.GattService: onClientRegistered() - UUID=e3699b5c-dfd5-4854-b81c-d5fd75e72974, clientIf=5
,09-23 10:45:23.423  5457  5468 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 10:45:23.424  4487  4552 D BtGatt.AdvertiseManager: message : 0
,09-23 10:45:23.426  4487  4552 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 10:45:23.438  4487  4549 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:23.444  4487  4549 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:23.445  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 10:45:23.445  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 10:45:23.446  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 10:45:23.448  5457  5503 I io.jxcore.node.ConnectionHelper: start: OK
09-23 10:45:23.448  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 10:45:23.448  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 10:45:23.448  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 10:45:23.448  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 10:45:23.448  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 10:45:23.448  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 10:45:23.451  5457  5457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 10:45:23.451  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:23.952  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-23 10:45:23.952  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 10:45:23.953  5457  5503 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 10:45:23.953  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 10:45:23.953  5457  5503 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 10:45:23.953  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:45:23.954  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-23 10:45:23.954  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 10:45:23.955  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 10:45:23.957  4487  4552 D BtGatt.AdvertiseManager: message : 1
09-23 10:45:23.959  4487  4552 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 10:45:23.972  4487  4549 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 10:45:23.972  4487  4549 D BtGatt.GattService: Client app is not null!
09-23 10:45:23.973  4487  4719 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 10:45:23.974  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:45:23.975  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:23.975  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:23.975  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 10:45:23.975  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:23.975  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-23 10:45:23.976  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:23.976  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:23.976  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 10:45:23.978  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:23.983  4487  4719 D BtGatt.GattService: registerClient() - UUID=9713a596-c598-46cc-9483-2f831da92814
09-23 10:45:23.984  4487  4549 D BtGatt.GattService: onClientRegistered() - UUID=9713a596-c598-46cc-9483-2f831da92814, clientIf=5
,09-23 10:45:23.985  5457  5467 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 10:45:23.987  4487  4552 D BtGatt.AdvertiseManager: message : 0
,09-23 10:45:23.992  4487  4552 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 10:45:24.010  4487  4549 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:24.018  4487  4549 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:24.019  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 10:45:24.019  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-23 10:45:24.019  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:45:24.019  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 10:45:24.019  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 10:45:24.019  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:45:24.019  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 10:45:24.020  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 10:45:24.020  5457  5503 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 10:45:24.021  5457  5503 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 10:45:24.021  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 10:45:24.021  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 10:45:24.022  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 10:45:24.022  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:24.022  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 10:45:24.022  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:45:24.022  5457  5508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 10:45:24.022  5457  5508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:24.022  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 10:45:24.022  5457  5508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 10:45:24.022  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:45:24.022  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 10:45:24.022  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:24.022  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:24.022  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 10:45:24.022  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 10:45:24.024  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:24.024  5457  5503 D BluetoothLeScanner: could not find callback wrapper
09-23 10:45:24.024  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 10:45:24.024  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 10:45:24.025  4487  4552 D BtGatt.AdvertiseManager: message : 1
09-23 10:45:24.025  4487  4552 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 10:45:24.033  4487  4549 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 10:45:24.033  4487  4549 D BtGatt.GattService: Client app is not null!
,09-23 10:45:24.034  4487  4719 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 10:45:24.035  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:45:24.035  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:24.035  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 10:45:24.035  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 10:45:24.035  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 10:45:24.036  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:24.036  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 10:45:24.036  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 10:45:24.037  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 10:45:24.039  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 10:45:24.039  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 10:45:24.039  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:24.039  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:24.039  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:24.039  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:45:24.040  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-23 10:45:24.040  5457  5503 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-23 10:45:24.042  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-23 10:45:24.042  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 10:45:24.043  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-23 10:45:24.043  5457  5503 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 10:45:24.044  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-23 10:45:24.044  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-23 10:45:24.045  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-23 10:45:24.045  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:24.046  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:24.046  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:24.046  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 10:45:24.047  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-23 10:45:24.048  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 10:45:24.048  5457  5503 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 10:45:24.048  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 10:45:24.052  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 10:45:24.052  5457  5503 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 10:45:24.052  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-23 10:45:24.052  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 10:45:24.052  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 10:45:24.052  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 10:45:24.053  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 10:45:24.054  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 10:45:24.054  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-23 10:45:24.055  5457  5503 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 10:45:24.055  5457  5503 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 10:45:24.055  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 10:45:24.055  5457  5503 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 10:45:24.055  5457  5503 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 10:45:24.055  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 10:45:24.055  5457  5503 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 10:45:24.055  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-23 10:45:24.060  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-23 10:45:24.062  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-23 10:45:24.062  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-23 10:45:24.064  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 10:45:24.064  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 10:45:24.064  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-23 10:45:24.064  5457  5503 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 10:45:24.066  4719  4719 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:24.066  4719  4719 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32112]" dev="sockfs" ino=32112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:24.065  5457  5503 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 10:45:24.065  5457  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
09-23 10:45:24.065  5457  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-23 10:45:24.065  5457  5512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:24.066  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,09-23 10:45:24.066  5457  5503 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 10:45:24.068  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-23 10:45:24.068  5457  5503 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 10:45:24.069  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-23 10:45:24.069  5457  5503 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 10:45:24.069  5457  5503 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 10:45:24.069  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 10:45:24.069  5457  5503 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 10:45:24.069  5457  5503 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 10:45:24.069  5457  5503 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 10:45:24.069  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 10:45:24.069  5457  5503 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 10:45:24.069  5457  5503 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 10:45:24.070  5457  5503 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 10:45:24.070  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 10:45:24.070  5457  5503 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 10:45:24.070  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-23 10:45:24.070  5457  5503 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 10:45:24.071  5457  5503 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 10:45:24.071  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-23 10:45:24.071  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-23 10:45:24.071  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:24.071  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 10:45:24.071  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:24.072  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:24.076  4500  4500 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30070]" dev="sockfs" ino=30070 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:24.076  4500  4500 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30070]" dev="sockfs" ino=30070 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:24.073  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 10:45:24.073  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 10:45:24.073  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:24.073  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:24.074  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 10:45:24.074  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:24.074  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:45:24.074  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:24.077  5457  5513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:24.077  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:45:24.077  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 10:45:24.079  5457  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 10:45:24.080  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:24.081  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:45:24.081  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:45:24.083  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 10:45:24.083  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:24.083  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-23 10:45:24.083  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:24.084  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:24.084  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 10:45:24.084  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:24.087  4487  4711 D BtGatt.GattService: registerClient() - UUID=7b523c71-f9de-4b7e-b448-3d82851fff21
09-23 10:45:24.087  4487  4549 D BtGatt.GattService: onClientRegistered() - UUID=7b523c71-f9de-4b7e-b448-3d82851fff21, clientIf=5
,09-23 10:45:24.087  5457  5467 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 10:45:24.088  4487  4552 D BtGatt.AdvertiseManager: message : 0
,09-23 10:45:24.090  4487  4552 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 10:45:24.099  4487  4549 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:24.105  4487  4549 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:24.105  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 10:45:24.105  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 10:45:24.107  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 10:45:24.108  5457  5503 I io.jxcore.node.ConnectionHelper: start: OK
09-23 10:45:24.108  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:24.108  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 10:45:24.108  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 10:45:24.108  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 10:45:24.108  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-23 10:45:24.108  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 10:45:24.111  5457  5457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 10:45:24.111  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:24.609  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:45:24.610  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 10:45:24.610  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:24.610  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 10:45:24.611  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:45:24.611  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 10:45:24.611  5457  5513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 10:45:24.611  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 10:45:24.611  5457  5513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:24.611  5457  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 10:45:24.611  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 10:45:24.612  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 10:45:24.612  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-23 10:45:24.612  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:24.615  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93651c7 removed from the list
09-23 10:45:24.615  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:45:24.615  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 10:45:24.615  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:24.615  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:24.616  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 10:45:24.616  5457  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
09-23 10:45:24.617  5457  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
09-23 10:45:24.617  4487  4708 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-23 10:45:24.618  5457  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
,09-23 10:45:24.619  5457  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
09-23 10:45:24.620  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:24.620  5457  5503 D BluetoothLeScanner: could not find callback wrapper
09-23 10:45:24.620  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:24.621  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 10:45:24.623  4487  4552 D BtGatt.AdvertiseManager: message : 1
09-23 10:45:24.624  4487  4552 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 10:45:24.634  4487  4549 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 10:45:24.634  4487  4549 D BtGatt.GattService: Client app is not null!
09-23 10:45:24.635  4487  4500 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 10:45:24.636  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 10:45:24.636  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:24.636  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 10:45:24.636  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 10:45:24.636  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 10:45:24.637  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:24.637  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 10:45:24.637  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 10:45:24.638  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 10:45:24.640  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 10:45:24.640  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:24.641  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:24.641  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff5a3f4 removed from the list
09-23 10:45:24.641  5457  5503 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:45:24.641  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:45:24.643  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-23 10:45:24.644  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:24.644  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:24.645  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 10:45:24.646  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 10:45:24.646  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:24.646  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:24.646  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:45:24.646  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:24.647  5457  5515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:24.647  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,09-23 10:45:24.648  5457  5503 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-23 10:45:24.648  5457  5503 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 10:45:24.648  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 10:45:24.649  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 10:45:24.649  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 10:45:24.646  4500  4500 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33128]" dev="sockfs" ino=33128 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:24.651  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-23 10:45:24.649  4500  4500 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33128]" dev="sockfs" ino=33128 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:24.652  5457  5515 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 10:45:24.655  5457  5503 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
09-23 10:45:24.656  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 10:45:24.656  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 10:45:24.656  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:24.656  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 10:45:24.657  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:45:24.657  5457  5515 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 10:45:24.657  5457  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:24.657  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 10:45:24.657  5457  5515 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 10:45:24.657  5457  5503 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93651c7 not in the list
09-23 10:45:24.657  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 10:45:24.657  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 10:45:24.657  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:24.657  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:45:24.657  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:24.657  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:24.657  5457  5503 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:45:24.657  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:45:24.658  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:24.658  5457  5503 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff5a3f4 not in the list
09-23 10:45:24.658  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:24.658  5457  5503 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:45:24.659  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:24.659  5457  5503 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:45:24.659  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:45:24.659  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:24.660  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-23 10:45:24.660  5457  5503 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 10:45:24.660  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 10:45:24.660  5457  5503 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 10:45:24.660  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-23 10:45:24.660  5457  5503 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 10:45:24.660  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 10:45:24.661  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-23 10:45:24.662  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
09-23 10:45:24.663  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-23 10:45:24.663  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 10:45:24.663  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-23 10:45:24.664  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-23 10:45:24.664  5457  5503 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 10:45:24.664  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 10:45:24.664  5457  5503 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 10:45:24.664  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-23 10:45:24.664  5457  5503 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 10:45:24.665  5457  5503 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 10:45:24.665  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-23 10:45:24.666  5457  5503 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-23 10:45:24.666  5457  5503 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 10:45:24.666  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-23 10:45:24.666  5457  5503 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 10:45:24.667  5457  5503 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 10:45:24.667  5457  5503 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 10:45:24.667  5457  5503 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 10:45:24.667  5457  5503 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-23 10:45:24.668  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 10:45:24.668  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643f224 added. We now have 3 listener(s)
,09-23 10:45:24.669  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:24.669  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 10:45:24.669  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:45:24.669  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 10:45:24.669  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8d418d added. We now have 3 listener(s)
09-23 10:45:24.669  5457  5503 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 10:45:24.670  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:45:24.672  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:24.676  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 10:45:24.677  5457  5503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:45:24.678  5457  5503 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 10:45:24.679  5457  5503 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 10:45:24.680   931   942 D WifiService: setWifiEnabled: true pid=5457, uid=10077
09-23 10:45:24.680   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 10:45:24.681  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:24.682  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
09-23 10:45:24.683  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:24.685  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
09-23 10:45:24.686  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-23 10:45:24.689   931  3422 D WifiService: setWifiEnabled: false pid=5457, uid=10077
09-23 10:45:24.689   931  3422 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:24.691   931  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-23 10:45:24.691   931  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 10:45:24.691   931  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 10:45:24.691   931  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 10:45:24.700   508   924 D CommandListener: Clearing all IP addresses on wlan0
09-23 10:45:24.700   931  5192 D DhcpClient: Clearing IP address
,09-23 10:45:24.708   508   924 D CommandListener: Setting iface cfg
09-23 10:45:24.709  3658  5245 V NativeCrypto: Read error: ssl=0x7f8590b280: I/O error during system call, Connection timed out
09-23 10:45:24.714  3658  5245 V NativeCrypto: SSL shutdown failed: ssl=0x7f8590b280: I/O error during system call, Broken pipe
,09-23 10:45:24.716   931  3591 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-23 10:45:24.716   931  5193 D DhcpClient: Receive thread stopped
09-23 10:45:24.717   931  5190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-23 10:45:24.719   931  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 10:45:24.719   931  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-23 10:45:24.723   931   931 D RttService: SCAN_AVAILABLE : 1
,09-23 10:45:24.724   931  3091 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 10:45:24.725   534   534 E Parcel  : Reading a NULL string not supported here.
,09-23 10:45:24.726   931  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 10:45:24.728   931  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 10:45:24.729   931  5190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-23 10:45:24.730  3527  3694 W QCNEJ   : |CORE| network lost: 100
09-23 10:45:24.731  3527  3694 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-23 10:45:24.733   931  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 10:45:24.755   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 10:45:24.779   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 10:45:24.780   508   924 D CommandListener: Clearing all IP addresses on wlan0
,09-23 10:45:24.780   508   924 D TetherController: Setting IP forward enable = 0
,09-23 10:45:24.781   931  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 10:45:24.781   931  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 10:45:24.783   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-23 10:45:24.786   931  2981 D DhcpClient: doQuit
09-23 10:45:24.786   931  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 10:45:24.787   931  5192 D DhcpClient: onQuitting
,09-23 10:45:24.788  5081  5081 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@671fc2e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-23 10:45:24.789  3643  3643 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:24.793  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:24.795  3907  3907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 10:45:24.797  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:24.797  4875  4888 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 10:45:24.797  4875  4888 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 10:45:24.797  4875  4888 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:24.801  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:24.802  4875  4888 E SarControlService: no key has been found,reset the power
09-23 10:45:24.803  4875  4913 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 10:45:24.803  4875  4913 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 10:45:24.803  4875  4913 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 10:45:24.803  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:24.803  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 10:45:24.803  4901  4901 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:24.807  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:24.809  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:24.810  4875  4913 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 10:45:24.811  4875  4913 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 10:45:24.811  4875  4913 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 10:45:24.811  3643  3643 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 10:45:24.811  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 10:45:24.811  4901  4901 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:24.813  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:24.815  3643  3643 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-23 10:45:24.815  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:24.816  3907  3907 D SystemUpdateService: onCreate
09-23 10:45:24.817  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:24.817  4901  4915 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7829d04 HexData = [00000000ea03000000000000ffffffff]
09-23 10:45:24.817  4901  4915 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 10:45:24.818  4901  4915 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-23 10:45:24.818  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:24.818  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 10:45:24.818  4875  4885 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 10:45:24.823  3907  3907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 10:45:24.827  4901  4915 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7829d04 HexData = [00000000eb03000000000000ffffffff]
09-23 10:45:24.827  4901  4915 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 10:45:24.827  4901  4915 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-23 10:45:24.828  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 10:45:24.828  4875  4886 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 10:45:24.833  3907  3907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-23 10:45:24.838  3907  5535 I SystemUpdateService: active receiver: enabled
09-23 10:45:24.840  3907  5217 I iu.UploadsManager: num queued entries: 0
09-23 10:45:24.840  3907  5217 I iu.UploadsManager: num updated entries: 0
09-23 10:45:24.842  3907  3907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 10:45:24.843  3907  3907 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 10:45:24.846   508   924 E Netd    : netlink response contains error (No such file or directory)
09-23 10:45:24.847  3907  5535 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-23 10:45:24.847   508   924 D TetherController: Setting IP forward enable = 0
,09-23 10:45:24.848  3907  5217 I iu.SyncManager: NEXT; no task
09-23 10:45:24.848   931  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-23 10:45:24.848   931  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 10:45:24.850  3907  5535 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-23 10:45:24.850  3907  5535 I SystemUpdateService: now status is 0 (complete)
09-23 10:45:24.850  3907  5535 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 10:45:24.850  3907  5535 I SystemUpdateService: file has been verified
09-23 10:45:24.850  3907  5535 I SystemUpdateService: OTA package size = 21989297
,09-23 10:45:24.855  3643  3643 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 10:45:24.855   931  3556 I ActivityManager: Start proc 5539:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-23 10:45:24.858  3907  5535 I SystemUpdateService: showing system update notification
,09-23 10:45:24.868  3643  3643 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 10:45:24.870  3907  3907 D SystemUpdateService: onDestroy
,09-23 10:45:24.885  5539  5539 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-23 10:45:24.888  5539  5539 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 10:45:24.896  5539  5539 D SprintDMHelper: simOperator: 
09-23 10:45:24.896  5539  5539 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 10:45:24.909   931  3556 I ActivityManager: Start proc 5552:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-23 10:45:24.909   931  3556 I ActivityManager: Killing 4839:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 10:45:24.975  4306  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 10:45:24.975   931  2981 D wifi    : In wifi stop Hal
09-23 10:45:24.975   931  2981 D wifi    : halHandle = 0x7f6f3a34e0, mVM = 0x7f8b9cd140, mCls = 0x100aea
09-23 10:45:24.975   931  3642 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-23 10:45:24.975   931  3642 D WifiHAL : Got a signal to exit!!!
09-23 10:45:24.975   931  3642 I WifiHAL : Exit wifi_event_loop
09-23 10:45:24.976   931  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 10:45:24.976   931  2981 E WifiHAL : Event processing terminated
09-23 10:45:24.976   931  2981 D wifi    : In wifi cleaned up handler
09-23 10:45:24.976   931  2981 I WifiHAL : Internal cleanup completed
,09-23 10:45:24.979  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:24.981  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:24.981  3490  4054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 10:45:24.983  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:24.997   931  3642 D wifi    : set interface wlan0 flags (DOWN)
09-23 10:45:24.998   931  2981 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 10:45:25.000  4306  5566 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 10:45:25.003   931  3421 I ActivityManager: Killing 5266:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-23 10:45:25.042   931  3421 I ActivityManager: Start proc 5567:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 10:45:25.070  5567  5567 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 10:45:25.078   931   941 I ActivityManager: Killing 5081:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-23 10:45:25.159  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 10:45:25.192  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:25.193   931  3162 D WifiService: setWifiEnabled: true pid=5457, uid=10077
,09-23 10:45:25.194   931  3162 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:25.200   931   948 D Tethering: InitialState.processMessage what=4
,09-23 10:45:25.202   508   924 D SoftapController: Softap fwReload - Ok
,09-23 10:45:25.207   508   924 D CommandListener: Setting iface cfg
09-23 10:45:25.208   508   924 D CommandListener: Trying to bring down wlan0
09-23 10:45:25.208   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 10:45:25.209   508   924 D CommandListener: Clearing all IP addresses on wlan0
,09-23 10:45:25.213   931  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 10:45:25.697   931   941 D WifiService: setWifiEnabled: true pid=5457, uid=10077
,09-23 10:45:25.699   931   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:25.831   931  2981 D wifi    : set interface wlan0 flags (UP)
,09-23 10:45:25.832   931  2981 I WifiHAL : Initializing wifi
,09-23 10:45:25.832   931  2981 I WifiHAL : Creating socket
,09-23 10:45:25.839   931  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 10:45:25.840   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-23 10:45:25.840   931  2981 D wifi    : Did set static halHandle = 0x7f6f3a34e0
,09-23 10:45:25.840   931  2981 D wifi    : halHandle = 0x7f6f3a34e0, mVM = 0x7f8b9cd140, mCls = 0x20199e
09-23 10:45:25.840   931  2981 D wifi    : array field set
,09-23 10:45:25.841   931  2981 I WifiNative-HAL: interface[0] = wlan0
09-23 10:45:25.843   931  5582 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547326932192
09-23 10:45:25.843   931  5582 D wifi    : waitForHalEvents called, vm = 0x7f8b9cd140, obj = 0x20199e, env = 0x7f6f39f380
,09-23 10:45:25.928  5583  5583 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 10:45:25.945   931  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 10:45:25.950  5583  5583 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 10:45:25.958  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:25.959  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:25.960  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:25.981  5583  5583 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-23 10:45:25.981  5583  5583 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 10:45:25.996   931  2981 D WifiConfigStore: Loading config and enabling all networks 
,09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.001  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:26.004  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:26.006   931  2981 D WifiConfigStore: loaded 0 passpoint configs
09-23 10:45:26.007   931  2981 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 10:45:26.007   931  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 10:45:26.008   931  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.008  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:26.009   931  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 10:45:26.009   931  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 10:45:26.009   931  2981 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 10:45:26.009   931  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 10:45:26.010  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:26.013  4306  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 10:45:26.013   931  2981 D WifiNative-HAL: Setting external_sim to 1
09-23 10:45:26.014   931  2981 D wifi    : setting dfs flag to true, 0x7f6f3b8e80
,09-23 10:45:26.014   931  2981 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 10:45:26.014   931  2981 D wifi    : setting scan oui 0x7f6f3b8e80
09-23 10:45:26.014   931  2981 D WifiHAL : Sending mac address OUI
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.015  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:26.018  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:26.019   931  2981 E native  : do suspend false
,09-23 10:45:26.026   931  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 10:45:26.026   931   931 D RttService: SCAN_AVAILABLE : 3
09-23 10:45:26.026   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 10:45:26.027   931  3091 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 10:45:26.027   508   924 D CommandListener: Setting iface cfg
,09-23 10:45:26.031   931  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 10:45:26.031   931  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 10:45:26.041   931  2980 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 10:45:26.045   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205318 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
09-23 10:45:26.046   931  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 10:45:26.203  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.219  4487  4545 D BluetoothAdapterState: Current state: ON, message: 23
09-23 10:45:26.219  4487  4545 D BluetoothAdapterProperties: Setting state to 13
09-23 10:45:26.219  4487  4545 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 10:45:26.222  4487  4545 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 10:45:26.223  4487  4545 I BluetoothAdapterState: Entering PendingCommandState
09-23 10:45:26.225  4487  4487 D BluetoothMapService: onReceive
,09-23 10:45:26.225  4487  4487 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-23 10:45:26.226  4487  4487 D BluetoothMapService: STATE_TURNING_OFF
09-23 10:45:26.226  4487  4487 D BluetoothMapService: MAP Service closeService in
09-23 10:45:26.226  4487  4487 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 10:45:26.226  4487  4487 D ObexServerSockets0: shutdown(block = true)
09-23 10:45:26.228  4487  4487 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 10:45:26.228  4487  4487 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 10:45:26.229  4487  4721 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 10:45:26.229  4487  4720 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-23 10:45:26.230  4487  4708 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 10:45:26.234  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.235  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:26.238  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:26.238  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:26.241  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.241  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:26.242  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 10:45:26.242  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:26.244  4487  4487 I BtOppRfcommListener: stopping Accept Thread
09-23 10:45:26.244  4487  5147 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 10:45:26.245  4487  5147 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 10:45:26.245  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:26.245  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:26.246  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 10:45:26.246  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:26.250   931   944 I ActivityManager: Start proc 5587:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-23 10:45:26.251  4487  4549 D BluetoothAdapterProperties: Scan Mode:20
09-23 10:45:26.252  4487  4545 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 10:45:26.255  4487  4487 D HeadsetService: Received stop request...Stopping profile...
09-23 10:45:26.255  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:26.258   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 10:45:26.258  3558  3868 D BluetoothHeadset: Proxy object disconnected
09-23 10:45:26.259   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 10:45:26.259   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 10:45:26.260  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:26.261  3123  3137 D BluetoothHeadset: Proxy object disconnected
09-23 10:45:26.261  3123  3123 D HeadsetProfile: Bluetooth service disconnected
09-23 10:45:26.263  4487  4487 D A2dpService: Received stop request...Stopping profile...
,09-23 10:45:26.264  4487  4713 D A2dpStateMachine: Exit Disconnected: -1
09-23 10:45:26.265   931   931 D BluetoothA2dp: Proxy object disconnected
09-23 10:45:26.265  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.265  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.265  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.265  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.265  3123  3123 D BluetoothA2dp: Proxy object disconnected
,09-23 10:45:26.266  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:26.266  4487  4487 D HidService: Received stop request...Stopping profile...
09-23 10:45:26.266  4487  4487 D HidService: Stopping Bluetooth HidService
09-23 10:45:26.267  3123  3123 D BluetoothInputDevice: Proxy object disconnected
09-23 10:45:26.267  3123  3123 D HidProfile: Bluetooth service disconnected
,09-23 10:45:26.268  4487  4487 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-23 10:45:26.268  4487  4487 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-23 10:45:26.269  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:26.269  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:26.269  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 10:45:26.269  4487  4487 D HealthService: Received stop request...Stopping profile...
09-23 10:45:26.269  4487  4549 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 10:45:26.270  4487  4549 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 10:45:26.271  4487  4487 D PanService: Received stop request...Stopping profile...
09-23 10:45:26.273  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 10:45:26.274  3123  3123 D PanProfile: Bluetooth service disconnected
09-23 10:45:26.281  4487  4487 D BluetoothMapService: Received stop request...Stopping profile...
09-23 10:45:26.281  4487  4487 D BluetoothMapService: stop()
09-23 10:45:26.281  4487  4487 D BluetoothMapAppObserver: deinitObservers()
09-23 10:45:26.281  4487  4487 D BluetoothMapAppObserver: removeReceiver()
09-23 10:45:26.282  3123  3123 D BluetoothMap: Proxy object disconnected
,09-23 10:45:26.282  3123  3123 D MapProfile: Bluetooth service disconnected
09-23 10:45:26.282  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.282  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.282  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.282  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.283  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:26.283  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:26.284  4487  4549 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 10:45:26.284  4487  4487 D SapService: Received stop request...Stopping profile...
09-23 10:45:26.284  4487  4487 V SapService: stop()
09-23 10:45:26.285  4487  4694 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 10:45:26.285  4487  4694 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-23 10:45:26.285  4487  4694 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 10:45:26.285  4487  4694 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-23 10:45:26.287  4487  4487 V BluetoothAdapterState: isTurningOff()=true
,09-23 10:45:26.287  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.287  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.287  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.288  4487  4487 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 10:45:26.288  4487  4487 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 10:45:26.288  4487  4549 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 10:45:26.288  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.288  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.288  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.288  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.288  4487  4487 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 10:45:26.288  4487  4549 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 10:45:26.291  4487  4487 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-23 10:45:26.291  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.291  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.291  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.291  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.292  4487  4487 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 10:45:26.292  4487  4487 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-23 10:45:26.293  4487  4487 D BluetoothMapService: MAP Service closeService in
,09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:26.293  4487  4487 D BluetoothMapService: cleanup()
09-23 10:45:26.293  4487  4487 D BluetoothMapService: MAP Service closeService in
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.293  4487  4487 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:26.294  4487  4545 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 10:45:26.294  4487  4545 D BluetoothAdapterProperties: Setting state to 15
09-23 10:45:26.294  4487  4545 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 10:45:26.294  4487  4545 I BluetoothAdapterState: Entering BleOnState
09-23 10:45:26.294   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:26.295  3123  3143 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-23 10:45:26.298  3123  3782 D BluetoothPan: onBluetoothStateChange on: false
09-23 10:45:26.298   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:26.299  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 10:45:26.299   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:26.299  3123  3143 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:26.300   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 10:45:26.300  3558  3578 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:26.300  3123  3782 D BluetoothMap: onBluetoothStateChange: up=false
09-23 10:45:26.301  3123  3137 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 10:45:26.302  5587  5587 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-23 10:45:26.302  4487  4545 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 10:45:26.302  4487  4545 D BluetoothAdapterProperties: Setting state to 16
09-23 10:45:26.302  4487  4545 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 10:45:26.303  4487  4545 D BluetoothAdapterProperties: onBleDisable
09-23 10:45:26.303  4487  4545 I BluetoothAdapterState: Entering PendingCommandState
09-23 10:45:26.303  4487  4546 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 10:45:26.305  4487  4694 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 10:45:26.305  4487  4694 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:26.306  4487  4549 D BluetoothAdapterProperties: Scan Mode:20
09-23 10:45:26.307  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:26.308  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.309  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.311  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.315  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.317  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.322  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 10:45:26.326   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a2c4dc:true
,09-23 10:45:26.328  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 10:45:26.341   931  3422 I ActivityManager: Start proc 5599:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 10:45:26.353  5587  5587 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 10:45:26.356  5587  5587 D BluetoothMap: Create BluetoothMap proxy object
,09-23 10:45:26.369  5587  5587 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 10:45:26.377  5599  5599 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 10:45:26.388  5587  5587 D DockEventReceiver: finishStartingService: stopping service
,09-23 10:45:26.390   931  3591 I ActivityManager: Killing 4559:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 10:45:26.512  4487  4549 I bt_hci  : shut_down
,09-23 10:45:26.514  4487  4555 D bt_hwcfg: hw_epilog_process
,09-23 10:45:26.515  4487  4555 I bt_vendor: low_power_mode_cb
,09-23 10:45:26.517  4487  4555 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 10:45:26.517  4487  4555 I bt_vendor: epilog_cb
09-23 10:45:26.517  4487  4555 I bt_hci  : epilog_finished_callback
,09-23 10:45:26.519  4487  4549 I bt_hci_h4: hal_close
09-23 10:45:26.520  4487  4549 I bt_userial_vendor: device fd = 54 close
,09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.586  5599  5599 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.586  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.587  5599  5599 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:26.587  5599  5599 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:26.594  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 10:45:26.599  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 10:45:26.603  5587  5587 D DockEventReceiver: finishStartingService: stopping service
09-23 10:45:26.609   931  3605 I ActivityManager: Killing 5321:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-23 10:45:26.637  4487  4546 D bt_stack_manager: event_shut_down_stack finished.
09-23 10:45:26.638  4487  4545 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 10:45:26.639  4487  4545 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 10:45:26.639  4487  4487 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 10:45:26.640  4487  4487 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 10:45:26.640  4487  4487 D BtGatt.GattService: stop()
09-23 10:45:26.640  4487  4487 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 10:45:26.641  4487  4487 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:26.641  4487  4487 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.641  4487  4487 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:26.641  4487  4487 V BluetoothAdapterState: isBleTurningOff()=true
09-23 10:45:26.642  4487  4545 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 10:45:26.642  4487  4545 D BluetoothAdapterProperties: Setting state to 10
09-23 10:45:26.642  4487  4545 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 10:45:26.642  4487  4545 I BluetoothAdapterState: Entering OffState
09-23 10:45:26.643   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 10:45:26.649  4487  4487 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 10:45:26.649  4487  4487 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 10:45:26.649  4487  4487 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 10:45:26.651  4487  4546 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-23 10:45:26.657  4487  4487 I art     : System.exit called, status: 0
09-23 10:45:26.657  4487  4487 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 10:45:26.705   931  3162 I ActivityManager: Process com.android.bluetooth (pid 4487) has died
,09-23 10:45:26.715  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:26.728   931   948 I ActivityManager: Start proc 5631:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 10:45:26.783  5631  5631 D AdapterServiceConfig: Adding HeadsetService
,09-23 10:45:26.783  5631  5631 D AdapterServiceConfig: Adding A2dpService
09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding HidService
09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding HealthService
,09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding PanService
09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding GattService
09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding BluetoothMapService
09-23 10:45:26.784  5631  5631 D AdapterServiceConfig: Adding SapService
,09-23 10:45:26.791   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88adb0d:true
,09-23 10:45:26.791  5631  5631 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 10:45:26.793  5631  5631 I bt_bluedroid: init
,09-23 10:45:26.793  5631  5643 I BluetoothAdapterState: Entering OffState
,09-23 10:45:26.795  5631  5644 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 10:45:26.795  5631  5644 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-23 10:45:26.795  5631  5644 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 10:45:26.795  5631  5644 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 10:45:26.796  5631  5631 I bt_bluedroid: get_profile_interface socket
,09-23 10:45:26.796  5631  5631 I bt_bluedroid: get_profile_interface sdp
09-23 10:45:26.797  5631  5647 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 10:45:26.798  5631  5647 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 10:45:26.799  5631  5642 I bt_bluedroid: config_hci_snoop_log
,09-23 10:45:26.800   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-23 10:45:26.803  5631  5643 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 10:45:26.804  5631  5643 D BluetoothAdapterProperties: Setting state to 14
09-23 10:45:26.804  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 10:45:26.805  5631  5643 D BluetoothBondStateMachine: make
,09-23 10:45:26.806  5631  5648 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 10:45:26.808  5631  5643 I BluetoothAdapterState: Entering PendingCommandState
,09-23 10:45:26.809  5631  5631 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 10:45:26.810  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:26.810  5631  5631 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 10:45:26.811  5631  5631 D BtGatt.GattService: Received start request. Starting profile...
,09-23 10:45:26.811  5631  5631 D BtGatt.GattService: start()
09-23 10:45:26.811  5631  5631 I bt_bluedroid: get_profile_interface gatt
09-23 10:45:26.811  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:26.811  5631  5631 D BtGatt.AdvertiseManager: advertise manager created
,09-23 10:45:26.814  5631  5631 V BluetoothAdapterState: isTurningOff()=false
,09-23 10:45:26.814  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:26.814  5631  5631 V BluetoothAdapterState: isBleTurningOn()=true
09-23 10:45:26.814  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:26.815  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-23 10:45:26.815  5631  5643 I bt_bluedroid: bt_bluedroid
09-23 10:45:26.816  5631  5644 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 10:45:26.816  5631  5644 I bt_hci  : start_up
,09-23 10:45:26.820  5631  5644 I bt_vendor: alloc value 0xf420b871
,09-23 10:45:26.820  5631  5644 I bt_vendor: init
09-23 10:45:26.820  5631  5644 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 10:45:26.820  5631  5644 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 10:45:26.843  5599  5619 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 10:45:26.851   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eef901a:true
,09-23 10:45:26.929  5631  5644 D bt_hci  : start_up starting async portion
,09-23 10:45:26.929  5631  5651 I bt_hci  : event_finish_startup
09-23 10:45:26.929  5631  5651 I bt_hci_h4: hal_open
09-23 10:45:26.929  5631  5651 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 10:45:26.930  5631  5651 I bt_userial_vendor: device fd = 54 open
09-23 10:45:26.926  5654  5654 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 10:45:26.942  5631  5651 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 10:45:26.943  5631  5651 D bt_hwcfg: Chipset BCM4358A3
,09-23 10:45:26.944  5631  5651 D bt_hwcfg: Target name = [BCM4358A3]
09-23 10:45:26.944  5631  5651 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 10:45:27.223  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 10:45:27.337  5631  5651 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 10:45:27.338  5631  5651 D bt_hwcfg: Settlement delay -- 100 ms
,09-23 10:45:27.338  5631  5651 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 10:45:27.461  5631  5651 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 10:45:27.461  5631  5651 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 10:45:27.463  5631  5651 I bt_hwcfg: vendor lib fwcfg completed
,09-23 10:45:27.463  5631  5651 I bt_vendor: firmware callback
09-23 10:45:27.463  5631  5651 I bt_hci  : firmware_config_callback
,09-23 10:45:27.472  5631  5656 I bt_btu  : btu_task pending for preload complete event
,09-23 10:45:27.472  5631  5656 I bt_btu_task: Bluetooth chip preload is complete
09-23 10:45:27.472  5631  5656 I bt_btu  : btu_task received preload complete event
,09-23 10:45:27.478  5631  5656 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 10:45:27.478  5631  5656 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 10:45:27.478  5631  5656 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 10:45:27.478  5631  5656 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-23 10:45:27.478  5631  5656 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_GAP
,09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_GATT
,09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 10:45:27.479  5631  5656 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-23 10:45:27.480  5631  5656 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 10:45:27.564  5631  5656 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4189549
09-23 10:45:27.565  5631  5656 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4189549 
,09-23 10:45:27.582  5631  5647 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 10:45:27.584  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 10:45:27.586  5631  5647 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 10:45:27.588  5631  5647 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 10:45:27.591  5631  5647 D BluetoothAdapterProperties: Scan Mode:20
,09-23 10:45:27.591  5631  5647 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 10:45:27.592  5631  5647 D bt_hci  : do_postload posting postload work item
09-23 10:45:27.592  5631  5651 I bt_hci  : event_postload
09-23 10:45:27.592  5631  5651 I bt_vendor: sco_config_cb
,09-23 10:45:27.592  5631  5651 I bt_hci  : sco_config_callback postload finished.
09-23 10:45:27.597  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.600  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.600  5631  5651 I bt_vendor: low_power_mode_cb
09-23 10:45:27.603  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.604  5631  5647 D bt_bte_conf: Device ID record 1 : primary
09-23 10:45:27.604  5631  5647 D bt_bte_conf:   vendorId            = 000f
09-23 10:45:27.605  5631  5647 D bt_bte_conf:   vendorIdSource      = 0001
09-23 10:45:27.605  5631  5647 D bt_bte_conf:   product             = 1200
09-23 10:45:27.605  5631  5647 D bt_bte_conf:   version             = 1436
,09-23 10:45:27.605  5631  5647 D bt_bte_conf:   clientExecutableURL = 
09-23 10:45:27.605  5631  5647 D bt_bte_conf:   serviceDescription  = 
09-23 10:45:27.605  5631  5647 D bt_bte_conf:   documentationURL    = 
09-23 10:45:27.605  5631  5647 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 10:45:27.605  5631  5644 D bt_stack_manager: event_start_up_stack finished
09-23 10:45:27.606  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 10:45:27.606  5631  5643 D BluetoothAdapterProperties: Setting state to 15
09-23 10:45:27.606  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 10:45:27.607  5631  5643 I BluetoothAdapterState: Entering BleOnState
,09-23 10:45:27.609  5631  5643 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-23 10:45:27.609  5631  5643 D BluetoothAdapterProperties: Setting state to 11
09-23 10:45:27.609  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 10:45:27.615  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.617  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.619  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:27.619  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.619  5631  5631 D HeadsetService: Received start request. Starting profile...
,09-23 10:45:27.621  5631  5631 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-23 10:45:27.622  5631  5631 D HeadsetStateMachine: make
,09-23 10:45:27.630  5631  5643 I BluetoothAdapterState: Entering PendingCommandState
,09-23 10:45:27.631  5631  5631 D HeadsetStateMachine: max_hf_connections = 1
09-23 10:45:27.632  5631  5631 I bt_bluedroid: get_profile_interface handsfree
09-23 10:45:27.632  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 10:45:27.632  5631  5647 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-23 10:45:27.635  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:27.635  5631  5631 D A2dpService: Received start request. Starting profile...
09-23 10:45:27.636  5631  5631 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 10:45:27.636  5631  5631 I bt_bluedroid: get_profile_interface avrcp
,09-23 10:45:27.641  5631  5631 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 10:45:27.641  5631  5631 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 10:45:27.641  5631  5631 D A2dpStateMachine: make
09-23 10:45:27.642  5631  5631 I bt_bluedroid: get_profile_interface a2dp
09-23 10:45:27.643  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 10:45:27.645  5631  5664 D A2dpStateMachine: Enter Disconnected: -2
,09-23 10:45:27.645  5631  5631 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 10:45:27.646  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:27.647  5587  5587 D BluetoothInputDevice: Proxy object connected
,09-23 10:45:27.648  5631  5631 D HidService: Received start request. Starting profile...
,09-23 10:45:27.648  5631  5631 I bt_bluedroid: get_profile_interface hidhost
09-23 10:45:27.648  5631  5631 D HidService: setHidService(): set to: null
09-23 10:45:27.648  5631  5647 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf416a56d
09-23 10:45:27.648  5587  5587 D HidProfile: Bluetooth service connected
09-23 10:45:27.648  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 10:45:27.649  5631  5631 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 10:45:27.649  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:27.650  5631  5631 D HealthService: Received start request. Starting profile...
,09-23 10:45:27.651  5631  5631 I bt_bluedroid: get_profile_interface health
,09-23 10:45:27.652  5631  5631 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 10:45:27.653  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:27.654  5587  5587 D BluetoothPan: BluetoothPAN Proxy object connected
,09-23 10:45:27.655  5587  5587 D PanProfile: Bluetooth service connected
09-23 10:45:27.655  5631  5631 D PanService: Received start request. Starting profile...
,09-23 10:45:27.656  5631  5631 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 10:45:27.656  5631  5631 I bt_bluedroid: get_profile_interface pan
09-23 10:45:27.656  5631  5647 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 10:45:27.659  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:27.660  5631  5631 D BluetoothMapService: Received start request. Starting profile...
09-23 10:45:27.660  5631  5631 D BluetoothMapService: start()
09-23 10:45:27.660  5587  5587 D BluetoothMap: Proxy object connected
09-23 10:45:27.661  5587  5587 D MapProfile: Bluetooth service connected
09-23 10:45:27.661  5587  5587 D BluetoothMap: getConnectedDevices()
09-23 10:45:27.662  5587  5587 D BluetoothMap: Bluetooth is Not enabled
,09-23 10:45:27.663  5631  5631 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 10:45:27.664  5631  5631 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 10:45:27.664  5631  5631 D BluetoothMapAppObserver: createReceiver()
,09-23 10:45:27.665  5631  5631 D BluetoothMapAppObserver: initObservers()
09-23 10:45:27.666  5631  5631 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 10:45:27.671  5631  5631 V SapService: SapBinder()
,09-23 10:45:27.671  5631  5631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:27.672  5631  5631 D SapService: Received start request. Starting profile...
09-23 10:45:27.672  5631  5631 V SapService: start()
,09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.674  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.675  5631  5662 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.675  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.676  5631  5631 V BluetoothAdapterState: isTurningOff()=false
,09-23 10:45:27.676  5631  5631 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:27.676  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.676  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.676  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 10:45:27.676  5631  5643 D BluetoothAdapterProperties: ScanMode =  20
09-23 10:45:27.676  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 10:45:27.676  5631  5643 D BluetoothAdapterProperties: State =  11
,09-23 10:45:27.681  5631  5647 D BluetoothAdapterProperties: Scan Mode:21
,09-23 10:45:27.681  5631  5643 D BluetoothAdapterProperties: Setting state to 12
,09-23 10:45:27.681  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 10:45:27.681  5631  5643 I BluetoothAdapterState: Entering OnState
09-23 10:45:27.681   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:27.681  5631  5647 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 10:45:27.682  5587  5597 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 10:45:27.682  3123  3143 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 10:45:27.683  5457  5457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 10:45:27.686  5457  5457 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 10:45:27.686  3123  3123 D BluetoothInputDevice: Proxy object connected
09-23 10:45:27.686  3123  3782 D BluetoothPan: onBluetoothStateChange on: true
09-23 10:45:27.686  3123  3123 D HidProfile: Bluetooth service connected
,09-23 10:45:27.690  5631  5631 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 10:45:27.690  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 10:45:27.690  3123  3123 D PanProfile: Bluetooth service connected
09-23 10:45:27.691   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:27.691  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:27.691  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 10:45:27.691  5631  5631 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-23 10:45:27.692  5631  5631 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 10:45:27.693   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:27.693  5587  5598 D BluetoothPan: onBluetoothStateChange on: true
,09-23 10:45:27.693  3123  3143 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 10:45:27.693  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:27.694  5631  5631 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:27.694   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 10:45:27.695  5587  5597 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 10:45:27.696  5631  5631 D ObexServerSockets: Succeed to create listening sockets 
09-23 10:45:27.697  5631  5631 D ObexServerSockets0: startAccept()
09-23 10:45:27.697  5631  5631 D ObexServerSockets0: prepareForNewConnect()
09-23 10:45:27.697  5587  5598 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:27.698  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:27.698  3558  3578 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:27.698  5631  5631 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 10:45:27.699  5631  5631 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 10:45:27.699  3123  3782 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 10:45:27.700   931   931 D BluetoothA2dp: Proxy object connected
09-23 10:45:27.700  3123  3123 D BluetoothA2dp: Proxy object connected
09-23 10:45:27.700  3123  3137 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 10:45:27.702  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:27.705  5631  5631 D BluetoothMapService: onReceive
09-23 10:45:27.705  5631  5631 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 10:45:27.705  5631  5631 D BluetoothMapService: STATE_ON
09-23 10:45:27.706  3123  3123 D BluetoothMap: Proxy object connected
09-23 10:45:27.706  3123  3123 D MapProfile: Bluetooth service connected
09-23 10:45:27.706  3123  3123 D BluetoothMap: getConnectedDevices()
09-23 10:45:27.706  5631  5670 D ObexServerSockets0: Accepting socket connection...
09-23 10:45:27.707   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 10:45:27.708  5631  5672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:27.709  5631  5669 D ObexServerSockets0: Accepting socket connection...
09-23 10:45:27.710  5631  5672 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 10:45:27.710  5631  5672 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:27.711  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:27.712  5587  5587 D LocalBluetoothProfileManager: Adding local A2DP profile
09-23 10:45:27.714  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:27.715  5587  5587 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-23 10:45:27.716  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.717  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.719  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.721  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 10:45:27.723  5587  5587 D BluetoothA2dp: Proxy object connected
09-23 10:45:27.725  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.725  5631  5631 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 10:45:27.725  5631  5631 D ObexServerSockets0: prepareForNewConnect()
09-23 10:45:27.725  5457  5503 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:45:27.726  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:45:27.728  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 10:45:27.729  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-23 10:45:27.729  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-23 10:45:27.731  5587  5587 D DockEventReceiver: finishStartingService: stopping service
09-23 10:45:27.733  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.733  5631  5643 D BluetoothAdapterState: Current state: ON, message: 23
09-23 10:45:27.733  5631  5643 D BluetoothAdapterProperties: Setting state to 13
09-23 10:45:27.733  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 10:45:27.734  5631  5643 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 10:45:27.734  5631  5643 I BluetoothAdapterState: Entering PendingCommandState
09-23 10:45:27.735  5631  5647 D BluetoothAdapterProperties: Scan Mode:20
09-23 10:45:27.735  5587  5587 D BluetoothPbap: Proxy object connected
09-23 10:45:27.735  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-23 10:45:27.736  5587  5587 D PbapServerProfile: Bluetooth service connected
09-23 10:45:27.737  5631  5631 D BluetoothMapService: onReceive
09-23 10:45:27.737  5631  5631 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 10:45:27.738  5631  5631 D BluetoothMapService: STATE_TURNING_OFF
09-23 10:45:27.738  5631  5631 D BluetoothMapService: MAP Service closeService in
09-23 10:45:27.738  5631  5631 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 10:45:27.738  5631  5631 D ObexServerSockets0: shutdown(block = true)
09-23 10:45:27.738  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:27.738  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:27.739  5631  5631 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 10:45:27.739  5631  5669 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 10:45:27.739  3123  3123 D BluetoothPbap: Proxy object connected
09-23 10:45:27.739  5631  5631 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 10:45:27.739  3123  3123 D PbapServerProfile: Bluetooth service connected
09-23 10:45:27.739  5631  5670 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 10:45:27.739  5631  5658 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 10:45:27.739  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:27.739  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:27.742  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:27.742  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:27.742  5457  5457 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:27.742  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:27.744  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.745  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.749  5631  5631 D HeadsetService: Received stop request...Stopping profile...
09-23 10:45:27.752  5631  5631 D A2dpService: Received stop request...Stopping profile...
09-23 10:45:27.752  5631  5664 D A2dpStateMachine: Exit Disconnected: -1
09-23 10:45:27.753   931   931 D BluetoothA2dp: Proxy object disconnected
09-23 10:45:27.762  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 10:45:27.765  5587  5587 D BluetoothA2dp: Proxy object disconnected
09-23 10:45:27.767  3123  3123 D BluetoothA2dp: Proxy object disconnected
,09-23 10:45:27.768  5631  5631 D HidService: Received stop request...Stopping profile...
09-23 10:45:27.768  5631  5631 D HidService: Stopping Bluetooth HidService
09-23 10:45:27.769  3123  3123 D BluetoothInputDevice: Proxy object disconnected
,09-23 10:45:27.769  3123  3123 D HidProfile: Bluetooth service disconnected
09-23 10:45:27.769  5631  5631 D HealthService: Received stop request...Stopping profile...
,09-23 10:45:27.771  5587  5587 D DockEventReceiver: finishStartingService: stopping service
,09-23 10:45:27.772  5587  5587 D BluetoothInputDevice: Proxy object disconnected
,09-23 10:45:27.772  5587  5587 D HidProfile: Bluetooth service disconnected
09-23 10:45:27.772  5631  5631 D PanService: Received stop request...Stopping profile...
09-23 10:45:27.773  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 10:45:27.773  5587  5587 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 10:45:27.773  3123  3123 D PanProfile: Bluetooth service disconnected
09-23 10:45:27.773  5587  5587 D PanProfile: Bluetooth service disconnected
09-23 10:45:27.774  5631  5631 D BluetoothMapService: Received stop request...Stopping profile...
09-23 10:45:27.774  5631  5631 D BluetoothMapService: stop()
,09-23 10:45:27.774  5631  5631 D BluetoothMapAppObserver: deinitObservers()
09-23 10:45:27.774  5631  5631 D BluetoothMapAppObserver: removeReceiver()
09-23 10:45:27.776  5587  5587 D BluetoothMap: Proxy object disconnected
09-23 10:45:27.776  5587  5587 D MapProfile: Bluetooth service disconnected
09-23 10:45:27.776  3123  3123 D BluetoothMap: Proxy object disconnected
09-23 10:45:27.776  3123  3123 D MapProfile: Bluetooth service disconnected
09-23 10:45:27.776  5631  5631 D SapService: Received stop request...Stopping profile...
09-23 10:45:27.776  5631  5631 V SapService: stop()
09-23 10:45:27.777  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.777  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.777  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.777  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.779  5631  5631 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 10:45:27.779  5631  5631 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 10:45:27.779  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.780  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.780  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.780  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.780  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.780  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.780  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:27.782  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 10:45:27.782  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-23 10:45:27.782  5631  5647 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-23 10:45:27.782  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.782  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.782  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.782  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.782  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.782  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.782  5631  5656 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 10:45:27.782  5631  5656 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 10:45:27.782  5631  5656 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 10:45:27.782  5631  5631 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 10:45:27.783  5631  5631 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 10:45:27.783  5631  5656 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 10:45:27.783  5631  5647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 10:45:27.783  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.783  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.783  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.783  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.783  5631  5631 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 10:45:27.784  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 10:45:27.784  5631  5647 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 10:45:27.784  5631  5631 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-23 10:45:27.785  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.785  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.785  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.785  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.785  5631  5631 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 10:45:27.785  5631  5631 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 10:45:27.786  5631  5631 D BluetoothMapService: MAP Service closeService in
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:27.786  5631  5631 D BluetoothMapService: cleanup()
09-23 10:45:27.786  5631  5631 D BluetoothMapService: MAP Service closeService in
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isTurningOff()=true
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:27.786  5631  5631 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:27.787  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 10:45:27.787  5631  5643 D BluetoothAdapterProperties: Setting state to 15
09-23 10:45:27.787  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 10:45:27.787  5631  5643 I BluetoothAdapterState: Entering BleOnState
09-23 10:45:27.787   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.788  5587  5597 D BluetoothMap: onBluetoothStateChange: up=false
09-23 10:45:27.788  5587  5598 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 10:45:27.789  3123  3782 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 10:45:27.790  3123  3143 D BluetoothPan: onBluetoothStateChange on: false
09-23 10:45:27.790   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.791  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 10:45:27.791   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.791  5587  5597 D BluetoothPan: onBluetoothStateChange on: false
09-23 10:45:27.792  3123  3782 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.792   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 10:45:27.792  5587  5598 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 10:45:27.793  5587  5597 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.793  5587  5598 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 10:45:27.794  3558  3574 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 10:45:27.794  3123  3143 D BluetoothMap: onBluetoothStateChange: up=false
09-23 10:45:27.794  3123  3137 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 10:45:27.795  5631  5643 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 10:45:27.796  5631  5643 D BluetoothAdapterProperties: Setting state to 16
09-23 10:45:27.796  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 10:45:27.796  5631  5643 D BluetoothAdapterProperties: onBleDisable
09-23 10:45:27.796  5631  5643 I BluetoothAdapterState: Entering PendingCommandState
09-23 10:45:27.796  5631  5644 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-23 10:45:27.797  5631  5656 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 10:45:27.797  5631  5656 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 10:45:27.800  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:27.802  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.806  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 10:45:27.808  5631  5647 D BluetoothAdapterProperties: Scan Mode:20
09-23 10:45:27.809  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.810  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:27.811  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 10:45:27.813  5587  5587 D DockEventReceiver: finishStartingService: stopping service
,09-23 10:45:27.998  5631  5647 I bt_hci  : shut_down
,09-23 10:45:27.998  5631  5651 D bt_hwcfg: hw_epilog_process
09-23 10:45:27.999  5631  5651 I bt_vendor: low_power_mode_cb
,09-23 10:45:28.003  5631  5651 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 10:45:28.003  5631  5651 I bt_vendor: epilog_cb
09-23 10:45:28.003  5631  5651 I bt_hci  : epilog_finished_callback
09-23 10:45:28.004  5631  5647 I bt_hci_h4: hal_close
,09-23 10:45:28.005  5631  5647 I bt_userial_vendor: device fd = 54 close
,09-23 10:45:28.130  5631  5644 D bt_stack_manager: event_shut_down_stack finished.
,09-23 10:45:28.130  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 10:45:28.135  5631  5643 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 10:45:28.135  5631  5631 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 10:45:28.136  5631  5631 D BtGatt.GattService: Received stop request...Stopping profile...
,09-23 10:45:28.136  5631  5631 D BtGatt.GattService: stop()
09-23 10:45:28.136  5631  5631 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 10:45:28.140  5631  5631 V BluetoothAdapterState: isTurningOff()=false
,09-23 10:45:28.140  5631  5631 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:28.141  5631  5631 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:28.141  5631  5631 V BluetoothAdapterState: isBleTurningOff()=true
09-23 10:45:28.141  5631  5643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-23 10:45:28.142  5631  5643 D BluetoothAdapterProperties: Setting state to 10
09-23 10:45:28.142  5631  5643 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 10:45:28.143  5631  5643 I BluetoothAdapterState: Entering OffState
09-23 10:45:28.144   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 10:45:28.158  5631  5631 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-23 10:45:28.158  5631  5631 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 10:45:28.159  5631  5631 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 10:45:28.161  5631  5644 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 10:45:28.170  5631  5631 I art     : System.exit called, status: 0
,09-23 10:45:28.170  5631  5631 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 10:45:28.198   931  3162 I ActivityManager: Process com.android.bluetooth (pid 5631) has died
,09-23 10:45:28.234  5457  5516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:28.234  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:28.234  5457  5516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 10:45:28.235  5457  5516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:28.237  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:28.267   931   948 I ActivityManager: Start proc 5685:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 10:45:28.347  5685  5685 D AdapterServiceConfig: Adding HeadsetService
,09-23 10:45:28.348  5685  5685 D AdapterServiceConfig: Adding A2dpService
09-23 10:45:28.348  5685  5685 D AdapterServiceConfig: Adding HidService
,09-23 10:45:28.348  5685  5685 D AdapterServiceConfig: Adding HealthService
09-23 10:45:28.348  5685  5685 D AdapterServiceConfig: Adding PanService
09-23 10:45:28.348  5685  5685 D AdapterServiceConfig: Adding GattService
,09-23 10:45:28.349  5685  5685 D AdapterServiceConfig: Adding BluetoothMapService
09-23 10:45:28.349  5685  5685 D AdapterServiceConfig: Adding SapService
,09-23 10:45:28.359   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63fe6da:true
,09-23 10:45:28.360  5685  5685 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 10:45:28.362  5685  5685 I bt_bluedroid: init
,09-23 10:45:28.362  5685  5697 I BluetoothAdapterState: Entering OffState
,09-23 10:45:28.364  5685  5698 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 10:45:28.364  5685  5698 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 10:45:28.364  5685  5698 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 10:45:28.364  5685  5698 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 10:45:28.365  5685  5685 I bt_bluedroid: get_profile_interface socket
,09-23 10:45:28.367  5685  5685 I bt_bluedroid: get_profile_interface sdp
09-23 10:45:28.367  5685  5701 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 10:45:28.368  5685  5701 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 10:45:28.372  5685  5696 I bt_bluedroid: config_hci_snoop_log
,09-23 10:45:28.374   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 10:45:28.378  5685  5697 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 10:45:28.378  5685  5697 D BluetoothAdapterProperties: Setting state to 14
09-23 10:45:28.378  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-23 10:45:28.380  5685  5697 D BluetoothBondStateMachine: make
,09-23 10:45:28.382  5685  5703 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 10:45:28.384  5685  5697 I BluetoothAdapterState: Entering PendingCommandState
,09-23 10:45:28.385  5685  5685 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 10:45:28.387  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:28.388  5685  5685 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 10:45:28.388  5685  5685 D BtGatt.GattService: Received start request. Starting profile...
,09-23 10:45:28.389  5685  5685 D BtGatt.GattService: start()
09-23 10:45:28.389  5685  5685 I bt_bluedroid: get_profile_interface gatt
09-23 10:45:28.390  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:28.391  5685  5685 D BtGatt.AdvertiseManager: advertise manager created
,09-23 10:45:28.395  5685  5685 V BluetoothAdapterState: isTurningOff()=false
,09-23 10:45:28.395  5685  5685 V BluetoothAdapterState: isTurningOn()=false
09-23 10:45:28.395  5685  5685 V BluetoothAdapterState: isBleTurningOn()=true
09-23 10:45:28.396  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:28.396  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 10:45:28.397  5685  5697 I bt_bluedroid: bt_bluedroid
09-23 10:45:28.397  5685  5698 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 10:45:28.398  5685  5698 I bt_hci  : start_up
,09-23 10:45:28.402  5685  5698 I bt_vendor: alloc value 0xf420b871
09-23 10:45:28.403  5685  5698 I bt_vendor: init
09-23 10:45:28.403  5685  5698 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-23 10:45:28.403  5685  5698 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 10:45:28.513  5685  5698 D bt_hci  : start_up starting async portion
09-23 10:45:28.513  5685  5706 I bt_hci  : event_finish_startup
,09-23 10:45:28.513  5685  5706 I bt_hci_h4: hal_open
09-23 10:45:28.513  5685  5706 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 10:45:28.509  5707  5707 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 10:45:28.515  5685  5706 I bt_userial_vendor: device fd = 54 open
,09-23 10:45:28.528  5685  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 10:45:28.530  5685  5706 D bt_hwcfg: Chipset BCM4358A3
,09-23 10:45:28.530  5685  5706 D bt_hwcfg: Target name = [BCM4358A3]
09-23 10:45:28.530  5685  5706 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 10:45:28.745  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 10:45:28.932  5685  5706 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 10:45:28.932  5685  5706 D bt_hwcfg: Settlement delay -- 100 ms
,09-23 10:45:28.932  5685  5706 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 10:45:29.056  5685  5706 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 10:45:29.056  5685  5706 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 10:45:29.058  5685  5706 I bt_hwcfg: vendor lib fwcfg completed
09-23 10:45:29.059  5685  5706 I bt_vendor: firmware callback
09-23 10:45:29.059  5685  5706 I bt_hci  : firmware_config_callback
,09-23 10:45:29.068  5685  5709 I bt_btu  : btu_task pending for preload complete event
,09-23 10:45:29.068  5685  5709 I bt_btu_task: Bluetooth chip preload is complete
09-23 10:45:29.068  5685  5709 I bt_btu  : btu_task received preload complete event
,09-23 10:45:29.077  5685  5709 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 10:45:29.077  5685  5709 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 10:45:29.077  5685  5709 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 10:45:29.077  5685  5709 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_GATT
,09-23 10:45:29.078  5685  5709 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 10:45:29.079  5685  5709 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 10:45:29.079  5685  5709 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 10:45:29.160  5685  5709 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4189549
,09-23 10:45:29.160  5685  5709 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4189549 
,09-23 10:45:29.186  5685  5701 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,09-23 10:45:29.187  5685  5701 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 10:45:29.188  5685  5701 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 10:45:29.190  5685  5701 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 10:45:29.195  5685  5701 D BluetoothAdapterProperties: Scan Mode:20
09-23 10:45:29.195  5685  5701 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 10:45:29.195  5685  5701 D bt_hci  : do_postload posting postload work item
09-23 10:45:29.195  5685  5706 I bt_hci  : event_postload
09-23 10:45:29.196  5685  5706 I bt_vendor: sco_config_cb
09-23 10:45:29.196  5685  5706 I bt_hci  : sco_config_callback postload finished.
09-23 10:45:29.199  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:29.200  5685  5701 D bt_bte_conf: Device ID record 1 : primary
,09-23 10:45:29.200  5685  5701 D bt_bte_conf:   vendorId            = 000f
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   vendorIdSource      = 0001
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   product             = 1200
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   version             = 1436
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   clientExecutableURL = 
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   serviceDescription  = 
09-23 10:45:29.200  5685  5701 D bt_bte_conf:   documentationURL    = 
09-23 10:45:29.201  5685  5701 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-23 10:45:29.201  5685  5698 D bt_stack_manager: event_start_up_stack finished
09-23 10:45:29.202  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 10:45:29.202  5685  5697 D BluetoothAdapterProperties: Setting state to 15
09-23 10:45:29.202  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 10:45:29.202  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:29.204  5685  5697 I BluetoothAdapterState: Entering BleOnState
,09-23 10:45:29.206  5685  5697 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-23 10:45:29.206  5685  5697 D BluetoothAdapterProperties: Setting state to 11
,09-23 10:45:29.206  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 10:45:29.206  5583  5583 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-23 10:45:29.209  5685  5706 I bt_vendor: low_power_mode_cb
09-23 10:45:29.213  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:29.216  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:29.217   931   931 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.217  5685  5685 D HeadsetService: Received start request. Starting profile...
09-23 10:45:29.218  3558  3578 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.219  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:29.219   931   931 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.219   931   931 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.220  5587  5597 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.220  5685  5685 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 10:45:29.220  5685  5685 D HeadsetStateMachine: make
,09-23 10:45:29.222  3123  3137 D BluetoothHeadset: Proxy object connected
09-23 10:45:29.222  3123  3123 D HeadsetProfile: Bluetooth service connected
09-23 10:45:29.224  5583  5583 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-23 10:45:29.225  5587  5587 D HeadsetProfile: Bluetooth service connected
,09-23 10:45:29.226  5685  5697 I BluetoothAdapterState: Entering PendingCommandState
,09-23 10:45:29.229  5583  5583 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 10:45:29.230  5685  5685 D HeadsetStateMachine: max_hf_connections = 1
,09-23 10:45:29.230  5685  5685 I bt_bluedroid: get_profile_interface handsfree
09-23 10:45:29.231  5685  5701 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 10:45:29.231  5685  5701 E bt_btif : btif_hf_upstreams_evt: Invalid index 27651
,09-23 10:45:29.232  5583  5583 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 10:45:29.233  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:29.234  5685  5685 D A2dpService: Received start request. Starting profile...
,09-23 10:45:29.235  5685  5685 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 10:45:29.235  5685  5685 I bt_bluedroid: get_profile_interface avrcp
,09-23 10:45:29.241  5685  5685 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-23 10:45:29.242  5685  5685 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-23 10:45:29.242  5685  5685 D A2dpStateMachine: make
,09-23 10:45:29.243  5685  5685 I bt_bluedroid: get_profile_interface a2dp
,09-23 10:45:29.243  5685  5701 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-23 10:45:29.245  5685  5719 D A2dpStateMachine: Enter Disconnected: -2
,09-23 10:45:29.245  5685  5685 I BluetoothHidServiceJni: classInitNative: succeeds
09-23 10:45:29.246  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:29.247  5685  5685 D HidService: Received start request. Starting profile...
,09-23 10:45:29.247  5685  5685 I bt_bluedroid: get_profile_interface hidhost
09-23 10:45:29.247  5685  5685 D HidService: setHidService(): set to: null
09-23 10:45:29.247  5685  5701 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf416a56d
09-23 10:45:29.247  5685  5701 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 10:45:29.247  5685  5685 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 10:45:29.248  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-23 10:45:29.248  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:29.248  5685  5685 D HealthService: Received start request. Starting profile...
,09-23 10:45:29.250  5685  5685 I bt_bluedroid: get_profile_interface health
,09-23 10:45:29.250  5685  5685 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 10:45:29.251  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:29.252  5685  5685 D PanService: Received start request. Starting profile...
,09-23 10:45:29.252  5685  5685 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 10:45:29.252  5685  5685 I bt_bluedroid: get_profile_interface pan
09-23 10:45:29.252  5685  5701 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 10:45:29.254  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:29.254  5685  5685 D BluetoothMapService: Received start request. Starting profile...
,09-23 10:45:29.254  5685  5685 D BluetoothMapService: start()
09-23 10:45:29.257  5685  5685 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 10:45:29.257  5685  5685 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 10:45:29.257  5685  5685 D BluetoothMapAppObserver: createReceiver()
,09-23 10:45:29.259  5685  5685 D BluetoothMapAppObserver: initObservers()
,09-23 10:45:29.259  5685  5685 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 10:45:29.264  5685  5685 V SapService: SapBinder()
,09-23 10:45:29.264  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
09-23 10:45:29.264  5685  5685 D SapService: Received start request. Starting profile...
09-23 10:45:29.265  5685  5685 V SapService: start()
,09-23 10:45:29.268  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.268  5685  5717 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.268  5685  5685 V BluetoothAdapterState: isTurningOn()=true
,09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isTurningOff()=false
,09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.269  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.270  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.271  5685  5685 V BluetoothAdapterState: isTurningOff()=false
09-23 10:45:29.271  5685  5685 V BluetoothAdapterState: isTurningOn()=true
09-23 10:45:29.271  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
09-23 10:45:29.271  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
09-23 10:45:29.271  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-23 10:45:29.271  5685  5697 D BluetoothAdapterProperties: ScanMode =  20
09-23 10:45:29.271  5685  5697 D BluetoothAdapterProperties: State =  11
,09-23 10:45:29.273  5685  5701 D BluetoothAdapterProperties: Scan Mode:21
,09-23 10:45:29.274  5685  5697 D BluetoothAdapterProperties: Setting state to 12
09-23 10:45:29.274  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 10:45:29.274  5685  5701 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 10:45:29.274   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:29.274  5685  5697 I BluetoothAdapterState: Entering OnState
09-23 10:45:29.274  5587  5597 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 10:45:29.277  5587  5598 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:29.277  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:29.279  3123  3782 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 10:45:29.279  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:29.281  3123  3143 D BluetoothPan: onBluetoothStateChange on: true
09-23 10:45:29.281  3123  3123 D BluetoothInputDevice: Proxy object connected
09-23 10:45:29.281  3123  3123 D HidProfile: Bluetooth service connected
09-23 10:45:29.282   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:29.283  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 10:45:29.283  5685  5685 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:29.283  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:29.283  5685  5685 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-23 10:45:29.284   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:29.284  5587  5598 D BluetoothPan: onBluetoothStateChange on: true
09-23 10:45:29.285  3123  3123 D BluetoothA2dp: Proxy object connected
09-23 10:45:29.285  5685  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:29.286  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:29.286  5587  5587 D BluetoothMap: Proxy object connected
09-23 10:45:29.286  5587  5587 D MapProfile: Bluetooth service connected
09-23 10:45:29.286  5587  5587 D BluetoothMap: getConnectedDevices()
09-23 10:45:29.286  3123  3143 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:29.287  5685  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:29.287   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 10:45:29.287   931   931 D BluetoothA2dp: Proxy object connected
,09-23 10:45:29.287  5587  5597 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 10:45:29.289  5587  5598 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 10:45:29.290  5685  5685 D ObexServerSockets: Succeed to create listening sockets 
09-23 10:45:29.290  5685  5685 D ObexServerSockets0: startAccept()
09-23 10:45:29.290  5685  5685 D ObexServerSockets0: prepareForNewConnect()
09-23 10:45:29.290  5587  5724 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 10:45:29.291  5685  5685 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 10:45:29.291  5685  5685 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 10:45:29.292  3558  3865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 10:45:29.292  3123  3137 D BluetoothMap: onBluetoothStateChange: up=true
09-23 10:45:29.292  5685  5725 D ObexServerSockets0: Accepting socket connection...
09-23 10:45:29.292  5685  5726 D ObexServerSockets0: Accepting socket connection...
09-23 10:45:29.293  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
,09-23 10:45:29.293  3123  3123 D PanProfile: Bluetooth service connected
09-23 10:45:29.294  3123  3123 D BluetoothMap: Proxy object connected
09-23 10:45:29.294  3123  3782 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 10:45:29.294  3123  3123 D MapProfile: Bluetooth service connected
09-23 10:45:29.294  3123  3123 D BluetoothMap: getConnectedDevices()
09-23 10:45:29.297   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 10:45:29.297   931   931 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-23 10:45:29.298  5685  5685 D BluetoothMapService: onReceive
09-23 10:45:29.298  5685  5685 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 10:45:29.298  5685  5685 D BluetoothMapService: STATE_ON
,09-23 10:45:29.298  5587  5587 D BluetoothA2dp: Proxy object connected
09-23 10:45:29.300  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:29.302  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:29.302  5685  5727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:29.303  5685  5727 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 10:45:29.304  5685  5727 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 10:45:29.304  5587  5587 D BluetoothInputDevice: Proxy object connected
09-23 10:45:29.304  5587  5587 D HidProfile: Bluetooth service connected
09-23 10:45:29.305  5587  5587 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 10:45:29.305  5587  5587 D PanProfile: Bluetooth service connected
,09-23 10:45:29.310  5587  5587 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 10:45:29.315  3658  3658 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 10:45:29.316  5587  5587 D DockEventReceiver: finishStartingService: stopping service
,09-23 10:45:29.322  5587  5587 D BluetoothPbap: Proxy object connected
,09-23 10:45:29.323  5587  5587 D PbapServerProfile: Bluetooth service connected
,09-23 10:45:29.325  5685  5685 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 10:45:29.325  5685  5685 D ObexServerSockets0: prepareForNewConnect()
09-23 10:45:29.325  3123  3123 D BluetoothPbap: Proxy object connected
09-23 10:45:29.325  3123  3123 D PbapServerProfile: Bluetooth service connected
,09-23 10:45:29.335  5685  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 10:45:29.349  5685  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 10:45:29.350  5685  5736 I BtOppRfcommListener: Accept thread started.
,09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:29.759  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:29.764  5457  5516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:29.767  5457  5503 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,09-23 10:45:29.770   931  3422 D WifiService: setWifiEnabled: false pid=5457, uid=10077
09-23 10:45:29.770   931  3422 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:29.772  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:29.775   931   931 D RttService: SCAN_AVAILABLE : 1
09-23 10:45:29.776   931  3091 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 10:45:29.786   931  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 10:45:29.787   508   924 D CommandListener: Clearing all IP addresses on wlan0
,09-23 10:45:29.796   931  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 10:45:29.798  5583  5583 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:29.808  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:29.813  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:29.817  5583  5583 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:29.820  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:29.822  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:29.850  5583  5583 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 10:45:29.851  5583  5583 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 10:45:29.955  4306  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 10:45:29.955   931  2981 D wifi    : In wifi stop Hal
09-23 10:45:29.955   931  2981 D wifi    : halHandle = 0x7f6f3a34e0, mVM = 0x7f8b9cd140, mCls = 0x20199e
09-23 10:45:29.955   931  5582 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 10:45:29.955   931  5582 D WifiHAL : Got a signal to exit!!!
09-23 10:45:29.955   931  5582 I WifiHAL : Exit wifi_event_loop
,09-23 10:45:29.957   931  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 10:45:29.957   931  2981 E WifiHAL : Event processing terminated
09-23 10:45:29.957   931  2981 D wifi    : In wifi cleaned up handler
09-23 10:45:29.958   931  2981 I WifiHAL : Internal cleanup completed
09-23 10:45:29.961  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:29.963  3490  4054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 10:45:29.964  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:29.987   931  5582 D wifi    : set interface wlan0 flags (DOWN)
,09-23 10:45:29.987   931  2981 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 10:45:30.190   931   948 D Tethering: InitialState.processMessage what=4
,09-23 10:45:30.197   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:30.282  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:30.288  5457  5516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:30.290   931  3556 D WifiService: setWifiEnabled: true pid=5457, uid=10077
,09-23 10:45:30.291   931  3556 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 10:45:30.292  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:30.298   508   924 D SoftapController: Softap fwReload - Ok
09-23 10:45:30.300   508   924 D CommandListener: Setting iface cfg
,09-23 10:45:30.300   508   924 D CommandListener: Trying to bring down wlan0
09-23 10:45:30.301   508   924 D CommandListener: Clearing all IP addresses on wlan0
,09-23 10:45:30.306   931  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 10:45:30.798   931  3395 D WifiService: setWifiEnabled: true pid=5457, uid=10077
,09-23 10:45:30.804   931  3395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 10:45:30.914   931  2981 D wifi    : set interface wlan0 flags (UP)
,09-23 10:45:30.915   931  2981 I WifiHAL : Initializing wifi
,09-23 10:45:30.916   931  2981 I WifiHAL : Creating socket
,09-23 10:45:30.922   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 10:45:30.925   931  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 10:45:30.925   931  2981 D wifi    : Did set static halHandle = 0x7f6f3a34e0
09-23 10:45:30.925   931  2981 D wifi    : halHandle = 0x7f6f3a34e0, mVM = 0x7f8b9cd140, mCls = 0x20193e
09-23 10:45:30.925   931  2981 D wifi    : array field set
09-23 10:45:30.926   931  2981 I WifiNative-HAL: interface[0] = wlan0
,09-23 10:45:30.927   931  5740 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547326932192
09-23 10:45:30.928   931  5740 D wifi    : waitForHalEvents called, vm = 0x7f8b9cd140, obj = 0x20193e, env = 0x7f6f3a0dc0
,09-23 10:45:30.987  5741  5741 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 10:45:31.008  5741  5741 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 10:45:31.017  5741  5741 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 10:45:31.017  5741  5741 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 10:45:31.034   931  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 10:45:31.039  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:31.045   931  2981 D WifiConfigStore: Loading config and enabling all networks 
,09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:31.047  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:31.049  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:31.056   931  2981 D WifiConfigStore: loaded 0 passpoint configs
,09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:31.056  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 10:45:31.056   931  2981 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 10:45:31.057   931  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 10:45:31.058   931  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 10:45:31.058  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:31.059   931  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 10:45:31.059   931  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 10:45:31.059   931  2981 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 10:45:31.059   931  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-23 10:45:31.060  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:31.063   931  2981 D WifiNative-HAL: Setting external_sim to 1
09-23 10:45:31.063  4306  4306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 10:45:31.064   931  2981 D wifi    : setting dfs flag to true, 0x7f702ac260
09-23 10:45:31.064   931  2981 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 10:45:31.065   931  2981 D wifi    : setting scan oui 0x7f702ac260
09-23 10:45:31.065   931  2981 D WifiHAL : Sending mac address OUI
,09-23 10:45:31.070   931  2981 E native  : do suspend false
,09-23 10:45:31.077   931  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 10:45:31.077   931   931 D RttService: SCAN_AVAILABLE : 3
09-23 10:45:31.077   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 10:45:31.077   931  3091 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 10:45:31.079   508   924 D CommandListener: Setting iface cfg
,09-23 10:45:31.083   931  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-23 10:45:31.083   931  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 10:45:31.090   931  2980 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 10:45:31.094   931  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 10:45:31.094   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=210366 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:31.313  5457  5516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:31.317  5457  5516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 10:45:31.319  5457  5503 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 10:45:31.319   931  3591 D WifiService: setWifiEnabled: true pid=5457, uid=10077
09-23 10:45:31.319   931  3591 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 10:45:31.320  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 10:45:31.320  5457  5503 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:45:31.320  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:45:31.321  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 10:45:31.321  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@643f224 removed from the list
09-23 10:45:31.321  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 10:45:31.321  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8d418d removed from the list
09-23 10:45:31.321  5457  5503 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:45:31.321  5457  5503 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 10:45:31.321  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 10:45:31.324  5457  5503 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
09-23 10:45:31.326  5457  5503 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-23 10:45:31.328  5457  5743 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-23 10:45:31.328  5457  5743 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 10:45:31.840  5457  5745 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-23 10:45:31.840  5457  5743 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-23 10:45:31.841  5457  5745 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 10:45:31.841  5457  5743 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 10:45:31.842  5457  5745 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 10:45:31.842  5457  5743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 10:45:31.844  5457  5743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 10:45:31.845  5457  5745 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 10:45:31.848  5457  5747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Sender)
,09-23 10:45:31.849  5457  5748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender)
,09-23 10:45:31.850  5457  5745 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 10:45:31.850  5457  5743 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 10:45:31.851  5457  5750 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: IncomingSocketThread/Receiver)
,09-23 10:45:31.852  5457  5749 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
09-23 10:45:31.852  5457  5749 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
09-23 10:45:31.853  5457  5749 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 10:45:31.853  5457  5749 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-23 10:45:31.854  5457  5750 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: IncomingSocketThread/Receiver)
,09-23 10:45:31.855  5457  5750 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 10:45:31.855  5457  5750 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 10:45:32.333  5457  5503 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-23 10:45:32.335  5457  5503 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
09-23 10:45:32.337  5457  5503 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-23 10:45:32.343  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-23 10:45:32.344  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-23 10:45:32.346  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-23 10:45:32.346  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-23 10:45:32.348  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-23 10:45:32.352  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-23 10:45:32.353  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ee99288 Bundle[{}]
09-23 10:45:32.354  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-23 10:45:32.354  5457  5503 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 10:45:32.354  5457  5503 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-23 10:45:32.356  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-23 10:45:32.356  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-23 10:45:32.358  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,09-23 10:45:32.359  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-23 10:45:32.360  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-23 10:45:32.360  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-23 10:45:32.361  5457  5503 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,09-23 10:45:32.362  5457  5503 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-23 10:45:32.365  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-23 10:45:32.368  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-23 10:45:32.370  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-23 10:45:32.372  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-23 10:45:32.373  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-23 10:45:32.374  5457  5503 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-23 10:45:32.376  5457  5503 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-23 10:45:32.379  5457  5751 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 10:45:32.379  5457  5751 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 10:45:32.382  5457  5751 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 10:45:32.383  5457  5751 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 10:45:32.383  5457  5751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 10:45:32.383  5457  5751 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 10:45:32.384  5457  5754 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Sender)
09-23 10:45:32.384  5457  5753 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-23 10:45:32.384  5457  5753 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 10:45:32.384  5457  5751 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-23 10:45:32.385  5457  5753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 10:45:32.385  5457  5755 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver)
,09-23 10:45:32.386  5457  5753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 10:45:32.386  5457  5755 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver)
09-23 10:45:32.386  5457  5755 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 10:45:32.386  5457  5756 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: IncomingSocketThread/Sender)
09-23 10:45:32.386  5457  5755 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 10:45:32.386  5457  5753 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 10:45:32.388  5457  5757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: IncomingSocketThread/Receiver)
09-23 10:45:32.389  5457  5757 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: IncomingSocketThread/Receiver)
09-23 10:45:32.389  5457  5757 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-23 10:45:32.390  5457  5757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 10:45:32.884  5457  5503 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-23 10:45:32.886  5457  5503 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,09-23 10:45:32.888  5457  5503 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-23 10:45:32.891  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-23 10:45:32.893  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-23 10:45:32.895  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-23 10:45:32.896  5457  5503 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 183)
,09-23 10:45:32.897  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-23 10:45:32.898  5457  5503 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-23 10:45:32.898  5457  5503 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 184)
09-23 10:45:32.899  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-23 10:45:32.901  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
09-23 10:45:32.903  5457  5503 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
09-23 10:45:32.904  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 10:45:32.904  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fdd8e added. We now have 3 listener(s)
,09-23 10:45:32.906  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 10:45:32.906  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 10:45:32.906  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 10:45:32.906  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 10:45:32.906  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6c9af added. We now have 3 listener(s)
09-23 10:45:32.906  5457  5503 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 10:45:32.907  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 10:45:32.911  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 10:45:32.916  5457  5503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 10:45:32.918  5457  5503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 10:45:32.919  5457  5503 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 10:45:32.922  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 10:45:32.924  5457  5503 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,09-23 10:45:32.925  5457  5503 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-23 10:45:32.925  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 10:45:32.925  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-23 10:45:32.925  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-23 10:45:32.925  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:32.925  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-23 10:45:32.925  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:32.926  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:32.927  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 10:45:32.927  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 10:45:32.927  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:32.928  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:32.928  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 10:45:32.928  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:32.928  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 10:45:32.928  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:32.929  5457  5758 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:32.929  5702  5702 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32345]" dev="sockfs" ino=32345 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:32.932  5457  5758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 10:45:32.929  5702  5702 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32345]" dev="sockfs" ino=32345 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:32.934  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:45:32.934  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 10:45:32.938  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 10:45:32.939  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:45:32.939  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:45:32.941  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 10:45:32.941  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:32.942  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-23 10:45:32.942  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 10:45:32.942  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:32.942  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 10:45:32.943  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:32.946  5685  5728 D BtGatt.GattService: registerClient() - UUID=c85dcb8a-3801-4882-90c9-83bcceaf2954
09-23 10:45:32.946  5685  5701 D BtGatt.GattService: onClientRegistered() - UUID=c85dcb8a-3801-4882-90c9-83bcceaf2954, clientIf=5
,09-23 10:45:32.947  5457  5467 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 10:45:32.949  5685  5704 D BtGatt.AdvertiseManager: message : 0
,09-23 10:45:32.952  5685  5704 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 10:45:32.963  5685  5701 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:32.969  5685  5701 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:32.970  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 10:45:32.970  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 10:45:32.972  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 10:45:32.973  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:32.973  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 10:45:32.973  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 10:45:32.973  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 10:45:32.973  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 10:45:32.973  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 10:45:32.976  5457  5457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:32.976  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:33.478  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 10:45:33.478  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 10:45:33.478  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:45:34.338   931  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 10:45:34.340   931  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 10:45:34.340   931  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 10:45:34.353   931  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 10:45:34.384   931  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 10:45:34.385  5741  5741 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 10:45:34.810  5741  5741 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 10:45:34.845  5741  5741 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 10:45:34.846  5741  5741 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 10:45:34.856   931  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 10:45:34.857   931  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 10:45:34.857   931  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 10:45:34.876   931  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 10:45:34.893   508   924 D CommandListener: Setting iface cfg
,09-23 10:45:34.899   931  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 10:45:34.906   931  5763 D DhcpClient: Receive thread started
,09-23 10:45:34.911   931  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 10:45:34.911   931  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 10:45:34.912   931  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 10:45:34.994   931  2981 E native  : do suspend false
,09-23 10:45:35.007   931  5762 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 10:45:35.020   931  5763 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172627, domain null
,09-23 10:45:35.021   931  5762 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172627 seconds
,09-23 10:45:35.022   931  5762 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 10:45:35.040   931  5763 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 10:45:35.040   931  5762 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 10:45:35.042   508   924 D CommandListener: Setting iface cfg
,09-23 10:45:35.046   931  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 10:45:35.049   931  5762 D DhcpClient: Scheduling renewal in 86399s
,09-23 10:45:35.056   931  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 10:45:35.056   931  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,09-23 10:45:35.057   931  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-23 10:45:35.060   931  2983 D ConnectivityService: Adding iface wlan0 to network 101
09-23 10:45:35.063   931  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 10:45:35.097   931  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 10:45:35.097   931  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 10:45:35.098   931  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 10:45:35.101   931  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 10:45:35.103   931  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 10:45:35.112   931  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 10:45:35.118   931  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-23 10:45:35.118   931  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-23 10:45:35.118   931  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 10:45:35.118   931  2983 D ConnectivityService:    accepting network in place of null
09-23 10:45:35.118   931  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 10:45:35.118   931  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 10:45:35.119   931  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 10:45:35.134   931  5761 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214406, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 10:45:35.140   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 10:45:35.161   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 10:45:35.165   931  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-23 10:45:35.165  3527  3694 W QCNEJ   : |CORE| network available: 101
,09-23 10:45:35.165   931  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 10:45:35.166   931  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 10:45:35.168  3527  3694 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-23 10:45:35.169   931   948 D Tethering: MasterInitialState.processMessage what=3
09-23 10:45:35.170  3527  3694 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 10:45:35.170  3527  3694 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:35.176  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 10:45:35.178  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:35.182  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:45:35.184  4875  4888 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 10:45:35.184  4875  4888 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 10:45:35.184  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:35.184  4875  4888 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 10:45:35.184  4875  4888 E SarControlService: no key has been found,reset the power
,09-23 10:45:35.184  4875  4913 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-23 10:45:35.184  4875  4913 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 10:45:35.185  4875  4913 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 10:45:35.185  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 10:45:35.185  4901  4901 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 10:45:35.187  4875  4913 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 10:45:35.187  4875  4913 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 10:45:35.187  4875  4913 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 10:45:35.188  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 10:45:35.188  4901  4901 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 10:45:35.189  5457  5457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 10:45:35.190  3907  3907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 10:45:35.191  5457  5457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 10:45:35.193  4901  4915 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7829d04 HexData = [00000000ec03000000000000ffffffff]
09-23 10:45:35.194  4901  4915 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-23 10:45:35.194  4901  4915 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 10:45:35.194  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 10:45:35.194  4875  4885 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 10:45:35.195  3907  3907 D SystemUpdateService: onCreate
,09-23 10:45:35.199  3907  3907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 10:45:35.200  4901  4915 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7829d04 HexData = [00000000ed03000000000000ffffffff]
09-23 10:45:35.200  4901  4915 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 10:45:35.200  4901  4915 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 10:45:35.201   931  5760 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-23 10:45:35.202  4901  4901 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 10:45:35.202  4875  4886 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 10:45:35.211  3907  3907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 10:45:35.217  3907  5217 I iu.UploadsManager: num queued entries: 0
,09-23 10:45:35.217  3907  5217 I iu.UploadsManager: num updated entries: 0
,09-23 10:45:35.218  3907  5773 I SystemUpdateService: active receiver: enabled
,09-23 10:45:35.222  3907  3907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 10:45:35.223  3907  3907 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 10:45:35.224  5539  5539 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 10:45:35.228  5539  5539 D SprintDMHelper: simOperator: 
09-23 10:45:35.228  5539  5539 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 10:45:35.247  3907  5217 I iu.SyncManager: NEXT; no task
,09-23 10:45:35.248   931  5760 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 14:45:35 GMT], X-Android-Received-Millis=[1474641935248], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474641935225]}
,09-23 10:45:35.249   931  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-23 10:45:35.249   931  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-23 10:45:35.249   931  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 10:45:35.250  3907  5773 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 10:45:35.250   931  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 10:45:35.264  3907  5773 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 10:45:35.264  3907  5773 I SystemUpdateService: now status is 0 (complete)
09-23 10:45:35.264  3907  5773 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 10:45:35.264  3907  5773 I SystemUpdateService: file has been verified
09-23 10:45:35.264  3907  5773 I SystemUpdateService: OTA package size = 21989297
,09-23 10:45:35.270  3907  5773 I SystemUpdateService: showing system update notification
,09-23 10:45:35.280  3907  3907 D SystemUpdateService: onDestroy
,09-23 10:45:35.373  4306  5777 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 10:45:36.167   931  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 10:45:36.477  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 10:45:36.477  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 10:45:36.477  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 10:45:36.477  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:36.478  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 10:45:36.478  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 10:45:36.478  5457  5758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 10:45:36.478  5457  5758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:36.478  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 10:45:36.479  5457  5758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 10:45:36.479  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 10:45:36.479  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:45:36.479  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 10:45:36.479  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:36.479  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:36.479  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 10:45:36.482  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:36.482  5457  5503 D BluetoothLeScanner: could not find callback wrapper
09-23 10:45:36.482  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:36.482  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 10:45:36.484  5685  5704 D BtGatt.AdvertiseManager: message : 1
09-23 10:45:36.485  5685  5704 D BtGatt.AdvertiseManager: stop advertise for client 5
09-23 10:45:36.499  5685  5701 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 10:45:36.500  5685  5701 D BtGatt.GattService: Client app is not null!
09-23 10:45:36.501  5685  5702 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 10:45:36.502  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:45:36.502  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:36.503  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 10:45:36.503  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 10:45:36.503  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 10:45:36.505  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:36.505  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 10:45:36.505  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:45:36.508  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:45:36.510  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 10:45:36.510  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 10:45:36.510  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:36.511  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:36.511  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 10:45:36.511  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:45:36.514  5457  5503 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-23 10:45:36.514  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:45:36.515  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 10:45:36.515  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 10:45:36.515  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 10:45:36.515  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 10:45:36.516  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 10:45:36.521  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:45:36.521  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 10:45:36.525  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:36.526  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 10:45:36.526  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 10:45:36.531  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 10:45:36.531  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 10:45:36.532  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 10:45:36.533  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:36.536  5685  5695 D BtGatt.GattService: registerClient() - UUID=8822a076-fb7c-471f-88c7-17561d49ea4e
,09-23 10:45:36.537  5685  5701 D BtGatt.GattService: onClientRegistered() - UUID=8822a076-fb7c-471f-88c7-17561d49ea4e, clientIf=5
09-23 10:45:36.537  5457  5467 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 10:45:36.538  5685  5716 D BtGatt.GattService: start scan with filters
,09-23 10:45:36.542  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 10:45:36.542  5685  5705 D BtGatt.ScanManager: handling starting scan
09-23 10:45:36.542  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 10:45:36.542  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 10:45:36.542  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 10:45:36.543  5685  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a17e2a5
,09-23 10:45:36.545  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 10:45:36.545  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 10:45:36.545  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 10:45:36.547  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 10:45:36.550  5685  5701 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 10:45:36.551  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:36.551  5685  5705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 10:45:36.557  5685  5701 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 10:45:36.557  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:36.558  5685  5705 D BtGatt.ScanManager: Starting BLE batch scan
09-23 10:45:36.558  5685  5705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 10:45:36.568  5685  5701 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 10:45:36.568  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 10:45:36.574  5685  5701 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 10:45:36.574  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 10:45:37.046  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 10:45:37.047  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:45:37.047  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:45:37.930   931  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 10:45:39.552  5457  5503 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-23 10:45:39.552  5457  5503 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 10:45:39.553  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 10:45:39.554  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 10:45:39.558  5457  5503 D BluetoothAdapter: STATE_ON,
,09-23 10:45:39.559  5685  5716 D BtGatt.GattService: stopScan() - queue size =1
,09-23 10:45:39.561  5685  5702 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 10:45:39.562  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:39.562  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-23 10:45:39.563  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 10:45:39.563  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 10:45:39.563  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 10:45:39.563  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 10:45:39.568  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:39.570  5685  5685 D BtGatt.ScanManager: awakened up at time 218842
09-23 10:45:39.577  5685  5701 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 10:45:39.577  5685  5702 D BtGatt.GattService: registerClient() - UUID=99961acd-8fa1-494e-aa6f-0ab7c3ee7600
09-23 10:45:39.577  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.578  5685  5705 D BtGatt.ScanManager: stopping BLe Batch
09-23 10:45:39.578  5685  5701 D BtGatt.GattService: onClientRegistered() - UUID=99961acd-8fa1-494e-aa6f-0ab7c3ee7600, clientIf=5
,09-23 10:45:39.579  5457  5467 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 10:45:39.580  5685  5728 D BtGatt.GattService: start scan with filters
,09-23 10:45:39.585  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 10:45:39.585  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 10:45:39.585  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-23 10:45:39.585  5457  5503 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 10:45:39.585  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 10:45:39.585  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 10:45:39.587  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 10:45:39.588  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 10:45:39.588  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 10:45:39.588  5685  5701 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 10:45:39.588  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.588  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 10:45:39.588  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 10:45:39.588  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-23 10:45:39.588  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 10:45:39.588  5685  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 10:45:39.588  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 10:45:39.589  5457  5503 D BluetoothAdapter: STATE_ON
09-23 10:45:39.589  5457  5786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 10:45:39.591  5685  5696 D BtGatt.GattService: stopScan() - queue size =0
09-23 10:45:39.592  5685  5716 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 10:45:39.593  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:39.593  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:39.593  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 10:45:39.593  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 10:45:39.594  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 10:45:39.596  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:39.592  5702  5702 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34093]" dev="sockfs" ino=34093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 10:45:39.592  5702  5702 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34093]" dev="sockfs" ino=34093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 10:45:39.597  5457  5786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 10:45:39.597  5457  5503 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 10:45:39.604  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 10:45:39.604  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 10:45:39.604  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-23 10:45:39.604  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:39.605  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 10:45:39.605  5457  5503 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 10:45:39.606  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:39.610  5685  5728 D BtGatt.GattService: registerClient() - UUID=c11a9e75-dbfa-4101-a69f-cfbc00976a6c
,09-23 10:45:39.611  5685  5701 D BtGatt.GattService: onClientRegistered() - UUID=c11a9e75-dbfa-4101-a69f-cfbc00976a6c, clientIf=5
09-23 10:45:39.611  5457  5468 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 10:45:39.613  5685  5701 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-23 10:45:39.613  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.613  5685  5701 D BtGatt.GattService: current time is 218885964522
,09-23 10:45:39.614  5685  5701 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -74, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -21, -101, -43, -48, -54, 116, 1, -128, -64, 45, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, -21, -101, -43, -48, -54, 116, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -75, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -74, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 10:45:39.615  5685  5704 D BtGatt.AdvertiseManager: message : 0
09-23 10:45:39.615  5685  5705 D BtGatt.ScanManager: handling starting scan
,09-23 10:45:39.617  5685  5701 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 10:45:39.618  5685  5701 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 10:45:39.619  5685  5704 D BtGatt.AdvertiseManager: starting multi advertising
09-23 10:45:39.619  5685  5701 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
09-23 10:45:39.619  5685  5701 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
09-23 10:45:39.619  5685  5701 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 10:45:39.620  5685  5701 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-23 10:45:39.620  5685  5701 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-23 10:45:39.626  5685  5701 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 10:45:39.627  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.627  5685  5705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 10:45:39.638  5685  5701 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 10:45:39.643  5685  5701 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 10:45:39.643  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.643  5685  5705 D BtGatt.ScanManager: Starting BLE batch scan
09-23 10:45:39.643  5685  5705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 10:45:39.648  5685  5701 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 10:45:39.649  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 10:45:39.649  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 10:45:39.650  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 10:45:39.652  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:39.652  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:39.652  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 10:45:39.652  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 10:45:39.652  5457  5457 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 10:45:39.653  5457  5457 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 10:45:39.653  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 10:45:39.655  5457  5457 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 10:45:39.655  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 10:45:39.659  5685  5701 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 10:45:39.659  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 10:45:39.665  5685  5701 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 10:45:39.665  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 10:45:39.671  5685  5701 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 10:45:39.671  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.671  5685  5705 D BtGatt.ScanManager: stopping BLe Batch
,09-23 10:45:39.676  5685  5701 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 10:45:39.676  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 10:45:39.676  5685  5705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 10:45:39.681  5685  5701 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-23 10:45:39.681  5685  5701 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 10:45:40.118   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 10:45:40.118   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 10:45:40.156  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 10:45:40.157  5457  5457 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 10:45:40.157  5457  5457 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 10:45:40.957   931  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 10:45:41.040   931  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-23 10:45:42.615   931  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-23 10:45:43.120   931  2983 D ConnectivityService: handlePromptUnvalidated 101
,09-23 10:45:43.156  5457  5503 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-23 10:45:43.157  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 10:45:43.157  5457  5503 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 10:45:43.157  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 10:45:43.157  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 10:45:43.159  5457  5786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 10:45:43.159  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 10:45:43.159  5457  5786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 10:45:43.160  5457  5503 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 10:45:43.160  5457  5786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 10:45:43.160  5457  5457 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 10:45:43.160  5457  5457 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 10:45:43.160  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 10:45:43.161  5457  5503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46fdd8e removed from the list
09-23 10:45:43.161  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 10:45:43.161  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 10:45:43.161  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 10:45:43.162  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 10:45:43.162  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 10:45:43.165  5457  5503 D BluetoothAdapter: STATE_ON
,09-23 10:45:43.165  5457  5503 D BluetoothLeScanner: could not find callback wrapper
09-23 10:45:43.165  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 10:45:43.166  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 10:45:43.169  5685  5704 D BtGatt.AdvertiseManager: message : 1
,09-23 10:45:43.171  5685  5704 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 10:45:43.181  5685  5701 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 10:45:43.181  5685  5701 D BtGatt.GattService: Client app is not null!
,09-23 10:45:43.183  5685  5696 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 10:45:43.183  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 10:45:43.183  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 10:45:43.183  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 10:45:43.184  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 10:45:43.184  5457  5503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 10:45:43.186  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 10:45:43.186  5457  5503 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 10:45:43.187  5457  5503 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 10:45:43.188  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 10:45:43.191  5457  5503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6c9af removed from the list
09-23 10:45:43.191  5457  5503 D io.jxcore.node.ConnectivityMonitor: stop
09-23 10:45:43.192  5457  5503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 10:45:43.193  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:43.194  5457  5457 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 10:45:43.194  5457  5457 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 10:45:43.195  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-23 10:45:43.195  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-23 10:45:43.195  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 10:45:43.195  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 10:45:43.195  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 10:45:43.195  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 10:45:43.196  5457  5503 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 10:45:43.197  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-23 10:45:43.200  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-23 10:45:43.201  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,09-23 10:45:43.203  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-23 10:45:43.204  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-23 10:45:43.205  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-23 10:45:43.206  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-23 10:45:43.207  5457  5503 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-23 10:45:43.208  5457  5503 I StreamCopyingThreadTest: Starting test: testRun
,09-23 10:45:43.212  5457  5788 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name)
,09-23 10:45:43.695  5457  5457 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 10:45:44.739  5457  5788 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 197
,09-23 10:45:44.740  5457  5788 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 197, name: My test thread name)
,09-23 10:45:44.740  5457  5788 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 10:45:45.217  5457  5503 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-23 10:45:45.220  5457  5790 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name)
,09-23 10:45:45.220  5457  5790 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 199, thread name: My test thread name)
09-23 10:45:45.221  5457  5790 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 10:45:45.224  5457  5503 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-23 10:45:45.226  5457  5503 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 10:45:45.231  5457  5503 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-23 10:45:45.234  5457  5791 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 203, name: My test thread name)
,09-23 10:45:45.235  5457  5791 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 203, thread name: My test thread name): Test exception.
,09-23 10:45:45.236  5457  5791 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 203, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 10:45:45.243  5457  5503 I jxcore-log: *Native tests were executed*
09-23 10:45:45.243  5457  5503 I jxcore-log: 
,09-23 10:45:45.243  5457  5503 I jxcore-log: Total number of executed tests:  82
09-23 10:45:45.243  5457  5503 I jxcore-log: 
09-23 10:45:45.243  5457  5503 I jxcore-log: Number of passed tests:  82
09-23 10:45:45.243  5457  5503 I jxcore-log: 
09-23 10:45:45.244  5457  5503 I jxcore-log: Number of failed tests:  0
09-23 10:45:45.244  5457  5503 I jxcore-log: 
09-23 10:45:45.244  5457  5503 I jxcore-log: Number of ignored tests:  0
09-23 10:45:45.244  5457  5503 I jxcore-log: 
,09-23 10:45:45.246  5457  5503 I jxcore-log: Total duration:  22466
09-23 10:45:45.246  5457  5503 I jxcore-log: 
,09-23 10:45:45.246  5457  5503 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 10:45:45.246  5457  5503 I jxcore-log: 
,09-23 10:45:45.254  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.254  5457  5503 I jxcore-log: 
,09-23 10:45:45.261  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.261  5457  5503 I jxcore-log: 
,09-23 10:45:45.264  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.264  5457  5503 I jxcore-log: 
09-23 10:45:45.266  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 10:45:45.266  5457  5503 I jxcore-log: 
,09-23 10:45:45.269  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 10:45:45.269  5457  5503 I jxcore-log: 
,09-23 10:45:45.272  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 10:45:45.272  5457  5503 I jxcore-log: 
,09-23 10:45:45.273  5457  5457 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 10:45:45.275  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.275  5457  5503 I jxcore-log: 
,09-23 10:45:45.278  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.278  5457  5503 I jxcore-log: 
,09-23 10:45:45.279  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.279  5457  5503 I jxcore-log: 
,09-23 10:45:45.281  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.281  5457  5503 I jxcore-log: 
,09-23 10:45:45.282  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.282  5457  5503 I jxcore-log: 
,09-23 10:45:45.284  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 10:45:45.284  5457  5503 I jxcore-log: 
,09-23 10:45:45.285  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.285  5457  5503 I jxcore-log: 
,09-23 10:45:45.286  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.286  5457  5503 I jxcore-log: 
09-23 10:45:45.287  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.287  5457  5503 I jxcore-log: 
,09-23 10:45:45.288  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.288  5457  5503 I jxcore-log: 
,09-23 10:45:45.289  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.289  5457  5503 I jxcore-log: 
,09-23 10:45:45.290  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.290  5457  5503 I jxcore-log: 
,09-23 10:45:45.291  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.291  5457  5503 I jxcore-log: 
,09-23 10:45:45.292  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.292  5457  5503 I jxcore-log: 
09-23 10:45:45.293  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.293  5457  5503 I jxcore-log: 
09-23 10:45:45.293  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.293  5457  5503 I jxcore-log: 
09-23 10:45:45.294  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.294  5457  5503 I jxcore-log: 
09-23 10:45:45.295  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.295  5457  5503 I jxcore-log: 
,09-23 10:45:45.296  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.296  5457  5503 I jxcore-log: 
,09-23 10:45:45.297  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.297  5457  5503 I jxcore-log: 
,09-23 10:45:45.298  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.298  5457  5503 I jxcore-log: 
,09-23 10:45:45.299  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.299  5457  5503 I jxcore-log: 
09-23 10:45:45.300  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.300  5457  5503 I jxcore-log: 
09-23 10:45:45.300  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 10:45:45.300  5457  5503 I jxcore-log: 
09-23 10:45:45.301  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.301  5457  5503 I jxcore-log: 
09-23 10:45:45.302  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.302  5457  5503 I jxcore-log: 
,09-23 10:45:45.302  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.302  5457  5503 I jxcore-log: 
,09-23 10:45:45.303  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 10:45:45.303  5457  5503 I jxcore-log: 
,09-23 10:45:45.304  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 10:45:45.304  5457  5503 I jxcore-log: 
09-23 10:45:45.305  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.305  5457  5503 I jxcore-log: 
09-23 10:45:45.306  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.306  5457  5503 I jxcore-log: 
09-23 10:45:45.306  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 10:45:45.306  5457  5503 I jxcore-log: 
,09-23 10:45:45.307  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-23 10:45:45.307  5457  5503 I jxcore-log: 
09-23 10:45:45.308  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 10:45:45.308  5457  5503 I jxcore-log: 
,09-23 10:45:45.309  5457  5503 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 10:45:45.309  5457  5503 I jxcore-log: 
,09-23 10:45:45.742  5792  5792 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 10:45:45.749  5792  5792 D AndroidRuntime: CheckJNI is OFF
,09-23 10:45:45.781  5792  5792 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 10:45:45.814  5792  5792 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 10:45:45.830  5792  5792 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 10:45:45.839   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 10:45:45.839   931   944 I ActivityManager: Killing 5457:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 10:45:45.899   931   942 I WindowState: WIN DEATH: Window{2495938 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-23 10:45:45.899   931  3589 D GraphicsStats: Buffer count: 2
,09-23 10:45:45.900   931  2982 D WifiService: Client connection lost with reason: 4
,09-23 10:45:45.987   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 10:45:45.988   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 10:45:45.988   931   954 I art     : Starting a blocking GC Explicit
,09-23 10:45:45.989   931   944 E ActivityManager: Failure starting process com.test.thalitest
09-23 10:45:45.989   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 10:45:45.989   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:45.989   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:45.989   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 10:45:45.989   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 10:45:45.989   931   944 I ActivityManager:   Force finishing activity ActivityRecord{2eeefb5 u0 com.test.thalitest/.MainActivity t2}
,09-23 10:45:45.998   931   949 W WindowManager: Attempted to add application window with unknown token Token{7c3664a ActivityRecord{2eeefb5 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 10:45:45.999   931   949 W WindowManager: Token{7c3664a ActivityRecord{2eeefb5 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{7c3664a ActivityRecord{2eeefb5 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-23 10:45:45.999   931   949 W WindowManager: view not successfully added to wm, removing view
09-23 10:45:45.999   931   949 W WindowManager: Exception when adding starting window
09-23 10:45:45.999   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{5de3e14 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 10:45:45.999   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 10:45:45.999   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 10:45:45.999   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 10:45:45.999   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 10:45:45.999   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 10:45:45.999   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:45.999   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:45.999   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 10:45:45.999   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 10:45:46.000   931  3605 W ActivityManager: Spurious death for ProcessRecord{e02b6bd 0:com.test.thalitest/u0a77}, curProc for 5457: null
,09-23 10:45:46.076   931   954 I art     : Explicit concurrent mark sweep GC freed 48665(3MB) AllocSpace objects, 9(292KB) LOS objects, 33% free, 28MB/43MB, paused 1.757ms total 87.107ms
,09-23 10:45:46.095   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 10:45:46.097   931  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,09-23 10:45:46.098  5792  5792 I art     : System.exit called, status: 0
09-23 10:45:46.098  5792  5792 I AndroidRuntime: VM exiting with result code 0.
,09-23 10:45:46.113   931   954 I ActivityManager: Start proc 5803:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-23 10:45:46.113   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 10:45:46.120   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-23 10:45:46.125  5685  5685 D BluetoothMapAppObserver: onReceive
09-23 10:45:46.125  5685  5685 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-23 10:45:46.125  3490  3994 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-23 10:45:46.132  3430  3430 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-23 10:45:46.139   931  2970 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 10:45:46.152  3430  5814 I Keyboard.Facilitator.DecoderInitializer: run(),
,09-23 10:45:46.180  3558  3558 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 10:45:46.186  3413  5818 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 10:45:46.194  3658  3658 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-23 10:45:46.194  3658  3658 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 10:45:46.209  3430  5814 I Decoder : createOrResetDecoder
,09-23 10:45:46.211   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-23 10:45:46.209   412   412 W kworker/4:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 10:45:46.212   412   412 W kworker/4:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 10:45:46.229   412   412 W kworker/4:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 10:45:46.241   931  3569 I ActivityManager: Start proc 5823:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-23 10:45:46.242  3606  3727 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 10:45:46.242  3606  3727 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3606
09-23 10:45:46.242  3606  3727 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.242  3606  3727 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 10:45:46.245  3658  3658 I ConfigService: onCreate
,09-23 10:45:46.249  3658  5833 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 10:45:46.249  3658  5833 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-23 10:45:46.250   931  3422 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 10:45:46.250  3658  5833 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-23 10:45:46.252  3658  5833 W SQLiteOpenHelper: Opened config.db in read-only mode
09-23 10:45:46.256   931  5834 E DropBoxManagerService: Can't write: system_app_crash
09-23 10:45:46.256   931  5834 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 10:45:46.256   931  5834 E DropBoxManagerService: 	... 5 more
,09-23 10:45:46.256  3606  3727 I Process : Sending signal. PID: 3606 SIG: 9
,09-23 10:45:46.263  3413  3446 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7ECAB4957) - 
,09-23 10:45:46.264  3413  3446 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-23 10:45:46.264  3413  3446 E AndroidRuntime: Process: android.process.acore, PID: 3413
09-23 10:45:46.264  3413  3446 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.264  3413  3446 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 10:45:46.268   931  5838 E DropBoxManagerService: Can't write: system_app_crash
09-23 10:45:46.268   931  5838 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 10:45:46.268   931  5838 E DropBoxManagerService: 	... 5 more
,09-23 10:45:46.274  3430  5814 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 10:45:46.286  3907  5822 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-23 10:45:46.296  3413  5818 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-23 10:45:46.296  3413  5818 I Process : Sending signal. PID: 3413 SIG: 9
,09-23 10:45:46.297  3907  5822 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 10:45:46.371   931  3421 D GraphicsStats: Buffer count: 1
,09-23 10:45:46.371   931  3591 I WindowState: WIN DEATH: Window{cbb0fd9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-23 10:45:46.376   931  3395 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3606) has died
,09-23 10:45:46.378   931  3395 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-23 10:45:46.379   931  3395 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-23 10:45:46.395   931   944 I ActivityManager: Start proc 5842:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-23 10:45:46.395   931  3605 I ActivityManager: Process android.process.acore (pid 3413) has died
,09-23 10:45:46.395   931  3605 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-23 10:45:46.444  5842  5842 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:46.444  5842  5842 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 10:45:46.444  5842  5842 D AndroidRuntime: Shutting down VM
,09-23 10:45:46.452  5842  5842 E AndroidRuntime: FATAL EXCEPTION: main
09-23 10:45:46.452  5842  5842 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5842
09-23 10:45:46.452  5842  5842 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-23 10:45:46.452  5842  5842 E AndroidRuntime: 	... 10 more
09-23 10:45:46.454   931  3395 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-23 10:45:46.454   931  5855 E DropBoxManagerService: Can't write: system_app_crash
09-23 10:45:46.454   931  5855 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 10:45:46.454   931  5855 E DropBoxManagerService: 	... 5 more
09-23 10:45:46.455  5842  5842 I Process : Sending signal. PID: 5842 SIG: 9
,09-23 10:45:46.470   931  3421 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5842) has died
,09-23 10:45:46.471   931  3421 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-23 10:45:46.486   931   944 I ActivityManager: Start proc 5856:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 10:45:46.536  5856  5856 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:46.536  5856  5856 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 10:45:46.537  5856  5856 D AndroidRuntime: Shutting down VM
,09-23 10:45:46.544  5856  5856 E AndroidRuntime: FATAL EXCEPTION: main
09-23 10:45:46.544  5856  5856 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5856
09-23 10:45:46.544  5856  5856 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-23 10:45:46.544  5856  5856 E AndroidRuntime: 	... 10 more
,09-23 10:45:46.547   931  3591 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 10:45:46.547   931  5868 E DropBoxManagerService: Can't write: system_app_crash
09-23 10:45:46.547   931  5868 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 10:45:46.547   931  5868 E DropBoxManagerService: 	... 5 more
,09-23 10:45:46.548  5856  5856 I Process : Sending signal. PID: 5856 SIG: 9
,09-23 10:45:46.558   931   942 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5856) has died
,09-23 10:45:46.560   931   942 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-23 10:45:46.575   931   944 I ActivityManager: Start proc 5869:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 10:45:46.611   383   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
